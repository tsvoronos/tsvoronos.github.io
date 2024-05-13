---
id: 817
title: 'Producing, Recording, Editing, and Sharing Animated Videos on iPad'
date: '2018-12-04T16:43:48-05:00'
author: 'Teddy Svoronos'
layout: post
guid: 'http://teddysvoronos.com/?p=817'
permalink: /2018/12/04/producing-recording-editing-and-sharing-animated-videos-on-ipad/
categories:
    - Pedagogy
    - Productivity
tags:
    - ios
    - ipad
    - production
---

<figure>
<img src="http://teddysvoronos.com/wp-content/uploads/2018/12/My-production-setup.jpeg" alt="" />
</figure>

<p>A significant part of my pedagogical approach involves the creation of <a href="https://bit.ly/SvoronosTeachingArtifacts">short, animated videos</a> that convey statistical concepts. Students watch these videos and answer a few quiz questions, which I can then use to make better use of the time we have in class together.</p>

<p>Initially, I would record these videos using Keynote on my Mac, edit them on my Mac, and post them online on my Mac. Over the past year or two, I’ve shifted the entire process onto my iPad - recording with an external mic, editing it in its entirety, and uploading it using Safari. I’m documenting that process in this post for my future self and for anyone else that is interested in doing this too.</p>

<h2>Recording</h2>

<h3>Video</h3>

<p>Recording a Keynote presentation has become possible since <a href="https://support.apple.com/en-us/HT207935">iOS 11 introduced screen recording to Control Center</a>. Now, I can tap record, go through a Keynote presentation, <a href="https://help.apple.com/keynote/ipad/4.3/#/tan72233051">write on slides</a> as I go<sup><a href="#fn1-10639" id="fnr1-10639" title="see footnote" class="footnote">1</a></sup>, and end up with a high quality recording of my presentation. </p>

<p>One thing to keep in mind is that I always use presentations with a 16:9 (widescreen) aspect ratio. This way the annotation tools don’t show up on the presentation as I go, and when I export the final video in widescreen all the UI is hidden from the viewer (more on that later).</p>

<h3>Audio</h3>

<p>iOS’ screen recording feature also allow you to keep the microphone on while recording, so that you can narrate over your slides. However, if you’re in a noisy environment or have a very hot mic (I’m looking at you, Blue Yeti), you might want to add a noise gate and some gain control. Luckily, if you use an app that can send your mic input through your headphones while in the background, iOS screen recording will pick up the processed audio!</p>

<p>I use <a href="https://itunes.apple.com/us/app/garageband/id408709785?mt=8&uo=4&at=1010lcfa">GarageBand</a> for this. It’s free, it’s reliable, and it <a href="https://support.apple.com/kb/PH24861?viewlocale=en_US&locale=en_US">integrates with third party apps</a>. </p>

<p>Here’s what my GarageBand file looks like. It’s a single, flat audio track taking in my mic input and feeding it through the monitor (which is set to on). You’ll notice that I keep the gain level pretty low on the left.</p>

<figure>
<img src="http://teddysvoronos.com/wp-content/uploads/2018/12/Garageband-track.png" alt="" />
</figure>

<p>Now for the fun part. If you tap the track control buttons on the top left and tap “Plug-ins & EQ”, you can add a noise gate, change the EQ, or utilize any number of third party effects. </p>

<figure>
<img src="http://teddysvoronos.com/wp-content/uploads/2018/12/Plugins.jpeg" alt="" />
</figure>

<p>One app I highly recommend is <a href="https://itunes.apple.com/us/app/brusfri/id1289165912?mt=8&uo=4&at=1010lcfa">Brusfri</a>. Once you record a few seconds of silence, you can let Brusfri listen to your recording and filter out background noise for when you record your video. </p>

<figure>
<img src="http://teddysvoronos.com/wp-content/uploads/2018/12/Brusfri.png" alt="" />
</figure>

<h2>Editing</h2>

<h3>Video</h3>

<p>Once your recording is complete, it’s time to edit.</p>

<p>Editing video on the iPad has become pretty easy since the introduction of <a href="https://itunes.apple.com/us/app/lumafusion/id1062022008?mt=8&uo=4&at=(null)">LumaFusion</a>. To begin with, LumaFusion allows you to create a video in the 16:9 aspect ratio, which immediately gets rid of all UI elements from my video (if you want to use a simpler solution like <a href="https://itunes.apple.com/us/app/imovie/id377298193?mt=8&uo=4&at=1010lcfa">iMovie</a>, I suggest <a href="https://itunes.apple.com/us/app/video-crop-trim-cut-videos/id1309610014?mt=8&uo=4&at=1010lcfa">Video Crop</a> as an inexpensive app that will impose the aspect ratio that you need). Once your video is in LumaFusion, the world’s your oyster. You can create crossfades, add titles, or do whatever chopping and screwing your heart desires. </p>

<h3>Audio</h3>

<p>Two things worth noting about audio editing. First, iOS apps sometimes take a screen recording video and play it back with no audio at all. After a helpful exchange with the developers of <a href="https://itunes.apple.com/us/app/ferrite-recording-studio/id1018780185?mt=8&uo=4&at=1010lcfa">Ferrite</a>, I learned that this is because the video file actually has <em>two</em> tracks: whatever sounds the iPad itself produced via software, and the microphone input. Some apps simply ignore the mic input. I’ve found that using the “Detach” button in LumaFusion fixes this<sup><a href="#fn2-10639" id="fnr2-10639" title="see footnote" class="footnote">2</a></sup>:</p>

<figure>
<img src="http://teddysvoronos.com/wp-content/uploads/2018/12/Detaching-audio.jpeg" alt="" />
</figure>

<p>Second, if you <em>didn’t</em> do any noise reduction/voice boosting before recording, you can share your video to <a href="https://itunes.apple.com/us/app/brusfri/id1289165912?mt=8&uo=4&at=1010lcfa">Brusfri</a> or <a href="https://itunes.apple.com/us/app/ferrite-recording-studio/id1018780185?mt=8&uo=4&at=1010lcfa">Ferrite</a> to clean up the audio, and then drop the audio file into LumaFusion alongside the video.</p>

<h2>Uploading</h2>

<p>Once this is all done, you’re ready to upload. While LumaFusion integrates with many video services and services, I need an actual file to upload to Kaltura, the video hosting platform that my institution uses, so I choose iCloud Drive and save the video in the Files app. Once I go to my media uploader in Safari, I simply select that file using the Browse option (any website with a standard file uploading interface should let you choose your video file via Browse):</p>

<figure>
<img src="http://teddysvoronos.com/wp-content/uploads/2018/12/Uploading.jpeg" alt="" />
</figure>

<h2>A fully functioning system</h2>

<p>At this point, 100% of my needs with respect to this workflow are satisfied by my iPad. This means that I have a fully mobile recording studio, and it’s quite easy to make a high quality video in a relatively short amount of time. Hope others will find this useful and, as always, please let me know if you have questions or thoughts. </p>

<div class="footnotes">
<hr />
<ol>

<li id="fn1-10639">
<p>Though I <em>really</em> wish Apple would beef up these annotation capabilities <a href="#fnr1-10639" title="return to article" class="reversefootnote">↩︎</a></p>
</li>

<li id="fn2-10639">
<p>I’ve also noticed that any app that compresses the video will mix all the audio to one track, which also fixes the problem. <a href="#fnr2-10639" title="return to article" class="reversefootnote">↩︎</a></p>
</li>

</ol>
</div>