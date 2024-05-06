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
Timed Actions are deactivated on Import as well. It will enable itself the next time you start StreamerBot, but you can also manually enable it under `Settings -> Timed Actions` 

- - - -

## Settings (optional)

- In the `[Temporary VIP] Add Time` action, you can set a default time. The `defaultTime` is either used when no time is specified in a command or when you use a channel point reward. So a default time of `1d` would add 1 day if used with a channel point reward.

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

{: .new }
The extension automatically checks for expired VIPs whenever your Twitch stream goes live, whenever you use the `refreshVip` command **and** every 15 minutes. If you want to change the check interval, you can go to `Settings -> Timed Actions` and set the time for `Temporary VIP Expiration Check` to your liking.


- - - -
