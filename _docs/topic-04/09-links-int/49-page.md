---
title: Linking Internally in the Site
module: topic-04
permalink: /topic-04/intro-int-links/
---

<div class="divider-heading"></div>

<div class="lightbulb-container">
  <span class="fa-stack fa-1x">
    <i class="far fa-lightbulb fa-stack-2x"></i>
    <i class="fas fa-lightbulb fa-stack-2x lightbulb-blink"></i>
    <i class="far fa-lightbulb fa-stack-2x"></i>
  </span>
</div>
_Remember?_ **Relative URLs** contain no protocols or domain information. This is convenient because they are shorter, but can _only_ reference files in the same path.


<img src="../img/home.svg" alt="Home Icon" style="width: 100px;" />


It also should be noted that in the language of web design, the `index.html` file is referred to as the **home page** once hosted, as it becomes the "entry" to your site. It is also the page most users will return to again and again as your "base of opperations," as it were.

<div id="code-heading">HTML</div>
```html
<a href="./index.html" target="_blank">Back to Home</a>
```
