---
layout: post
title: 'Writing and Posting on iOS with Working Copy'
author: [Erik Hess]
categories: [technology]
tags: [writing, meta, ios]
banner: large-lathe.jpg
caption: "Illustrated Catalogue and General Description of Improved Machine Tools for Working Metal [Sellers, William & Co., 1899](https://flic.kr/p/oxe2XT)"
---

As you may have heard, Panic is ending development on Transmit for iOS. While they’re continuing work on their excellent IDE Coda, which offers a superset of Transmit’s functionality, it’s still appropriate to mourn the loss of such a professional, focused application. 

While it’s not immediately leaving the app store, some are understandably reevaluating their iOS-blogging workflows. Even though I haven’t used it much lately, this is probably the right time to briefly walk through mine in case it’s useful.

First let’s talk infrastructure, since that will determine whether anything below this paragraph is applicable in your case. This site is a Jekyll blog hosted via Github Pages. Doing so kills two birds with one stone. First, Github Pages offers a free, reliable hosting service for one of the most appealing static blog engines out there. Second, it ensures my site is version-controlled, so when I mess something up I can undo my changes fairly quickly. 

If you use Git to manage your site repository, then Working Copy may offer the functionality you need to move forward. Over the past couple of years this versatile app has gradually taken over much of my formerly-complicated iOS writing workflow.

Working Copy is an iOS Git client that doubles as a pretty nice text editor. My posts start in a `_drafts` folder, where they stay invisible to Github Pages but will show up on my dev server which is hosted on Digital Ocean. This isn’t strictly necessary unless you like to preview your posts before they go live. 

{% include image.html class="right" title="Disable Spellcheck for Markdown" file="disable-spellcheck.jpg" %}

If you are going to use Working Copy as your text editor, one think I'll advise _immediately_ is to turn off spell checking in the editor menu. If not, you'll get smart quotes and hyphens where you don't want them. For a static site like Jekyll this can be frustrating and/or a disaster, depending on where things get replaced.

My header images usually come from Flickr Commons, which has a nearly endless supply of interesting, royalty-free images. Using the share sheet, you can take an image and send it directly to Working Copy, naming it whatever you like.

{% include image.html class="" title="You can save to your repository right from Safari." file="safari-share.jpg" %}

If you’ve got an image saved locally, say you’ve made some edits in Pixelmator, you can do the same thing from there.

{% include image.html class="" title="Pixelmator is great." file="pixelmator-share.jpg" %}

It can even pull in files or photos directly, although unlike the share sheet interface it doesn’t give you a chance to rename them first. If you’re importing directly from the photo library, this can cause you to do a little searching for the new file, which gets named `asset.jpg`. Thankfully the new file hasn’t been committed yet, so it should have a green dot to highlight it.