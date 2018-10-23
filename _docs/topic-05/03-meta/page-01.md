---
title: The Meta Element
module: topic-05
permalink: /topic-05/meta-about/
categories: html
tags: elements, meta
---

<div class="divider-heading"></div>

If you remember from a few Topics back, we explored how **meta elements** are placed inside of the `<head>` element, and briefly described what role they perform. Let's dig a little deeper into this concept.


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
  The <code>&lt;meta&gt;</code> element <a href="../../topic-04/head-meta/">describes metadata about an HTML page</a>. This <b>metadata is not displayed to users</b>, but used by browsers and search engines. This may describe  what character encoding the document contains, the published date, author information, descriptions for search engines, keywords, etc.</p>
</div>

The meta element is an “empty element.” As such, no closing tag is necessary. Also, as with form elements, metadata is always passed as a name="value" pair. Typically via the `name=""` and `content=""` attributes.

<span class="label label-danger">Important</span> `<meta>` elements are _always_ placed inside the `<head>` element.



<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Meta data and information about your site, not visible to visitors. -->
  </head>

</html>
```
