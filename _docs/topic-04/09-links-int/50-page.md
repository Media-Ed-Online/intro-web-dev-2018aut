---
title: From One Page to Another
module: topic-04
permalink: /topic-04/page-to-page/
---

<div class="divider-heading"></div>

Relative URLs help with building a site locally before pushing it to the web. This way you can develop on your local machine, and still have links to pages be valid. But how do we navigate to a different directory using a relative URL?

Consider this 3-page site, which has an “**index.html**,” an “**about.html**,” and a “**contact.html**,” all of which _link_ (or connect) to each other:

<img src="../img/page-map.gif" alt="simple site page of three pages" style="width: 450px;" />

The directory of this site has the **index.html** in the root directory, and the other pages in the child-directory **/pages**:


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── index.html
└── <i class="far fa-folder-open"></i> pages/
    ├── <i class="fab fa-html5"></i> about.html
    └── <i class="fab fa-html5"></i> contact.html
</pre>


I have a menu at the top of each page that needs to link to each of these pages despite what page the visitor is currently on. So how do I do this?


<div class="divider-pg"></div>


<h2 id="deeper-level-linking">Go Deeper (Forwards)</h2>
<p style="font-size: 1em; font-weight: bold; letter-spacing: 2px; margin: 3rem 0;">
  <i class="fas fa-long-arrow-alt-right" style="color: #DF382C"></i>
  <span style="font-family: monospace;">From Index to About: <code>&lt;a href="./pages/about.html"&gt;About Me&lt;/a&gt;</code></span>
</p>


<img src="../img/page-go-deeper.gif" alt="index linking to about" style="width: 450px;" />


This process may look familar, as you've been doing it with screenshots located in an **images** directory. When “going deeper” into our directory, we must add any additional sub-directories (folders) to our URL path, like `<a href="./folder-name/page-name.html"`


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── index.html<img class="fas bounce" src="../img/dots-horizontal.png" style="width: 2em; margin: 0 0 0 1em;" /><img class="fas bounce" src="../img/dots-horizontal.png" style="width: 2em; margin: 0 0;" /><img class="fas bounce" src="../img/dots-corner-open.png" style="width: 2em; margin: 0;" />
└── <i class="far fa-folder-open"></i> pages/<img class="fas bounce" src="../img/dots-vertical.png" style="width: 2em; margin: 0 0 0 7.35em;" />
    ├── <i class="fab fa-html5"></i> about.html<img class="fas bounce" src="../img/dots-corner-close-arrow.png" style="width: 2em; margin: 0 0 0 1.2em;" />
    └── <i class="fab fa-html5"></i> contact.html
</pre>


<div class="divider-pg"></div>


<h2 id="same-level-linking">Same-Level</h2>
<p style="font-size: 1em; font-weight: bold; letter-spacing: 2px; margin: 3rem 0;">
  <i class="fas fa-long-arrow-alt-right" style="color: #DF382C"></i>
  <span style="font-family: monospace;">From About to Contact: <code>&lt;a href="./contact.html"&gt;Contact Me&lt;/a&gt;</code></span>
</p>


<img src="../img/page-same-level.gif" alt="about linking to contact" style="width: 450px;" />


A single `./` states that we need to stay in the current level of our directory. If two pages are on the same level of a directory, the link would simply be `<a href="./page-name.html">`.


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── index.html
└── <i class="far fa-folder-open"></i> pages/
    ├── <i class="fab fa-html5"></i> about.html<img class="fas bounce" src="../img/dots-corner-open-arrow.png" style="width: 2em; margin: 0 0 0 1.2em;" />
    └── <i class="fab fa-html5"></i> contact.html<img class="fas bounce" src="../img/dots-corner-close-arrow.png" style="width: 2em; margin: 0;" />
</pre>


<div class="divider-pg"></div>


<h2 id="shallower-level-linking">Go Shallower (Backwards)</h2>
<p style="font-size: 1em; font-weight: bold; letter-spacing: 2px; margin: 3rem 0;">
  <i class="fas fa-long-arrow-alt-right" style="color: #DF382C"></i>
  <span style="font-family: monospace;">From Contact to Index: <code>&lt;a href="../"&gt;Back to Home&lt;/a&gt;</code></span>
</p>


<img src="../img/page-go-backwards.gif" alt="contact linking to index" style="width: 450px;" />


Not only can we go deeper, but we can also take steps backwards, going higher up in our directory. A link for this direction would look something like `<a href"../page-name.html">`.

If a single `./` states that we need to remain in the current level of our directory heirarchy, two `../` is effectively saying “to find this file, begin here and then step back a directory.”


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── index.html<img class="fas bounce" src="../img/dots-horizontal-left.png" style="width: 2em; margin: 0 0 0 1em;" /><img class="fas bounce" src="../img/dots-horizontal.png" style="width: 2em; margin: 0 0;" /><img class="fas bounce" src="../img/dots-corner-open.png" style="width: 2em; margin: 0;" />
└── <i class="far fa-folder-open"></i> pages/<img class="fas bounce" src="../img/dots-vertical.png" style="width: 2em; margin: 0 0 0 7.35em;" />
    ├── <i class="fab fa-html5"></i> about.html<img class="fas bounce" src="../img/dots-vertical.png" style="width: 2em; margin: 0 0 0 2.95em;" />
    └── <i class="fab fa-html5"></i> contact.html<img class="fas bounce" src="../img/dots-corner-close.png" style="width: 2em; margin: 0;" />
</pre>


<span class="label label-info">Note</span> You will never have more than two “dots” in a path segment. Further stepping may look something like this: `../../../images/profile.png`
