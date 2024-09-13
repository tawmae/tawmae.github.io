---
title: User Birthdays
layout: default
nav_order: 5
---


![Picture](assets/media/user_birthdays_title.png)

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

Have users set their birthday date and automatically wish them happy birthday as soon as they join your stream!

![Picture](assets/media/user_birthdays_title_2.gif)

{: .new }
Haven't streamed on their birthday? No worries, because belated birthday wishes are integrated, too!

---

## Import Code
```scss
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
```

---

## Installation

1. Copy the import code from above and import the content

    ![Import Actions](assets/media/import_actions.png)

2. Move to the `Commands` tab and enable the imported commands

    ![How To Enable Commands](assets/media/enable_commands.png)


3. Done! 🥳

---

## Settings

- In the action `[User Birthday] 1 - Set / Change / Delete` you can change `dateFormat` to your liking. The default one is `dd.MM.`, but `MM/dd` works, too. Other formats might work aswell, but this hasn't been tested. Feel free to try out. You can also change the number `upcomingBdays` to show on the `!birthday next` commands. This is how many upcoming birthdays will show in chat.

  ![Picture](assets/media/user_birthdays_settings_1.png)

- In the action `[User Birthday] 2 - Check` you can change the number of `belatedBirthday` to your liking aswell. This is how many days later belated birthday wishes are given.

  ![Picture](assets/media/user_birthdays_settings_2.png)

---

## Commands

- ## `!BIRTHDAY SET [DATE]`
  {: .no_toc }

  ![Picture](assets/media/user_birthdays_set.png)

  Sets your own birthday date.

---

- ## `!BIRTHDAY CHECK [USERNAME]`
  {: .no_toc }

  ![Picture](assets/media/user_birthdays_check.png)

  Posts the birthday date of the specified user to chat.

---

- ## `!BIRTHDAY NEXT`
  {: .no_toc }

  ![Picture](assets/media/user_birthdays_next.png)

  Posts the next upcoming birthdays into chat.

---

- ## `!BIRTHDAY ADD [USERNAME] [DATE]`
  {: .no_toc }

  Add a birthday date for the specified user.

---

- ## `!BIRTHDAY CHANGE [USERNAME] [DATE]`
  {: .no_toc }

  ![Picture](assets/media/user_birthdays_change.png)

  Changes the set birthday date of the specified user.

---

- ## `!BIRTHDAY DELETE [USERNAME]`
  {: .no_toc }

  ![Picture](assets/media/user_birthdays_delete.png)

  Deletes the birthday date of the specified user.

---

{: .new }
You can also have users set their birthday date with a channel point reward. Make sure you create the reward itself in StreamerBot and not in Twitch, so the "Owned" column in `Platforms -> Twitch -> Channel Point Rewards` shows "Yes". This way wrong date inputs can be refunded automatically.

---

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| September 14, 2024           | Added a '!birthday add' command | 1.0.2 |
| August 16, 2024           | Updated to Streamer.bot version 0.2.4 | 1.0.1 |
