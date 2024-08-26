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

2. Restart StreamerBot or go into the `[Date Time Trigger] Code` action, rightclick the `Streamer.bot Started` trigger and click "Test Trigger".

3. Done! 🥳

{: .note }
You need to restart / test the trigger only after the import. It will automatically start the next time you open up StreamerBot :) 

---

## Settings

In the `[Date Time Trigger] Settings` action, you'll be able to set your times (and dates). You can have as many timers as you want. You can have it trigger on a certain time **each** day or at a certain time on a **specific** day. This day can be a date like the 8th May of 2024 (`05/08/2024`) or a specific day of the week (`Sunday`).

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
| August 11, 2024           | Added debugging | 1.1.1 |
| August 04, 2024           | `date_1` ... `date_x` can now be a weekday (Monday to Sunday) to always trigger on a specific day of the week | 1.1.0 |
| June 28, 2024           | Release | 1.0.0 |
