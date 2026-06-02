---
title: "New plugin: SchemaField Mapper for Bubble AI/API response mapping"
url: "https://forum.bubble.io/t/new-plugin-schemafield-mapper-for-bubble-ai-api-response-mapping/396777#post_1"
date: "2026-06-01"
author: "@gagefassam01 Gagefassam01"
feed_url: "https://forum.bubble.io/posts.rss"
---
I kept seeing the same Bubble problem: the API or AI step succeeds, the JSON technically exists, but the next workflow step still cannot use the values cleanly. I built SchemaField Mapper to handle that narrow pain. What it does: takes JSON text you already received extracts the paths you care about enforces required fields returns clear errors when the shape is wrong keeps the result usable inside Bubble workflows Good fit for: OpenAI / Anthropic / API Connector responses nested JSON objects webhook payload inspection backend workflow return data that needs predictable fields Not a fit for: c
