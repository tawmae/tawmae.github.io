---
title: Date Time Trigger
layout: default
nav_order: 20
---

![Picture](assets/media/dt_title_1.png)

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
Trigger actions at a specific time every day or at a specific time at a specific date. You can set up as many times as you want.

![Picture](assets/media/dt_title_2.png)

---

## Import Code
```scss
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
```

---


## Installation

1. Copy the import code from above and import the content

    ![Import Actions](assets/media/import_actions.png)

2. Restart StreamerBot or go into the `[Date Time Trigger] Code` action, rightclick the `Streamer.bot Started` trigger and click "Test Trigger".

3. Done! 🥳

{: .note }
You need to restart / test the trigger only after the import. It will automatically start the next time you open up StreamerBot :) 

---

## Settings

In the `[Date Time Trigger] Settings` action, you'll be able to set your times (and dates). You can have as many timers as you want. You can have it trigger on a certain time **each** day or at a certain time on a **specific** day.

Each `Global (Set)` subaction is one timer. So `time_1` set at `00:00:00` will trigger at midnight. Now if `time_1` has a corresponding `date_1`, it will only trigger at midnight at the date of `date_1`. If you delete `date_1`, it will trigger ad midnight of **every** day.

The format for times is the 24h format `hh:mm:ss` and dates is `MM/DD/YYYY`.

{: .new }
If `time_X` has a corresponding `date_X`, it will trigger at the specific date. If there's no correspondig `date_X`, `time_1` will trigger daily.

![Picture](assets/media/dt_settings.png)

{: .highlight }
If you change times and/or dates, you need to rightclick the `Test` trigger and hit "Test Trigger"

![Import Actions](assets/media/dt_test.png)

---

## Custom Trigger

What you actually use to trigger other actions is the custom `Date Time Trigger` trigger.

![Import Actions](assets/media/dt_trigger.png)

This trigger triggers for **all** timers that you have set up. To narrow the trigger down to a specific one, you can use the variables that it populates

`%timeOnly%` is a bool that is either `True` or `False`. It indicates whether the trigger was set to a specific date (=`False`) or to every day (=`True`)

`%timeTrigger%` is the date and/or time of your timer. So if `%timeOnly%` was `True`, it will only show the time in the format `hh:mm:ss`. If `%timeOnly%` is `False`, it will show the entire datetime in the format `MM/DD/YYYY hh:mm:ss`.

![Import Actions](assets/media/dt_vars.png)

![Import Actions](assets/media/dt_vars2.png)

---

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| June 28, 2024           | Release | 1.0.0 |
