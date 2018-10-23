---
title: 2. Source
module: topic-05
permalink: /topic-05/video-src/
categories: html
tags: attribute, codec, required, src, video
---

<div class="divider-heading"></div>

The `<video>` element takes a **source attribute** (`src=""`), which accepts a URL (relative or absolute) to a single video file.

It is always recommended you have at least two versions of a video file, and should use the `<source>` element instead, which is described below.


## Single-Source

<div id="code-heading">Element Breakdown <i class="fas fa-battery-quarter"></i></div>
<pre id="breakdown-block">
<video <span class="pulsate">src="#"</span> poster="#" width="" height="" preload controls></video>
</pre>


<div class="divider-pg"></div>


## Multiple-Source
You can use multiple **source elements**, which specifies to the browser the video is available in multiple formats. This is the `<source>` element, and again, it is used _instead_ of the `src=""` attribute of a `<video>` element.

<span class="label label-info">Note</span> Due to a bug on the iPad, you should provide the MP4 video as the first format.

<div id="code-heading">Element Breakdown <i class="fas fa-battery-quarter"></i></div>
<pre id="breakdown-block">
&lt;video poster="#" width="" height="" preload controls&gt;
   <span class="pulsate">&lt;source src="#" type=""&gt;</span>
   <span class="pulsate">&lt;source src="#" type=""&gt;</span>
&lt;/video&gt;
</pre>

### Types
After the source, you'll notice the **type attribute**.

Use the `type=""` attribute to tell the browser what format the video is in. Otherwise, it will download some of the video to see if it can play the file, find that it cannot, and then try the next one until it has exhausted all options or found a valid file format. **This takes time and bandwidth!**

The codec that was used to encode the video is supplied within the type attribute, following the video file type, separated by a semicolon (`;`). Here are the codecs for the more popular video filetypes:
- _MP4_ - `type='video/mp4; codecs="avc1.4D401E, mp4a.40.2"'`
- _WebM_ -`type='video/webm; codecs="vp8.0, vorbis"'`
- _OGV_ - `type='video/ogg; codecs="theora, vorbis"'`
