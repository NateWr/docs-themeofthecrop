---
layout: default
slug: restaurant-reservations
menu: user
title: Frequently Asked Questions
---
Quick answers to your most common questions. Anything missing? [Let me know](https://themeofthecrop.com/about/support).

## <a name="shortcode"></a>Is there a shortcode to print the booking form?

Yes, use the `[booking-form]` shortcode.

## <a name="date-time-format"></a>Can I change the format of the date or time?

Yes, set the format for the datepicker in **Bookings > Settings**. The format used in the backend will depend on the date and time formats in your WordPress settings.

## <a name="no-datepicker"></a>The datepicker or timepicker is not working.

If you load up the form and no date or time picker is popping up when you select those fields, this is likely caused by a Javascript error from another plugin or theme.

You can find the problematic plugin by deactivating other plugins you're using one-by-one. Test after each deactivation to see if the date and time pickers work.

If you have deactivated all other plugins and still have a problem, try switching to a default theme (like TwentyFifteen).

## <a name="no-emails"></a>I'm not receiving notification emails for new bookings.

This is almost always the result of issues with your server and can be caused by a number of things. Before posting a support request, please run through the following checklist:

1. Double-check that the notification email in **Bookings > Settings > Notifications** is correct.
2. Make sure that WordPress is able to send emails. The admin email address in the WordPress settings page should receive notifications of new users.
3. If you're not able to receive regular WordPress emails, contact your web host and ask them for help sorting it out.
4. If you're able to receive regular WordPress emails but not booking notifications, check your spam filters or junk mail folders.
5. If you still haven't found the emails, contact your web host and let them know the date, time and email address where you expected to receive a booking. They should be able to check their logs to see what is happening to the email.

If your web host is not able or willing to resolve the problem, or you'd like to explore more reliable email delivery, read [how I use Postmark to make sure emails are delivered every time](https://themeofthecrop.com/2016/05/24/make-sure-restaurant-emails-delivered-every-time/).

## <a name="required-phone-number"></a>Can I make the phone number required?

This is a common request so I have written a small addon to do this for you. [Learn more](https://themeofthecrop.com/2015/01/08/simple-phone-validation-restaurant-reservations/).

## <a name="translate"></a>Can I translate the booking form?
Yes, everything in this plugin can be translated using the standard translation process and software like PoEdit.

If you're not familiar with that process, I'd recommend you take a look at the [Loco Translate](https://wordpress.org/plugins/loco-translate/) plugin, which provides a simple interface in your WordPress admin area for translating themes and plugins.

*If you make a translation, please help others out by adding it to the [GitHub repository](https://github.com/NateWr/restaurant-reservations) so that I can distribute it for others.*

## <a name="early-late-restrictions"></a>I set Early or Late Bookings restrictions, but I scan still book during that time
Users with the Administrator and Booking Manager roles are exempt from these restrictions. This is so that they can make last-minute changes to bookings as needed. If you want to test the Early or Late Bookings restrictions, try submitting a reservation while logged out from the site.

## <a name="custom-fields"></a>I want to add a field to the form. Can I do that?
The [Custom Fields addon](https://themeofthecrop.com/plugin/custom-fields-restaurant-reservations)  will allow you to add a field or modify some of the existing fields of the booking form.

Developers who are comfortable coding up plugins for WordPress can add their own fields using the hooks provided. See the [developer documentation](../developer).

## <a name="wpml"></a>Is this compatible with WPML?

The plugin comes with a `wpml-config.xml` file that improves compatibility with [WPML](https://wpml.org/) for multi-lingual websites. However, there are some limitations.

WPML works by checking the current locale and adjusting things on-the-fly. When an administrator or booking manager approves or rejects a message, WordPress is run in whatever language they're using.

For that reason, the subsequent notification emails are sent out in the administrator's or booking manager's language -- not the language used in the original booking request.

I usually recommend that people just make their notificaton emails multi-language, by including text for both languages into every email.

## <a name="support"></a> How do I contact support?

I provide the best support for the free plugin that I'm able to provide for free. But there is only so much I'm able to do while keeping my business sustainable. Still, I'd encourage you to [post your support request on the official forums](http://wordpress.org/support/plugin/restaurant-reservations) and I'll help out as best I can.

If you have purchased any of the commercial addons, please reach out to me via the [support form on my website](https://themeofthecrop.com/about/support).

{% include faq/refund.md %}

{% include faq/more-help.md %}
