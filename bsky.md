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

Linebreaks

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

Emded images.

You can embed an image from a link with two curly brackets. Example:
```
{https://www.example.com/image.png}
```

You also also embed images from a filepath with square brackets. Example:
```
[C:\User\tawmae\Image.png]
```

---

Clickable URLs

To make URLs clickable, you can put them into angled brackets. Example:
```
<www.twitch.tv/tawmae>
```

---

So this text input would result in the following post:

{: .new }
Pretend there are variables in the example text below, github pages just won't let me populate them here KEKW

bskyText:
`Well hello there, || || we are live at <www.twitch.tv/targetUserName> || || We are playing Game XY today! Hope to see you there! {targetUserProfileImageUrl}`

![Picture](assets/media/bsky_title_2.png)

 {: .note }
 > You **can** embed multiple images at once
 >
 > You **cannot** create a URL preview

---

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| October 23, 2024           | Added Mention support | 1.0.2 |
| October 23, 2024           | Added Hashtag support | 1.0.1 |
| August 30, 2024           | Release | 1.0.0 |
