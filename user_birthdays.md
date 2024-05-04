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

