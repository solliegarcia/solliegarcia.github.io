---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---

<img class="ui medium right floated rounded image" src="../images/meteor-destruction.png">

# Smooth Landing

My first experience with Meteor has gone much smoother than past experiences with other web frameworks. I've done a lot of work on [Ruby on Rails](http://rubyonrails.org/) and my first experience with that was interesting. I had no clue where to place anything, how different files interacted with each other, etc. I pushed through it and it soon clicked in my head how everything communicated. My experience with Meteor has gone the exact opposite. Having been exposed to Ruby on Rails, the layout of files are almost the same except Meteor is **much** more lenient. It is easy for me to grasp on to the concept of all these file systems because it is so much like Rails. 

> Practice Makes Perfect

The "Model View Controller" is pushed by Rails extrenuiously and has now been engraved in my mind. The cool thing with Meteor is that I can lay out my code anyway I want; there is no routes and no forced controllers. However, there were some bumps in the road getting Meteor setup. 

## Meteor Distuputs Time...

Setting up Meteor was simple, however deploying it is a different story. I found my two year old high end laptop struggling to deploy a development environment in under 10 minutes. That is a lot of down time. I have yet to figure out how to fix the problem by using meteor commands but I have an idea that might fix it. It may just be easier to boot up a [VagrantBox](https://www.vagrantup.com/) and run meteor through there. It is simple enough to install and getting the development environment takes only takes one command, 'vagrant up'. This would require some testing because I have come across vagrant boxes that everytime they boot, they have to redownload all the assets and I assume that is why deploying the normal way takes quite a while. 