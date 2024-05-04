---
title: Hot Potato
layout: default
nav_order: 15
---

![Picture](assets/media/hot_potato_title.png)

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
A chat game for Twitch - start a game of "Hot Potato" to throw a hot potato into your crowd of active chatters. Once in your hand, you need to quickly pass the potato to another user within 15 seconds. If you fail to pass it, you will burn your hands! 

![Picture](assets/media/hot_potato_title_2.png)

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

3. If you only want to use the game with chat commands, you are already done here! 🥳

4. If you want to start the game and pass the potato on with channel point rewards, you can continue here.

5. In StreamerBot, go to `Platforms -> Twitch -> Channel Point Rewards` and create two rewards. One to start the game, one to pass on the potato. Name them whatever you want. Keep `User Input Required` and `Redemption Skips Queue` unchecked, so the reward can be refunded.

    ![Picture](assets/media/hot_potato_rewards_1.png)   

6. Assign the rewards as a trigger in the `[Hot Potato] Start` and `[Hot Potato] Pass On` action.

7. In the `[Hot Potato] Start` action, you will find a folder called `Config (for Channelpoint Rewards only` with two subactions in there. Go back into `Platforms -> Twitch -> Channel Point Rewards`, rightclick the rewards and copy their Reward ID. Paste the reward ID of the Start-Reward into `startRewardId` and the Pass-Reward-ID into `passRewardId` of the `[Hot Potato] Start` action.

    ![Picture](assets/media/hot_potato_rewards_2.png)  

9. Now you're done!

 {: .new }
 Once you start a game with a channel point reward, the "Start" reward will automatically get disabled and the "Pass" reward will get enabled. Once a game ends, it'll be the other way round.

---

## Settings

- In the `[Hot Potato] Start` action, you can set `minimumActiveChatters` to a number of your liking. On `5` it means a game will only start if 5 or more people have chatted within the last five minutes.

  ![Picture](assets/media/hot_potato_settings_1.png) 

- In the `[Hot Potato] End` action, you can edit the `Twitch Timeout` subaction and edit the time and reason to your liking. If a moderator gets a timeout, they'll be remodded automatically afterwards.

  ![Picture](assets/media/hot_potato_settings_2.png)

   
   {: .new }
   The broadcaster and bot account are not being counted as "active chatters".   

- In the `[Hot Potato] Pass On` action, you can set `passesGameEnd` to a number of your liking. The game will automatically end and resolve in a draw once the potato has been passed along this many times-

  ![Picture](assets/media/hot_potato_settings_3.png) 

---

## Commands

- ## `!HOTPOTATO START`
  {: .no_toc }


  Starts the game.

---

- ## `!PASS`
  {: .no_toc }


  Pass the hot potato to another random player.

---

- ## `!HOTPOTATO EXCLUDE`
  {: .no_toc }

  Exclude yourself from the game. Type it again to include yourself back in.

---

- ## `!HOTPOTATO EXCLUDE [USERNAME]`
  {: .no_toc }

  Exclude the specified user from the game. Only usable by moderators. To include them back in, retype the command.

---

