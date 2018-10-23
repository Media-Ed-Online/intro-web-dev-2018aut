---
title: 3. Poster
module: topic-05
permalink: /topic-05/video-poster/
categories: html
tags: attribute, image, video
---

<div class="divider-heading"></div>

The **poster attribute** (`poster="#"`) should always be supplied with the `<video>` element. This attribute takes a URL as its value, which should point to an image that is displayed in place of the video until the visitor elects play the video.


## Single-Source


<div id="code-heading">Element Breakdown <i class="fas fa-battery-half"></i></div>
<pre id="breakdown-block">
<video src="#" <span class="pulsate">poster="#"</span> width="" height="" preload controls></video>
</pre>


<div class="divider-pg"></div>


## Multiple-Source


<div id="code-heading">Element Breakdown <i class="fas fa-battery-half"></i></div>
<pre id="breakdown-block">
&lt;video <span class="pulsate">poster="#"</span> width="" height="" preload controls&gt;
   &lt;source src="#" type=""&gt;
   &lt;source src="#" type=""&gt;
&lt;/video&gt;
</pre>


<div class="divider-pg"></div>


<span class="label label-info">Note</span> The image should be the same width/height ratio as the video element.
![Image of matching video and video poster sizes](../img/video-poster-sizing.png)
