---
title: Forgot Password Feature
layout: post
---

Today I implemented a feature that allows users to reset their password if they forget it. This required another column for my user table called a reset password token. This token is a randomly generated string that can be emailed to a user to reset the password. I also had to implement a mailer in order to actually send these emails. 

For next time, I will implement threaded comments, so I will like use associations. As always, you can follow my progress on my Github account.