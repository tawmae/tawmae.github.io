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

- - - -

## Settings (optional)

- In the `[Temporary VIP] Add Time` action, you can set a default time. The `defaultTime` is either used when no time is specified in a command or when you use a channel point reward. So a default time of `1d` would add 1 day if used with a channel point reward.

{: .new }
Allowed time formats:  1y / 2mo / 3d / 4h / 5min / 6s

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

  Removes VIP time. If the removed time exceeds the time the user had left, it will un-vip them. So to completely remove someone from being a timed VIP, you can just remove 100 years.


- - - -

- ## `!CHECKVIP`
  {: .no_toc }

  ![Picture](assets/media/temporary_vip_check_vip.png)

  Will allow the users to check when their VIP status expires. If a moderator or permanent VIP uses this, it lists all current temporary VIPs.


- - - -

- ## `!REFRESHVIP`
  {: .no_toc }
  
    ![Picture](assets/media/temporary_vip_refresh_vip.png)

   A manual refresh and checks for expired VIPs. If any are expired, they'll be removed.


- - - -

The extension checks automatically for expired VIPs whenever your Twitch stream goes live, whenever you use the `refreshVip` command **and** every 15 minutes. If you want to change the check interval, you can go to `Settings -> Timed Actions` and set the time for `Temporary VIP Expiration Check` to your liking.

