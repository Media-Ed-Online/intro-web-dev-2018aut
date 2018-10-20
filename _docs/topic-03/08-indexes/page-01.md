---
title: The Index.html
module: topic-03
permalink: /topic-03/index-intro/
categories: development
tags: directory, index, request, url
---

<div class="divider-heading"></div>

Almost every website you encounter has a master file called the **index.** _There can be multiple index files on a site, but at least one index is the homepage of the site._

You are going to create a lot of files labeled `index.html`. Like stated earlier, when a URL is passed to a browser that does not specify a file, the browser automatically requests `index.html` from the host server.


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── <i class="far fa-folder-open"></i> css/
│   └── <i class="fab fa-css3-alt"></i> style.css
├── <i class="far fa-folder-open"></i> images/
│   ├── <i class="far fa-image"></i> photo-1.jpg
│   └── <i class="far fa-image"></i> photo-2.jpg
├── <i class="far fa-folder-open"></i> pages/
│   └── <i class="fab fa-html5"></i> about.html
└── index.html <i class="fas fa-long-arrow-alt-left bounce"></i>
</pre>


<span class="label label-success">Neat-O</span> Essentially, this means something like `http://baseurl.com` and `http://baseurl.com/index.html` are the same! (This is not true for all websites, but for many.)
