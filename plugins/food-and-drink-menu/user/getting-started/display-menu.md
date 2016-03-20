---
layout: default
slug: food-and-drink-menu
menu: user
title: Display Menu
---
Once you've [created a menu](create-menu), you can display it on your website in a variety of ways.

## Link to your menu from a navigation menu

Each Menu has it's own URL, and you can link to this directly from any navigation menu in your WordPress site.

To do this, go to the **Appearance > Menus** page in your WordPress admin area.

![Screenshot of the WordPress menus page](/img/{{ page.slug }}/add-to-nav-menu.png)

You'll see a new section of links you can add to the navigation menus specifically for your Food and Drink Menus. Add any Menu you've created from this page to link directly to it.

When you link to a Menu this way, it will use the same template as regular WordPress Posts. That's not appropriate in a lot of cases, so it *if it doesn't look good, read on*.

## Use a shortcode to add the menu to any page or post

Each Menu also has it's own shortcode, a small text snippet that you can drop into any page or post to display the menu.

You can find this shortcode by going to the **Menus** page in your WordPress admin area. This will bring up the list of menus you've created and each menu's shortcode is displayed in this list.

![Screenshot of the Menu list pointing to the shortcode placement](/img/{{ page.slug }}/menu-shortcode.png)

In the screenshot, the shortcode is `[fdm-menu id=36]`. Just copy that string of text and paste it into the content of any page or post and the menu will appear there.

This is great for two-column menus. If your theme includes a full-width page template, you'll probably want to use that so that your menu has enough room.

Learn more about the [shortcodes](../advanced/shortcodes) in this plugin.

## Add a menu to any widget area

This plugin also comes with widgets for displaying any Menu or Menu Item in a sidebar.

You'll find these under the **Appearance > Widgets** page in your WordPress admin area. Simply add them to any widget area and select the Menu or Menu Item you wish to display.

---

You should now know everything you need to get started with this plugin. If you want to keep learning, take a look at the [advanced topics](../advanced) or learn about the exciting features of the [Pro addon](../pro).
