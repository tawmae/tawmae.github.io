---
title: Advice Giver
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

![Picture](assets/media/bsky_giver_title_2.png)

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

1. Linebreaks
   - You create line breaks with two pipe symbols. Example:
    ```
    Hello, || my name is tawmae.
    ```
    turns into
    ```
    Hello,
    my name is tawmae
    ```

2. Emded images.
   - You can embed an image from a link with two curly brackets. Example:
    ```
    {https://www.example.com/image.png}
    ```

  - You also also embed images from a filepath with square brackets. Example:
    ```
    [C:\User\tawmae\Image.png]
    ```

3. Clickable URLs
   - To make URLs clickable, you can put them into angled brackets. Example:
    ```
    <www.twitch.tv/tawmae>
    ```


So this text input would result in the following post:

bskyText:
```
Well hello there, || || we are live at <www.twitch.tv/%targetUserName%> || || We are playing %game% today! Hope to see you there! {%targetUserProfileImageUrl%}
```

|
V

![Picture](assets/media/bsky_giver_title_2.png)

 {: .note }
 > You **can** embed multiple images at once
 >
 > You **cannot** create a URL preview

---

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| August 30, 2024           | Release | 1.0.0 |
