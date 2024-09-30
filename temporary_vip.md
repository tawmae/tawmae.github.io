---
title: Temporary VIP
layout: default
nav_order: 3
---

![User Inventory](assets/media/temporary_vip_title.png)

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
Give users a VIP status - but only for a limited amount of time! You can either add a custom amount of time with a command or use a channel point reward with a set amount of time.

![User Inventory](assets/media/temporary_vip_title_2.png)

- - - -

## Import Code
```scss
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
```
- - - -

## Installation

1. Copy the import code from above and import the content

    ![Import Actions](assets/media/import_actions.png)

2. Move to the `Commands` tab and enable the imported commands

    ![How To Enable Commands](assets/media/enable_commands.png)

3. Done! 🥳

{: .highlight }
Timed Actions are deactivated on Import as well. It will enable itself the next time you start Streamer.bot, but you can also manually enable it under `Settings -> Timed Actions`.

- - - -

## Settings (optional)

- In the `[Temporary VIP] 1 - Add Time` action, you can set a default time. The `defaultTime` is either used when no time is specified in a command or when you use a channel point reward. So a default time of `1d` would add 1 day if used with a channel point reward.

{: .new }
Allowed time formats:  1y / 2mo / 3w / 4d / 5h / 6min / 7s

![Import Actions](assets/media/temporary_vip_settings.png)

- `allowStacking` will, as the name already suggests, allow that time is being stacked. So if you redeem it here twice, you will get 1 day + 1 day, so a total of 2 days of VIP. If set to false, it will just "refresh" to 1 day upon a new redemption.

- `maxSlots` is the maximum amount of available concurrent temporary VIPs. If it set to 5 and you have 5 temporary VIPs, then noone else will be able to become a new temporary VIP. You can however still stack additional time if you already are a temporary VIP.

- If you have **permanent VIPs**, you can add them to a group called `Permanent VIPs`. To create a group, go to `Settings -> Groups` and type in the name of the group down under "Add Group". In the `Viewers` tab, you can then rightclick a user and add them to the group.

- If you use the extension with a **Channel Point Reward**, make sure the reward is owned by StreamerBot, so it can be automatically be refunded whenever someone redeems it who wasn't supposed to do so. Also make sure `Redemption Skips Queue` stays unchecked in the reward's settings.

  ![Import Actions](assets/media/temporary_vip_cpr_settings.png)

- - - -

## Commands

- ## `!ADDVIP [USERNAME] [TIME]`
  {: .no_toc }

  ![Picture](assets/media/temporary_vip_add_vip.png)

  Adds VIP time to the specified user. If `[Time]` has been left blank, it will pick the default time that is set in the action. See the available time formats above.


- - - -


- ## `!REMOVEVIP [USERNAME] [TIME]`
  {: .no_toc }

  ![Picture](assets/media/temporary_vip_remove_vip.png)

  Removes VIP time. If no time is given or if the removed time exceeds the time the user had left, it will un-vip them immediately.


- - - -

- ## `!CHECKVIP`
  {: .no_toc }

  ![Picture](assets/media/temporary_vip_check_vip.png)

  Will allow the users to check when their VIP status expires. If a moderator or permanent VIP uses this, it lists all current temporary VIPs.

  ![Picture](assets/media/temp_vip_check_2.png)
  

- - - -

- ## `!REFRESHVIP`
  {: .no_toc }
  
    ![Picture](assets/media/temporary_vip_refresh_vip.png)

   A manual refresh and checks for expired VIPs. If any are expired, they'll be removed.


- - - -

{: .new }
The extension automatically checks for expired VIPs whenever your Twitch stream goes live, whenever you use the `refreshVip` command **and** every 15 minutes. If you want to change the check interval, you can go to `Settings -> Timed Actions` and set the time for `Temporary VIP Expiration Check` to your liking.


- - - -

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| September 30, 2024           | Removed "Ignore Internal Messages" checkmark from commands, changed `!removevip [User]` command to remove them as a VIP entirely if no time is given | 1.0.2 |
| September 29, 2024           | Added debugging | 1.0.1 |
| August 16, 2024           | Updated to Streamer.bot version 0.2.4 | 1.0.0 |
| July 27, 2024           | Changed the date format output | 0.2.5 |
| May 06, 2024           | Added a "StreamerBot Started" trigger to automatically enable the Timed Action // Added a message split if the `!checkVip` response has more than 500 characters | 0.2.4 |
