=== Plugin Name ===

Contributors: GeroNikolov
Donate link: http://blogy.co/
Tags: Listing, Shortcode, Open Source, Media, Media Listing, List Media, List Media Plugin, Listing Shortcode
Requires at least: 3.0.1
Tested up to: 5.4.1
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Installation ==

Download and activate the plugin from WP.Org or
clone the repository from GitHub - https://github.com/Gero0Nikolov/list-media-wp.git -
to your wp-content/wp-plugins/ folder and activate it from the WordPress Dashboard after that.

== Description ==

This plugin allows you to list all (or part) of your medias on custom Page / Post.
With one simple shortcode - <strong>[list_media]</strong>

It can take 7 attributes:
<ul>
<li><strong>order</strong> - This tells the plugin how to sort the results. By default it is <strong>ASC</strong></li>
<li><strong>order_by</strong> - This tells the plugin by what to sort the results (It can use all of the WordPres sorting methods). By defualts it is <strong>publish_date</strong></li>
<li><strong>posts_per_page</strong> - This tells the plugin how much attachments should list. By defaults it is <strong>-1</strong>, which means <strong>All</strong></li>
<li><strong>post_status</strong> - This tells the plugin which attachments to list. By default it is <strong>null</strong> with that it lists all available attachments.</li>
<li><strong>post_parent</strong> - This tells the plugin to list all attachments with parent ID equal to the given parameter. By defaults it is <strong>null</strong>.</li>
<li><strong>default_styles</strong> - This tells the plugin how the Front-end Table should look like. If the parameter is <strong>true</strong> it appends the default styles of the table. By default it is <strong>true</strong>.</li>
<li><strong>date_format</strong> - This is tells the plugin how the date should be formated into the <strong>Date</strong> field of the Table.</li>
</ul>Full description of the Shortcode and it's attributes can be found here - https://github.com/Gero0Nikolov/list-media-wp.git

== Screenshots ==

1. Front Demo
2. Admin Demo
