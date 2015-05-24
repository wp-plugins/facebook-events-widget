=== Facebook Events Widget ===
Contributors: roidayan
Donate link: http://roidayan.com
Tags: events, Facebook, fanpage, group, Facebook Events
Requires at least: 3.2.1
Tested up to: 4.2.2
Stable tag: 1.9.11

Widget to display events from Facebook page or group

== Description ==

Widget to display events from Facebook page or group

Based on code by Mike Dalisay
http://www.codeofaninja.com/2011/07/display-facebook-events-to-your-website.html

Version 1.9 requires PHP 5.4 or up.

Upgrade note: 
If you modified style.css remember to save it before doing updates to the plugin.

== Installation ==

1. Extract the folder into your Wordpress plugins directory.
2. You'll have a new widget in the widgets page.
3. Create a Facebook app to get an app id and app secret.
4. Add a widget to a sidebar you want.
5. Fill in the widget settings.
   The app id and app secret are from step 3.


== Frequently Asked Questions ==

= How to modify the style? =

You need to edit the style.css file.


== Screenshots ==

1. example
2. example2


== Changelog ==

= 1.9.11 =
* Fix for empty events
* some cleanup

= 1.9.10 =
* fix textdomain
* display admin error notice if php < 5.4

= 1.9.9 =
* fix issue with events without end time
* fix missing events description

= 1.9.8 =
* update fb sdk to v4.0.23. default graph api is v2.3

= 1.9.7 =
* small style change in display margin
* consider events that started but on going as future events
* add separators "Upcoming events" and "Past events"

= 1.9.6 =
* fix possible error when no events found

= 1.9.5 =
* use graph api v2.2 as using the next page api doesn't pass the version and default seems v2.2
* fix showing current events when there are many future events

= 1.9.4 =
* add translation support and en pot file

= 1.9.3 =
* remove left over debug output

= 1.9.2 =
* use graph api v2.3

= 1.9.1 =
* fix getting access token
* when requesting future only events show asc order

= 1.9 =
* updated fb sdk to v4 and using graph api v2.2 only

= 1.1.11 =
* fixed graph api return future events first. now reversing it when going over the results.
  thanks topherjamessf.

= 1.1.10 =
* fixed showing event too far in the future and not next events.

= 1.1.9 =
* fixed missing future events
* added option to use graph api instead of fql.
with the graph api it is possible to access groups events
and not just fan page events.
when using graph api then currently the following options
are not relevent: small picture, future events only,

= 1.1.8 =
* fix event times with daylight saving times.

= 1.1.7 =
* displaying no events message where there are no events.

= 1.1.6 =
* fix not displaying times for events
* added new checkbox for old timestamps. if your using an old app id and you notice events from the past then you should mark this.

= 1.1.5 =
* fix parsing events timestamps

= 1.1.4 =
* fix something with time offsets.
* fix to support new time format in facebook replies.

= 1.1.3 =
* fixed time offsets.

= 1.1.2 =
* fixed missing div element when there are no events.
* fixed not accepting negative time offsets.

= 1.1.1 =
* fixed external css issue.

= 1.1.0 =
* Option for facebook access token to access private calendar.
* External css file.
* Option for date separators like in facebook.
* Option to open events in new window.

= 1.0.1 =
* fixed bug in echo statement.

= 1.0 =
* first