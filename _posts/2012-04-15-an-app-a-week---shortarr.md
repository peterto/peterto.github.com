---
layout: post
title: "An App A Week   Shortarr"
category: 
tags: [development]
---

Here's my first app, [shortarr](https://github.com/peterto/shortarr).

Check out the demo here on [heroku](http://shortarr.herokuapp.com/).

Basic functionality works, it takes a valid URL, you can't give it a URL
that's not a URL and gives you back a shortened link for it.

Software Stack
==============

* [Ruby on Rails](http://rubyonrails.org/) version 3.2.1
* [MongoDB](http://www.mongodb.org/) via [Mongoid](http://mongoid.org/)
  with a free add-on from [MongoHQ](https://mongohq.com/)
* [Heroku](http://www.heroku.com/) for hosting
* [git/github](https://github.com/) for version control

How it was created
------------------

So for the first few apps, I'm coding them in Ruby on Rails, since I
just finished a 2 month class at [General
Assembly](http://generalassemb.ly/). I decided
to add in something I didn't have experience with, a [NoSQL
database](http://nosql-database.org/) in
the form of [MongoDB](http://www.mongodb.org/).

Funtionally, everything is there. Everything is composed of one
controller with a match in the route that calls a method in the
controller that redirects to the submitted URL. For ease of coding, I used Mongo's ID has as
the URL instead of generating my own hash to complete the shortened URL.


Issues and stuff I could have done better
-----------------------------------------

So I could have wrote more tests, but, I wanted to get this out of the
door, so I didn't catch everything I needed to test. I could've used
shorter hashes for the shortened URL, but why do more work for myself
when Mongo does all the heavy lifting for me.


Next App
========

I'm not sure what I'll make, but I think I'll make a
[flickr](http://www.flickr.com/) clone or make a basic tetris game in
flixel. If you have an idea, let me know in the comments and if I don't
think it's too crazy for my skill level, I'll make it happen.

P.S. I cheated a little and did some of the prework on this thing a few weeks
ago by removing all of activerecord. Yes, I know there's a command for
that, but I didn't know that at the time. I'm still a noob.

{% include JB/setup %}
