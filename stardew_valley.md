---
title: Stardew Valley
layout: default
parent: Games
---


![Picture](assets/media/stardew_valley_title.png)

Twitch
{: .label .label-purple }

StreamerBot
{: .label .label-blue }


# Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## **Description**
Receive game events through custom triggers and interact with the game.

![Picture](assets/media/stardew_valley_title_2.png)



---

## **Import Code**
```scss
Test
```

--- 

## **Mod Download**

{: .highlight }
You will need to install [SMAPI](https://smapi.io/) in order to use mods and then the actual `StardewWebApi (Streamer.bot)` mod, a slightly modified mod by the original creator [zunderscore](https://github.com/zunderscore/StardewWebApi).
 

- [StardewWebApi for StreamerBot.rar](assets/dlls/StardewWebApi_StreamerBot.rar)


 
---

## **Setup**

1. Download [**SMAPI**](https://stardewvalleywiki.com/Modding:Player_Guide/Getting_Started#Install_SMAPI) and install it. Detailed install instructions [here](https://stardewvalleywiki.com/Modding:Player_Guide/Getting_Started#Install_SMAPI).

{: .highlight }
Make sure to read the install instructions. SMAPI is required to load mods into Stardew Valley.

2. Download `StardewWebApi (Streamer.bot).rar` from above and unzip the folder into your `\Stardew Valley\Mods` directory.
   
   ![Picture](assets/media/stardew_valley_mod_dir.png)

3. Go into Streamer.bot, copy the import code from above and import the content
   
   ![Import Actions](assets/media/import_actions.png)

4. Done! 🥳 The import also included a websocket client. It is set to auto-connect, but once you've started the game, make sure it's connected and set to `Open`.

   ![Picture](assets/media/stardew_valley_ws.png)

---

## **Custom Triggers**

The mod comes with a bunch of events that can be used a custom trigger under `Custom -> Stardew Valley`.

![Picture](assets/media/stardew_valley_triggers_1.png)
![Picture](assets/media/stardew_valley_triggers_2.png)

### Connected
Triggers when the mod connects.
Variables: `none`

### SaveLoaded
Triggers when a save has been loaded.
Variables:
- `farmName` *(string)* - the name of the farm
- `playerName` *(string)* - the name of the player
  
### Saved
Triggers when the game saves.
Variables:
- `farmName` *(string)* - the name of the farm
- `playerName` *(string)* - the name of the player

### Return To Title
Triggers when the game returns to title screen.
Variables: `none`

### Day Started
Triggers when a new day starts.
Variables:
- `season` *(string)* - the current season
- `day` *(int)* - the current day
- `year` *(int)* - the current year
- `dayOfWeek` *(string)* - the current day of the week
- `shortDayOfWeek` *(string)* - a shortened version of the current day of the week
- `weather` *(string)* - the current weather

### Day Ending
Triggers when a day is ending.
Variables:
- `season` *(string)* - the current season
- `day` *(int)* - the current day
- `year` *(int)* - the current year
- `dayOfWeek` *(string)* - the current day of the week
- `shortDayOfWeek` *(string)* - a shortened version of the current day of the week
- `weather` *(string)* - the current weather

### Time Changed
Triggers when the time updates (e.g. 06:30 AM to 06:40 AM).
Variables:
- `oldTime` *(int)* - the old time value
- `newTime` *(int)* - the new time value

### Player Inventory Changed
Triggers when the players get a new item, loses an item or gets more items to an already existing stack.
Variables:
- `playerName` *(string)* - the name of the player
- `addedItemCount` *(int)* - count of newly added unique items (e.g. +1 Diamond, +1 Stone that the player did not have in their inventory before makes an `addedItemCount` of `2`)
- `removedItemCount` *(int)* - same as above but for removed items
- `changedItemCount` *(int)* - same as above but for items that changed in quantity
- `addedItem_[i]_itemId` *(string)* - indexed added item id (starting with i=0, like input0 etc.)
- `addedItem_[i]_itemName` *(string)* - indexed added item name
- `addedItem_[i]_itemDisplayName` *(string)* - indexed added item display name
- `addedItem_[i]_itemQuality` *(int)* - indexed added item quality value
- `addedItem_[i]_itemCategory` *(int)* - indexed added item category value
- `addedItem_[i]_stackSize` *(int)* - indexed added item stack size
- `removedItem_[i]_itemId` *(string)* - indexed removed item id (starting with i=0, like input0 etc.)
- `removedItem_[i]_itemName` *(string)* - indexed removed item name
- `removedItem_[i]_itemDisplayName` *(string)* - indexed removed item display name
- `removedItem_[i]_itemQuality` *(int)* - indexed removed item quality value
- `removedItem_[i]_itemCategory` *(int)* - indexed removed item category value
- `removedItem_[i]_stackSize` *(int)* - indexed removed item stack size
- `quantityChangedItem_[i]_itemId` *(string)* - indexed quantity changed item id (starting with i=0, like input0 etc.)
- `quantityChangedItem_[i]_itemName` *(string)* - indexed quantity changed item name
- `quantityChangedItem_[i]_itemDisplayName` *(string)* - indexed quantity changed item display name
- `quantityChangedItem_[i]_oldQuantity` *(int)* - indexed quantity changed item previous stack size
- `quantityChangedItem_[i]_newQuantity` *(int)* - indexed quantity changed item new stack size

### Player Level Changed
Triggers when the player's level changes.
Variables:
- `playerName` *(string)* - the name of the player
- `skill` *(string)* - the player's skill
- `oldLevel` *(int)* - the old level
- `newLevel` *(int)* - the new level

### Player Warped
Triggers when the player gets warped (changes location).
Variables:
- `playerName` *(string)* - the name of the player
- `oldLocation` *(string)* - the old location
- `newLocation` *(string)* - the new location

### Player Warped
Triggers when the player gets warped (changes location).
Variables:
- `npcName` *(string)* - the name of the NPC
- `npcType` *(string)* - the old location
- `newLocation` *(string)* - the new location

### Friendship Increased
Triggers when the player's friendship with an NPC increases.
Variables:
- `npcName` *(string)* - the name of the NPC
- `npcType` *(int)* - the type of NPC
- `previousPoints` *(int)* - the previous friendship points
- `newPoints` *(int)* - the new friendship points
- `previousHearts` *(int)* - the previous heart count
- `newHearts` *(int)* - the new heart count

### Multiple Friendships Increased
Triggers when the player's friendship with multiple NPCs increases.
Variables:
- `npcCount` *(int)* - the number of NPCs whose friendship increased
- `npc_[i]_name` *(string)* - indexed NPC name
- `npc_[i]_type` *(int)* - indexed NPC type
- `npc_[i]_previousPoints` *(int)* - indexed previous friendship points
- `npc_[i]_newPoints` *(int)* - indexed new friendship points
- `npc_[i]_previousHearts` *(int)* - indexed previous heart count
- `npc_[i]_newHearts` *(int)* - indexed new heart count

### Friendship Decreased
Triggers when the player's friendship with an NPC decreases.
Variables:
- `npcName` *(string)* - the name of the NPC
- `npcType` *(int)* - the type of NPC
- `npcUrl` *(string)* - the URL of the NPC
- `previousPoints` *(int)* - the previous friendship points
- `newPoints` *(int)* - the new friendship points
- `previousHearts` *(int)* - the previous heart count
- `newHearts` *(int)* - the new heart count

### Multiple Friendships Decreased
Triggers when the player's friendship with multiple NPCs decreases.
Variables:
- `npcCount` *(int)* - the number of NPCs whose friendship decreased
- `npc_[i]_name` *(string)* - indexed NPC name
- `npc_[i]_type` *(int)* - indexed NPC type
- `npc_[i]_previousPoints` *(int)* - indexed previous friendship points
- `npc_[i]_newPoints` *(int)* - indexed new friendship points
- `npc_[i]_previousHearts` *(int)* - indexed previous heart count
- `npc_[i]_newHearts` *(int)* - indexed new heart count

### Player Started Dating
Triggers when the player starts dating an NPC.
Variables:
- `npcName` *(string)* - the name of the NPC
- `npcType` *(int)* - the type of NPC

### Player Stopped Dating
Triggers when the player stops dating an NPC.
Variables:
- `npcName` *(string)* - the name of the NPC
- `npcType` *(int)* - the type of NPC

### Player Engaged
Triggers when the player gets engaged to an NPC.
Variables:
- `npcName` *(string)* - the name of the NPC
- `npcType` *(int)* - the type of NPC

### Player No Longer Engaged
Triggers when the player is no longer engaged to an NPC.
Variables:
- `npcName` *(string)* - the name of the NPC
- `npcType` *(int)* - the type of NPC

### Player Married
Triggers when the player marries an NPC.
Variables:
- `npcName` *(string)* - the name of the NPC
- `npcType` *(int)* - the type of NPC
- `isRoommate` *(bool)* - whether the NPC is a roommate

### Player Divorced
Triggers when the player divorces an NPC.
Variables:
- `npcName` *(string)* - the name of the NPC
- `npcType` *(int)* - the type of NPC
- `wasRoommate` *(bool)* - whether the NPC was a roommate

### Festival Started
Triggers when a festival starts.
Variables:
- `festivalName` *(string)* - the name of the festival

### Festival Ended
Triggers when a festival ends.
Variables:
- `festivalName` *(string)* - the name of the festival

---

## Requests

The extension also comes with a bunch of requests

### Fully Heal Player
Fully heals the player.
Parameters:
- `hudMessage` *(string)* - a notification message that shows which user redeemed which request
Variables: `none`

### Get Player Info
Fetches various player info.
Variables:
- `name` *(string)* - the name of the player
- `displayName` *(string)* - the display name of the player
- `farmName` *(string)* - the name of the farm
- `money` *(string)* - the amount of money the player has
- `stamina` *(string)* - the current stamina of the player
- `maxStamina` *(string)* - the maximum stamina of the player
- `health` *(string)* - the current health of the player
- `maxHealth` *(string)* - the maximum health of the player
- `location` *(string)* - the current location of the player
- `dailyLuck` *(string)* - the daily luck value
- `dailyLuckDescription` *(string)* - the description of the daily luck value
- `skillName[i]` *(string)* - indexed name of the player's skill
- `skillLevel[i]` *(string)* - indexed level of the player's skill
- `skillProfessions[i]` *(string)* - indexed professions of the player's skill (comma-separated list)
- `datingWith` *(string)* - comma-separated list of NPCs the player is dating
- `engagedTo` *(string)* - comma-separated list of NPCs the player is engaged to
- `marriedTo` *(string)* - comma-separated list of NPCs the player is married to
- `roommateWith` *(string)* - comma-separated list of NPCs the player is a roommate with
- `divorcedTo` *(string)* - comma-separated list of NPCs the player is divorced from

### Get Player Inventory
Fetches inventory info.
Variables:
- `item[i]Name` *(string)* - indexed name of the item in the inventory
- `item[i]Quality` *(string)* - indexed quality of the item in the inventory
- `item[i]StackSize` *(string)* - indexed stack size of the item in the inventory
- `itemDictionary` *(string)* - JSON string representing the item dictionary, where the key is the item name and the value is a tuple of quality and stack size

### Give Item By ID
Gives the player one item of the specified ID.
Parameters:
- `hudMessage` *(string)* - a notification message that shows which user redeemed which request
Variables: `none`
Full List of Items here:

### Give Item By Name
Gives the player one item of the specified display name.
Parameters:
- `hudMessage` *(string)* - a notification message that shows which user redeemed which request
Variables: `none`
Full List of Items here:

### Give Money
Gives the player gold of the specified amount.
Parameters:
- `hudMessage` *(string)* - a notification message that shows which user redeemed which request
- `amount` *(int)* - the amount of gold to give (can also be a negative value)
Variables: `none`

### Knockout Player
Knocks the player out (essentially "kills" them).
Parameters:
- `hudMessage` *(string)* - a notification message that shows which user redeemed which request
Variables: `none`

### Pass Player Out
Fully drains the player's energy, causing them to pass out.
Parameters:
- `hudMessage` *(string)* - a notification message that shows which user redeemed which request
Variables: `none`

### Play Music Track
Plays a specified music track.
Parameters:
- `hudMessage` *(string)* - a notification message that shows which user redeemed which request
- `music` *(string)* - the music track
Variables: `none`
Full List of Music Tracks here:

### Play Sound
Plays a specified sound.
Parameters:
- `hudMessage` *(string)* - a notification message that shows which user redeemed which request
- `sound` *(string)* - the sound name
Variables: `none`
Full List of Sounds here:

### Refill Player's Energy
Fully refills the player's energy.
Parameters:
- `hudMessage` *(string)* - a notification message that shows which user redeemed which request
Variables: `none`

### Refill Player's Energy
Fully refills the player's energy.
Parameters:
- `largeHudMessage` *(string)* - shows a large text on screen with a specified message
Variables: `none`

###  Warp Player
Warps the player to a specified location (**Note: Can cause spoilers if you teleport yourself to a location you haven't unlocked or discovered yet**)
Parameters:
- `hudMessage` *(string)* - a notification message that shows which user redeemed which request
- `locationName` *(string)* - the name of the location
Variables: `none`
Full List of Locations here:

---

## **Changelog**

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|:-----|
| August 21, 2024           | Release | 1.0.0 |
