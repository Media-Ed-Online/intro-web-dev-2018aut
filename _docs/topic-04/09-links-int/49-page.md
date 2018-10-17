---
title: Linking Internally in the Site
module: topic-04
permalink: /topic-04/intro-int-links/
tags: relative, link, url
---

<div class="divider-heading"></div>

<div class="lightbulb">
   <svg viewBox='0 0 64 64'>
     <g>
       <line x1='32' y1='16' x2='32' y2='0' />
       <line x1='41.40' y1='19.05' x2='50.80' y2='6.11' />
       <line x1='47.21' y1='27.05' x2='62.43' y2='22.11' />
       <line x1='47.21' y1='36.94' x2='62.43' y2='41.88' />
       <line x1='16.78' y1='36.94' x2='1.56' y2='41.88' />
       <line x1='16.78' y1='27.05' x2='1.56' y2='22.11' />
       <line x1='22.59' y1='19.05' x2='13.19' y2='6.11' />
     </g>
   </svg>

   <i class="far fa-lightbulb"></i>
   <i class="fas fa-lightbulb blink"></i>
</div>
_Remember?_ **Relative URLs** contain no protocols or domain information. This is convenient because they are shorter, but can _only_ reference files in the same path.


Consider the file “**index.html**,” found on your website:

<img src="../img/home-page.png" alt="simple about page" style="width: 200px;" />


In the language of web design, the `index.html` file is referred to as the **home page** once hosted, as it becomes the "entry" to your site. It is also the page most users will return to again and again as your "base of opperations," as it were.

All important pages in a site will need to link back to the home, and to each other. Creating this site map is part of making the site's **main navigation**.

<div id="code-heading">HTML</div>
```html
<a href="./index.html" target="_blank">Home</a>
```
