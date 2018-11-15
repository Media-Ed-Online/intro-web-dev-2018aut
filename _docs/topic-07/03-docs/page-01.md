---
title: Using CSS Documents
module: topic-07
permalink: /topic-07/css-docs/
categories: development
tags: best-practice, css, directory, file
---

<div class="divider-heading"></div>

<div class="container-row">
  <img src="../img/logo-css3.svg" alt="CSS3 Logo" title="CSS3" style="float: right; width: 125px; margin-top: 0; margin-left: 1em;" />

  <p>CSS documents are separate files dedicated solely to styling.</p>

  <p>Unlike HTML documents which can include bits of styling or scripts if they are minimal enough, CSS documents will only contain styling rules. They do not require the structural elements like HTML documents, but can contain just as many lines of code, if not significantly more.</p>

  <p>A CSS document is given the <code>.css</code> file extension. As with images and media, it is considered best-practice to place your CSS documents in a separate child directory labeled either <b>css</b> or <b>style</b>.</p>
</div>


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── index.html
├── <i class="far fa-folder-open"></i> css/
│   └── <i class="fab fa-css3-alt"></i> style.css <i class="fas fa-long-arrow-alt-left bounce-x"></i>
├── <i class="far fa-folder-open"></i> images/
│   ├── <i class="far fa-image"></i> photo-1.jpg
│   └── <i class="far fa-image"></i> photo-2.jpg
└── <i class="far fa-folder-open"></i> pages/
    ├── <i class="fab fa-html5"></i> about.html
    ├── <i class="fab fa-html5"></i> contact.html
    └── <i class="fab fa-html5"></i> gallery.html
</pre>
