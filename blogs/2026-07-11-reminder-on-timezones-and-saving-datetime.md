---
title: "Reminder on timezones and saving datetime"
url: "https://forum.bubble.io/t/reminder-on-timezones-and-saving-datetime/398134#post_1"
date: "2026-07-11"
author: "@ihsanzainal84 Ihsantonio"
feed_url: "https://forum.bubble.io/posts.rss"
---
Datetimes formatted as ISO will always return UTC (ends with Z ) It’s important to note that formatting as other than ISO will use the user/browser’s timezone. This includes extracting hours and minutes. It extracts values as of the user/browser timezone.
