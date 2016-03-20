---
layout: default
slug: food-and-drink-menu
title: Shortcodes
---
There are two shortcodes available with this plugin, one for displaying a full Menu and one for displaying a single Menu Item. Below you'll find a list of the attributes available.

## Menu Shortcode

`fdm-menu id=1 show_title=0 show_content=0`

Prints a single menu without the title or description.

`id` Accepts the ID of the desired menu. Must be an integer.

`show_title` Whether or not to display the menu's title. Accepts 0 (hide title) or 1 (show title).

`show_content` Whether or not to display the menu's description. Accepts 0 (hide content) or 1 (show content).

## Menu Item Shortcode

`[fdm-menu-item id=1]`

Prints a single menu item as it appears in a menu.

`id` Accepts the ID of the desired menu. Must be an integer.
