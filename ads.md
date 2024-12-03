---
title: Ad Notification
layout: default
nav_order: 9
---

![Picture](assets/media/ad_title_1.png)

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
An overlay for when Twitch ads are about to start or are currently in progess.

![Picture](assets/media/ads_1.gif)

![Picture](assets/media/ads_2.gif)


- - - -

## <span class="iconify" data-icon="tabler:tool" data-inline="false"></span> Setup

1. Go into Streamerbot and head to the tab `Servers/Clients -> WebSocket Server` and start the websocket server. Leave the adress at `127.0.0.1` and the port at `8080`. Check `Auto Start` as well. You can set a password, but you don't have to. If you do, make sure `Enforce for All Requests` stays unchecked.

   [![Picture](assets/media/notif_sb.png)](https://tawmae.github.io/assets/media/notif_sb.png)
   
2. Copy the URL: 
   ```
   https://tawmae.github.io/overlays/Ads.html
   ```
   
3. Go into your OBS, create a browser source and paste the URL in there. Preferably set the resolution to your canvas size.
   
   [![Picture](assets/media/notif_obs_1.png)](https://tawmae.github.io/assets/media/notif_obs_1.png)
   
   [![Picture](assets/media/recent_events_new_obs_1.png)](https://tawmae.github.io/assets/media/recent_events_new_obs_1.png)
   
4. Done 🥳

{: .new }
To have the events in multiple scenes, don't create an individual browser source in every scene, but instead create a new **nested** scene and put just a single browser source in there. Then place that scene into all your other scenes. This way you won't have to create 20 browser sources for 20 scenes.

- - - -

## <span class="iconify" data-icon="material-symbols:dataset-linked-sharp" data-inline="false"></span> URL Parameters 

You can add `?sound=true` at the end of the URL to get a "plop" sound whenever the overlay pops up.

{: .new }
You can simulate events by creating a trigger (`Twitch -> Ads`), then rightclick it and hit `Simulate Event`. 

---

## <span class="iconify" data-icon="material-symbols:published-with-changes" data-inline="false"></span> Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| December 03, 2024           | Release | 1.0.0 |
