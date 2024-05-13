---
id: 279
title: 'Save files on iOS with Workflow'
date: '2015-01-04T18:49:29-05:00'
author: 'Teddy Svoronos'
layout: post
guid: 'http://teddysvoronos.com/?p=279'
permalink: /2015/01/04/save-files-on-ios-with-workflow-2/
categories:
    - Productivity
tags:
    - icloud
    - ios
    - Workflow
---

<p>I like getting work done on my iPhone and iPad. At times it gets impractical (I&#8217;m looking at you Stata), but there are lots of simple actions that I can do from my iOS devices, oftentimes faster than I can do on my Mac. One task that I always thought I <em>should</em> be able to quickly do from my iOS device is save a file from Safari, Mail, or any other app to a folder on Dropbox. This has been a pretty clunky process involving using the &#8220;Open In…&#8221; menu, opening a file in the Dropbox app, choosing a folder, tapping Save, and returning to the original app.</p>

<p>With the release of <a href="https://my.workflow.is/" target="_blank">Workflow</a>, I can finally say that it&#8217;s just as easy to save a file on iOS as it is on my Mac.</p>

<p>If you haven&#8217;t heard about Workflow, it&#8217;s a $2.99 app that lets you build custom actions that you can run from your device. Unlike previous workflow apps like <a href="http://omz-software.com/pythonista/" target="_blank">Pythonista</a> and <a href="http://omz-software.com/editorial/" target="_blank">Editorial</a>, Workflow is extremely easy for non-programmers to use. Lots has been written about it since its release in December, ranging from the <a href="http://macsparky.com/blog/2014/12/workflow-ios-automation?rq=workflow" target="_blank">simple</a> to the <a href="http://www.macstories.net/reviews/workflow-review-integrated-automation-for-ios-8/" target="_blank">extensive</a> to the <a href="https://onetapless.com/workflow-automation-for-everyone" target="_blank">extremely nerdy</a>. This app can do a million things, but in this post I will focus on an extremely useful, and extremely simple to set up, action to save a file.</p>

<h2>The final product</h2>

<p>I often come across a PDF in Safari that I&#8217;d like to save. With Workflow, I tap &#8220;Open In…,&#8221; select &#8220;Run Workflow,&#8221; and choose one of three actions that I&#8217;ve set up:</p>

<img src="http://teddysvoronos.com/wp-content/uploads/2015/01/wpid-Workflow1.png" alt="" />


<p>These actions, in increasing order of both complexity and flexibility are:</p>

<ol>
<li>Save the file to a folder in my Dropbox called &#8220;1Read,&#8221; where I save PDFs for later reading;</li>
<li>Save the file to an arbitrary folder in Dropbox;</li>
<li>Save the file to a folder in iCloud Drive, Dropbox, Box, Google Drive, or any other third party service that supports <a href="http://www.imore.com/ios-8-document-provider-extensions-explained" target="_blank">document provider extensions in iOS 8</a>.</li>
</ol>

<p>Here&#8217;s a collection of screenshots that show the 1Read workflow (1), the Dropbox workflow (2), and the iCloud Drive (3a) or third party document provider (3b) workflow:</p>

<img src="http://teddysvoronos.com/wp-content/uploads/2015/01/wpid-Workflow2.png" alt="" />


<p>Workflow (1) has zero additional steps; it saves it to the 1Read folder and that&#8217;s it. Workflow (2) has the additional step of selecting a Dropbox folder in which to save the file. Workflow (3) involves first choosing a document provider, then choosing a folder<a href="#fn:1" id="fnref:1" title="see footnote" class="footnote">[1]</a>.</p>

<h2>The crazy part</h2>

<p><em>&#8220;That&#8217;s fine for a PhD student, but setting this up must take a lot of time, energy, and frustration.&#8221;</em></p>

<p>I hear you, dear reader, but fear not.</p>

<p>I give you, in its entirety, the setup for each of these three workflows:</p>

<img src="http://teddysvoronos.com/wp-content/uploads/2015/01/wpid-Workflow3.png" alt="" />


<p>Some notes:</p>

<ul>
<li>As you can see, Workflows (1) and (2) are identical, except for the toggle &#8220;Ask Where to Save.&#8221;</li>
<li>If you have a frequently used &#8220;inbox&#8221; folder, it&#8217;s worth setting up a separate workflow just for that folder.</li>
<li>Make sure you specify these workflows as &#8220;Action Extensions&#8221; so that they show up in the Share Sheet.</li>
<li>Workflow (3) is one that I&#8217;ve come to rely on quite a bit. Besides the third party providers, iCloud Drive is actually a nice save location, since if you don&#8217;t have an internet connection at the time of saving, it&#8217;ll save it locally and upload it once you get a connection.</li>
</ul>

<p>If you check out the <a href="https://twitter.com/WorkflowHQ" target="_blank">@WorkflowHQ</a> twitter page or the <a href="http://www.workflowgallery.co/" target="_blank">Workflow Gallery</a>, you&#8217;ll find lots and lots of other Workflows. But this is one that&#8217;s easy to set up, easy to use, and fills a real need in my work habits.</p>

<div class="footnotes">
<hr />
<ol>

<li id="fn:1">
<p>You may notice that Dropbox is a document provider that shows up in Workflow (3). Since I use it so much, and since the native document picker will sometimes crash, I made a separate Dropbox-only action. <a href="#fnref:1" title="return to article" class="reversefootnote">&#160;&#8617;</a></p>
</li>

</ol>
</div>