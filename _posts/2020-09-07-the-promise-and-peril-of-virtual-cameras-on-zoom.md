---
id: 1037
title: 'The Promise and Peril of Virtual Cameras on Zoom'
date: '2020-09-07T11:58:12-05:00'
author: 'Teddy Svoronos'
layout: post
categories:
    - Pedagogy
tags:
    - Pedagogy
    - 'atem mini'
    - mmhmm
    - obs
    - 'online teaching'
    - 'virtual cameras'
    - zoom
---

<h2>A problem and a potential solution</h2>
<p>This post is the product of several months of experimenting, learning, conversing, and purchasing. It came from a desire to move away from <a href="https://twitter.com/tedsvo/status/1286299229116301314?s=21">traditional screen sharing</a>, which is often characterized by <strong>your slides/visuals taking over a huge portion of your students' screens</strong> (which can be offset somewhat with <a href="https://support.zoom.us/hc/en-us/articles/115004802843-Side-by-side-Mode-for-screen-sharing">side-by-side mode</a>).</p>
<p>One way of getting around this is to use what are called &quot;<strong>virtual cameras</strong>&quot; - in essence, using software or hardware to create a more sophisticated overlay of video/images/feeds, which then get treated by Zoom as a regular webcam. Using software tools like <a href="https://obsproject.com">OBS</a> or <a href="https://www.mmhmm.app">mmhmm</a>, or hardware tools like the <a href="https://www.blackmagicdesign.com/products/atemmini">ATEM Mini</a>, you can get some really fun and engaging visuals. Here are a few examples, starting with an excellent introduction by the always insightful and creative <a href="https://twitter.com/lukestein/status/1297306413358866433">Luke Stein</a>:</p>
</div>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">If you’d like to dip your toes into using <a href="https://twitter.com/OBSProject?ref_src=twsrc%5Etfw">@OBSProject</a>, it’s easy to get started. Most tutorials seemed geared towards gamers, though.<br><br>Here’s a four minute “quickstart” for anyone who wants to try it for teaching. Seriously, you can be up and running.* <a href="https://t.co/vAD5QG7NFT">https://t.co/vAD5QG7NFT</a> <a href="https://t.co/9dqwk7vQDK">https://t.co/9dqwk7vQDK</a> <a href="https://t.co/TZWP9JSWDG">pic.twitter.com/TZWP9JSWDG</a></p>&mdash; ⑆Luke Stein⑈ (@lukestein) <a href="https://twitter.com/lukestein/status/1297306413358866433?ref_src=twsrc%5Etfw">August 22, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">A lightboard-style setup without the lightboard. All you need is an ipad, a stylus, and OBS. Thanks <a href="https://twitter.com/rithvikra0?ref_src=twsrc%5Etfw">@rithvikra0</a> for the idea! <a href="https://twitter.com/hashtag/EconTwitter?src=hash&amp;ref_src=twsrc%5Etfw">#EconTwitter</a> <a href="https://t.co/YPPotUZSEe">pic.twitter.com/YPPotUZSEe</a></p>&mdash; Shengwu Li (@ShengwuLi) <a href="https://twitter.com/ShengwuLi/status/1300529367827841032?ref_src=twsrc%5Etfw">August 31, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


Once you have a virtual camera all set up, all you have to do is select it from Zoom's list of cameras to start using it:

![](/assets/img/2020-09-virtual-cameras.png)

Theoretically, the use of virtual cameras should let you create rich, overlaid environments where students can see you and additional content through a single webcam, without having to futz with Zoom's screen sharing interface (which can be clunky and slow in my experience).

It was with this promise that I embarked on dozens of hours of experimentation with all the software and hardware that I could find.

**The problem is, at least with Zoom, this ends up not working very well.**

## The bad news

The reason for this is that **Zoom is constantly making tradeoffs between quality (resolution) and smoothness (framerate) to optimize video, and in doing so is making a lot of assumptions about the nature of your video**. In short, it assumes that you want your webcam to be smooth at the expense of quality (it's weird to have choppy video of you talking) and your screen sharing to prioritize quality at the expense of smoothness (you're often showing a static image with text on it, and that text must be readable).

Perhaps you can see the problem already - if you're sharing your slides with you overlaid on top of them, you want your slides to be high quality and your video camera to be smooth. But since you're just piping in a single virtual camera into Zoom, it's treating your feed like a webcam - smooth and low quality, making it difficult to read text.

### The worse news

**This problem has gotten worse since COVID hit**, since the huge pressure on Zoom's infrastructure has led them to essentially disable the sharing of a webcam in HD regardless of your settings ([accessed September 7, 2020](https://support.zoom.us/hc/en-us/articles/207347086-Group-HD)):

> Note: As our world comes together to slow the spread of COVID-19 and stays connected through Zoom globally, we are working to quickly scale our bandwidth during this unprecedented demand.
> 
> For the time being, standard video, not HD video, will be activated when 3 or more participants join a group meeting. HD video (720p) will be activated for 2 participants or when a Zoom Room or Conference Room Connector joins a group meeting. HD video (1080p) will only be activated for selective use cases such as large format broadcast events.

That means that your webcam will pretty much always be transmitted at 360p in any classroom setting.

### The even worse news

The part that concerns me the most is that **it's difficult to test this on your own**, since (a) On your computer, Zoom shows your local uncompressed video feed so it looks fine to you; and (b) The nature of its compression changes as more people join. What this means is you might end up getting comfortable a really cool virtual camera setup, starting a large Zoom class, and finding out that none of your students can make out what you've typed or written. That's, like, teaching-stress-dream-level bad news.

### A (kind of) workaround

One way to get around this issue is to use an option in Zoom's Advanced Screen Sharing window called "Content from 2nd Camera":

![](/assets/img/2020-09-second-camera.png)

Once you click this and then switch to the appropriate virtual camera, Zoom will start to transmit that camera in high resolution, prioritizing it like it would prioritize a regular screen share.

The problem is - you guessed it - doing so drastically reduces the frame rate that Zoom sends from that camera. You can try to offset this by clicking "Optimize Screen Share for Video Clip," but that ends up transmitting a quality that's quite similar to what you'd get from just using the webcam itself. Here, you can see it switching between high resolution (1080p) low frame rate (vacillating between 20 and 2 fps) and low resolution (360p) high frame rate (30 fps):

<iframe width="560" height="315" src="https://www.youtube.com/embed/YaW_GCNDsJ0?si=vx74rrrMCCLMSqTf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## A cry for help

My sincere hope is that this entire post will become out of date as soon as possible - Zoom will return to enabling full HD webcam output and we can go back to trying out lots of cool software and hardware solutions to bring engaging content to our students.

Until then, I hope this post is a warning to teachers jumping on the virtual camera train without adequately testing out its implications for their students.

Finally, if you have figured out some way around these constraints, please let me know in the comments! The saving grace of these frustrations has been encountering an innovative and passionate community focused on teaching effectively online. I'm hopeful that there's something I haven't thought of that will be shared - I'll update this post accordingly if so!
