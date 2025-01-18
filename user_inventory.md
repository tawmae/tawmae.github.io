---
title: User Inventory
description: A full inventory system for your Twitch chat
layout: default
parent: Utility
---

![Picture](assets/general/title_inventory.png)

Twitch
{: .label .label-purple }

StreamerBot
{: .label .label-blue }


# Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## <span class="iconify" data-icon="material-symbols:description-outline-sharp" data-inline="false"></span> Description

Users in chat are able to store items in their own inventory. They can either loot a random item or have an item added manually. Upon usage, specific items can trigger specific actions and allow for funny interactions!

![User Inventory](assets/media/user_inventory_title_2.png)

_Examples:_
- a *VIP voucher* that grants a user VIP
-  a *Potion Of Silence* that mutes the streamer's mic
- a *Ban Hammer* that allows the user to timeout another user

- - - -

## <span class="iconify" data-icon="material-symbols:content-copy-outline-sharp" data-inline="false"></span> Import Code
```
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
```

- - - -

## <span class="iconify" data-icon="tabler:tool" data-inline="false"></span> Installation

1. Copy the import code from above and import the content

    ![Import Actions](assets/media/import_actions.png)

2. Move to the `Commands` tab and enable the imported commands

    ![How To Enable Commands](assets/media/enable_commands.png)

3. Done! 🥳

- - - -

## <span class="iconify" data-icon="rivet-icons:exclamation-mark-circle-solid" data-inline="false"></span> Commands

- ## `!ADDITEM [USERNAME] [ITEM] <AMOUNT>`
  {: .no_toc }

    ![User Inventory](assets/media/user_inventory_add_item.png) 

    Add an item of your choice to a user's inventory. The items can contain spaces. Set the optional amount in angled brackets (e. g. Health Potion <10>).

- - - -


- ## `!REMOVEITEM [USERNAME] [ITEM] <AMOUNT>`
  {: .no_toc }

    ![User Inventory](assets/media/user_inventory_remove_item.png)

    Remove a specific item from a user's inventory with an optional amount in angled brackets(e. g. Health Potion <10>).

- - - -


- ## `!USE [ITEM] <AMOUNT>`
  {: .no_toc } 

    ![User Inventory](assets/media/user_inventory_use_item.png)

    Use an item in your inventory with an optional amount in angled brackets (e. g. Health Potion <10>). This populates the variables `usedItem` and `usedItemAmount`.

- - - -


- ## `!ITEMS` or `!INVENTORY`
  {: .no_toc } 

    ![User Inventory](assets/media/user_inventory_items.png)

    See the content of your inventory.

- - - -

- ## `!TRADE [USER] [OFFERED ITEM] <AMOUNT> | [WANTED ITEM] <AMOUNT>`
  {: .no_toc } 

    ![User Inventory](assets/media/user_inventory_trade_item.png)

    Trade items with a user. Only one trade request at the time. Amount is optional. Example: `!trade tawmae Health Potion <10> | Obsidian Sword` to trade 10 Health Potions for one Obsidian Sword.

  If you don't enter a pipe symbol `|`, you can gift the item to the other user. Example: `!trade tawmae Cookie`.

- - - -

- ## `!ACCEPTTRADE`
  {: .no_toc } 

    ![User Inventory](assets/media/user_inventory_accept_trade.png)

    Accept a trade offer.

- - - -

- ## `!CANCELTRADE`
  {: .no_toc } 

    ![User Inventory](assets/media/user_inventory_cancel_trade.png)

    Decline a trade offer or take your own offer back.

- - - -

{: .new }
Items are case-sensitive!

- - - -

## <span class="iconify" data-icon="material-symbols:family-star-outline" data-inline="false"></span> Example: Trigger an item effect

As mentioned in the `!use [Item]` command, you can use the populated variables to trigger specific actions for specific items (and their amount). The easiest way is to create an if/else-subaction under `Core -> Logic -> If/Else`.

You then check for `usedItem` -> `Equals` -> "The Name Of Your Item" and attach the action to it that you want to fire. For example playing a sound or triggering an OBS filter. In my example below, my item is called "Catnap", which triggers the "Catnip Sound" action.

[![Picture](assets/media/user_inventory_example_use.png)](https://tawmae.github.io/assets/media/user_inventory_example_use.png)

You can stack as many if/else-subactions as you want, ideally one for every item you have.

- - - -

## <span class="iconify" data-icon="material-symbols:family-star-outline" data-inline="false"></span> Example: Loot a random item

![User Inventory](assets/media/user_inventory_loot_3.png)

The previous versions had a dedicated loot action. This one doesn't, but you can still achieve that. For that, you can simply create a new group in the `[User Item Inventory] 1 - Add Item` action and put the `Set Argument - itemName` subaction in there. You can then duplicate that `Set Argument` subaction as many times as you like - each subaction will be one item.

[![Picture](assets/media/user_inventory_loot_1.png)](https://tawmae.github.io/assets/media/user_inventory_loot_1.png)

You then rightclick the group and select `Random`. This will pick one of the subactions at random. To specifiy the odds even more, you can rightclick the `Set Argument` subactions and set their weighting. Higher weight -> higher probability. 

![User Inventory](assets/media/user_inventory_loot_2.png)

The `!addItem` command is not affected by this. This only applies to any other trigger that is **not** a command (like a Channel Point Reward Redemption).

- - - - 

{: .highlight }
If you used this extension prior to version 2.0.0, use the `Convert Old Inventory` action to convert the older inventories to the structure of the new ones.

## <span class="iconify" data-icon="material-symbols:published-with-changes" data-inline="false"></span> Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| September 8, 2024           | Complete overhaul, added trading | 2.0.0 |
| August 16, 2024           | Updated to Streamer.bot version 0.2.4 | 1.0.0 |
| May 9, 2024           | Changed the global variable methods to userId instead of the user's display name | 0.2.4 |
