---
title: Media on the Web
module: topic-05
permalink: /topic-05/media-about/
categories: development
tags: best-practice, directory, file, media, organize
---

<div class="divider-heading"></div>

Nearly every page we visit has some form of embedded media.

[HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) introduced new features, specifications, and elements. One of the stated goals for the W3 Consortium with these new specs was to address multimedia in order to “make video and audio first-class citizens in the Open Web.”

From this work came new elements, like `<video>`, `<audio>`, and `<picture>` elements. As their names imply these elements are intended to provide multimedia functionality to webpages.

As with all stages in web design, it is important to keep a well-organized media directory. And as HTML5 is still in development and being accepted by browsers, we need to provide text or fallback files should the intended media files or elements not be accessible.


## Directory Structure

As you've been doing with image files, you are encouraged to store multimedia files in a separate sub-directory so as to keep the directory structure of your site clean.

The following demonstrates a possible directory structure:


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── index.html
├── <i class="far fa-folder-open"></i> images/
│   ├── <i class="far fa-image"></i> photo-1.jpg
│   │   <i class="far fa-image"></i> photo-2.jpg
│   └── <i class="far fa-image"></i> movie-poster.png
└── <i class="far fa-folder-open"></i> media/
    ├── <i class="fas fa-music"></i> song.mp3
    ├── <i class="fas fa-music"></i> song.ogg
    ├── <i class="fas fa-video"></i> movie.mp4
    └── <i class="fas fa-video"></i> movie.webm
</pre>


<span class="label label-info">Note</span> GitHub has a repo limit of **20 megabytes**, which is pretty small when thinking about website media. The next few pages list some options for finding smaller files to use.
