---
title: Friend Stream Notifications
layout: default
nav_order: 19
---

![Picture](assets/media/friend_stream_notifications_title_1.png)

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
Get a custom trigger whenever a streamer you follow goes live.

![Picture](assets/media/friend_stream_notifications_title_2.png)

---

## Import Code
```scss
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
```

---


## Installation

1. Copy the import code from above and import the content

    ![Import Actions](assets/media/import_actions.png)

2. Restart Streamer.bot (or rightclick the trigger and hit "Test Trigger". *The action will automatically start once your Twitch account connects to Streamer.bot, so you will only have to do this on the initial import*.

3. Done! 🥳

---

## Variables

After setting the action up, you'll have a custom trigger called "Friend Stream Notifications" that will fire once one of your followed streamers goes live. You will have a bunch of variables available for use:

![Picture](assets/media/friend_stream_notifications_trigger.png)

![Picture](assets/media/friend_stream_notifications_variables.png)

- `%user%`
 
   The user's display name.

- `%userName%`
 
   The user's login name.

- `%userId%`
 
   The user's ID.

- `%profileImageUrl%`
 
   The user's profile image URL.

- `%title%`
 
   The stream's title.

- `%channelDescription%`
 
   The user's channel description.

- `%gameName%`
 
   The stream's category.

- `%startedAt%`
 
   Date and time of the stream start.

- `%language%`
 
   Language code of the stream, e.g. `en`.

- `%thumbnailUrl%`
 
   URL of the thumbnail in 1920x1080. Note: might not be populated right after stream start.

- `%isMature%`
 
   Bool whether the stream is set to "mature".

- `%tags%`
 
   The stream tags.

- `%isModerator%`
 
   Bool whether the user is a moderator in your channel.

- `%isFollowing%`
 
   Bool whether the user is following your channel.

- `%isSubscribed%`
 
   Bool whether the user is subscribed to your channel.

- `%isAffiliate%`
 
   Bool whether the user is an affiliate.

- `%isPartner%`
 
   Bool whether the user is a partner.


---

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| November 17, 2024           | Code optimization | 1.0.3 |
| November 14, 2024           | Code optimization | 1.0.2 |
| October 26, 2024           | Added more variables | 1.0.1 |
| October 25, 2024           | Release | 1.0.0 |
