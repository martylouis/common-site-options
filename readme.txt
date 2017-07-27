=== Common Site Options for ACF ===
Contributors: martylouiswp
Tags: options, addons, advanced custom fields, acf, contact, address
Requires at least: 4.0
Tested up to: 4.7.2
Stable tag: 1.0.0

Common site options used on most websites, somehow missing from WordPress. Install with Advanced Custom Fields PRO.

== Description ==
**NOTE: This plugin only works with an installed active version of [Advanced Custom Fields PRO v5](https://www.advancedcustomfields.com/pro/). By itself, this plugin does NOTHING.**

This add-on for Advanced Custom Fields creates a Site Options menu

**This plugin requires:**

  * Advanced Custom Fields version 5+

== Example ==

You can display each field the same way you would display any other option page field:

`
<p><?php the_field('cso_contact_address_line1', 'option'); ?></p>
`

Read more about the Options Page [here](https://www.advancedcustomfields.com/add-ons/options-page/).

== Fields ==

To see a list of fields available in this plugin, go to our GitHub repo [here](https://github.com/martylouis/common-site-options/).

== Installation ==
1. Copy the `common-site-options` folder into your plugins folder
2. Activate the plugin via the Plugins admin page

== Changelog ==

= 1.0 =
* Initial Release