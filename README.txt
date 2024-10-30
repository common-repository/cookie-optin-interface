=== COII - Cookie-Opt-In-Interface ===
Contributors: @nre
Donate link: https://www.nickyreinert.de
Tags: tracking, opt-in-interface, cookies, cookie, notice, notification, opt-in, notify, cookie compliance, dsgvo, gdpr, privacy, cookie consent, eu cookie
Requires at least: 4.9.4
Tested up to: 4.9.4
Stable tag: 1.1.2
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

COII offers the visitor of your website to choose between enabling or disabling tracking by, for example, Google Analytics.

COII ermöglicht den Besuchern deiner Webseite selber zu entscheiden, ob sie das Tracking durch z.B. Google Analytics erlauben oder nicht.

== Beschreibung ==

Wenn der Besucher deine Seite zum ersten Mal aufruft, wird ein Dialog angezeigt. Der Benutzer kann entscheiden, ob er die Verwendung eines Tracking-Pixels zulässt.

Dazu muss in den Einstellungen das Tracking-Pixel hinterlegt werden. Die Nachricht kann beliebig angepasst werden.

Außerdem kann der Shortcode dazu verwendet werden, die Abfrage auch auf Seiten oder Beiträgen einzublenden.

== Description ==

When a user visits your site for the first time, a dialogue will pop up. The user has to decide whether he allows the usage of tracking or not.

The plugin requires you to add your tracking pixel in the backend. You also may define the message, the user will see.

Besides you can use the shortcode [coii_dialogue] to place the dialogue inside any page or post.

== Installation ==

1. Upload `coii` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Place the shortcode [coii_dialogue] inside any given page or post, if required
4. Edit the dialogue text and insert your tracking pixel

== Known bugs ==

COII offers default values for the dialogue, but you have to save them for yourself. Go to the settings-page of this plugin (Settings / Cookie-OptIn-Interface) and simply push the save-button. Or edit the message text.

== Frequently Asked Questions ==

== Changelog ==

= 1.1.2 =
* fix: empty po/mo-files, wrong i18n-folder declaration

= 1.1.1 =
* fix: pixels not fired after cookies was set
* add: default text
* fix: plenk / header already sent

= 1.1.0 =
* add: do not reload page after user confirm tracking
* add: support for more than one tracking-pixel
* add: support for new Google's global site tag
* add: german translation
* fix: shortcodes-engine throws an notice because of missing property
* remove: debugging messages, as there currently is no debug-flag in the backend

= 1.0.2 =
* fix: wrong domain cookie
* add: default values for dialogue text, yes-no-buttons

= 1.0.1 =
* fatal error when installing plugin because hook-function „add“
requires 6 instead of 4 parameters
* renamed debug-functions globally
* changed short description text

= 1.0 =
* first release with all basic features
* opt-in dialogue for first-time visitors
* shortcode to be used on pages / posts to opt-in for tracking
* options page with custom tracking-code and customizable opt-in-message
