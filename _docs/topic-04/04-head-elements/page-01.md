---
title: "Review: The Head"
module: topic-04
permalink: /topic-04/head-elements/
categories: html
tags: elements, head
---

<div class="divider-heading"></div>

There are a number of elements which we can consider as required in the **head element**, and others that you are _encouraged_ to include. These elements tell the browser and processor information about the HTML document, such as the title, author, and publication date.


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
  The <code>&lt;head&gt;</code> element is a container for processing information and document metadata. The <code>&lt;head&gt;</code> contains high-level information about the site, and always comes first within the root element. In this sense, we can consider the <code>&lt;head&gt;</code> to contain the thoughts of the page.</p>
</div>


<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Meta data and information about your site, not visible to visitors. -->
  </head>

</html>
```


The following pages provide you a proper order of placement of elements within the `<head>`; however, there is no strict documentation on this order.
