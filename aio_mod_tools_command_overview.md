---
layout: default
title: All-In-One Moderation Tools Command Overview
nav_exclude: true
---

![Picture](assets/general/title_aiomod.png)

Here's a full command overview for the All-In-One Moderation Tools extension. Most of them have extra settings that are highly customizable within the Settings UI.

---

# Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# **URL Filter**

- ## `!permit [User]`
  {: .no_toc }
 
   Permit a specified user to post links to chat for a given amount of time.

- ## `!whitelistURL [URL]`
  {: .no_toc }
 
   Add a link to the whitelist.

- ## `!removeWhitelistURL [URL]`
  {: .no_toc }
 
   Removes a link from the whitelist.

# **Follow Bot Attacks**

- ## `!followShield [on/off]`
  {: .no_toc }
 
   Toggles the Follow Bot Attack shield mode.

- ## `!followAttackUndoAll`
  {: .no_toc }
 
   Unblocks and unbans every user that got caught during an active Follow Attack Shield. This is just a safety measure.

- ## `!removeAllFollowers [Minutes]`
  {: .no_toc }
 
   Removes all followers that have followed within the last X minutes. Also works if Streamer.bot wasn't active during the follows.

---

# **Hate Raid**

- ## `!hateShield [on/off]` or `!hateRaid [on/off]`
  {: .no_toc }
 
   Toggles the hate raid shield.

---

# **Channel Management**

- ## `!addCommand [!command] [Command Text]`
  {: .no_toc }
 
  Adds a custom command with a simple text output. Can contain `%user%` and `%userName%` variables.

- ## `!editCommand [!command] [Command Text]`
  {: .no_toc }
 
  Edits a custom command.

- ## `!removeCommand [!command]`
  {: .no_toc }
 
  Removes a custom command.

- ## `!customCommands`
  {: .no_toc }
 
  Shows all custom commands.

- ## `!channelTitle [Title]`
  {: .no_toc }
 
   Set a channel title.

- ## `!channelGame [Game]` or `!channelCategory [Category]`
  {: .no_toc }
 
   Set the channel game/category.

- ## `!channelSetTags [Tag1] | [Tag2] | [Tag3] ...`
  {: .no_toc }
 
   Set up to 10 channels tags, seperated by a `|` symbol.

- ## `!channelAddTag [Tag]`
  {: .no_toc }
 
   Add a channel tag.

- ## `!channelRemoveTag [Tag]`
  {: .no_toc }
 
   Remove a channel tag.

- ## `!channelClearTags`
  {: .no_toc }
 
   Clear all channel tags (Note: The Twitch API requires at least one tag to always be set, so it will instead remove all tags and add a "No Tags" placeholder).

---

# **OBS Management**

- ## `!scenes`
  {: .no_toc }
 
   Lists all OBS scene names in chat.

- ## `!setScene [Scene Name]` or `!changeScene [Scene Name]`
  {: .no_toc }
 
   Set a specific active OBS scene.

- ## `!endStream`
  {: .no_toc }
 
   Ends the stream. The possibility for mods to end the stream can be crucial in some situations. This is disabled by default and, if enabled, requires a double-confirmation to avoid accidentally ending the stream.

  


--- 

# **Raids and Shoutouts**

- ## `!raid [User]`
  {: .no_toc }
 
   Raid a channel.

- ## `!raidCancel` or `!cancelRaid`
  {: .no_toc }
 
   Cancel an ongoing raid.

- ## `!raidMessage`
  {: .no_toc }
 
   Posts a custom raid message into chat (for users to copy, when you are about to start a raid).

- ## `!modShoutout [User]`
  {: .no_toc }
 
   Posts a shoutout into chat and also does the Twitch integrated shoutout.

--- 

# **Chat Management**

- ## `!modTranslate [Text]`
  {: .no_toc }
 
   Translates a given text into a chosen language (also works with just `!modTranslate` when used in a reply).

- ## `!clearChat`
  {: .no_toc }
 
   Clear chat.

- ## `!warn [User] [Reason]`
  {: .no_toc }
 
   Warn a specified user. The reason is optional.

- ## `!timeout [User] [Duration] [Reason]`
  {: .no_toc }
 
   Timeout a specified user. Duration (seconds) and reason are optional.

