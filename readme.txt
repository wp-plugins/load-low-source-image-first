=== Load low source image first ===
Contributors: stroknal
Tags: image, low source, fast loading website
Requires at least: 4.0
License: GPL2
Tested up to: 4.1
Stable tag: 1.0.1

The load low source image first plugin makes your website load faster, by loading the images after the document has loaded completely; lazy loading.

== Description ==
The load low source image first plugin does just that: it replaces the source of every image on the page with a 1 pixel image, s.png, and creates an attribute, highsrc, with the original source url. Finally, a jquery script is loaded that shows the original image, after the page has been loaded.

Instead of using this plugin, it is of course possible to use optimized images, or progressive jpeg. But not every Wordpress user is familiar with those concepts. The end user does not always comply with best practices, and inserts a heavy weight image instead, with slow websites as a result. 

Remarks:
This plugin does not create a fallback for people who have javascript disabled.
If your site already uses lazy loading scripts, this plugin might create conflicts. If you use a theme you didn’t develop yourself and don’t know if what scripts are included, test the plugin first!

== Installation ==
To install this plugin:

1) Download the plugin
2) Upload the plugin in your plugins directory,
3) Go to “plugins” in your wordpress admin, then click activate.

== Frequently Asked Questions ==
My site doesn’t work correct with your plugin, what’s going on?
Your site probably already has an lazy loading script in place. This might conflict with the jquery used in this plugin. Jus deactivate, you’re already set!

== Changelog ==
extended readme.txt

== Upgrade notice ==

== Screenshots ==