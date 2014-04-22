---
layout: post
title: "Give a try to Interactors."
quote: Need food
image: false
video: false
---
I've been playing with interactors for a few weeks, and I have to admit I like the way it behave. It's a neat way to separate this kind of code, you either put in controller methods (bad) or in this fat model (have you seen my five hundreds lines User class ?).

It's basically a service object, with some helper methods, the ability to decide if the action you initiate failed or not, and rollback possibilities. None of this is really new, but all together it makes a nice and really useful plain-ruby object. I recommend you to read <a href='https://github.com/collectiveidea/interactor' target="_blank">this article</a>, and to test it. You probably have somewhere this huge `process_stuff` or `update_this_regarding_that` method you can give a try on.

I won't re-write the doc, I'd rather look further in the interactor gem code.

