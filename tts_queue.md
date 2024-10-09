---
title: TTS Queue
layout: default
nav_order: 12
---

![Picture](assets/media/tts_queue_title.png)

Twitch
{: .label .label-purple }

StreamerBot
{: .label .label-blue }


# Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---


## Description
Put TTS messages into a queue and have it play one by one whenever you want. You can skip messages, listen to the previous one again and you can remove all messages of a user from the remaining queue. You can even post the message to your Discord and have it linked your current VOD with a timestamp. It also comes with helpers for your own OBS overlay.

![Picture](assets/media/tts_queue_title_2.png)

- - - -

## Import Code
```scss
```
- - - -

## Installation

1. Copy the import code from above and import the content

    ![Import Actions](assets/media/import_actions.png)

2. Move to the `Commands` tab and enable the imported commands

    ![How To Enable Commands](assets/media/enable_commands.png)

3. Head into the `Actions` tab and navigate to the action `[TTS Queue]  1 - Settings`. Rightclick the "Test" trigger and hit "Test Trigger". This will open the settings menu. Paste your voice alias into "Prefix Voice Alias" as well as "Message Voice Alias". They can of course have the same voice alias if you want. Save and exit once you are done.

      ![Picture](assets/media/tts_queue_voice_alias.png)

6. Done! 🥳

- - - -

## Settings 

In the `[TTS Queue]  1 - Settings` action, you can customize chat responses, whether it posts to Discord or whether you want to use an OBS overay.

![Picture](assets/media/tts_queue_settings_1.png)

![Picture](assets/media/tts_queue_settings_2.png)

![Picture](assets/media/tts_queue_settings_3.png)

{: .new }
To use an OBS overlay, you can create your own text sources. One text source for the queue count `42/100` and one for the time `00:42:13`. You can then paste the names into the settings menu and it will automatically update whenever the queue count changes.
- - - -

## Commands

- ## `!AUCTION`
  {: .no_toc }

  Gives information about the currently active auction (like the redeemer's own bid, the highest bid, etc).
  
- - - -

{: .new }
You can essentially use any trigger you want for reading a new message, reading a previous one, skipping, clearing etc. Just the triggers that add to the queue are final. If you think a different trigger is required, feel free to suggest it and I will see what I can do :)

--- 

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| October 09, 2024           | Release | 1.0.0 |
