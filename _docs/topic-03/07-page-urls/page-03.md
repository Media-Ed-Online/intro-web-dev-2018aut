---
title: Via a Child Directory
module: topic-03
permalink: /topic-03/via-child/
categories: development
tags: directory, organize, page, child
---

<div class="divider-heading"></div>

<p style="font-size: 1.2em; font-weight: bold; letter-spacing: 2px; margin: 3rem 0;">
  <i class="fas fa-long-arrow-alt-right" style="color: #DF382C"></i>
  <span style="font-family: monospace;">https://www.baseurl.com/about/</span>
</p>


If you wished to have a “cleaner” looking URL, you could create an additional child directory labeled `about/` and place a file saved as `index.html` within that directory.

In the next sub-topic, you'll see how an `index.html` is one of those files browsers expect to find. Because of this, if an `index.html` file is in a directory, you usually do not have to include it in the file path; the browser will request it automatically.

<span class="label label-info">Note</span> Notice how we do not add `/index.html` at the end of the URL above; instead the URL simply ends with a directory slash (**/**).


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── <i class="far fa-folder-open"></i> about/ <i class="fas fa-long-arrow-alt-left bounce-x"></i>
│   └── <i class="fab fa-html5"></i> index.html
├── <i class="far fa-folder-open"></i> css/
│   └── <i class="fab fa-css3-alt"></i> style.css
├── <i class="far fa-folder-open"></i> images/
│   ├── <i class="far fa-image"></i> photo-1.jpg
│   └── <i class="far fa-image"></i> photo-2.jpg
└── index.html
</pre>
