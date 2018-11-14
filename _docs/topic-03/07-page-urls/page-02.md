---
title: Via the Root Directory
module: topic-03
permalink: /topic-03/via-root/
categories: development
tags: directory, organize, page, root
---

<div class="divider-heading"></div>

<p style="font-size: 1.2em; font-weight: bold; letter-spacing: 2px; margin: 3rem 0;">
  <i class="fas fa-long-arrow-alt-right" style="color: #DF382C"></i>
  <span style="font-family: monospace;">https://www.baseurl.com/about.html</span>
</p>


One way to avoid longer URLs is to place the page in the root of the site (in our case, **web-dev-hw/**). No additional pathing is needed, as the page are not in any other directories.

This is not to say that we could not have additional pages that we explicitly address. For example we could have additional HTML pages at the same directory level, such as an `contact.html`.

This method is fine for sites will few pages. But for sites with many, using child directories is preferable, as it helps with site organization.


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── about.html <i class="fas fa-long-arrow-alt-left bounce-x"></i>
├── <i class="far fa-folder-open"></i> css/
│   └── <i class="fab fa-css3-alt"></i> style.css
├── <i class="far fa-folder-open"></i> images/
│   ├── <i class="far fa-image"></i> photo-1.jpg
│   └── <i class="far fa-image"></i> photo-2.jpg
└── index.html
</pre>
