=== ACF: URL Field ===
Contributors: tylerdigital, croixhaug
Tags: Advanced Custom Fields, ACF, URL
Requires at least: 3.5
Tested up to: 4.2
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds a URL field type to ACF that ensures a valid http/https URL is entered.

== Description ==

** This is an extension for the popular [Advanced Custom Fields](https://wordpress.org/plugins/advanced-custom-fields/) plugin. By itself, this plugin does NOTHING. **

This plugin prevent users from accidentally entering a URL without http://

This Advanced Custom Field type prevents data entry error that results in a broken link on your site (like http://mysite.com/www.externalwebsite.com)

* Just to be sure there's no confusion... * ** This plugin does nothing unless [ACF](https://wordpress.org/plugins/advanced-custom-fields/) is active on your site **

= Compatibility =

This ACF field type is compatible with:
* ACF 4
* ACF 5

A URL Field was added as a core function of ACF 5. This plugin will not conflict with ACF 5, but is redundant when used with ACF 5.

== Installation ==

1. Copy the `acf-url` folder into your `wp-content/plugins` folder
2. Activate the URL plugin via the plugins admin page
3. Create a new field via ACF and select the URL type
4. Please refer to the description for more info regarding the field type settings

== Changelog ==

= 1.0 =
* Initial Release.