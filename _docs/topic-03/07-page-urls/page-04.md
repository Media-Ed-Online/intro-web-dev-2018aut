---
title: Via Referenced Files
module: topic-03
permalink: /topic-03/via-refs/
categories: development
tags: directory, organize, page, child
---

<div class="divider-heading"></div>

<p style="font-size: 1.2em; font-weight: bold; letter-spacing: 2px; margin: 3rem 0;">
  <i class="fas fa-long-arrow-alt-right" style="color: #DF382C"></i>
  <span style="font-family: monospace;">https://www.baseurl.com/pages/about.html</span>
</p>


For our class, we will create some of our **assignment/** and **project/** directories with a sub-directory called **pages/**. It will contain all of our additional `.html` pages, not <u>any</u> of which will be called `index.html`.

This is good for those of us learning directory structure for the first time, but because these sub-directories will not have an `index.html` file to request, `https://www.baseurl.com/pages/` will likely return a 404 error.


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── index.html
├── <i class="far fa-folder-open"></i> css/
│   └── <i class="fab fa-css3-alt"></i> style.css
├── <i class="far fa-folder-open"></i> images/
│   ├── <i class="far fa-image"></i> photo-1.jpg
│   └── <i class="far fa-image"></i> photo-2.jpg
└── <i class="far fa-folder-open"></i> pages/
    ├── <i class="fab fa-html5"></i> about.html <i class="fas fa-long-arrow-alt-left bounce-x"></i>
    ├── <i class="fab fa-html5"></i> contact.html
    └── <i class="fab fa-html5"></i> gallery.html
</pre>


<span class="label label-success">Neat-O</span> This site has over 100 child and grandchild directories to keep its many pages organized!
