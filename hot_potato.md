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

- In the `[Hot Potato] Pass On` action, you can set `passesGameEnd` to a number of your liking. The game will automatically end and resolve in a draw once the potato has been passed along this many times.

  ![Picture](assets/media/hot_potato_settings_3.png)

- In the `[Hot Potato] Fetch Active Users` action, you can set `ignoreMods` to `True` for it to ignore moderators for the game. You can also enter a group in `excludedGroup`. All users in that group will also get ignored for the game.

  ![Picture](assets/media/hot_potato_settings_10.png) 

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


## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| May 10, 2024           | Fixed an issue when the potato has been passed in the very last milliseconds. Added `ignoreMods` and `excludedGroup` settings to the `Fetch Active Users` action | 0.2.5 |
| May 09, 2024           | Added "User Timed Out" and "User Banned" Twitch triggers to the `Exclude` action, to exclude timeouted and banned users from the active chatters list // Added an option to have accounts in a group ignored for active chatters (requires to go into the `Fetch Active Users` code and replacing the group name in there) | 0.2.4 |
| May 06, 2024           | Fixed an issue with disabling and re-enabling the channel rewards after a game has ended | 0.2.3 |

