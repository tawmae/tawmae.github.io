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

This trigger triggers for **all** timers that you have set up. To narrow the trigger down to a specific one, you can use the variables that it populates

`%timeOnly%` is a bool that is either `True` or `False`. It indicates whether the trigger was set to a specific date (=`False`) or to every day (=`True`)

`%timeTrigger%` is the date and/or time of your timer. So if `%timeOnly%` was `True`, it will only show the time in the format `hh:mm:ss`. If `%timeOnly%` is `False`, it will show the entire datetime in the format `MM/DD/YYYY hh:mm:ss` or `dddd hh:mm:ss` in case it was triggered on a specific day of the week.

![Import Actions](assets/media/dt_vars.png)

![Import Actions](assets/media/dt_vars2.png)

![Import Actions](assets/media/dt_vars3.png)

---

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| August 11, 2024           | Added debugging | 1.1.1 |
| August 04, 2024           | `date_1` ... `date_x` can now be a weekday (Monday to Sunday) to always trigger on a specific day of the week | 1.1.0 |
| June 28, 2024           | Release | 1.0.0 |
