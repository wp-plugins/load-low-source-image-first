=== Load low source image first ===
Contributors: stroknal
Tags: image, low source, fast loading website
Requires at least: 4
License: GPL2
Tested up to: 4
Stable tag: trunk

The load low source image first plugin makes your website load really fast, by loading the images after the document has loaded completely. 

== Description ==
The load low source image first plugin does just that: it replaces the source of every image on the page with a 1 pixel image, s.png, and creates an attribute, highsrc, with the original source url. Finally, a jquery script is loaded that shows the original image, after the page has been loaded.

Instead of using this plugin, it is of course possible to use optimized images, or progressive jpeg. But not every Wordpress user is familiar with those concepts. The end user does not always comply with best practices, and inserts a heavy weight image instead, with slow websites as a result. 

There is a but: This plugin does not create a fallback for people who have javascript disabled.

== Installation ==
To install this plugin:

Download the plugin
upload the plugin in your plugins directory,
Go to “plugins” in your wordpress admin, then click activate.

== Frequently Asked Questions ==
no questions yet

== Changelog ==


== Upgrade notice ==

== Screenshots ==