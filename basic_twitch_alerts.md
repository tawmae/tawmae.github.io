---
title: Basic Twitch Alerts
layout: default
nav_order: 6
---

![Picture](assets/media/basic_twitch_alerts_title.png)

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
A simple OBS overlay for your Twitch alerts (supports Ko-Fi, StreamElements and StreamLabs donations too).

![Picture](assets/media/basic_twitch_alerts_title_2.gif)

---

## Required OBS Plugins
1. [Stroke Glow Shadow Plugin](https://obsproject.com/forum/resources/stroke-glow-shadow.1800/)
2. [Source Copy Plugin](https://obsproject.com/forum/resources/source-copy.1261/) 


{: .highlight }
Make sure you have the latest version of Source Copy (Feb 15, 2024) and OBS on version `30.1.1` or newer

---

## Import Code
```scss
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
```

---

## Installation

1. Download and install both OBS plugins.

2. Copy the import code from above and import the content

    ![Import Actions](assets/media/import_actions.png)


3. Head into the `Basic Alerts` action, rightclick the `Test` trigger and hit "Test Trigger". This will create the scene and sources in OBS for you. You will get a confirmation in your chat afterwards.

  ![Picture](assets/media/basic_twitch_alerts_test_trigger.png)
   
  ![Picture](assets/media/basic_twitch_alerts_setup_completed.png)

4. Done 🥳

---

## Settings

- Set `anonymousFollows` to `True` for follows to be displayed as anonymous
- Customize `alertDuration` with a the amount of milliseconds you want the alert to last (the follow duration is always half of the set time)

- The color of the alert bar is randomized by default. You can set `randomColors` to `False` and then pick a color of your choice in the `Pick Color` subaction below

- You can have the messages of the different alerts spoken out loud by SpeakerBot. Just replace `ttsVoiceAlias` with the voice  alias of your choice.

   ![Picture](assets/media/basic_twitch_alerts_settings.png)

---

## Extras (totally optional)

-  If you want a sound to be played on the alert, you can simply add the sound of your choice as a `Media Source` into the `# Basic Alerts` group in OBS. Leave it visible in there, it will automatically be played when the alert shows.

   ![Picture](assets/media/basic_twitch_alerts_sources.png)

- If you want the color of the alert bar to match the user's chat color, you can create a second action with a `Twitch -> Chat -> Chat Message` trigger. You then create a single `Core -> Globals -> Global (Set)` subaction and have it like this:

  ![Picture](assets/media/basic_twitch_alerts_global.png)

   Then rightclick the action and exclude it from history.
   
  ![Picture](assets/media/basic_twitch_alerts_exclude.png)
 
  {: .note }
  The user needs to have chatted at least once in your channel for StreamerBot to save their color.


## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| June 27, 2024           | Fixed a breaking issue on 0.2.3 with StreamElements and KoFi | 1.0.1 |
| May 12, 2024           | Fixed a breaking issue on 0.2.3 with the color variable | 1.0.0 |



