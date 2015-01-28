---
layout: post
title: Code Fun - The Elf Name Generator
author: Richard Bennett
author_email: richard.bennett.cti@gmail.com
feature_img: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI4IiBoZWlnaHQ9IjgiPjxwYXRoIGQ9Ik0tMiAxMEwxMCAtMlpNMTAgNkw2IDEwWk0tMiAyTDIgLTIiIHN0cm9rZT0iI2ZmZiIgc3Ryb2tlLXdpZHRoPSI0LjciPjwvcGF0aD4KPC9zdmc+"),url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiPgo8bGluZWFyR3JhZGllbnQgaWQ9ImciIHgyPSIxIiB5Mj0iMSI+CjxzdG9wIHN0b3AtY29sb3I9IiNFRTI1MjQiPjwvc3RvcD4KPHN0b3Agb2Zmc2V0PSIxMDAlIiBzdG9wLWNvbG9yPSIjRjEyMTE1Ij48L3N0b3A+CjwvbGluZWFyR3JhZGllbnQ+CjxyZWN0IHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiIGZpbGw9InVybCgjZykiPjwvcmVjdD4KPC9zdmc+")
---

# Preface

I have to start this off with a preface.  A bit of an explanation as to what this is.

It all started with an app I was working on.  It required people to specify a username.  So when I finally connected the login API, ran the simulator, opened the app; I just sat there for a second.  I was thinking...

> What the hell should I use as my username?

For some reason (too much "holiday cheer?") my mind wasn't working.  Then I thought back at how many times I was forced to come up with a username for a site or an app I used and I couldn't think of anything.

I have my standard usernames, sure - but this one was context sensitive.  This was a holiday-themed app, and therefore required something special.

# Enter __Donkeyhill Butterbottom__

I found a quick little tutorial on Tuts+ (__[Quick Tip: How to Code a Simple Character Name Generator](http://warpedvisions.org)__).  With some simple modifications, I created a fun and effortless way to create a user account for my app.

The most time-consuming part of the whole process was coming up with all the words that would make-up these elf names.  I'll admit that I'm a surly bugger, and my demeanor doesn't usually improve around the holidays, so I don't usually get in the "mood."

With some help of a few colleagues, I had my (ever-expanding) list.

My favourite so far is my current username, __Donkeyhill Butterbottom__.  It still makes me laugh just thinking about it.

# Why stop there?

At this point, I coded the signup form to generate the username each time the user entered an empty "username" input.  I found that I was deleting the name and re-entering it over and over just to see the crazy names it would produce.

I'm too lazy to let that continue.

So I added a gesture event that detected a device shake.  As the device shook beyond a defined threshold, an alertbox appeared with a new elf name.  Brilliant.

# Make it viral

The shake + alert box was all well and good.  I was generating names like mad.  People laughed.  Some cried.

My girl enjoyed them a lot.  Maybe in an unhealthy way.

So I naturally had to appease her humor by sending them to her contstantly.  To make this easier, I added a bit functionality to copy the name to the device clipboard instead of just dismissing the alert.

Now, you can dismiss AND copy.  Shazam.

A simple paste in my Message app of choice and she's happy.

# Next steps

Before the onset of the 2015 holiday season, you can expect this app to finish.

In addition to what's mentioned above, I'd like to...

+ add the ability for users to enter their own comma-separated list of words for name generation (who knows how horribly inappropriate it will get)
+ add the ability to instantly share to Twitter, Facebook, or Google

...voila.

Instant marketing strategy.
