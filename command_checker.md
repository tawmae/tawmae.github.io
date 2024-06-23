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
