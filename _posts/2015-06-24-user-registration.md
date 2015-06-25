---
title: User Registration for Haxxor
layout: post
---

After updating the application with the features for articles, I'm working on the users side of the application. So far, I've created the ability to register for an account using ActiveRecord's [has_secure_password](http://apidock.com/rails/ActiveModel/SecurePassword/ClassMethods/has_secure_password) method. This required a lot of code in the users controller I generated, as well as a form to accept a username, email, password, and password confirmation. However, I still need to add rspec tests to ensure that any changes I make in the future will not change the working model.

I also worked on letting users login to their registered account. Currently, I'm planning on using sessions to hold user data during a login. Next, I will make sure that a user must be logged in in order to post an article.