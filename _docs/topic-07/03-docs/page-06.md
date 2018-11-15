---
title: 4. Href
module: topic-07
permalink: /topic-07/link-href/
categories: css
tags: attribute, href, link
---

<div class="divider-heading"></div>


<div id="code-heading">Element Breakdown <i class="fas fa-battery-full"></i></div>
<pre id="breakdown-block">
<link rel="stylesheet" type="text/css" <span class="pulsate">href="#"</span> />
</pre>


Provide the _relative_ or _absolute URL_ as the value to the **href attribute** (`href="#"`). This tells the browser where the document is located at.

The process of linking CSS documents is the same as you've been doing for other site files, such as images and videos.


## Internal Style Sheets
Internal files, like your own created CSS document, should be linked via _relative URL_.


<div id="code-heading">HTML</div>
```html
<head>
  <title>My Way-Cool Awesome Site</title>
  <link rel="stylesheet" type="text/css" href="./css/style.css">
</head>
```


<span class="label label-info">Note</span> When linking the same stylesheet within your child pages (i.e. /pages/about.html), you would need to add an additional 'dot' to your file path (`../`) to move up a directory.


## External Style Sheets
Many sites link out to external CSS documents as well, and will be linked via an _absolute URL_.


<div id="code-heading">HTML</div>
```html
<head>
  <title>My Way-Cool Awesome Site</title>
  <link rel="stylesheet" type="text/css" href="https://www.example.com/style.css">
</head>
```
