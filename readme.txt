=== Upcoming.org Public Events ===
Contributors: nicpow 
Tags: upcoming, upcoming.org, events, local, local events, public events
Requires at least:
Tested up to: 2.8
Stable tag: 1.0.1 

Fetches Events from Upcoming.org by location via shortcode.

== Description ==

This plugin is very simple. It fetches events from upcoming.org based on a given location. You need the (free) upcoming.org API key which you can find here: http://upcoming.yahoo.com/services/api/keygen.php
To include the local events, use this shortcode in a post/page: [upcomingorg_events]San Francisco, CA[/upcomingorg_events]. You can use other formats of locations as well, such as ZIP codes.
In the settings you can define:

<ul>
<li> Number of events to show (will obviously be lower if not that many events are available for your query).</li>

<li> Radius to search around the given location</li>

<li> Show (or don't show) the event images if they are available</li> 

<li> Display the upcoming.org logo with the results or not</li>
</ul>

To edit the CSS, modify the upcoming.org_events.css file in the plugin folder upcoming.org_events/

== Installation ==

1. Install via wordpress' plugin directory or upload the upcoming.org_events.zip through the admin interface
1. Make sure your file access settings are set to 755 for the php & css file.

== Screenshots ==

1. Example of 3 events fetched for San Francisco

== Changelog ==

= 1.0 =
* First version

= 1.0.1 =
* Minor fixes related to url format of plugin actually being available :)
