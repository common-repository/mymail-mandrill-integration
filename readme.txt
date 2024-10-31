=== MyMail Mandrill Integration ===
Contributors: everpress, revaxarts
Tags: mandrill, mymail, delivery, deliverymethod, newsletter, email, revaxarts, mymailesp
Requires at least: 3.6
Tested up to: 4.7.1
Stable tag: 0.4.1
License: GPLv2 or later

== Description ==

> This Plugin requires [MyMail Newsletter Plugin for WordPress](https://evp.to/mymail?utm_campaign=wporg&utm_source=Mandrill+integration+for+MyMail)

Uses Mandrill App by Mailchimp to deliver emails for the [MyMail Newsletter Plugin for WordPress](https://evp.to/mymail?utm_campaign=wporg&utm_source=Mandrill+integration+for+MyMail).

== Installation ==

1. Upload the entire `mymail-mandrill-integration` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to Settings => Newsletter => Delivery and select the `Mandrill` tab
4. Enter your credentials
5. Send a testmail

== Changelog ==

= 0.4.1 =
* tested with 4.7.1

= 0.4 =
* changed the way the core plugin is detected
* rearranged settings assets
* removed some references to MyMail assets
* cleanup
* updated formatting

= 0.3.6 =
* increased timeouts to prevent false positives on sending

= 0.3.5 =
* fixed: PHP Warning

= 0.3.4 =
* SVN problems, sorry

= 0.3.3 =
* added: unsubscribes or spam complaints via the Mandrill API unsubscribes the users now

= 0.3.2 =
* fixed: issue with SSL on some servers

= 0.3.1 =
* fixed: unexpected output on activation

= 0.3 =
* update for MyMail 2
* moved functions into class

= 0.2.3 =
* sending via SMTP is now faster

= 0.2.2 =
* fixed a bug where mails are not send at an early stage of the page load

= 0.2.1 =
* small typo

= 0.2 =
* fixed some stuff and bugs

= 0.1 =
* initial release

== Upgrade Notice ==

== Additional Info ==

This Plugin requires [MyMail Newsletter Plugin for WordPress](https://evp.to/mymail?utm_campaign=wporg&utm_source=Mandrill+integration+for+MyMail)

