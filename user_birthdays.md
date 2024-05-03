---
title: User Birthdays
layout: default
nav_order: 14
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

- **!birthday set [Date]**

  ![Picture](assets/media/user_birthdays_set.png)

  Sets your own birthday date.

---

- **!birthday check [User]**

  ![Picture](assets/media/user_birthdays_check.png)

  Posts the birthday date of the specified user to chat.

---

- **!birthday next**

  ![Picture](assets/media/user_birthdays_next.png)

  Posts the next upcoming birthdays into chat.

---

- **!birthday change [User] [Date]**

  ![Picture](assets/media/user_birthdays_change.png)

  Changes the set birthday date of the specified user.

---

- **!birthday delete [User]**

  ![Picture](assets/media/user_birthdays_delete.png)

  Deletes the birthday date of the specified user.

---

{: .new }
You can also have users set their birthday date with a channel point reward. Make sure you create the reward itself in StreamerBot and not in Twitch, so the "Owned" column in `Platforms -> Twitch -> Channel Point Rewards` shows "Yes". This way wrong date inputs can be refunded automatically.

