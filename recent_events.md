---
title: Recent Events
layout: default
nav_order: 5
---

![Picture](assets/general/title_recentevents.png)

Twitch
{: .label .label-purple }

OBS
{: .label .label-yellow }

StreamerBot
{: .label .label-blue }


# Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---



## <span class="iconify" data-icon="material-symbols:description-outline-sharp" data-inline="false"></span> Description
Display the four recent Twitch events in your OBS overlay.

![Picture](assets/media/recent_events_new_title_2.png)

Supported events are follows, raids, subs, resubs, giftsubs, giftbombs, cheers and kofi donations.

- - - -

## <span class="iconify" data-icon="tabler:tool" data-inline="false"></span> Setup

1. Go into Streamerbot and head to the tab `Servers/Clients -> WebSocket Server` and start the websocket server. Leave the adress at `127.0.0.1` and the port at `8080`. Check `Auto Start` as well. You can set a password, but you don't have to. If you do, make sure `Enforce for All Requests` stays unchecked.

   [![Picture](assets/media/notif_sb.png)](https://tawmae.github.io/assets/media/notif_sb.png)
   
2. Copy the URL: `https://tawmae.github.io/overlays/RecentEvents.html`
   
3. Go into your OBS, create a browser source and paste the URL in there. Preferably set the resolution to your canvas size.
   
   [![Picture](assets/media/notif_obs_1.png)](https://tawmae.github.io/assets/media/notif_obs_1.png)
   
   [![Picture](assets/media/notif_obs_2.png)](https://tawmae.github.io/assets/media/recent_events_new_obs_1.png)
   
4. Done 🥳

{: .new }
To have the events in multiple scenes, don't create an individual browser source into any scene, but instead create a new **nested** scene and put just a single browser source in there. Then place that scene into all your other scenes. This way you won't have to create 20 browser sources for 20 scenes.

- - - -

## <span class="iconify" data-icon="material-symbols:dataset-linked-sharp" data-inline="false"></span> URL Parameters 

To customize the event list, you can add URL parameters. The first parameter gets added with a `?`, every next one with `&`.

Example:  
`https://tawmae.github.io/overlays/RecentEvents.html?color=red&font=Arial&usernamesize=36px`

---

### <span class="iconify" data-icon="ion:color-palette" data-inline="false"></span> Background Color

Changes the background color of the individual event bars. Supports hex codes.

`color=white`

`color=FFFFFF`

---

### <span class="iconify" data-icon="mdi:format-font" data-inline="false"></span> Font Family

Changes the font used for the event text. Supports standard fonts.

`font=Arial`

`font=Poppins`

---

### <span class="iconify" data-icon="mdi:account" data-inline="false"></span> Username Text Color

Changes the color of the username displayed in the event.

`usernamecolor=blue`

`usernamecolor=FF5733`

---

### <span class="iconify" data-icon="mdi:format-color-text" data-inline="false"></span> Event Text Color

Changes the color of the event description.

`eventcolor=green`

`eventcolor=00FF00`

---

### <span class="iconify" data-icon="mdi:format-size" data-inline="false"></span> Username Text Size

Changes the font size of the username text.

`usernamesize=26px`

`usernamesize=32px`

---

### <span class="iconify" data-icon="mdi:format-size" data-inline="false"></span> Event Text Size

Changes the font size of the event description text.

`eventsize=20px`

`eventsize=24px`

---

### <span class="iconify" data-icon="mdi:view-column" data-inline="false"></span> Container Width

Changes the width of the event container.

`width=700px`

`width=50%`

---

### <span class="iconify" data-icon="mdi:account-circle-outline" data-inline="false"></span> Anonymous Follows

Replaces the username and avatar with placeholders for follow events.

`anonymousfollows=true`

---

{: .new }
To clear the event list, you can hit the "Interact" button on the browser source and then press the `Escape` button on your keyboard.

---

## <span class="iconify" data-icon="material-symbols:published-with-changes" data-inline="false"></span> Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| December 01, 2024           | Release | 1.0.0 |
