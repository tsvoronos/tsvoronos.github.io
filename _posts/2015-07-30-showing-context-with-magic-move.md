---
id: 308
title: 'Showing Context with Magic Move'
date: '2015-07-30T20:50:44-05:00'
author: 'Teddy Svoronos'
layout: post
guid: 'http://teddysvoronos.com/?p=308'
permalink: /2015/07/30/showing-context-with-magic-move/
categories:
    - Pedagogy
    - Productivity
tags:
    - Keynote
    - presentations
---

<p>I use Keynote for all of my presentations. It&#8217;s a hassle to have to run them off of my own devices instead of using a venue&#8217;s PC (though it&#8217;s <a href="http://teddysvoronos.com/2014/04/03/wireless-presenting-just-got-a-lot-easier/" target="_blank">getting easier</a>), but it&#8217;s worth it for one reason: making animations is incredibly easy in Keynote.</p>

<h2>Fitting In</h2>

<p>When I say animations, I don&#8217;t mean dissolves and <a href="https://en.m.wikipedia.org/wiki/Smash_cut" target="_blank">smash cuts</a>. I mean moving objects within a slide in a way that shows them in a new light or reveals more context.</p>

<p>For example, here&#8217;s a graph showing changes in global surface temperatures over the past thirteen ears (which looks flat), which I then frame in terms of a much longer timescale (which shows temperatures rising at an increasing rate):</p>

<img src="http://teddysvoronos.com/wp-content/uploads/2015/07/wpid-ClimateChange.gif" alt="" id="climate" />


<p>Here&#8217;s another example from my dissertation work. My research involves taking randomized trials and analyzing them as an interrupted time series analysis. This can be a little difficult to understand conceptually, so I use an animation to visually show the difference between the two analytic strategies:</p>

<img src="http://teddysvoronos.com/wp-content/uploads/2015/07/wpid-ITSanimation.gif" alt="" id="its" />


<p>To me, these animations are useful because the objects of interest never disappear from the screen. They are simply reframed in a different context, allowing the audience to make the leap from one setting to another.</p>

<p>I&#8217;m sure there&#8217;s some great literature on why this is more compelling, but all I can say is that it has worked very well in my experience. Better still, the time cost of making these is much lower than you might think.</p>

<h2>From Transitions to Animations</h2>

<p>I made a toy example that builds a diagram using three methods: a simple dissolve transition, an animation, and an animation with an additional delay that I find appealing. Here they in sequence:</p>

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/JDj-aZlDEhw" frameborder="0" allowfullscreen></iframe></center>

<p>And here they are next to one another (I timed it so that the actual length of transitions is the same for all three):</p>

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/cNhq_d96NSs" frameborder="0" allowfullscreen></iframe></center>

<p><a href="http://teddysvoronos.com/wp-content/uploads/2015/07/Magic-Move-Sample.key.zip">Here&#8217;s a link to the Keynote file</a>, if you&#8217;d like to play with it further.</p>

<h3>From Dissolve to Magic Move</h3>

<p>Going from the dissolve transitions to the animated transitions is as simple as changing the transition between slides from &#8220;Dissolve&#8221; to &#8220;Magic Move&#8221;. Magic Move is a Keynote-specific transition that detects identical objects between two slides, then transitions between the slides by having those objects move from their place in Slide 1 to their place in Slide 2. The easiest way to make this happen is as follows:</p>

<ol>
<li>Duplicate Slide 1 and change its transition to &#8220;Magic Move&#8221;;</li>
<li>Move around the objects in the duplicated slide as you&#8217;d like;</li>
<li>Profit.</li>
</ol>

<p>It can be a little finicky at times, especially if you have lots of similar objects (I&#8217;ve had this problem when there were lots of arrows on a slide - more on that later), but for most situations it works.</p>

<h3>From Magic Move to Delayed Transitions</h3>

<p>The jump in quality from Dissolve to Magic Move is enormous; now let&#8217;s talk add some frills. I often like to have the objects in Slide 2 that are brand new to fade in <em>after</em> the initial movement has taken place, as opposed to <em>during</em>. Doing this requires a few more steps:</p>

<ol>
<li>Select all the objects in Slide 2 that aren&#8217;t part of the Magic Move transition;</li>
<li>Give them each a &#8220;Fade In&#8221; animation (I tend to use Dissolve with a short duration);</li>
<li>Click on Build Order;</li>
<li>Decide if you want these objects to fade all at once or one at a time, and make the appropriate adjustment;</li>
<li>Make sure that the first animation in Build Order is set to start &#8220;After Transition&#8221;.</li>
</ol>

<p>This may seem like a lot of steps for a small change, but there&#8217;s an added benefit: by having objects fade in after the transition, you remove them from Magic Move&#8217;s detection algorithm. So, if you&#8217;re noticing that Magic Move is choosing the wrong objects to move, you can remove them from the equation by having them fade in afterwards. Bingo!</p>

<h2>From Slides to Videos</h2>

<p>In my opinion, these animations make presentations a much more valuable tool to convey complex information in a comprehensible way. So valuable, in fact, that I&#8217;ve taken the additional step of making them full fledged videos. Almost all of the materials in the <a href="http://www.teddysvoronos.com/teaching" target="_blank">Teaching</a> section of my website were made using Keynote. After setting up animations to my liking, I use the &#8220;Record Slideshow&#8221; function to add a voiceover and export it as a video file. But that&#8217;s for another post.</p>