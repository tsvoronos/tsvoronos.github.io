---
title: 'Showing Context with Magic Move'
author: 'Teddy Svoronos'
layout: post
categories:
    - Pedagogy
    - Productivity
tags:
    - Keynote
    - presentations
---
I use Keynote for all of my presentations. It's a hassle to have to run them off of my own devices instead of using a venue's PC (though it's [getting easier](http://teddysvoronos.com/2014/04/03/wireless-presenting-just-got-a-lot-easier/)), but it's worth it for one reason: making animations is incredibly easy in Keynote.

## Fitting In

When I say animations, I don't mean dissolves and [smash cuts](https://en.m.wikipedia.org/wiki/Smash_cut). I mean moving objects within a slide in a way that shows them in a new light or reveals more context.

For example, here's a graph showing changes in global surface temperatures over the past thirteen ears (which looks flat), which I then frame in terms of a much longer timescale (which shows temperatures rising at an increasing rate):

![](/assets/img/2015-07-climatechange.gif) 

Here's another example from my dissertation work. My research involves taking randomized trials and analyzing them as an interrupted time series analysis. This can be a little difficult to understand conceptually, so I use an animation to visually show the difference between the two analytic strategies:

![](/assets/img/2015-07-its.gif) 

To me, these animations are useful because the objects of interest never disappear from the screen. They are simply reframed in a different context, allowing the audience to make the leap from one setting to another.

I'm sure there's some great literature on why this is more compelling, but all I can say is that it has worked very well in my experience. Better still, the time cost of making these is much lower than you might think.

## From Transitions to Animations

I made a toy example that builds a diagram using three methods: a simple dissolve transition, an animation, and an animation with an additional delay that I find appealing. Here they in sequence:

And here they are next to one another (I timed it so that the actual length of transitions is the same for all three):

[Here's a link to the Keynote file](/downloads/Magic-Move-Sample.key.zip), if you'd like to play with it further.

### From Dissolve to Magic Move

Going from the dissolve transitions to the animated transitions is as simple as changing the transition between slides from "Dissolve" to "Magic Move". Magic Move is a Keynote-specific transition that detects identical objects between two slides, then transitions between the slides by having those objects move from their place in Slide 1 to their place in Slide 2. The easiest way to make this happen is as follows:

  1. Duplicate Slide 1 and change its transition to "Magic Move";
  2. Move around the objects in the duplicated slide as you'd like;
  3. Profit.

It can be a little finicky at times, especially if you have lots of similar objects (I've had this problem when there were lots of arrows on a slide - more on that later), but for most situations it works.

### From Magic Move to Delayed Transitions

The jump in quality from Dissolve to Magic Move is enormous; now let's talk add some frills. I often like to have the objects in Slide 2 that are brand new to fade in _after_ the initial movement has taken place, as opposed to _during_. Doing this requires a few more steps:

  1. Select all the objects in Slide 2 that aren't part of the Magic Move transition;
  2. Give them each a "Fade In" animation (I tend to use Dissolve with a short duration);
  3. Click on Build Order;
  4. Decide if you want these objects to fade all at once or one at a time, and make the appropriate adjustment;
  5. Make sure that the first animation in Build Order is set to start "After Transition".

This may seem like a lot of steps for a small change, but there's an added benefit: by having objects fade in after the transition, you remove them from Magic Move's detection algorithm. So, if you're noticing that Magic Move is choosing the wrong objects to move, you can remove them from the equation by having them fade in afterwards. Bingo!

## From Slides to Videos

In my opinion, these animations make presentations a much more valuable tool to convey complex information in a comprehensible way. So valuable, in fact, that I've taken the additional step of making them full fledged videos. Almost all of the materials in the [Teaching](http://www.teddysvoronos.com/teaching) section of my website were made using Keynote. After setting up animations to my liking, I use the "Record Slideshow" function to add a voiceover and export it as a video file. But that's for another post.
