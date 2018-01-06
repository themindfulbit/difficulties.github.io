---
layout: post
title: 'Writing and Publishing with Working Copy'
author: [Erik Hess]
categories: [technology]
tags: [writing, meta, ios]
banner: large-lathe.jpg
caption: "Illustrated Catalogue and General Description of Improved Machine Tools for Working Metal [Sellers, William & Co., 1899](https://flic.kr/p/oxe2XT)"
---

As you may have heard, [Panic](http://panic.com) is [shelving](https://panic.com/blog/the-future-of-transmit-ios/) Transmit for iOS. While they’re continuing work on their excellent IDE [Coda](https://panic.com/coda-ios/) (which offers a superset of Transmit’s functionality) it’s hard not to mourn the loss of yet another professional application on iOS. While Transmit isn't immediately leaving the app store, announcements like this offer an opportunity for its users to reevaluate their workflows. In case it's useful, here's a brief look at how I write and publish from iOS.

This site uses Jekyll as an engine, and is hosted via Github Pages. Doing so allows me to kill two birds with one stone. First, Github Pages offers a free, reliable hosting service for one of the most appealing static blog engines out there. Second, it ensures my site is version-controlled, so when I mess something up (it happens _a lot_) I can undo things quickly and easily. 

[Working Copy](https://itunes.apple.com/us/app/working-copy/id896694807?mt=8) is an iOS Git client that doubles as a pretty nice text editor. If you use Git to manage your site repository (and if not, what _do_ you use?) Working Copy may offer the functionality you're looking for. Over the past few years this versatile app has taken over nearly all of my formerly-complicated iOS writing workflow.

{% include image.html class="right" title="Attack of the Clones" file="working-copy-cloning.jpg" %}

You begin by cloning your repository, which is quite easy if you've already signed in with your Github or BitBucket account. Once you've done that, you'll see a standard folders-and-files view of your repository. Tapping on an individual file will let you view and edit that file's content, see what's changed since the last commit, and see file status and recent commits. You can create new text files or import them from other apps through the iOS file interface.

My posts start in a `_drafts` folder, where they stay invisible to Github Pages but will show up on my dev server which is hosted on Digital Ocean. This isn’t strictly necessary unless you like to preview your posts before they go live. 

{% include image.html class="right" title="Disable Spellcheck for Markdown" file="disable-spellcheck.jpg" %}

If you do decide to use Working Copy as your text editor, one thing I'll advise _immediately_ is to turn off spell checking in the editor menu. If not, you'll get smart quotes and hyphens where you don't want them. For a static site like Jekyll this can be frustrating and/or a disaster, depending on where things get replaced.

{% include image.html class="" title="You can save to your repository right from Safari." file="safari-share.jpg" %}

My header images usually come from Flickr Commons, which has a nearly endless supply of interesting, royalty-free images. Using the share sheet, you can take an image and send it directly to Working Copy, naming it whatever you like. If you’ve got an image saved locally, say you’ve made some edits in Pixelmator, you can do the same thing from there. Pixelmator can also open existing files from Working Copy then overwrite them with the changes you've made.

Working Copy can even pull in files or photos directly, although unlike the share sheet interface it doesn’t give you a chance to rename them first. If you’re importing directly from the photo library, this can cause you to do a little searching for the new file, which gets named `asset.jpg`. Thankfully the new file hasn’t been committed yet, so it should have a green dot to highlight it.