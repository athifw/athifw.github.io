---
title: Haxxor News is Live!
layout: post
---

After fixing problems brought in my pull request, I uploaded Haxxor News to Heroku! I ran into a few problems here - after receiving countless 502 HTTP request errors, I realized that I did not push the branch right. Also, I had issues with my Procfile. I had to install a web application server, so I ended up using the 'thin' gem. After taking these steps, my application worked flawlessly on Heroku. You can check it out here: [athif-haxxor.herokuapp.com](https://athif-haxxor.herokuapp.com). Currently, the only working part is the [articles model](https://athif-haxxor.herokuapp.com/articles). For the rest of the week, I'll work on the the user model. This includes user registration and authentication. 