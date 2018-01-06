—
layout: post
title: ‘An iOS Writing Workflow’
author: [Erik Hess]
categories: [technology]
tags: [writing, meta, ios]
banner: large-lathe.jpg
caption: “Illustrated Catalogue and General Description of Improved Machine Tools for Working Metal [Sellers, William & Co., 1899](https://flic.kr/p/oxe2XT)”
—

As you may have heard, Panic is ending development on Transmit for iOS. While they’re continuing work on their excellent IDE Coda, which offers a superset of Transmit’s functionality, it’s still appropriate to mourn the loss of such a professional, focused application. 

While it’s not immediately leaving the app store, some are understandably reevaluating their iOS-blogging workflows. Even though I haven’t used it much lately, this is probably the right time to briefly walk through mine in case it’s useful.

First let’s talk infrastructure, since that will determine whether anything below this paragraph is applicable in your case. This site is a Jekyll blog hosted via Github Pages. Doing so kills two birds with one stone. First, Github Pages offers a free, reliable hosting service for one of the most appealing static blog engines out there. Second, it ensures my site is version-controlled, so when I mess something up I can undo my changes fairly quickly. 

If you use Git to manage your site repository, then Working Copy may offer the functionality you need to move forward. Over the past couple of years this versatile app has gradually taken over much of my formerly-complicated iOS writing workflow.

Working Copy is an iOS Git client that doubles as a decent text editor. My posts start in a `_drafts` folder, where they stay invisible to Github Pages but will show up on my dev server which is hosted on Digital Ocean. This isn’t strictly necessary unless you like to preview your posts before they go live.

My header images usually come from Flickr Commons, which has a nearly endless supply of interesting, royalty-free images. Using the share sheet, you can take an image and send it directly to Working Copy, naming it whatever you like. If you’ve got an image stored locally, 