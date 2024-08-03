---
layout: default
title: All-In-One Moderation Tools Command Overview
nav_exclude: true
---

![Picture](assets/media/aio_command_overview.png)

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

---

# **Hate Raid**

- ## `!chatShield [on/off]` or `!hateRaid [on/off]`
  {: .no_toc }
 
   Toggles the hate raid shield.

---

# **Channel Management**

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

- ## `!timeout [User] [Duration] [Reason]`
  {: .no_toc }
 
   Timeout a specified user. Duration (seconds) and reason are optional.

- ## `!ban [User] [Reason]`
  {: .no_toc }
 
   Timeout a specified user. The reason is optional.

- ## `!purge [User]`
  {: .no_toc }
 
   Deletes all messages of a specified user.

--- 

# **Raids and Shoutouts**

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
 
   Translates a given text into a chosen language.

- ## `!clear`
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
 
   Timeout a specified user. The reason is optional.

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

- ## `!predictionCreate [Title] | [Duration] | [Outcome1] | [Outcome2] | [Outcome3] ...`
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

- ## `!pollCreate [Title] | [Duration] | [Option1] | [Option2] | [Option2] ...`
  {: .no_toc }
 
   Creates a poll with up to 5 options. Requires a title and at least two options. The duration is optional. Seperated by a `|` symbol.

--- 