- ## `!ban [User] [Reason]`
  {: .no_toc }
 
   Ban a specified user. The reason is optional.

- ## `!unban [User]`
  {: .no_toc }
 
   Unban a specified user.

- ## `!purge [User]`
  {: .no_toc }
 
   Deletes all messages of a specified user.

- ## `!addBlockedTerm [Term]`
  {: .no_toc }
 
   Adds a blocked term to the Twitch internal block list.

- ## `!removeBlockedTerm [Term]`
  {: .no_toc }
 
   Removes a blocked term from the Twitch internal block list.

- ## `!modRunAd [Duration]`
  {: .no_toc }
 
  Runs a commercial for the specified duration (max. 180 seconds, will default to 180 if exceeded).

- ## `!slowMode [Delay (seconds)]`
  {: .no_toc }
 
  Toggles the chat slow mode for the specified delay in seconds.

- ## `!followerMode [Delay]` or `!followersOnly [Duration]`
  {: .no_toc }
 
  Toggles the followers-only chat with the specified minimum follow duration. If [Duration] is just a number, it will default to hours. You can specify the time format with `min`, `h` or `d`, like `!followerMode 1d` for set it to a day.

- ## `!emoteOnly [on/off]`
  {: .no_toc }
 
  Toggles the followers-only chat with the specified minimum follow duration in hours.

- ## `!subMode` or `!subOnly`
  {: .no_toc }
 
  Toggles the subscribers-only chat.

- ## `!ttsStop` or `!stopTts`
  {: .no_toc }
 
  Stops the current TTS.

- ## `!ttsPause` or `!pauseTts`
  {: .no_toc }
 
  Pauses the TTS queue.

- ## `!ttsClear` or `!clearTts`
  {: .no_toc }
 
  Clears the TTS queue.

- ## `!ttsResume` or `!resumeTts`
  {: .no_toc }
 
  Resumes the TTS queue.

- ## `!autoMod [Level]`
  {: .no_toc }
 
  Enables AutoMod level 0 to 4.

--- 

# **Channel Point Rewards**

- ## `!rewardEnable [Reward Name]`
  {: .no_toc }
 
   Enables a specified channel point reward.

- ## `!rewardDisable [Reward Name]`
  {: .no_toc }
 
   Disables a specified channel point reward.

- ## `!rewardPause [Reward Name]`
  {: .no_toc }
 
   Pauses a specified channel point reward.

- ## `!rewardUnpause [Reward Name]`
  {: .no_toc }
 
   Unpauses a specified channel point reward.

- ## `!rewardTitle [Reward Name] | [Title]`
  {: .no_toc }
 
   Sets the title of a specified channel point reward, seperated by a `|` symbol.

- ## `!rewardPrompt [Reward Name] | [Prompt]` or `!rewardDescription [Reward Name] | [Cost]`
  {: .no_toc }
 
   Sets the prompt/description of a specified channel point reward, seperated by a `|` symbol.

- ## `!rewardCost [Reward Name] | [Cost]`
  {: .no_toc }
 
   Sets the cost of a specified channel point reward, seperated by a `|` symbol.

--- 

# **Predictions**

- ## `!predictionCreate [Title] | [Duration] | [Outcome1] | [Outcome2] ...`
  {: .no_toc }
 
   Creates a channel point prediction with up to 10 outcomes. Requires a title and at least two outcomes. The duration is optional. Seperated by a `|` symbol.

- ## `!predictionLock`
  {: .no_toc }
 
   Locks the currently active prediction.

- ## `!predictionCancel`
  {: .no_toc }
 
   Cancels the currently active prediction.

- ## `!predictionResolve [Outcome Number]` or `!predictionResolve [Outcome Title]`
  {: .no_toc }
 
   Resolves a prediction after it's been locked. Can either be an outcome number like `1` or the actual outcome title.

--- 

# **Polls**

- ## `!pollCreate [Title] | [Duration] | [Option1] | [Option2] ...`
  {: .no_toc }
 
   Creates a poll with up to 5 options. Requires a title and at least two options. The duration is optional. Seperated by a `|` symbol.

- ## `!pollEnd`
  {: .no_toc }
 
   Ends the current poll.

- ## `!pollArchive`
  {: .no_toc }
 
   Archives the current poll.

--- 
