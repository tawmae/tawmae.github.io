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

- In the action `[User Birthday] Set / Change / Delete` you can change `dateFormat` to your liking. The default one is `dd.MM.`, but `MM/dd` works, too. Other formats might work aswell, but this hasn't been tested. Feel free to try out. You can also change the number `upcomingBdays` to show on the `!birthday next` commands. This is how many upcoming birthdays will show in chat.

  ![Picture](assets/media/user_birthdays_settings_1.png)

- In the action `[User Birthday] Check` you can change the number of `belatedBirthday` to your liking aswell. This is how many days later belated birthday wishes are given.

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

