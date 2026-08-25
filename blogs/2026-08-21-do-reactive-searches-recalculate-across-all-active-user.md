---
title: "Do reactive searches recalculate across all active user sessions?"
url: "https://forum.bubble.io/t/do-reactive-searches-recalculate-across-all-active-user-sessions/399598#post_3"
date: "2026-08-21"
author: "@georgecollier George @ Not Quite Unicorns"
feed_url: "https://forum.bubble.io/posts.rss"
---
jmfcristo: Does Bubble re-evaluate the reactive searches in all active sessions , even if the change does not belong to the user of those sessions? Only if the results would be different If you have a search for Invoices where User = current user then an update to the Invoices table that adds a new user won’t refresh that user’s search, but a record that does match that constraint will. I believe it’s managed by a reversed search (see ‘percolator’ if you want to read more about how it works) So the client subscribes to the query, and Bubble’s websocket notifier will notify when the result set 
