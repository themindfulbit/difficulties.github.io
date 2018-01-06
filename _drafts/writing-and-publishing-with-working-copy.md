---
layout: post
title: 'Writing and Publishing with Working Copy'
author: [Erik Hess]
categories: [technology]
tags: [writing, meta, ios]
banner: large-lathe.jpg
caption: "Illustrated Catalogue and General Description of Improved Machine Tools for Working Metal [Sellers, William & Co., 1899](https://flic.kr/p/oxe2XT)"
---

As you [may](https://daringfireball.net/linked/2018/01/05/transmit-ios) [have](https://sixcolors.com/link/2018/01/panic-ceases-development-of-transmit-for-ios/) [heard](http://leancrew.com/all-this/2018/01/dont-panic/), [Panic](http://panic.com) is [shelving](https://panic.com/blog/the-future-of-transmit-ios/) Transmit for iOS. While they’re continuing work on their excellent IDE [Coda](https://panic.com/coda-ios/) (which offers a superset of Transmit’s functionality) it’s hard not to mourn the loss of yet another professional application on iOS. While Transmit isn't immediately leaving the app store, announcements like this offer an opportunity for its users to reevaluate their workflows. In case it's useful, here's a brief look at how I write and publish from iOS.

This site uses Jekyll as an engine, hosted via Github Pages. Doing so kills two birds with one stone. First, Github Pages offers a free, reliable hosting service for an appealing static blog engine. Second, it ensures my site is version-controlled, so when I mess something up (it happens _a lot_) I can undo things quickly and easily. 

[Working Copy](https://itunes.apple.com/us/app/working-copy/id896694807?mt=8) is an iOS Git client that doubles as a pretty nice text editor. If you use Git to manage your site repository (and if not, what _do_ you use?) Working Copy may offer the functionality you're looking for. Over the past few years this versatile app has taken over nearly all of my formerly-complicated iOS writing workflow.

{% include image.html class="right" title="Attack of the Clones" file="working-copy-cloning.jpg" %}

You begin by cloning your site's repository, which is quite easy if you've already signed in with your Github or BitBucket account. Once that's finished, you'll see a standard folders-and-files view on the left and details on the right. Tapping on an individual file will let you view and edit that file's content, see what's changed since the last commit, and see file status and recent commits. You can create new text files or import them from other apps through the iOS file interface. Once you're ready, you can commit and push any changes back to Github. If they're doing your site's hosting that will initiate a rebuild and the changes should be live a few seconds later.

{% include image.html class="right" title="Disable Spellcheck for Markdown" file="disable-spellcheck.jpg" %}

If you _do_ decide to use Working Copy as your text editor, one thing I'll advise _immediately_ is to turn off spell checking in the editor menu. If not, you'll get smart quotes and hyphens where you don't want them. For a static engine like Jekyll this can be frustrating and/or a disaster, depending on where things get replaced.

My header images usually come from Flickr Commons, which has a nearly endless supply of interesting, royalty-free images as long as your tastes run towards the quirky-historical. Using the Safari share sheet, you can take an image and send it directly to Working Copy, naming it whatever you like. If you’ve got an image saved locally -- say you’ve made some edits in Pixelmator -- you can do the same thing from there. Pixelmator can also open existing files from within Working Copy then overwrite them with the changes you've made.

{% include image.html class="right" title="You can save to your repository right from Safari." file="safari-share.jpg" %}

Working Copy can even pull in files or photos directly, although it doesn’t give you a chance to rename them first. If you’re importing directly from the photo library, you'll have to hunt down the new file, which gets auto-named `asset.jpg`. Thankfully the new file hasn’t been committed yet, so it should have a green dot to highlight it.

Working Copy doesn't yet have Workflow integration. It isn't going to let you quickly throw a random file up on Amazon S3 or your web host. But if you're modifying or adding an asset to your Git-based project, it'll work great.

[Federico Viticci](https://mobile.twitter.com/viticci) has extensive coverage of Working Copy at [MacStories](http://macstories.net). He manages the entire site from an iPad and it's a core part of his workflow. Check out these articles for more:

* [A Computer for Everything: One Year of iPad Pro](https://www.macstories.net/stories/one-year-of-ipad-pro/7/#github-and-markdown-editing)
* [My Must-Have iOS Apps & Web Services, 2016 Edition](https://www.macstories.net/roundups/my-must-have-ios-apps-web-services-2016-edition/)
* [My Must-Have iOS Apps, 2017 Edition](https://www.macstories.net/stories/my-must-have-ios-apps-2017-edition/)