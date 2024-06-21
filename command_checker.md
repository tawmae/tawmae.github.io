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

![Picture](assets/media/command_check_1.png)


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


