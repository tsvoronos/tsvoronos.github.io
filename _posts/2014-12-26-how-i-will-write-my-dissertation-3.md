---
id: 269
title: 'How I will write my dissertation'
date: '2014-12-26T17:14:23-05:00'
author: 'Teddy Svoronos'
layout: post
guid: 'http://teddysvoronos.com/?p=269'
permalink: /2014/12/26/how-i-will-write-my-dissertation-3/
categories:
    - Productivity
    - Research
tags:
    - latex
    - markdown
---

<p>In the spirit of getting my procrastinating done during the holidays (that&#8217;s how procrastinating works, right?), I thought I&#8217;d share how I choose to write complex papers. For my purposes, &#8220;complex&#8221; means any paper that involves some combination of:</p>

<ul>
<li>citations linked to some bibliography manager;</li>
<li>equations;</li>
<li>internal links (a.k.a. &#8220;<a href="https://support.office.com/en-us/article/Create-or-update-a-cross-reference-aa35c606-34e8-4c64-b6eb-c6321d190645?ui=en-US&amp;rs=en-US&amp;ad=US" target="_blank">cross references</a>&#8221;).</li>
</ul>

<p>For simpler papers, I really do like <a href="https://www.apple.com/mac/pages/" target="_blank">Pages</a>. It makes formatting relatively easy, it has (basic) <a href="http://support.apple.com/kb/PH15342" title="Pages for Mac 5.0: Use EndNote and MathType" target="_blank">EndNote and MathType support</a>, and it looks lovely on high resolution displays. More recently, I&#8217;ve become smitten with Apple&#8217;s new <a href="http://support.apple.com/en-us/HT6337" target="_blank">Handoff</a> feature that works with iOS 8 and OSX Yosemite devices. Being able to work on a paper at my desk, then pick up where I left off on my iPad as I move to the couch, then switch to my iPhone so I can stretch my legs, is pretty neat. Maybe this will get old someday, but for now it&#8217;s the bee&#8217;s knees.</p>

<p>Then there are the problems. In addition to the inability of Pages to satisfy my need for numbered equations, Apple is developing a bit of a reputation for poor backward-compatibility. I am terrified by the prospect of trying to open my dissertation in a few years and getting an alert like this (source: <a href="https://plus.google.com/u/0/+StefanUrbanek/posts/LKkGeEoPUzA" title="&quot;This presentation can’t be opened because it’s too old. To open it, save it…" target="_blank">Google+</a>):</p>

<img src="http://teddysvoronos.com/wp-content/uploads/2014/12/wpid-TooOld.png" alt="" />


<p>This is totally unacceptable, and I hope Apple understands what a massive detterent this is.</p>

<p>The opposite end of the usability vs. flexibility spectrum, there&#8217;s <a href="http://latex-project.org/" title="LaTeX – A document preparation system" target="_blank">LaTeX</a>. LaTeX combines the longevity of <a href="http://txtglory.com/" title="Text and Glory - Plain text file format praise" target="_blank">plain text</a> with a robust <a href="https://www.economics.utoronto.ca/osborne/latex/BIBTEX.HTM" title="Using BibTeX: a short guide" target="_blank">bibliography management system</a>, not to mention the fact that LaTeX was conceived for the purpose of printing mathematical formulas. But, as the above links may suggest, LaTeX tools won&#8217;t be winning any awards for UI design.</p>

<p>Enter <a href="http://fletcherpenney.net/" title="Home --- fletcherpenney.net" target="_blank">multimarkdown</a>. Developed by Fletcher Penny, MMD allows me to use one of the <a href="http://brettterpstra.com/ios-text-editors/" title="iTextEditors - iPhone and iPad text/code editors and writing tools compared" target="_blank">hundreds</a> of markdown<a href="#fn:1" id="fnref:1" title="see footnote" class="footnote">[1]</a> text editors for iOS using a syntax that can be exported as LaTeX. This export process does take some time to set up (see <a href="http://fletcherpenney.net/multimarkdown/use/" title="MultiMarkdown" target="_blank">here</a> for details), but once it&#8217;s read I simply have to prepend this metadata to the beginning of a file to make it export-ready:</p>

<pre><code>Title: Title of my document
Author: Teddy Svoronos
latex input: /path/to/header/mmd-teddy-header
latex footer: /path/to/footer/mmd-teddy-footer
Base header level: 2
Bibtex: /path/to/bibtex/file/bibfull
Biblio Style:plain
</code></pre>

<p>I may get into the details of this setup in a later post; let me know if there&#8217;s any interest.</p>

<p>My editor of choice is Byword (which was recently <a href="http://www.macstories.net/linked/byword-updated-with-handoff-document-providers-on-ios-8/" title="Byword Updated with Handoff, Document Providers on iOS 8 – MacStories" target="_blank">updated to support Handoff</a>), though I use Fletcher&#8217;s own <a href="http://multimarkdown.com/" title="The best MultiMarkdown editor just got better!" target="_blank">MultiMarkdown Composer</a> when I need to get in the weeds of internal links, table creation, and using the app&#8217;s native table of contents viewer. </p>

<p>The only potential rub in this setup is if my advisors want to use Word track changes to provide comments. In this case, I&#8217;ll have to export my file as rich text and do some manual futzing to make it presentable. Not great, but those occasional costs are outweighed by the benefits outlined above. </p>

<p>Boy, I&#8217;d better get writing. </p>

<div class="footnotes">
<hr />
<ol>

<li id="fn:1">
<p>For background on markdown, see <a href="http://daringfireball.net/projects/markdown/">Gruber&#8217;s original specification</a>. For an introduction to the syntax for non-coders and why you should use it, I recommend <a href="http://macsparky.com/markdown/">David Spark&#8217;s excellent iBook</a>. <a href="#fnref:1" title="return to article" class="reversefootnote">&#160;&#8617;</a></p>
</li>

</ol>
</div>