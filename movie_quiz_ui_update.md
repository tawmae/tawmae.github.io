---
title: Movie Quiz (test)
layout: default
nav_order: 25
---

{: .warning }
This is just a test site for the next update. Please refer to this [Movie Quiz](https://tawmae.github.io/movie_quiz.html) for the current version


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
to be released
```

--- 

## ddl-Downloads

1. [DuoVia.FuzzyStrings.dll](assets/media/DuoVia.FuzzyStrings.dll)

2. SettingUI.dll

{: .highlight }
> Both dll files are required to run this extension
>
> `DuoVia.FuzzyStrings.dll` is responsible for the chat responses by your viewers. This allows the input to not be 100% accurate. So if the movie was `Schindler's List`, the chat message `schindlers list` would count as a correct answer, even though it's not an exact match.
>
> `SettingUI.dll` is a release by [TerrierDarts](https://terrierdarts.co.uk/en/home/) that allows to have a user-friendly UI for various settings. You will be easily able to customize a lot of stuff to your liking.

---

## Required OBS plugins (optional if you only want the chat version)

1. [Stroke Glow Shadow Plugin](https://obsproject.com/forum/resources/stroke-glow-shadow.1800/)
3. [Source Copy Plugin](https://obsproject.com/forum/resources/source-copy.1261/) 
4. [Advanced Masks Plugin](https://obsproject.com/forum/resources/advanced-masks.1856/)

{: .highlight }
Make sure you have the latest version of Source Copy `0.2.3` (or newer) and OBS on version `30.1.1` (or newer)

---

## Setup
1. (Optional) If you want the OBS overlay, download and install all **three OBS plugins**.

2. Download both the `DuoVia.FuzzyStrings.dll` and `SettingsUI.dll` files and paste it into your `StreamerBot/dlls` folder

   ![Picture](assets/media/movie_quiz_dlls.png)

3. Go into StreamerBot, copy the import code from above and import the content
   
   ![Import Actions](assets/media/import_actions.png)

4. Move to the `Commands` tab and enable the imported commands

   ![How To Enable Commands](assets/media/enable_commands.png)

5. In the `[Movie Quiz] Settings` action, rightclick the `Test` trigger and hit `Test Trigger`. This will open a settings window for you.

   ![Picture](assets/media/movie_quiz_settings_action.png)

   This might take 2-3 seconds and might also not pop up on top of other windows, so check your taskbar.

   ![Picture](assets/media/movie_quiz_open_settings.png)

7. You will have three different tabs now. For the setup, we will only need the `General` tab. On the very top, paste your TMDB API key into the according field. 

   ![Picture](assets/media/movie_quiz_paste_api_key.png)

8. If you **don't** want to play with the OBS overlay, set `OBS Overlay` at the bottom to `No`. Otherwise leave it as it is.

   ![Picture](assets/media/movie_quiz_obs_overlay_no.png)

9. Hit `Save` and close the settings window.

10. If you want to play with the OBS overlay, navigate to the `[Movie Quiz] Start Game` action and rightclick the `Test` trigger there too and hit `Test Trigger`. This will create the OBS scene for you, which you can then nest into your other scenes.

    ![Picture](assets/media/movie_quiz_startgame_action.png)

    You will get a confirmation in chat if it's been successfully created.

11. Done! 🥳

---

## Settings

Thanks to a brand new release of [TerrierDarts](https://terrierdarts.co.uk/en/home/), there's now a UI for the settings. You can customize general settings as well as the specific search parameters for movies and for TV shows individually. You can set your own quiz language, you can exclude certain genres, specify the release years / air dates, the user vote count and average user rating and the original languages of the movies / TV shows.

To access the settings, navigate into the `[Movie Quiz] Settings` action, rightclick the `Test` trigger and hit `Test Trigger`.

{: .new }
Settings will only apply if you save them.

General settings:

![Picture](assets/media/movie_quiz_settings_window_1.png)

Expert settings (one tab for movies, one for TV shows):

![Picture](assets/media/movie_quiz_settings_window_2.png)



{: .highlight }
Depending how narrow your search parameters are, it might happen that the first search will not find any results. This will fix itself after the first error, so the second time you start the game it will have adjusted itself. If the error persists, your seach parameters are **too narrow** and you will have to check them. Reset them in the worst case.


---

{: .new }
By default, every user type can use `!moviequiz start` to start a single round. You can make it more strict in the command's settings. Starting multiple rounds or ending a quiz is for **moderators only** and is not affected by the command's permissions. Channel Point Rewards can be used by everyone and will **always** start a **single** round. If you use a Channel Point Reward to start a game, points will automatically get refunded if something goes wrong. So make sure the reward has been created in SB and is owned by it.

---

## Commands

- ## `!MOVIEQUIZ START` or `!MQ START`
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


{: .note }
If you don't have a bot account connected, your broadcaster account will be excluded from giving the correct answer.

{: .note }
If you upgrade to a newer version that contained OBS UI changes, delete the old Movie Quiz scene entirely and **then** re-import it again.

---


## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| May 30, 2024           | Complete Settings UI overhaul (powered by TerrierDarts) // much improved title and answer filter | 1.3.0 |
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
