---
title: Hearthstone Battlegrounds MMR
layout: default
parent: Games
---

![Picture](assets/media/bgs_title.png)

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

Display your current MMR and your today's MMR progress in chat.

![Picture](assets/media/bgs_mmr.png)

---

## Required Plugin

-  [Hearthstone Decktracker](https://hsreplay.net/downloads/)


{: .highlight }
You need the decktracker installed and running for the MMR to update properly.

---

## Import Code
```scss
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
```

---

## Installation

1. Download and install Hearthstone Decktracker.

2. Copy the import code from above and import the content

    ![Import Actions](assets/media/import_actions.png)

3. Move to the `Commands` tab and enable the imported commands

    ![How To Enable Commands](assets/media/enable_commands.png)

4. On your keyboard, press `Windows Key + S` and type `%appdata%` into the input field. Go to `/AppData/Roaming/HearthstoneDeckTracker/BgsLastGames.xml` and make sure the file is there. Copy the entire path and paste it into the `Set Argument` subaction.

5. Done! 🥳

---

## Commands



- ## `!MMR`
  {: .no_toc }
  
  Displays the MMR in chat.

---
