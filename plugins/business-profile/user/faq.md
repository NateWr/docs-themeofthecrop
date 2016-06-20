---
layout: default
slug: business-profile
menu: user
title: Frequently Asked Questions
---
Quick answers to your most common questions. Anything missing? [Let me know](http://themeofthecrop.com/about/support).

## <a name="shortcode"></a> Can I show or hide something with the shortcode?

The shortcode, `[contact-card]`, supports a number of attributes you can use to show or hide part of your profile.

Using `[contact-card show_name=0]` would show the whole contact card except for your business name. The following is a list of supported attributes:

- `show_name` &mdash; Whether or not to show the name of the business.

- `show_address` &mdash; Whether or not to show the address.

- `show_get_directions` &mdash; Whether or not to show a link to Google maps with directions from the user's current location to the business's address.

- `show_phone` &mdash; Whether or not to show your phone number.

- `show_contact` &mdash; Whether or not to show a link to your contact page, if a contact page has been selected. Otherwise, it will show the email address if you've added one to the business profile.

- `show_opening_hours` &mdash; Whether or not to show your opening hours.

- `show_opening_hours_brief` &mdash; Whether or not to show a short, one-line version of your opening hours. This is turned off by default.

- `show_map` &mdash; Whether or not to show a Google Map with your location.

- `location` &mdash; An optional location post ID. If multi-locations are enabled, you can pass the ID of a location to display the contact card for that location instead of the main business profile.

Most of these are turned on by default. But you can turn them off by including the attribute and setting it to `0`. The following would show only a map and none of the other details:

`[contact-card show_name=0 show_address=0 show_get_directions=0 show_phone=0 show_contact=0 show_opening_hours=0]`

The following would show the full contact card, but display the opening hours in a brief, one-line format:

`[contact-card show_opening_hours_brief=1]`

## <a name="map-latlon"></a> Google Maps shows my business in the wrong location

Unfortunately, in some cases Google is unable to find the right latitude and longitude to match your address.

In some cases, you may be able to get it to properly locate you by tweaking the address. Sometimes Google just needs a bit of help. Once you've got the right coordinates you can go back and restore your original address, and save the form without touching the coordinates again.

If you're unable to get Google to recognize your location, the best thing to do is to leave the Google Map out when you print your contact card. You will also want to hide the Get Directions link, because Google will guide your customers to the wrong location.

There's not much I can do about this, unfortunately. Even if you were able to manually set the latitude and longitude, Google would still show bad directions, because it uses the address, not the coordinates, for this feature.

## <a name="schema-type"></a> What's the Schema Type?

This allows you to let search engines like Google know exactly what kind of business you run.

That way, when someone looks for a real estate agent or a restaurant in your area, they'll know to include you in their search results.

You may not find a type that's a perfect match for your business. Choose the option that's *most appropriate* for your business, and fall back to a more generic type, such as Local Business, if you need.

## <a name="support"></a> How do I contact support?

I provide the best support for the free plugin that I'm able to provide for free. But there is only so much I'm able to do while keeping my business sustainable. Still, I'd encourage you to [post your support request on the official forums](http://wordpress.org/support/plugin/business-profile) and I'll help out as best I can.
