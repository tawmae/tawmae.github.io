---
title: Extended Hugs
layout: default
nav_order: 7
---

![Picture](assets/media/extended_hugs_title_2.png)

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

Let your viewers hug other viewers if they have given their consent (optional). Consent can be given to all, to none, to specific users and for individual hug requests. 

Stats for hugs given and received are saved in user variables (total hugs and individual hugs given/received to/from specific users). Those can be displayed in a leaderboard for example.

![Picture](assets/media/extended_hugs_title.gif)

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

3. Done! 🥳 

---

## Configuration

1. You can set `consentOn` to `True` if you want to activate the requirement for consent in total 

    ![Picture](assets/media/extended_hugs_settings_1.png)


2.  `showStats` can be set to `True` if you want individual user stats shown after each hug (these get saved nontheless) 

    ![Picture](assets/media/extended_hugs_show_stats.png)

3. For the leaderboard, you can set the argument to `True` to exclude the broadcaster and bot account 

    ![Picture](assets/media/extended_hugs_settings_2.png)
  
    ![Picture](assets/media/extended_hugs_leaderboard.png)

---

## Commands

- ## `!HUG [USERNAME]`
  {: .no_toc }

   (Request to) Hug a user. The username does not have to be exact. The command will first go through your Twitch viewer list. So if you typed "!hug tommy" and a person in your viewerlist is called "Tommy_123", that user will get hugged. A precise name is of course always the best way to ensure to hug the correct person :)

---

- ## `!HUG ALL`
  {: .no_toc }

   Hugs everyone in chat.

---

- ## `!CONSENT` or `!CONSENT [USER]`
  {: .no_toc }

   If you type "!consent" without a specified user, you will give consent to the first hug request in your queue.

---

- ## `!NOCONSENT` or `!NOCONSENT [USER]`
  {: .no_toc }

   If you type "!noconsent" without a specified user, you will refuse consent to the first hug request in your queue.

---

- ## `!CONSENT ALL`
  {: .no_toc }

   Give consent for all upcoming hug requests.

---

- ## `!CONSENT ALL REVOKE`
  {: .no_toc }

   Revoke the consent-for-all hug requests.

---

- ## `!CONSENT NONE`
  {: .no_toc }

   Give no-consent for all upcoming hug requests.

---

- ## `!CONSENT NONE REVOKE`
  {: .no_toc }

   Revoke the no-consent for all hug requests.

---

- ## `!CONSENT USER [USERNAME]`
  {: .no_toc }

   Give consent for all upcoming hug requests to a specified user.

---

- ## `!CONSENT USER REVOKE [USERNAME]`
  {: .no_toc }

  Revoke the consent for all upcoming hug requests for a specified user.

---

- ## `!HUGLEADERBOARD`
  {: .no_toc }

   Shows the top 5 leaderboard of all hug givers and receivers.

---

{: .note }
You can only give consent to the latest hug request. If user1 requests to hug you and so does user2 before you could give consent to user1, then the request will be overwritten.


{: .note }
You can give "no-consent" to everyone (`!consent none`) while at the same time whitelist specified users (`!consent user [Username]`). 

---

## Changelog

{: .warning }
Extended Hugs update 2.0.0 receives a complete overhaul. It will not work natively with older versions. If you happened to run an older version and want to upgrade, please feel free to DM me and I'll work something out to transfer the user stats

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| June 29, 2024 | Using user IDs instead of user names // added viewer list to allow for not 100% precise user name inputs for hugs // added a consent queue, consent requests now stack // added !noconsent // added the possibility to give (no) consent to a specific user's request if you have multiple requests up | 2.0.0 |

