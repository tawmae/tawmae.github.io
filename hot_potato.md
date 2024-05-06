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

Here's a cool little image of a hot potato I found online and resized for channel point rewards. Feel free to use! :)

![Picture](assets/media/hot_potato_reward_picture.png) 

![Picture](assets/media/hot_potato_112x112.png) ![Picture](assets/media/hot_potato_56x56.png) ![Picture](assets/media/hot_potato_28x28.png) 



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

