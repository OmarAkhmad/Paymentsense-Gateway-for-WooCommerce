=== WooCommerce Paymentsense Gateway ===
Tags: paymentsense, payments
Requires at least: 4.4
Tested up to: 4.9.4
Stable tag: 3.0.0
Requires PHP: 5.6.0
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Paymentsense is a plugin that extends WooCommerce, allowing you to take payments via Paymentsense.

== Description ==

Paymentsense is a plugin that extends WooCommerce, allowing you to take payments via Paymentsense. The plugin provides integration with the Paymentsense Hosted and Paymentsense Direct payment methods.

== Installation ==

= Minimum Requirements =

* PHP version 5.6.0 or greater
* WordPress 4.4+
* WooCommerce 3.x (tested up to 3.3.3)
* PCI-certified server using SSL/TLS in order to use the Direct Method

= Plugin Installation =

The Paymentsense plugin can be installed by any of the following three ways:

= Installation trough the WordPress plugin directory =

1. Login into the admin area of your WordPress website.
2. Go to "Plugins" -> "Add New".
3. Type "Paymentsense" into the search box.
4. The plugin should appear in the search results.
5. Click the "Install Now" button.
6. Wait while the plugin is retrieved.
7. Click the "Activate" link associated with "Paymentsense Gateway for WooCommerce" plugin.

= Installation by uploading of the plugin's zip file trough the admin area =

1. Login into the admin area of your WordPress website.
2. Go to "Plugins" -> "Add New".
3. Click "Upload Plugin" link at the top of the page.
4. Click "Browse" and choose to the plugin's zip file.
5. Click the "Install Now" button.
6. Wait while the plugin is uploaded to your server.
7. Click the "Activate" link associated with "Paymentsense Gateway for WooCommerce" plugin.

= Installation by copying the content of the plugin's zip file =

1. Copy the content of the plugin's zip file to the `/wp-content/plugins` directory.
2. Login into the admin area of your WordPress website.
3. Go to "Plugins".
4. Click the "Activate" link associated with "Paymentsense Gateway for WooCommerce" plugin.

= Activation and configuration of the Paymentsense Hosted Gateway =

1. Go to "WooCommerce" -> "Settings" -> "Checkout".
2. Click on the Paymentsense Hosted Gateway.
3. Check the "Enable Paymentsense Hosted" checkbox.
4. Set the values for the "Gateway MerchantID", "Gateway Password", "Gateway PreSharedKey" and "Gateway Hash Method" settings according to their respective values in the Paymentsense Merchant Management System (MMS).
5. Optionally, set the rest of the settings as per your needs.
6. Click the "Save changes" button.

= Activation and configuration of the Paymentsense Direct Gateway =

1. Go to "WooCommerce" -> "Settings" -> "Checkout".
2. Click on the Paymentsense Direct Gateway.
3. Check the "Enable Paymentsense Direct" checkbox.
4. Set the values for the "Gateway MerchantID" and "Gateway Password" settings according to their respective values in the Paymentsense Merchant Management System (MMS).
5. Optionally, set the rest of the settings as per your needs.
6. Click the "Save changes" button.
7. Enable the WooCommerce Secure Checkout (see WooCommerce Secure Checkout).

= WooCommerce Secure Checkout =

The usage of the Paymentsense Direct Gateway involves the following additional steps:

1. Make sure SSL/TLS is configured on your PCI-DSS certified server.
2. Login into the admin area of your WordPress website.
3. Go to "WooCommerce" -> "Settings" -> "Checkout".
4. Check the "Force secure checkout" checkbox in the "Checkout process" section.

== Changelog ==

See changelog.txt file

== Upgrade Notice ==

= 3.0.0 =
3.0.0 is a major update that implements new features, compatibility and security fixes

== Support ==

[support]: mailto:devsupport@paymentsense.com
