=== Page-list ===
Contributors: webvitaly
Donate link: http://web-profile.com.ua/wordpress/plugins/page-list/
Plugin URI: http://web-profile.com.ua/wordpress/plugins/page-list/
Tags: page, page-list, pagelist
Author URI: http://web-profile.com.ua/wordpress/
Requires at least: 3.0
Tested up to: 3.1.1
Stable tag: 1.0.0

"Page-list" plugin helps you to show list of pages of your web-site (hierarchical tree of pages) with [pagelist] shortcode.

== Description ==

You can use aditional parameters: **`[pagelist depth="2" child_of="4" exclude="6,7,8"]`**.

Plugin is based on [wp_list_pages('sort_column=menu_order&title_li=')](http://codex.wordpress.org/Template_Tags/wp_list_pages) function;
= Usage: =
* the depth (how many levels in the hierarchy of pages are to be included in the list) by default is unlimited, but you can specify it like this: `[pagelist depth="3"]`;
* if you want to show flat list of pages (not hierarchical tree) you can use this shortcode: `[pagelist depth="-1"]`;
* if you want to show subpages of the specific page you can use this shortcode: `[pagelist child_of="4"]` where `4` is the ID of the specific page;
* if you want to show subpages of the current page you can use this shortcode: `[pagelist child_of="current"]` or `[pagelist child_of="this"]`;
* if you want to exclude some pages from the list you can use this shortcode: `[pagelist exclude="6,7,8"]` where `exclude` parameter accepts comma-separated list of Page IDs;

[WordPress stuff](http://web-profile.com.ua/wordpress/)

== Changelog ==

= 1.0.0 =
* Initial release;

== Installation ==

1. Install plugin and activate it on the Plugins page;
2. Add shortcode **`[pagelist]`** to page content;

