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

If you use 3rd party bots like StreamElements and have active commands there, you can put them into the `whitelistCommands` subaction. Put each command in there, seperate by a comma and a space if you have multiple ones.

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
| June 23, 2024           | Added a commands whitelist for 3rd party bots | 1.0.3 |
| June 22, 2024           | Changed the list-fetch-method so mod-only commands won't break the process for regular users | 1.0.2 |
| June 22, 2024           | Added a default command to just return the command list | 1.0.1 |
