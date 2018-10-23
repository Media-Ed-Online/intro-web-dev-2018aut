---
title: 3. Other Attributes
module: topic-05
permalink: /topic-05/audio-other-att/
categories: html
tags: attribute, audio
---

<div class="divider-heading"></div>

There are several other attributes that can be applied to the `<audio>` to make it behave as intended.


<div id="code-heading">Element Breakdown <i class="fas fa-battery-three-full"></i></div>
<pre id="breakdown-block">
<audio src="#" <span class="pulsate">preload controls</span>></audio>
</pre>


<div class="divider-pg"></div>


## Multiple-Source


<div id="code-heading">Element Breakdown <i class="fas fa-battery-full"></i></div>
<pre id="breakdown-block">
&lt;audio <span class="pulsate">preload controls</span>&gt;
   &lt;source src="#" type=""&gt;
   &lt;source src="#" type=""&gt;
&lt;/audio&gt;
</pre>


<div class="divider-pg"></div>


### preload
As with the `<video>` element, this attribute tells the browser what to do when the page loads. It can have one of three values:

- `none` - The browser should not load the audio until the user presses play.
- `auto` (default) - The browser should download the audio when the page loads.
- `metadata` - The browser should just collect information such as the size, first frame, track list, and duration.


### controls
When the `controls` attribute is supplied it indicates the browser should supply its own controls for playback. If you do not use this attribute, no controls will be shown by default.


### loop
This tells the browser whether or not to loop the audio.


### autoplay
When used, this attribute specifies that the file should play automatically.

<span class="label label-info">Note</span> Remember, this is considered poor-practice, and in most cases, it is better to let the user choose whether to start the audio or not.
