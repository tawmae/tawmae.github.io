---
title: Movie Quiz
layout: default
nav_order: 5
---

![Picture](assets/media/movie_quiz_title_1.png)

Twitch
{: .label .label-purple }

OBS
{: .label .label-yellow }

StreamerBot
{: .label .label-blue }


# Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Description
Have your chat guess the movie and/or TV show based on its description! Either with an OBS overlay or just in chat.

![Picture](assets/media/movie_quiz_title_2.gif)


---

## API key

- This extension requires a The Movie Database API key. You can get yours for free at: [https://developer.themoviedb.org/reference/intro/getting-started](https://developer.themoviedb.org/reference/intro/getting-started)

---

## Import Code
```scss
-
```

--- 

## Downloads
- [DuoVia.FuzzyStrings.dll](assets/media/DuoVia.FuzzyStrings.dll)

{: .highlight }
This .dll file is required for the chat answers and allows for not-100% accurate matches. So if the movie was `Schindler's List`, then the answer `schindlers list` would count as well. This is not 100% accurate and may occasionally have a match when it's not supposed to, but it's better than having to type the movie/show name 100% accuratley.

## Required OBS plugins (optional if you only want the chat version)
1. [Stroke Glow Shadow Plugin](https://obsproject.com/forum/resources/stroke-glow-shadow.1800/)
3. [Source Copy Plugin](https://obsproject.com/forum/resources/source-copy.1261/) 
4. [Advanced Masks Plugin](https://obsproject.com/forum/resources/advanced-masks.1856/)

{: .highlight }
Make sure you have the latest version of Source Copy (Feb 15, 2024) and OBS on version `30.1.1` or newer

---

## Setup
1. (Optional) If you want the OBS overlay, download and install all **three OBS plugins**.

2. Download the `DuoVia.FuzzyStrings.dll` file and paste it into your `StreamerBot/dlls` folder

   ![Picture](assets/media/movie_quiz_settings_3.png)

3. Go into StreamerBot, copy the import code from above and import the content
   
   ![Import Actions](assets/media/import_actions.png)

4. Move to the `Commands` tab and enable the imported commands

   ![How To Enable Commands](assets/media/enable_commands.png)

5. In the `[Movie Quiz] Start Game` action, doubleclick the "Set Argument" subaction in the `API Key` group and paste your API key in there.

   ![Picture](assets/media/movie_quiz_settings_5.png)

7. If you **don't** want the OBS overlay, go into the `[Movie Quiz] Start Game` action and set `movieQuiz_obsOverlay` to `False`.

   ![Picture](assets/media/movie_quiz_settings_4.png)

   Otherwise leave it at `True` and instead rightclick the "Test" trigger and hit "Test Trigger".

   ![Picture](assets/media/event_list_test_trigger.png)

   This creates the scene and sources in OBS. As confirmation it says "Quiz Movie setup completed" in your Twitch chat. You can then nest the scene anywhere you want.

8. Done! 🥳

---

## Settings

- As mentioned in the installation above, you can decide whether you want to use the OBS overlay by setting `movieQuiz_obsOverlay` to either `True` or `False` and change your `movieQuiz_obsConneciton` if needed. But usually leave this at `0`.

  ![Picture](assets/media/movie_quiz_obs_overlay.png)

- You can decide whether you want only movies, only TV shows or both included in the quiz. Just set `movieQuizMedia` accordingly to either `Movies`, `TV Shows` or `Both`.

- You can set the language `movieQuizLanguage`for the movie description and title (ISO code prefix + suffix, e.g. `en-US`, see [here](https://tawmae.github.io/movie_quiz.html#language-codes). Other languages may have weird titles and super long descriptions though, so no guarantee for good quality for languages other than english. You might want to decrease the font size for the image description too in that case.

- You can also change the `movieQuizTime` in seconds. **Important: This time has to match with the `Movie Quiz` timer in `Settings -> Timed Actions`!** If you are playing with an OBS overlay and hints, don't set the time below 45 seconds. I recommend leaving it at 60.

- If you want the description to be read out loud by your TTS, type in the voice alias into `ttsVoiceAlias`.


- By setting `showEnglishDescriptionInChat` to `True`, the english movie/show description will always **additionally** get posted to chat, even with the OBS overlay in use. This is useful for multi-language streams.
 
   ![Picture](assets/media/movie_quiz_general_settings.png)

- To show hints (release year + genre, the cast and a movie image in OBS), leave `showHints` at `True`

  ![Picture](assets/media/movie_quiz_title_3.png)
  
- In the `Expert Settings (Movies)` and `Expert Settings (TV Shows)` you can set exact criteria for the search queries. That includes the minimum user votes, the minimum average user rating from 1-10, excluded genres and original languages. The input has to match **exactly**, so see below for [genres](https://tawmae.github.io/movie_quiz.html#genres) or [language codes](https://tawmae.github.io/movie_quiz.html#language-codes). If you are unsure about the settings or getting errors, contact me.

  ![Picture](assets/media/movie_quiz_expert_settings_movie.png)

  ![Picture](assets/media/movie_quiz_expert_settings_tvseries.png)

{: .note }
If you change the parameters, it might happen that the first round will abort because the criterias are too narrow (and it was looking for page 100 when there's only 50 pages). This will fix itself after you get the error message. The second attempt will update the available page count. If it does not change, your expert settings have exactly `0` movies/TV shows.


- In the `[Movie Quiz] Correct Answer` action, you can optionally only allow 100% accurate answers. They're still not case sensitive, but it has to match the actual title. I'd recommend to leave this at `False`.

  ![Picture](assets/media/movie_quiz_settings_2.png)

---

{: .new }
By default, every user type can use `!moviequiz start` to start a single round. Starting multiple rounds or ending a quiz is for **moderators only**. Channel Point Rewards can be used by everyone and will **always** start a single round. If you use a Channel Point Reward to start a game, points will automatically get refunded if something goes wrong. So make sure the reward has been created in SB and is owned by it.

---

## Commands

- ## `!MOVIEQUIZ START`
  {: .no_toc }

  Starts one round of the game.

---

- ## `!MOVIEQUIZ START ROUNDS [NUMBER]` or `!MQ START ROUNDS [NUMBER]`
  {: .no_toc }

  Starts x rounds of the game.

---

- ## `!MOVIEQUIZ END` or `!MQ END`
  {: .no_toc }

  Ends the game after the current round has finished.

---

- ## `!MOVIEQUIZSTATS` or `!MQSTATS`
  {: .no_toc }

  Shows the total games and how many movies the user has guessed correctly.

---

{: .note }
If a movie title has a number that is greater than 1 (for example `Terminator 2` or `Star Wars Episode IV`), then the user input **must** have that number in there. So `Star Wars Episode 4` as well as `Star Wars Episode IV` would count.


{: .highlight }
If you don't have a bot account connected, your broadcaster account will be excluded from giving the correct answer.

{: .highlight }
If you upgrade to a newer version that contained OBS UI changes, delete the old Movie Quiz scene entirely and **then** re-import it again.

---

## Genres

{: .highlight }
If you have translated the genre names in the code, the genres have to match in `excludedGenres` aswell! 

| Movie Genres     |  TV Series Genres     | 
|:-------------    |:-------------    |
| Action           | Action & Adventure |
| Adventure | Animation |
| Animation           | Comedy |
| Comedy           | Crime |
| Crime           | Documentary | 
| Documentary           | Drama | 
| Drama           | Family |
| Family           | Kids | 
| Fantasy           | Mystery | 
| History           | News | 
| Horror           | Reality | 
| Music           | Sci-Fi & Fantasy | 
| Mystery           | Soap | 
| Romance           | War & Politics | 
| Science Fiction          | Western | 
| TV Movie           | 
| Thriller           | 
| War           | 
| Western           | 

---

## Language Codes

| Language      | Language Code (for expert settings) | Language Code (your description language)       |
|:--------------|:--------------|:----------------------|
| Afrikaans     | af            | af-ZA                 |
| Arabic        | ar            | ar-BH, ar-KW, ar-LB, ar-OM, ar-QA, ar-SA, ar-AE, ar-EG |
| Bengali       | bn            | bn-BD                 |
| Bosnian       | bs            | bs-BA                 |
| Bulgarian     | bg            | bg-BG                 |
| Catalan       | ca            | ca-ES                 |
| Chinese       | zh            | zh-CN, zh-HK, zh-TW, zh-Hans-HK, zh-Hans-TW, zh-Hant-HK, zh-Hant-TW |
| Croatian      | hr            | hr-HR                 |
| Czech         | cs            | cs-CZ                 |
| Danish        | da            | da-DK                 |
| Dutch         | nl            | nl-BE, nl-NL          |
| English       | en            | en-US, en-CA, en-GB, en-AU, en-IN, en-SG, en-NZ, en-ZA, en-IE, en-JM, en-BZ, en-TT |
| Estonian      | et            | et-EE                 |
| Finnish       | fi            | fi-FI                 |
| French        | fr            | fr-FR, fr-BE, fr-CA, fr-CH, fr-LU |
| German        | de            | de-DE, de-AT, de-CH, de-LU |
| Greek         | el            | el-GR                 |
| Hebrew        | he            | he-IL                 |
| Hindi         | hi            | hi-IN                 |
| Hungarian     | hu            | hu-HU                 |
| Icelandic     | is            | is-IS                 |
| Indonesian    | id            | id-ID                 |
| Italian       | it            | it-IT, it-CH          |
| Japanese      | ja            | ja-JP                 |
| Korean        | ko            | ko-KR                 |
| Latvian       | lv            | lv-LV                 |
| Lithuanian    | lt            | lt-LT                 |
| Malay         | ms            | ms-MY                 |
| Norwegian     | no            | no-NO                 |
| Polish        | pl            | pl-PL                 |
| Portuguese    | pt            | pt-PT, pt-BR          |
| Romanian      | ro            | ro-RO                 |
| Russian       | ru            | ru-RU                 |
| Serbian       | sr            | sr-RS                 |
| Slovak        | sk            | sk-SK                 |
| Slovenian     | sl            | sl-SI                 |
| Spanish       | es            | es-ES, es-MX, es-AR, es-CO, es-PE, es-VE, es-CL, es-EC, es-GT, es-CU, es-BO, es-DO, es-HN, es-PY, es-SV, es-NI, es-CR, es-PA, es-UY, es-PR, es-419 |
| Swedish       | sv            | sv-SE                 |
| Thai          | th            | th-TH                 |
| Turkish       | tr            | tr-TR                 |
| Ukrainian     | uk            | uk-UA                 |
| Urdu          | ur            | ur-PK                 |
| Vietnamese    | vi            | vi-VN                 |


---

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| May 25, 2024           | Added Expert Settings // New OBS design | 1.2.0 |
| May 24, 2024           | If the title differs from the english title, it will show both titles in the answer // added a new settings "showEnglishDescriptionInChat" that will always post the english description to chat, even with OBS overlay on (useful for multi-language streams) // fixed an issue with roman letters from VI to VIII // added new command aliases // added debugging  | 1.1.9 |
| May 23, 2024           | Movies are now scanned whether they are part of a collection (e.g. prequels). Even if the part number is not within the title, the chat input should count (example: "Indiana Jones 2" would count for the title "Indiana Jones and the Temple of Doom" | 1.1.8 |
| May 23, 2024           | If the original movie/show name varies from the translated one, it will show both titles in the overlay and in chat // some slight OBS UI changes | 1.1.7 |
| May 22, 2024           | Added a prevention for duplicate movies/shows to appear within the same session (as long as SB is running) // fixed a minor bug with showing the wrong amount of guessed movies after the rounds have finished // slight OBS UI changes | 1.1.6 |
| May 21, 2024           | Improved input accuracy and description redacting | 1.1.5 |
| May 20, 2024           | The exact title will now be censored in the description // Removed mod-restriction for starting a single round via command // moved the API key to a seperate group // adjusted hint timers // input accuracy adjustments | 1.1.4 |
| May 20, 2024           | Added TV shows (optional) | 1.1.0 |
| May 20, 2024           | Added cast hints and pictures // code improvements // OBS UI changes | 1.0.0 |
| May 19, 2024           | Added the possibility to play multiple rounds automatically // added a non-blocking queue // OBS UI changes | 0.2.3 |
