---
title: Optimizing for the Web
module: topic-05
permalink: /topic-05/media-optimizing/
categories: development
tags: best-practice, design, file, image, web
---

<div class="divider-heading"></div>

The process of **optimizing** files compresses or rewrites them to be as efficient as possible for their desired platform. For the web, this means optimizing media for **screens** and screen resolution, in order to keep file sizes as small and accessible as possible.

_On your own, it is easiest to optimize images._ This can be done cheaply and quickly, and doing so will drastically improve the efficiency of your site. For video and audio, it is generally recommended to use a service to do the heavy-lifting for you.


## Images
Generally, images should be **less-than 1,000 KB** in size (under 1 megabyte).

If you remember from your introductory design classes, creating and saving files for print is much different than for web. For example, printers print at _300 ppi_, but screens only need _72 ppi_ for proper resolution. The larger your files, the longer it will take your page to load. And no one likes a slow-loading page.

To optimize images for the web, many image editors have a "Save for Web and Devices" or "Export As" in their save options. There, you can change image formats and sizes to try and get your files of an appropriate size.

<img src="../img/save-imgs-for-web.jpg" alt="Image of 'Save for Web' dialogue in Photoshop CC" title="Save for Web" width="1000" height="auto" style="border: none" />

Here is the <a href="https://images.pexels.com/photos/241828/pexels-photo-241828.jpeg" target="_blank">original dog image</a>, which clocks in at an _enormous_ 23.9 mB, and 5597px by 3148px. Watch how long that loads in another tab.

In contrast the one you see below was optimized for web, sized and cropped to 1000px by 500px. It's much more manageable at 110 kB, and is hardly distinguishable from the original (at least on the web).

<img src="../img/dogs-in-field.jpeg" alt="An image dogs laying in a field while the sun sets" title="Dogs in a Sunlit Field" width="1000px" height="auto" />


<div class="divider-pg"></div>


## Video
_It is recommend you use a service to host videos. We will not discuss optimization in-depth here._

A 10-minute YouTube video is often near **100 MB** in size. Full-length movies can reach up-to **25GB** - this is beyond the capacity of most web hosting companies.

If these files from other sources, you likely will not have access to the original file, and therefore will not be able to correctly re-format or compress it. If you do, however, Certain plugins can be downloaded for video editors like Adobe Premiere so that you can export .webm and other filetypes without a band-aide online conversion, through sites like [CloudConvert](https://cloudconvert.com/).


<div class="divider-pg"></div>


## Audio
_It is recommend you use a service to host audio. We will not discuss optimization in-depth here._

A single MP3 song is **approximately 3-4 MB**.

While this is not particularly large, you will need multiple versions of the song for the site, as well as a higher-quality format. This can add up quickly, and it can be a process to accomplish.

For example, with audio, to export an .ogg file (whether it's a song you own or have recently sourced), you may need to use an online converter like [Convertio](https://convertio.co/mp3-ogg/) or [Zamzar](http://www.zamzar.com/convert/mp3-to-ogg/). Again, this is only a band-aide; ideally, you're providing your own created audio (music, recordings, sound effects, etc) which you can export as an .ogg legally.
