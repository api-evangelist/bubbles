---
title: "React Flow Plugin Specialist"
url: "https://forum.bubble.io/t/react-flow-plugin-specialist/400011#post_7"
date: "2026-09-05"
author: "@peplosv Peplosv"
feed_url: "https://forum.bubble.io/posts.rss"
---
Hi, The graph itself is simple, one parent and a list of children. The part people usually get wrong with the React Flow plugin in Bubble is the data shaping: the plugin expects nodes and edges as separate lists in a specific format, and if you feed it the Property and its connected Meters directly, it either renders nothing or does not update when a meter is added or removed. The clean way is a small workflow that builds the node list (one for the Property, one per Meter) and the edge list (Property to each Meter) from your existing data types, so the graph stays live as your data changes wit
