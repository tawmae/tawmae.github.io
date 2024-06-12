---
title: User Inventory
layout: default
nav_order: 3
---

![User Inventory](assets/media/user_inventory_title.png)

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

Users in chat are able to store items in their own inventory. They can either loot a random item or have an item added manually. Upon usage, specific items can trigger specific actions and allow for funny interactions!

![User Inventory](assets/media/user_inventory_title_2.png)

_Examples:_
- a [*VIP-Voucher*](https://tawmae.github.io/user_inventory.html#items-to-import) that grants a user VIP
-  a *Potion Of Silence* that mutes the streamer's mic
- a *Ban Hammer* that allows the user to timeout another user

- - - -

## Import Code
```scss
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
```

- - - -

## Installation

1. Copy the import code from above and import the content

    ![Import Actions](assets/media/import_actions.png)

2. Move to the `Commands` tab and enable the imported commands

    ![How To Enable Commands](assets/media/enable_commands.png)

3. Done! 🥳

- - - -

## Commands

- ## `!ADD ITEM [USERNAME] [ITEM]`
  {: .no_toc }

    ![User Inventory](assets/media/user_inventory_add_item.png) 

    Add an item of your choice to a user's inventory. The items can contain spaces and can have a set amount before them (e. g. 10x Health Potion).

- - - -


- ## `!REMOVE ITEM [USERNAME] [ITEM]`
  {: .no_toc }

    ![User Inventory](assets/media/user_inventory_remove_item.png)

    Remove a specific item from a user's inventory (you can only remove a single item at once).

- - - -


- ## `!USE [ITEM]`
  {: .no_toc } 

    ![User Inventory](assets/media/user_inventory_use_item.png)

    Use an item in your inventory.

- - - -


- ## `!ITEMS` or `!INVENTORY`
  {: .no_toc } 

    ![User Inventory](assets/media/user_inventory_items.png)

    See the content of your inventory.

- - - -

{: .highlight }
Items are case-sensitive!


## Configuration

1. In the action `[User Inventory] Use Item`, a variable called `%usedItem%` is being populated that can then be used in an if/else-subaction to trigger another action off of it. An example would be:

    `if usedItem equals Health Potion <do action for Health Potion> then continue, else continue"`

      ![User Inventory](assets/media/user_inventory_used_item.png)


2. In the action `[User Inventory] Loot (Channel Point Reward)` you can duplicate a `Set Argument` subaction inside the "Random Item" group and add any items you want to be in the loot pool. By rightclicking the subactions, you can change the "Weight" and therefore its loot probabilites. The item is picked randomly and will be added to the user's inventory.

   
   ![User Inventory](assets/media/user_inventory_loot_item_action.png)


   The `Set Argument` subaction allows you to set a %-chance for *noItemChance* that __no__ item will be looted.  The user will then simply draw a blank :) It is set to 0% by default.

- - - -

## Items to import

