=== TE Icecast 2 Station Information ===
Contributors: xdjxdaveyx
Donate Link: http://tauriemotum.uk/index.php/icecast-2-server-information-plugin-for-wordpress-by-tauri-emotum/
Tags: Displays Icecast 2 now playing tracks
Requires at least: 5.1
Tested up to: 5.2.4
Stable tag: 1.0.5
Requires PHP: 5.6
License: GPL3
License URI: https://www.gnu.org/licenses/gpl-3.0.en.html

== Description ==
Hi and welcome to the free Wordpress plugin: TE Icecast 2 Server Information
This displays information on the artist and song currently playing from an Icecast stream

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Once you've clicked install on the plugin and activated it, there will be a new widget available for you to add to your layout.
You can drag the plugin from the list into one of your page areas and adjust the settings from there.
If you have trouble with the settings not opening at first, put you wordpress admin into Accessibility Mode (see the top right of the screen) and click on Edit next
to the plugin where you can put in some values to start with and after that you should find you can edit the settings in any mode.

The settings you need to add are:

Title : What you want displayed at the top of the widget on the front end.
Server : The server URL where your stream is coming from. As standard Icecast uses port 8000 so just pop :8000 on the end of the address unless you use a custom port.
Username : Your Icecast admin username
Password : Your Icecast admin password
Show server: If ticked, this will show the server address in the frontend
Show mountpoint: If ticked, this will show the currently active mount that is streaming. Note that this will not show if it's not possible to get station information.
Mount 1 : your default mountpoint, usually /stream but it may be different in your Icecast configuration.
Mount 2 : Secondary mountpoint.
Mount 3 : Tertiary mopuntpoint.
Display Tauri Emotum Branding: This is off by default, but you may wish to promote us for our efforts! It provides a link to our website where you can find additional
information on the plugin. The link is http://tauriemotum.uk/index.php/icecast-2-server-information-plugin-for-wordpress-by-tauri-emotum/
Feel free to contact us via our website if you have any questions or want to give feedback.
http://tauriemotum.uk/index.php/contact/

Thanks for downloading and we hope you enjoy using the plugin as much as I enjoyed creating it!

David Cropley.
Tauri Emotum.
http://tauriemotum.uk

== Frequently Asked Questions ==
Q. The plugin does not automatically update when a new song is played.
A. I will be looking into an auto-update feature later on, for real-time information.

Q. How do I get support?
A. Use the contact us page on my website tauriemotum.uk or email dave@tauriemotum.uk and when
I pick up the email I will try to help. For minor issues I most likely
will help for free, but for more advanced customisation or in depth
help I may charge - but you are free to ask a question!

== Screenshots ==
1. Front-end of widget
2. Back-end widget controls
3. Activate Accessibility mode initially if needed
4. Edit in Acccessibility mode in needed
5. Front end on website of original custom version
6. HexBG theme in action on the widget

== Changelog ==

= 1.0.5 =
* Updated heights in CSS stylesheet

= 1.0.4 = Updates to readme file only

= 1.0.3 =
* Added proper WP stylesheet loading to avoid conflicts on plugins page and other areas
* Added 1 more skin plus screenshot of the new skin
* Correction to previous log about the .te-ic2-custom {} class... it can be used with any sub-classes, of course(!)
* Updated on 15th October 2019

= 1.0.2 =
* Updated code to allow custom CSS control over .te-ic2-custom button {}
* in addition to .te-ic2-custom {} .te-ic2-custom h5 {} and .te-ic2-custom h6 {}
* More info on how to use with example on tauriemotum.uk
* Updated on 20th of September 2019

= 1.0.1 =
* Added a theme dropdown in the widget to pick different colourschemes for the widget
* Added a custom theme option so that users can control the CSS for the widget
* Updated on 17th of September 2019

= 1.0.0 =
* First release on 8th of April 2019

== Upgrade Notice ==

= 1.0.0 =
Let's get started!
