---
title: Finished with Hacker News!
layout: post
---

Sorry for the long update time, but I finally finished the Hacker News clone! You can even check it out live on [Heroku](https://athif-haxxor.herokuapp.com/). After adding the comments model, I added the votes model which lets any logged in user vote on either an article or a comment. Because of the nature of this model, I used a polymorphic association between votes and 'voteable', which includes articles and comments. Implementing this model was actually easy, but I had to go back and re-write parts of the articles and comments model to improve efficiency. You can check out all the code on my [GitHub](https://github.com/athifw/haxxor).

In the future, I'll add Bootstrap to the site to make it more aesthetically pleasing and look like an actual web application. Let me know if you have any other improvements for the site!

For the rest of my internship here \(it's already week 6!\) I'll work on a personal project as well as the group intern project with the other interns here at Viget.