1. VIP-Voucher ![Picture](assets/media/vip.png)

    Here's an item called **VIP-Voucher** that grants a user a VIP status for a limited amount of time upon usage. This only works in combination with the [Temporary VIP extension](https://tawmae.github.io/temporary_vip.html).

    ```scss
    U0JBRR+LCAAAAAAABADNV1tT2zgUft+Z/Q8e9mF3Z+og323eSighoYQNSRxIw3RkSXZM5MvackLa6X/fYzsBcoEFpg9lBoP1nZs+HZ1z/P333yTpYM6yPEzigyNJ+1AthFGaZMLdXo7COIyK6HH9ADXUhi5jnk5xQz9YSTGBAftevsBrjCNWirrtf2Q3KciUZbUgYLgQ0yQrUYEXEWYPwHzThfYAUJaTLEzFCvwYS6FgkeQnmSSmTBrmLJPa8ZzFIsmWErsXLC4NSX9NhUjzo8PD2lEjCMW08BphcliAytdwrdKYioj//UFKYr6UFkk2y6UwlkgSeWGMS6/SAjQrXwNWsoTBDWztVa7EWuPrPExrT0+pSK6K+CNZbS0uOC+hHzWpFG+QiiuxHFa+1CvSGqrgkJbk+LZpKBoismdiJuumZssY20Q2DGqqyLKJSv21/0rt34IVbOX76TqLscdZaVNkBdtA7gkvKDvNkugszEsCQcjHPN+QWqfAl83jOZLawMittCczKrUgS4q01NunJjUTzlnN1lMlzBd4mQOT+wLJcEyT6IHjHZwkMSmyDPzsQ0UWBgEkZsn67YbP3dPYOpE6qTGv6D0YvSevjqQ35NVTSlY74/VF+8NGCJ2e7gjUKWNZtoc8ZMuK72FZpwaWPeLYsmPomulT7FmqtqO6YGEwLRlDDbSNiWVabllByNmGHo53x+Cz+VZHGlN2X9p8uv7jw8vMZ2FpsrtKRKBplXCDMGI7/h8OSqE7WHlPB/Wm9gZX0YhsTVFtw5JV0zJkHf6VHVO3ZF3zqa3aukcN5100qtrPZtF4C4srWvpMVJkqgDxpmiwknsRBtTKvWZXyaVJwKgVw4USZxu/NR1Wjjmpplkw8lci6Z1myrVNHNjTDMoipEsdHv0o+au9g8uMch7w0XnMJbSzCIof4ltKhpEYJPLUFPHQKD2MKDxOaMPyx8hcoRchG+i4vNaUe0xhRICNtG9uyTjRfxhQpsscM3bGJxRym/yqU6u+gtFXmXF5lY9naJSyJjYKaCyyKl9h7MSGZQxBF0FMVYulQID0ke7YB19uwDZN6DlIN/1dhD72evXWH3vG0NW/t4BnzGfRLwna6XwU3jyaTEcSTLPLJ5CIkWZInvmh0Pw0mk9MMnJYjlqlPJnO9gRoa0hRnMolykmQ89BqU84NNk7fb/r2lYM2EVsHT627qRSQYavwbbbnicoHOT3rpgo46OR5dBDfq/ZRoF0FPOW73RwasGRxw66SXdMiZG3otftdudeaeugiurqf8RnPRuB+kJc7AVrPHT4afgsI96xhXqot61534vNlRiOouB9GpGPfbebvlKLR5/I2edapYICZOZsbUGw3Ty+dtqPj6eORp7h1uuUu3xffbivjCjRzlRp1ywq/SbZvDlT06UrgX95J2xAvYF7pogq0z99v4unN5A9j5IO82g1mn5OEz73L66XQ51lwxHhlgDHzFxwo9+RR+bh7viWtW8dUcdnv9ptGnI+P4RoNYVKPJhnwG+nfd6HQ2Ho3vLvtI67auZp8HPbUb3YibQffuYon0i7vZ/cUgULqt3nLcaofreEjkInrdKdpnV0s6GlZ+/B46L393Ei/NGExPacjZnlFtlbocL/sCZ/uGuUoix3N2xfKCi0HirkaEl2Q3pHbvQl0hKHQqokKFUC0dRijEGJRWmAIo9YnjMWha1u7E8YoK4ZQ/z5aIkyT+E5py2X5/SrV4fNkz6bZKr/877tZ0aDr0cB2GSaSaMAppxIaJkiqyBsOkaihI997YwdelCoYQEcbBbiWvh/znznG9XfX1xXHVN22sWb6uyr6qlaOx6UHlV3XZVhhhhmVaqvm20Xi9kZeO7nV7MV9zdNDgOE5zRh9P73YNr3TW8vWH4MZ3DqhHEQSzubhgXp6QGRN9ls23vowewSYP4YtqEyzHnewxCAjgx3/TBeghjBAAAA==
    ```

   
- - - - 

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| May 09, 2024           | Changed the global variable methods to userId instead of the user's display name | 0.2.4 |
