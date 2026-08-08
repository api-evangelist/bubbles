---
title: "Add Concurrency Control to Backend Workflow Mutations"
url: "https://forum.bubble.io/t/add-concurrency-control-to-backend-workflow-mutations/399072#post_4"
date: "2026-08-05"
author: "@th18 Tluz"
feed_url: "https://forum.bubble.io/posts.rss"
---
I think one of the most discussed topics here is race conditions and concurrency, I think for advanced apps, Bubble MUST implement a way to protect us from this. Last year I had a customer trying to use Bubble for banking, balance, statements and some web hooks and it was crazy how I could not protect the database from race conditions. I remember we needed to keep a consistency serial number, if we need to start with 01 the next should be 02 and can’t be sent again, and Bubble could not make it safe, I used the method " :make static "and finally the system had some alternative but most of the 
