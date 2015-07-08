---
title: Almost Done With Hacker News!
layout: post
---

Since the last update, I've updated most of the project and implemented many features. I added a comments model that could reply to both articles and other comments. I implemented this by first creating a polymorphic association making both articles and comments "commentable". This association allowed me to easily get what a comment was commenting on. However, I implemented the polymorphic association after I implemented article commenting, so I had to replace a lot of the code I wrote to accept the association as opposed to just the article.

The other challenge was to actually display the comments in the article view. I ended up recursively rendering each comment as a list, so that it's clear which comments the comments are replying to. Currently, I have a functioning site, but I'm working on implementing voting, including upvotes and downvotes. Let me know if there are other features you think I should implement!