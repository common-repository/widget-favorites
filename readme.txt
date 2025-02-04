=== Widget Favorites ===
Contributors: xwp, westonruter
Tags: widgets, customizer, revisions
Requires at least: 4.1
Tested up to: 4.1
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Store revisions of widget instances for re-use.

== Description ==

Sometimes you have a certain widget configuration that you need to use over-and-over again.
Widget Favorites provides a way to save a widget instance by name to identify it later 
when loading the favorited widget instance into another widget.

Another way to look at this plugin is that it provides (non-automatic) revisions for widgets.

Note that this only adds functionality to widgets managed in the Customizer.

**Development of this plugin is done [on GitHub](https://github.com/xwp/wp-widget-favorites). Pull requests welcome. Please see [issues](https://github.com/xwp/wp-widget-favorites/issues) reported there before going to the [plugin forum](https://wordpress.org/support/plugin/widget-favorites).**

== Other Related Plugins ==

* [Settings Revisions](https://wordpress.org/plugins/settings-revisions/)
* [Oomph Clone Widgets](https://wordpress.org/plugins/oomph-clone-widgets/)
* [Widget Alias](https://wordpress.org/plugins/widget-alias/)
* [Duplicate Widget](https://wordpress.org/plugins/duplicate-widget/) (not updated in 2+ years)

== Changelog ==

= 0.1 =
Initial release

= 0.1.1 =
Fix conflict with Make theme. [#5](https://github.com/xwp/wp-widget-favorites/issues/5)

= 0.1.2 =
* Fix WAMP issue wrt backslash `DIRECTORY_SEPARATOR` [PR #12](https://github.com/xwp/wp-widget-favorites/pull/12)
* Fix sanitize & unserialize failures ([PR #13](https://github.com/xwp/wp-widget-favorites/pull/13))

= 0.2 =
Improvements from [PR #14](https://github.com/xwp/wp-widget-favorites/pull/14):

* Prevent showing existing dropdown when loading
* Disable fields while loading/saving
* Hide load button if no widget selected
* Display any error messages instead of failing silently.
