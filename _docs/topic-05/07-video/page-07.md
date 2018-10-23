---
title: 5. Other Attributes
module: topic-05
permalink: /topic-05/video-other-att/
categories: html
tags: attribute, video
---

<div class="divider-heading"></div>

There are several other attributes that can be applied to the `<video>` to make it behave as intended.


<div id="code-heading">Element Breakdown <i class="fas fa-battery-three-full"></i></div>
<pre id="breakdown-block">
<video src="#" poster="#" width="" height="" <span class="pulsate">preload controls</span>></video>
</pre>


<div class="divider-pg"></div>


## Multiple-Source


<div id="code-heading">Element Breakdown <i class="fas fa-battery-full"></i></div>
<pre id="breakdown-block">
&lt;video poster="#" width="" height="" <span class="pulsate">preload controls</span>&gt;
   &lt;source src="#" type=""&gt;
   &lt;source src="#" type=""&gt;
&lt;/video&gt;
</pre>


<div class="divider-pg"></div>


### preload
The `preload` attribute takes one of three values and tells the browser how to load the video file if `autoplay` is not present.

- `preload="none"` - tells the browser to do nothing until told to do so by the user.
- `preload="auto"` - tells the browser to download the media file when the page loads.
- `preload="metadata"` - tells the browser to only collect metadata, such as size and length.


### controls
The `controls` attribute is passed alone and does not require a trailing value. This attribute indicates whether the player should display controls. If you do not use this attribute, no controls will be shown by default.


### loop
The `loop` attribute, when present, tells the browser to loop the file.


### autoplay
Like the `controls` attribute, the `autoplay` attribute is included as a single word or not at all. When present, this attribute tells the browser to start playing the file on load.

<span class="label label-info">Note</span> This is considered poor-practice, and in most cases, it is better to let the user choose whether to start the video or not.
