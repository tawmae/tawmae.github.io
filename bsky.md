---
title: Bluesky
layout: default
nav_order: 30
---

![Picture](assets/media/bsky_title_1.png)

StreamerBot
{: .label .label-blue }


# Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---


## Description
Create a post on Bluesky.

![Picture](assets/media/bsky_title_2.png)

---

## Import Code
```scss
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
```

---

## Installation

1. Copy the import code from above and import the content

    ![Import Actions](assets/media/import_actions.png)

2. Go into the `[Bluesky] Create Post` action and replace the information in the `Bsky Login Information` folder with yours. Be careful to not accidentally show this info on stream.

    ![Picture](assets/media/bsky_settings.png)

3. Done! 🥳

---


## Text Formatting

You edit the content of your post in the `bskyText` subaction of the `Settings` folder. It can just be plain text, but you can also have line breaks, embed images or make a URL clickable.

---

### Linebreaks

You create line breaks with two pipe symbols. Example:
```
Hello, || || my name is tawmae
```

turns into

```
Hello,

my name is tawmae
```

---

### Emdedded images

You can embed an image from a link with two curly brackets. Example:
```
{https://www.example.com/image.png}
```

You also also embed images from a filepath with square brackets. Example:
```
[C:\User\tawmae\Image.png]
```
---

 {: .new }
 > You can also use Alt Text for images by using a pipe symbol `|` after the link/path.
 >
 > Example: `{www.randompicture.com/picture.jpg|This is a picture of a cute orange cat}`
 

---

### URLs

To make URLs clickable, you can put them into angled brackets. Example:
```
<www.twitch.tv/tawmae>
```

---

So this text input would result in the following post:



bskyText:

```
This is a test message for the Bluesky extension by @tawmae.bsky.social 🔵 || || Find more Streamer.bot extensions over at <https://tawmae.github.io/> 🔥 || || #Streamerbot ✨ || #Twitch ✨ {https://tawmae.github.io/assets/media/sb_title.png|This is an alt text. The image says 'StreamerBot extensions' and contains logos of Twitch, Tawmae, OBS and Streamerbot}
```

![Picture](assets/media/bsky_title_2.png)

 {: .note }
 > You **can** embed multiple images at once
 >
 > You **cannot** create a URL preview



---

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| November 4, 2024           | Auto-compression of images that exceed 1 MB | 1.0.5 |
| November 3, 2024           | Fixed handling for special characters and emojis | 1.0.4 |
| October 24, 2024           | Added Alt Text support for images | 1.0.3 |
| October 23, 2024           | Added Mention support | 1.0.2 |
| October 23, 2024           | Added Hashtag support | 1.0.1 |
| August 30, 2024           | Release | 1.0.0 |
