---
title: File- vs Directory-Based URLs
module: topic-03
permalink: /topic-03/file-vs-direct-urls/
tags: directory, page
---

<div class="divider-heading"></div>

There are several ways we can control how our `HTML` where our files are stored, retrieved by browsers, and how they appear in the address bar of a those browsers.

Consider the file “**about.html**,” found on your website:

<img src="../img/about-page.png" alt="simple about page" style="width: 200px;" />

We need to decide where to place this file in our directory, and how the site should locate it. This will also affect its URL.


## Pages In and Outside Directories:
Browsers treat pages differently from other files. They have _expectations_ of what pages will be titled, what languages they'll use, and where they'll live in the site directory.

This means browsers have some default behaviors they do automatically with pages when the site is accessed by a visitor. Where we put pages is a conscious decision on our part, mostly regarding keeping the site files organized and URLs clean. If you'll remember, anything inside of a directory needs that directory added to its **path** in order to be accessed; too few or too many directories can clutter up your site and its pages' URLs.


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── page-01.html
└── <i class="far fa-folder-open"></i> directory-name/
    └── page-02.html
</pre>
