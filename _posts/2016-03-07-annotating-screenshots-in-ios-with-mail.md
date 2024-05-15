---
title: 'Annotating Screenshots in iOS with Mail'
author: 'Teddy Svoronos'
layout: post
categories:
    - Productivity
tags:
    - Productivity
    - ios
    - workflows
---


Gabe Weatherhead has [an awesome post](http://www.macdrifter.com/2016/03/redaction-and-annotation-with-pixelmator-for-ios.html) about how he uses [the awesome Pixelmator](https://itunes.apple.com/us/app/pixelmator/id924695435?mt=8&uo=4&at=1010lcfa) to annotate screenshots. It's awesome. 

Gabe's discussion of the limitations of all the [many](https://itunes.apple.com/us/app/pointout-show-what-you-mean!/id985172637?mt=8&uo=4&at=1010lcfa) different [existing](https://itunes.apple.com/us/app/pinpoint-mark-up-screenshots/id669858907?mt=8&uo=4&at=1010lcfa) iOS [apps](https://itunes.apple.com/us/app/omnigraffle-2/id899656932?mt=8&uo=4&at=1010lcfa) to annotate screenshots got me thinking about another option: [the Markup extension in iOS Mail](http://www.iphonejd.com/iphone_jd/2015/09/markup-ios-9.html).

In addition to being built in, the Markup extension has some nice properties:

  * it has excellent shape recognition, including arrows;
  * it's pressure sensitive using 3D Touch on the iPhone 6s and the Pencil on the iPad Pro;
  * it has a very simple and easy to use interface.

There's just one big downside to markup: for reasons I cannot fathom, it's only available in Mail[^1]. This is in spite of the fact that it exists in the action extension share sheet in Mail:

![](/assets/img/2016-03-markup-share.png){width=40%}

Despite this major limitation, the usability of the markup extension makes it worth using by sharing a photo via Mail, then saving the sent image back to your photo library.

First, share an image via Mail and tap on the image to get the Markup option (I sometimes have to tap it more than once):

![](/assets/img/2016-03-markup-sharesheet.png)

You can then edit the image to your heart's content including shapes (notice the nice shape recognition option at the bottom), text, and even a magnifier callout:

![](/assets/img/2016-03-magnifier.png)

Once that's done, you can either send it to yourself and save/share the image from iOS mail, or you can use [this handy dandy IFTTT recipe](https://ifttt.com/recipes/394053-send-a-photo-to-your-photo-library) to email it to IFTTT which saves it back into your photo library, annotated and all. A bit roundabout, but it works.

* * *

[^1]: That's right, not even Notes or Messages. Maybe in iOS 10?
