---
title: Date Time Trigger
layout: default
nav_order: 20
---

![Picture](assets/media/dt_title.png)

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

![Picture](assets/media/dt_title_2.gif)

---

## Import Code
```scss
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
```

---


## Installation

1. Copy the import code from above and import the content

    ![Import Actions](assets/media/import_actions.png)

2. Restart StreamerBot or go into the `[Date Time Trigger] 2 - Code` action, rightclick the `Streamer.bot Started` trigger and click "Test Trigger".

3. Done! 🥳

{: .note }
You need to restart / test the trigger only after the import. It will automatically start the next time you open up StreamerBot :) 

---

## Settings

In the `[Date Time Trigger] 1 - Settings` action, you'll be able to set your times (and dates). You can have as many timers as you want. You can have it trigger on a certain time **each** day or at a certain time on a **specific** day. This day can be a date like the 8th May of 2024 (`05/08/2024`) or a specific day of the week (`Sunday`).

Each `Global (Set)` subaction is one timer. So `time_1` set at `00:00:00` will trigger at midnight. Now if `time_1` has a corresponding `date_1`, it will only trigger at midnight at the date of `date_1`. If you delete `date_1`, it will trigger at midnight of **every** day.

The format for times is the 24h format `hh:mm:ss` and dates is `MM/DD/YYYY` or the day of the week `Wednesday`.

{: .new }
If `time_X` has a corresponding `date_X`, it will trigger at the specific date. If there's no correspondig `date_X`, `time_X` will trigger daily.

![Picture](assets/media/dt_settings.png)

{: .highlight }
If you change times and/or dates, you need to rightclick the `Test` trigger and hit "Test Trigger"

![Import Actions](assets/media/dt_test.png)

---

## Custom Trigger

What you actually use to trigger other actions is the custom `Date Time Trigger` trigger.

![Import Actions](assets/media/dt_trigger.png)

This trigger triggers for **all** timers that you have set up. To narrow the trigger down to a specific one, you can use the variables that it populates in an **if/else subaction** (`Core -> Logic -> If/Else).

`%timeOnly%` is a bool that is either `True` or `False`. It indicates whether the trigger was set to a specific date (=`False`) or to every day (=`True`)

`%timeTrigger%` is the date and/or time of your timer. So if `%timeOnly%` was `True`, it will only show the time in the format `hh:mm:ss`. If `%timeOnly%` is `False`, it will show the entire datetime in the format `MM/DD/YYYY hh:mm:ss` or `dddd hh:mm:ss` in case it was triggered on a specific day of the week.

![Import Actions](assets/media/dt_vars.png)

![Import Actions](assets/media/dt_vars2.png)

![Import Actions](assets/media/dt_vars3.png)


### Example
![Import Actions](assets/media/dt_Example_2.png)
![Import Actions](assets/media/dt_Example.png)
*(rightclick -> Copy Image URL to make it the image bigger)*

---

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| November 14, 2024           | Code optimization | 1.1.2 |
| August 11, 2024           | Added debugging | 1.1.1 |
| August 04, 2024           | `date_1` ... `date_x` can now be a weekday (Monday to Sunday) to always trigger on a specific day of the week | 1.1.0 |
| June 28, 2024           | Release | 1.0.0 |
