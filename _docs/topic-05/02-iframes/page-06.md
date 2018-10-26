---
title: Websites in the Iframe Element
module: topic-05
permalink: /topic-05/iframe-element-websites/
categories: html
tags: elements, iframe, website
---

<div class="divider-heading"></div>

Some websites allow their pages to be loaded on other sites using iframes.

Let's see how our own site looks in an iframe. You should see the “mobile view,” or a compressed view optimized for smaller portals.


<div id="code-heading">HTML</div>
```html
<iframe src="https://media-ed-online.github.io/intro-web-dev/" width="600px" height="500px"></iframe>
```


<div class="external-embed" style="width: 600px; height: 500px;">
  <iframe src="https://media-ed-online.github.io/intro-web-dev/" width="100%" height="500px"></iframe>
  <p><a href="https://media-ed-online.github.io/intro-web-dev/" target="_blank"><cite>Introduction to Web Design and Development</cite></a></p>
</div>


<br>


<div class="divider-pg"></div>


## How-To:
To embed an external site to your page, simply build the `<iframe>` element, and include the site's absolute URL.

<span class="label label-danger">Important</span> For a variety of reasons, not all sites will work in an iframe. Including a hyperlink to the site below the iframe is a good idea. You can test a site using an <a href="http://www.tinywebgallery.com/blog/advanced-iframe/free-iframe-checker" target="_blank">iframe checker</a>.
