---
title: Back to Master Branch
layout: post
---

Just a short update here - today I just cleaned up some branches for the Hacker News clone and updated the master branch. I also added some tests to make sure the 'article' model was working correctly. Then I implemented a feature that limits the number of articles viewable to the last 20 made. Instead of adding this feature in the view page, as I originally did, I edited the controller itself so that it doesn't need to load all of the articles everytime the page was loaded. This saves resources, especially when there are hundreds or even thousands or articles.