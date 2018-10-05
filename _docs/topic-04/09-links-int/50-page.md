---
title: From One Page to Another
module: topic-04
permalink: /topic-04/page-to-page/
---

<div class="divider-heading"></div>

Relative URLs help with building a site locally before pushing it to the web. This way you can develop on your local machine, and still have links to pages be valid. But how do we navigate to a different directory using a relative URL?

Consider this example. We have a three-page site, with an **index.html** in the root directory, and two pages, **about.html** and **contact.html** in the child-directory **/pages**.


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── index.html
└── <i class="far fa-folder-open"></i> pages/
    ├── <i class="fab fa-html5"></i> about.html
    └── <i class="fab fa-html5"></i> contact.html
</pre>


I have a menu at the top of each page that needs to link to each of these pages despite what page the visitor is currently on. So how do I do this?


## Same-Level
<i class="fas fa-long-arrow-alt-right" style="color: #DF382C"></i> <span style="font-weight: bold; letter-spacing: 2px;">From About to Contact: `<a href="./contact.html">Contact Me</a>`</span>

A single `./` states that we need to stay in the current level of our directory. If two pages are on the same level of a directory, the link would simply be `<a href="./page-name.html">`.


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── index.html
└── <i class="far fa-folder-open"></i> pages/
    ├── <i class="fab fa-html5"></i> about.html<img class="fas bounce" src="../img/dots-corner-open-arrow.png" style="width: 2em; margin: 0 0 0 1.2em;" />
    └── <i class="fab fa-html5"></i> contact.html<img class="fas bounce" src="../img/dots-corner-close-arrow.png" style="width: 2em; margin: 0;" />
</pre>


## Go Deeper (Forwards)
<i class="fas fa-long-arrow-alt-right" style="color: #DF382C"></i> <span style="font-weight: bold; letter-spacing: 2px;">From Index to About: `<a href="./pages/about.html">To About</a>`</span>

This process may look familar, as you've been doing it with screenshots located in an **images** directory. When “going deeper” into our directory, we must add any additional sub-directories (folders) to our URL path, like `<a href="./folder-name/page-name.html"`


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── <i class="far fa-folder-open"></i> images/
│   ├── <i class="far fa-image"></i> photo-1.jpg
│   └── <i class="far fa-image"></i> photo-2.jpg
├── index.html<img class="fas bounce" src="../img/dots-horizontal.png" style="width: 2em; margin: 0 0 0 1em;" /><img class="fas bounce" src="../img/dots-horizontal.png" style="width: 2em; margin: 0 0;" /><img class="fas bounce" src="../img/dots-corner-open.png" style="width: 2em; margin: 0;" />
└── <i class="far fa-folder-open"></i> pages/<img class="fas bounce" src="../img/dots-vertical.png" style="width: 2em; margin: 0 0 0 7.35em;" />
    ├── <i class="fab fa-html5"></i> about.html<img class="fas bounce" src="../img/dots-corner-close-arrow.png" style="width: 2em; margin: 0 0 0 1.2em;" />
    └── <i class="fab fa-html5"></i> contact.html
</pre>


## Go Shallower (Backwards)
<i class="fas fa-long-arrow-alt-right" style="color: #DF382C"></i> <span style="font-weight: bold; letter-spacing: 2px;">From Contact to Index: `<a href="../">Back to Home</a>`</span>

Not only can we go deeper, but we can also take steps backwards, going higher up in our directory. A link for this direction would look something like `<a href"../page-name.html">`.

If a single `./` states that we need to remain in the current level of our directory heirarchy, two `../` is effectively saying “to find this file, begin here and then step back a directory.”


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── <i class="far fa-folder-open"></i> images/
│   ├── <i class="far fa-image"></i> photo-1.jpg
│   └── <i class="far fa-image"></i> photo-2.jpg
├── index.html<img class="fas bounce" src="../img/dots-horizontal-left.png" style="width: 2em; margin: 0 0 0 1em;" /><img class="fas bounce" src="../img/dots-horizontal.png" style="width: 2em; margin: 0 0;" /><img class="fas bounce" src="../img/dots-corner-open.png" style="width: 2em; margin: 0;" />
└── <i class="far fa-folder-open"></i> pages/<img class="fas bounce" src="../img/dots-vertical.png" style="width: 2em; margin: 0 0 0 7.35em;" />
    ├── <i class="fab fa-html5"></i> about.html<img class="fas bounce" src="../img/dots-vertical.png" style="width: 2em; margin: 0 0 0 2.9em;" />
    └── <i class="fab fa-html5"></i> contact.html<img class="fas bounce" src="../img/dots-corner-close.png" style="width: 2em; margin: 0;" />
</pre>


<span class="label label-info">Note</span> You will never have more than two “dots” in a path segment. Further stepping may look something like this: `../../../images/profile.png`
