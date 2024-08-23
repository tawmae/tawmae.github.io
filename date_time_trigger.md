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
