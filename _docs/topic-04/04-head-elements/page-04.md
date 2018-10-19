---
title: Title
module: topic-04
permalink: /topic-04/head-title/
tags: head, html, title
---

<div class="divider-heading"></div>

The **title** tag defines the title of a document. This action:

- defines a title in the browser toolbar.
- provides a title for the page when it is added to favorites.
- displays a title for the page in search-engine results.

You cannot have more than one title element. However, you _must_ have the title element for the document to validate as HTML.

<span class="label label-danger">Important</span> **This is the only required element in the head.**


<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Other meta elements -->
    <title>My Way-Cool Awesome Site</title>

  </head>

</html>
```


<div class="container-row">
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
  <p><span class="remember-text">Remember?</span><br/>
  The <i>title</i> tag aptly contains your site's or page's title, and shows up on the browser's tabs.</p>
</div>
