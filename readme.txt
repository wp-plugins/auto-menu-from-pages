=== Auto Menu From Pages ===
Contributors:      McGuive7, MIGHTYminnow
Donate link:       http://wordpress.org/plugins/auto-menu-from-pages
Tags:              auto, automatic, menu, navigation, page, hierarchy
Requires at least: 3.5
Tested up to:      4.2
Stable tag:        1.0.2
License:           GPLv2 or later
License URI:       http://www.gnu.org/licenses/gpl-2.0.html

Automatically generate a navigation menu from your page hierarchy.

== Description ==

**A <a href="http://mightyminnow.com/plugin-landing-page?utm_source=auto-menu-from-pages&utm_medium=plugin-repo&utm_campaign=WordPress%20Plugins">MIGHTYminnow</a> plugin.**

Auto Menu From Pages generates a WordPress navigation menu that matches your page order and hierarchy. The menu automatically updates to reflect any changes you make to your pages so it is always current.

The auto menu works just like any other WordPress navigation menu, meaning that you can assign it to any of your theme's menu locations, output it using the Custom Menu widget, and do anything else that you could normally do to a navigation menu.

= Instructions =
1. Install and activate the plugin.
2. Navigate to Appearance > Menus in the WordPress admin and select the "Auto Menu From Pages" menu to edit (this should automatically happen on activation).
3. Assign the auto menu to one or more of your theme's menu locations using the normal "Theme locations" checkboxes, and save the menu.
4. That's it! The menu will now auto-output to match your pages.
5. Note: To hide a page from the auto-menu, check the "Hide from the auto menu" checkbox when editing that page.

== Installation ==

1. Install and activate the plugin.
2. Navigate to Appearance > Menus in the WordPress admin and select the "Auto Menu From Pages" menu to edit (this should automatically happen on activation).
3. Assign the auto menu to one or more of your theme's menu locations using the normal "Theme locations" checkboxes, and save the menu.
4. That's it! The menu will now auto-output to match your pages.
5. Note: To hide a page from the auto-menu, check the "Hide from the auto menu" checkbox when editing that page.

== Frequently Asked Questions ==

= How does the menu work? =

The menu takes your hierarchy of pages and creates a nav menu item for each page. Every time you make a change to your site that affects your pages, the menu will automatically edit these nav menu items to reflect that change.

= Can I exclude pages from the auto menu? =

Yes. When editing a page, look for the "Auto Menu From Pages" metabox, and simply check the box for "Hide from the auto menu".

= Why can't I directly edit the menu? =

You'll notice that the auto menu doesn't have the same editing abilities (manually adding a menu item, drag-and-drop sorting of menu items, etc) as other menus. That's because the menu automatically updates to match your page hierarchy, so any manual edits you made to the menu would only be overwritten the next time you edited your pages.


= Can I manually add/items to the menu? =

At present, no. The menu auto generates based on your page hierarchy, and therefore isn't able to allow for manually added nav menu items.

== Screenshots ==

1. The Auto Menu From Pages menu in action. Looks the same as any other menu, just simplified!

== Changelog ==

= 1.0.2 =
* Fix admin notice dismiss bug that was redirecting to the incorrect page
* Remove functionality that deletes the menu on plugin deactivation

= 1.0.1 =
* Fix bug causing admin CSS to render on non-menu pages, hiding various elements

= 1.0.0 =
* First release

== Upgrade Notice ==

= 1.0.2 =
* Fix admin notice dismiss bug that was redirecting to the incorrect page
* Remove functionality that deletes the menu on plugin deactivation

= 1.0.1 =
* Fix bug causing admin CSS to render on non-menu pages, hiding various elements

= 1.0.0 =
First Release