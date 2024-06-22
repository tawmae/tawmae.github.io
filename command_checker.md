---
title: Command Checker
layout: default
nav_order: 19
---

![Picture](assets/media/command_checker_title_1.png)

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
Whenever a user types in a command (starting with an exclamation mark `!`) that does not exist, it will instead return a list of all your available commands. You can specify which commands to show (like groups, commands the user has permission for etc. pp.). To prevent spam, you can get a cooldown for the list to show in chat.

![Picture](assets/media/command_checker_title_2.png)

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

You can set `cooldown` to a cooldown duration of your choice in **seconds**. That means, if it's on `60`, the first wrong command will show the command list, but the second won't. Only if 60 seconds have passed, it will show the entire list in chat again whenever someone types in a wrong command.

You can also set `defaultCommand` to a command of your choice, so it will just return the list without the `...does not exist` message. That one is not affected by the cooldown.

![Picture](assets/media/command_check_1.png)

![Picture](assets/media/command_check_8.png)


In the `Get Commands` subaction, you can choose whether you only want to show a specific command group or all of them. And then, whether you want to include command aliases and permission rights. If you want to show multiple command groups, you can duplicate the subaction and replace `selectedCommands[x]` with the next higher number.

--- 

So the first subaction shows all my commands in the "Movie Quiz" group.

![Picture](assets/media/command_check_2.png)

![Picture](assets/media/command_check_5.png)

---

The second subaction then shows the "Video Game Quiz" group. I changed `selectedCommands1` to `selectedCommands2`

![Picture](assets/media/command_check_3.png)

![Picture](assets/media/command_check_6.png)

---

The third subaction then shows the "User Inventory" group. I changed `selectedCommands2` to `selectedCommands3`

![Picture](assets/media/command_check_4.png)
![Picture](assets/media/command_check_7.png)


---

{: .note }
If your commands exceed Twitch's character limit, it will automatically split the messages

---

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| June 22, 2024           | Changed the list-fetch-method so mod-only commands won't break the process for regular users | 1.0.2 |
| June 22, 2024           | Added a default command to just return the command list | 1.0.1 |
