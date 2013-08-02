=== PHP Code for posts ===
Contributors: the.missing.code
Donate link:
Tags: PHP, allow php, exec php, execute php, php shortcode, php in posts, use php, embed html
Requires at least: 3.3.1
Tested up to: 3.4.1
Stable tag: 1.0
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Add PHP code to your WordPress posts, pages, custom post types and even sidebars using shortcodes

== Description ==

PHP Code for posts allows you to add your own PHP code to posts, pages, custom post types (posts) and even sidebars without the need for custom templates

The plugin enables a shortcode and options page so you can add your code to the admin options page and then output it in your post using shortcodes

Multiple code snippets can be used on a post, and multiple posts can use the same code snippet, allowing you to re-use code.

The shortcodes can be used to also display plain HTML content, allowing you to add in iframe, objects, areas and other tags that are removed by the post editor

The plugin also contains a variable array which you can add variables to for use between snippets called $_var and is available though the global variable $PHPPC which is an object, so its $PHPPC->$_vars[]

== Installation ==
1. Download the plugin to your computer
1. Extract the contents
1. Upload (via FTP) to a sub folder of the WordPress plugins directory
1. Activate the plugin in the admin dashboard.

== Frequently Asked Questions ==

= You mentioned a variable array to assign variables to for use between snippets, how do I do this? =

To assign variables to the array, use the following code:
` global $PHPPC;
  $PHPPC->$_vars["myvaridentifier"] = $myvar;`

and to read a variable from the array use this code:
` global $PHPPC;
	$myvar = $PHPPC->$_vars["myvaridentifer"];`
Simples!

= No other questions yet! =

:)

== ChangeLog ==

= 1.0 =
* Initial Release
* No changes

== Upgrade Notice ==

= 1.0 =
* Nothing :)

== Screenshots ==
1. The plugin options menu