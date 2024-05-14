---
title: 'How I will write my dissertation'
author: 'Teddy Svoronos'
layout: post
categories:
    - Productivity
    - Research
tags:
    - Productivity
    - Research
    - latex
    - markdown
---
In the spirit of getting my procrastinating done during the holidays (that's how procrastinating works, right?), I thought I'd share how I choose to write complex papers. For my purposes, "complex" means any paper that involves some combination of:

  * citations linked to some bibliography manager;
  * equations;
  * internal links (a.k.a. "[cross references](https://support.office.com/en-us/article/Create-or-update-a-cross-reference-aa35c606-34e8-4c64-b6eb-c6321d190645?ui=en-US&rs=en-US&ad=US)").

For simpler papers, I really do like [Pages](https://www.apple.com/mac/pages/). It makes formatting relatively easy, it has (basic) [EndNote and MathType support](http://support.apple.com/kb/PH15342), and it looks lovely on high resolution displays. More recently, I've become smitten with Apple's new [Handoff](http://support.apple.com/en-us/HT6337) feature that works with iOS 8 and OSX Yosemite devices. Being able to work on a paper at my desk, then pick up where I left off on my iPad as I move to the couch, then switch to my iPhone so I can stretch my legs, is pretty neat. Maybe this will get old someday, but for now it's the bee's knees.

Then there are the problems. In addition to the inability of Pages to satisfy my need for numbered equations, Apple is developing a bit of a reputation for poor backward-compatibility. I am terrified by the prospect of trying to open my dissertation in a few years and getting an alert like this (source: [Google+](https://plus.google.com/u/0/+StefanUrbanek/posts/LKkGeEoPUzA)):

![](/assets/img/2014-12-keynote.png){: .mx-auto.d-block :}

This is totally unacceptable, and I hope Apple understands what a massive detterent this is.

The opposite end of the usability vs. flexibility spectrum, there's [LaTeX](http://latex-project.org/). LaTeX combines the longevity of [plain text](http://txtglory.com/) with a robust [bibliography management system](https://www.economics.utoronto.ca/osborne/latex/BIBTEX.HTM), not to mention the fact that LaTeX was conceived for the purpose of printing mathematical formulas. But, as the above links may suggest, LaTeX tools won't be winning any awards for UI design.

Enter [multimarkdown](http://fletcherpenney.net/). Developed by Fletcher Penny, MMD allows me to use one of the [hundreds](http://brettterpstra.com/ios-text-editors/) of markdown[^1] text editors for iOS using a syntax that can be exported as LaTeX. This export process does take some time to set up (see [here](http://fletcherpenney.net/multimarkdown/use/) for details), but once it's read I simply have to prepend this metadata to the beginning of a file to make it export-ready:
    
    
    Title: Title of my document
    Author: Teddy Svoronos
    latex input: /path/to/header/mmd-teddy-header
    latex footer: /path/to/footer/mmd-teddy-footer
    Base header level: 2
    Bibtex: /path/to/bibtex/file/bibfull
    Biblio Style:plain
    
I may get into the details of this setup in a later post; let me know if there's any interest.
    
My editor of choice is Byword (which was recently [updated to support Handoff](http://www.macstories.net/linked/byword-updated-with-handoff-document-providers-on-ios-8/)), though I use Fletcher's own [MultiMarkdown Composer](http://multimarkdown.com/) when I need to get in the weeds of internal links, table creation, and using the app's native table of contents viewer. 
    
The only potential rub in this setup is if my advisors want to use Word track changes to provide comments. In this case, I'll have to export my file as rich text and do some manual futzing to make it presentable. Not great, but those occasional costs are outweighed by the benefits outlined above. 
    
Boy, I'd better get writing. 
    
[^1]: For background on markdown, see [Gruber's original specification](http://daringfireball.net/projects/markdown/). For an introduction to the syntax for non-coders and why you should use it, I recommend [David Spark's excellent iBook](http://macsparky.com/markdown/).   
    
    
    
