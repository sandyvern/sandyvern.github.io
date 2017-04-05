---
layout: post
title:  "A Few of my New Favorite Ruby Gems"
date:   2017-04-05 10:36:36 -0400
---


This is the fifth installment of the blogging assignments (out of seven), that I am required to complete during the Fullstack Web Development online program, [LearnVerified](https://learn.co/verified), at the [Flatiron School](http://www.flatironschool.com/). Not only do they ‘make us’ learn lots of code…they want us to blog about it as well. This installment will cover some of my new favorite Ruby gems that I have discovered so far during my learning to code journey.

As the saga continues...

## Progress Update

I am still, ever so slowly, pushing my way through the curriculum. After my pretty impressive code streak early on in the race, I hit a few 'bumps in the road of life' that have significantly slowed my progress. Yet, despite those bumps, my love of learning and love of code continues. My progress through the course may have slowed down, but I am still coding every day and enjoying the learning process.

During the last few months, despite the crawling pace through the LearnCo curriculum, I have managed to work my way through a couple of in-depth, Rails coding courses, through Udemy that I had previously purchased but hadn't gotten around to working on yet. As well, as making progress through other coding platforms like [Treehouse](https://www.teamtreehouse.com) and [SoloLearn](https://www.sololearn.com/), which may not seem all that productive in the grand scheme of things, but for me, they are life savers for squeezing in free moments throughout the day to code.

## Despite My Bumps in the Road of Life

Even with my 'bumps in the road of life' I have managed to achieve a pretty 'green' GitHub contribution graph, considering at the beginning of 2016, I didn't even know what GitHub was, nevermind knowing the significance of the GitHub Contribution graph?!?!

![My GitHub Contribution graph](http://i.imgur.com/CBpGttQ.jpg)

I am actually glad to have put these courses off till I had worked my way through a good portion of the curriculum at LearnCo, as it was a cool way to sort of solidify some of the stuff I have been learning and being able to see it in action as I went through these tutorials building various apps.

During my little 'side trip of Udemy tutorials', I have stumbled upon some useful little 'gems' (pun totally intended) at RubyGems.org that have been great additions to my growing list of helpful gems to use while working with Rails applications.

So without further ado...

## My 12+ new (well, new to me) favorite Ruby gems

1. [hirb](https://rubygems.org/gems/hirb/versions/0.7.3) - provides a mini view framework for console applications and uses it to improve rails console (or irb) default inspect output. This was probably my first cool gem find (at least until I further investigated and found #2 on this list), other than the more commonly used gems like Devise, Bootstrap and even Rails (which are all pretty cool in their own right!), cause it just makes the output in the console so much easier to read and search through.
2. [table_print](https://rubygems.org/gems/table_print) - similar to the Hirb gem...but even cooler! TablePrint turns objects into nicely formatted columns for easy reading. I find this much easier to customize the information you would like to see by using symbols or strings to reference the columns.
![Default console output vs. TablePrint output](http://i.imgur.com/bVKrklX.jpg)

3. [simple_form](https://rubygems.org/gems/simple_form) - as the description says 'Forms made easy!' For basic forms, the gem simplifies the code for a Rails form. I have read some cautionary tales about using it as a newbie, as you should concentrate on learning how to first use the Rails regular form helpers before 'simplifying' things...but I added it as a new gem I encountered on my 'Udemy tutorial side trip.'
4. [bootstrap-twitter-rails]() - this gem makes it incredibly simple to create/generate a nice-looking website. It provides a few generators to create a Bootstrap layout and resource CRUD views.
5. [rubocop](https://rubygems.org/gems/rubocop) - is a Ruby static code analyzer. Out of the box, it will enforce many of the guidelines outlined in the community Ruby Style Guide. In my relative newbie status as a Ruby on Rails developer, I have quickly become aware of 'DRY principles' and 'code smell'...Rubocop has opened my eyes to a whole 'nother level of coding OCD!
6. [cancancan](https://rubygems.org/gems/cancancan) - is an authorization library that restricts what resources a given user is allowed to access. Use it to define which role can read/update/delete which resource. All permissions defined in a single location and not duplicated across all controllers, views and database queries.
7. [kaminari](https://rubygems.org/gems/kaminari) - for easily adding pagination to your application. Similar to [will_paginate](https://rubygems.org/gems/will_paginate) which I have also used on my 'Udemy tutorial side trip' with ease as well.
8. [devise](https://rubygems.org/gems/devise) - I have learned quickly that this is the go-to gem for user authentication. Basically, authentication determines who the user is, via email/username + password. Devise handles sign in, sign up, reset password, and etc.
9. [carrierwave](https://rubygems.org/gems/carrierwave) - allows you to upload files to your application. Restricting file types or defining styles when working with images such as thumbnails and profile sizes is made simple. Similar to [Paperclip](https://rubygems.org/gems/paperclip) which I have also used with a couple of different applications including the very first Rails tutorial I ever completed, in which we created a Pinterest-clone, you can check my finished app out [here](https://sandypinterested.herokuapp.com/).
10. [gritter](https://rubygems.org/gems/gritter/versions/1.2.0) - this gem allows you to easily add Growl-like notifications to your application using a jQuery plugin called 'gritter'. When I was first introduced to this gem I didn't exactly know what Growl notifications were (I have since Googled it), I thought learning how to implement this gem was cool cause I could have snazzy new flash messages.
11. [coderay](https://rubygems.org/gems/coderay) - is a Ruby library for syntax highlighting. As someone learning to code, being able to reference a line of code and have syntax highlighting applied when writing a blog post or commenting on a coding blog post, is something you get used quickly and then feel 'naked' without it when you don't have it. You put your code in, and you get it back colored; Keywords, strings, floats, comments - all in different colors. And with line numbers. ![Code Snippet](http://i.imgur.com/O7lOh0T.jpg)
12. [redcarpet](https://rubygems.org/gems/redcarpet) - a gem that easily adds extensible Markdown to (X)HTML parser. This gem I find particularly useful considering one of the first basic apps you might create when learning to code is a blogging app. And although creating the app is pretty cool, if you wanted to use it for your blog you would quickly find that there is no styling to your text...it just ends up as one big wall of text. Being able to markup your blog post with Markdown (so that you can having the ability to add headings, paragraph breaks, images or links etc) makes the app feel more real.

## Lessons Learned Might Justify the Snail Paced Progress

Although I am disappointed with myself for letting the pace of my LearnCo lessons slide, I can at least be happy that I am still learning. And in fact, I think my little 'side trip of Udemy tutorials' has been beneficial to my progress through the curriculum. It has shown me a lot of the concepts I have already been learning in another light which has helped to solidify further that knowledge.

So it takes me a little bit longer to get through the curriculum...that is ok. Just this week, I was able to explain to another newbie Rails developer what a line of code in the Devise documentation, about Configuring Routes was doing. To me (and to the guy I was helping), that was a big deal.






