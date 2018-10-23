---
title: 2. Source
module: topic-05
permalink: /topic-05/audio-src/
categories: html
tags: attribute, audio, codec, required, src
---

<div class="divider-heading"></div>

The `<audio>` element takes a **source attribute** (`src=""`), which accepts a URL (relative or absolute) to a single audio file.

As with video, it is always recommended you have at least two versions of an audio file, and should use the `<source>` element instead.


## Single-Source

<div id="code-heading">Element Breakdown <i class="fas fa-battery-half"></i></div>
<pre id="breakdown-block">
<audio <span class="pulsate">src="#"</span> preload controls></audio>
</pre>


<div class="divider-pg"></div>


## Multiple-Source
You can use multiple **source elements**, which specifies to the browser the audio that is available in multiple formats. This is the `<source >` element, and again, it is used _instead_ of the `src=""` attribute of an `<audio>` element.


<div id="code-heading">Element Breakdown <i class="fas fa-battery-half"></i></div>
<pre id="breakdown-block">
&lt;audio preload controls&gt;
   <span class="pulsate">&lt;source src="#" type=""&gt;</span>
   <span class="pulsate">&lt;source src="#" type=""&gt;</span>
&lt;/audio&gt;
</pre>

### Types
When using more than just `.mp3` you should include multiple versions of the file, with decreasing preference. This allows the browser to then use the file format that it supports.

The `<source>` element is an empty element, and accepts the `src=""` attribute to provide the URL to the browser. Use the `type=""` attribute to include the [MIME type](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types), which allows the browser to instantly know if it can play that file.

Here are the types (and codecs when applicable) for the more popular audio filetypes:
- _MP3_ - `type="audio/mpeg"`
- _WAV_ - `type="audio/wav"`
- _OGG_ -`type="audio/ogg; codecs=vorbis"`
