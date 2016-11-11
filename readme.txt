=== Stripe Checkout for Easy Digital Downloads (EDD) ===
Contributors: halgatewood
Donate link: https://halgatewood.com/donate/
Tags: edd,easy digital downloads,stripe,payment gateway,gateway,payments,stripe checkout
Requires at least: 3.5
Tested up to: 4.6
Stable tag: 1.6.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Use Stripe Checkout for EDD to sell your digital goods

== Description ==

>This plugin has basic functionality on purpose. Please use the [official Stripe plugin by EDD](http://j.mp/edd-stripe) to connect to other awesome plugins like the Recurring Payments or Software Licensing add-ons.

My Simple Stripe Checkout payment gateway allows you to accept credit cards directly on your site through your Stripe.com account using the built-in Stripe Checkout Button.

When purchasing downloads through the Simple Stripe Checkout Gateway with Easy Digital Downloads for WordPress, users enter their credit card details during the checkout process and never leave your site, resulting in a better experience for the user, and more successful conversions for you.

https://www.youtube.com/watch?v=YNhLP56JeZg

https://www.youtube.com/watch?v=51S2h9H8Nx4


= Easy to setup =

The Simple Stripe Checkout gives you basic Stripe checkout functionality without any of the extra plugin support you are paying for with the full plugin. Simply load in your Stripe API keys, upload a profile image and you're good to go. There are even more options to make your setup even more pro.

This is ideal for simple sites that want to use Stripe instead of PayPal.

= Notes =

- This plugin will not work with EDD taxes turned on.
- I totally recommend the [official Stripe Payment Gateway found the in EDD Add-on section](http://j.mp/edd-stripe). My plugin is a super basic payment gateway and offers less functionality on purpose. My plugin also does not work with the Recurring Payments extension and other quality plugins that the EDD crew develop.
- The Stripe API requires that CURL is installed on your server.
- Stripe is capable of working in over 130 currencies. If you would like to add more options to your EDD Settings, copy [this gist](https://gist.github.com/halgatewood/654f75a64703665b9cd6) to your theme's functions.php file:



== Installation ==

1. Add plugin to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Add settings in wp-admin : Downloads -> Settings -> Payment Gateways: https://www.youtube.com/watch?v=51S2h9H8Nx4


== Screenshots ==

1. Popup view
1. Settings view

== Changelog ==

= 1.6.1 - October 28, 2016 =

* This plugin has been discontinued. Please upgrade to the Stripe plugin offered by [Easy Digital Downloads](https://easydigitaldownloads.com/downloads/stripe-gateway/)

= 1.6 - Jan 12, 2015 =
* Added settings into new settings subsections (EDD 2.5+)
* Updated translation to edd-stripe-gateway from hg_edd
* Added filter for the statement_descriptor: edd_stripe_checkout_descriptor

= 1.5 - Sep 11, 2015 =
* Loaded into WordPress.org
* Removed HalGatewood.com auto updating code

= 1.4.1 - Apr. 30, 2015 =
* Ability to hide Stripe Button
* Ability to hide EDD Purchase Button
* Create/change custom jQuery selectors for the Stripe Checkout to pop on.
* Thanks to graphicfy.com for helping in this update!

= 1.4 - Nov 11, 2014 =
* Now creates a Stripe Customer first and then charges the customer

= 1.3.1 - May 7, 2014 =
* Updated to the latest Stripe PHP library

= 1.3 - March 27, 2014 =
* New setting to hide Remember me box
* New settings to require user billing address and/or shipping address in Stripe Popup
* Remote updates of plugin added so the plugin can get the latest versions

= 1.2.2 - Feb. 20, 2014 =
* New setting to change the text for the radio buttons when multiple gateways are available.

= 1.2.1 - Feb. 6, 2014 =
* Error fixed when using multiple gateways at the same time.

= 1.2 - Jan. 16, 2014 =
* Inline support for Guest Checkout
* Code Cleanup

= 1.1 - Dec. 26, 2013 =
* Better Required Field Handling (Terms of Service and Last Name)
* New settings for Stripe Popup: Image, Title, Description

= 1.0 - Dec. 11, 2013 =
* Initial Release

== Upgrade Notice ==

This plugin has been discontinued. Please upgrade to the Stripe plugin offered by [Easy Digital Downloads](https://easydigitaldownloads.com/downloads/stripe-gateway/)