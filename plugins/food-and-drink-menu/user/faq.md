---
layout: default
slug: food-and-drink-menu
title: Frequently Asked Questions (FAQ)
---
Quick answers to your most common questions. Anything missing? [Let me know](http://themeofthecrop.com/about/support).

## <a name="menu-item-order"></a> How do I change the order of items on my menu?

When [editing a Menu Item](getting-started/create-menu#create-menu-item), you'll see a panel on the right-hand side which has an **Order** input field. Menu Items are listed in order of this value, from lowest to highest.

If you want one Menu Item to be listed after another, make sure it's **Order** value is higher.

*This can get cumbersome for large menus. Check out the [Simple Page Ordering](https://wordpress.org/plugins/simple-page-ordering/) plugin for an easy way to order items by dragging and dropping them right from the list of **Menu Items**.*

## <a name="multiple-prices"></a> How do I show multiple prices?

Multiple prices per-product are not yet supported by this plugin. The [Pro addon](pro) supports a discounted price, but not multiple regular prices.

I do plan to add support for multiple prices in the future, but this feature will not be available in the near future.

In the meantime, I often recommend that people simply add the pricing information into the **Menu Item** description.

![Screenshot of multiple prices](/img/{{ page.slug }}/multiple-prices.png)

## <a name="columns-collapsed"></a> I have a two-column menu but it displays in one column.

The plugin tries hard to be compatible with as many themes as possible. But in some cases a theme will add extra spacing that prevents the columns from displaying side-by-side.

In such cases, you'll need to reach out to the developer of your theme for help resolving the issue. It should be a quick snippet of CSS that solves the problem.

Unfortunately, there isn't any one snippet of CSS code that works across the board. If there was, *I'd add it to the plugin*.

## <a name="section-description"></a> How can I show that a collection of dishes come with a side?

Each **Menu Section** can have a description. When available, it displays below the section title.

To add a description to a section, go to the **Menu Items > Menu Sections** page in your WordPress admin area. Click the **Edit** link below the section you'd like to change.

On the Edit screen, you'll see an area to type in a description. This is a great place to put in details such as:

- All entrees come with a side salad or fries.
- Add cheese to any burger for $1. Add bacon for $2.
- Add fries and a coke to any order during lunchtime for just $10.

## <a name="customize"></a> Can I customize the look and layout of my menu?

The plugin comes with a base style, which inherits the look of your theme, as well as a classic style. You can [learn more about these settings](advanced/settings).

If you want to make more bespoke customizations to the design and style of your menu, you may need to know CSS code and how to modify PHP templates. You can [read some simple tutorials](advanced/complex-layouts) or take a look at the [developer documentation](../developer).

## <a name="footer"></a> How can I indicate that we add a gratuity?

Each **Menu** has an additional editor for the **Menu Footer**. You'll see this when [editing a menu](getting-started/create-menu#create-menu).

The Menu Footer is a great place to add details such as:

- All parties of 6 or more will automatically be charged a gratuity of 10%.
- All dishes are cooked in a kitchen with nuts.
- All of our meat is free-range and sourced from local producers.

## <a name="menu-icons"></a> I need to mark some dishes as vegetarian, spicy or similar?

The [Pro addon](pro) features a wide range of icons covering dietary needs, healthy choices and religious preferences. Learn more about the [menu icons](pro/menu-icons).


## <a name="wpml"></a> Is this compatible with WPML?

This plugin includes a `wpml-config.xml` file which provides compatibility with the WPML multi-language plugin.

Although Food and Drink Menu is compatible with WPML, I'm not personally very familiar with the multi-language plugin and so may not be able to provide very helpful support if you run into any problems or find the editing process confusing.

## <a name="support"></a> How do I contact support?

I provide the best support for the free plugin that I'm able to provide for free. But there is only so much I'm able to do while keeping my business sustainable. Still, I'd encourage you to [post your support request on the official forums](http://wordpress.org/support/plugin/food-and-drink-menu) and I'll help out as best I can.

If you have purchased the [Pro addon](pro), please reach out to me via the [support form on my website](http://themeofthecrop.com/about/support).

{% include faq/refund.md %}

{% include faq/more-help.md %}
