---
title: The Style Element
module: topic-06
permalink: /topic-06/basic-style-element/
categories: html
tags: elements, style
---

<div class="divider-heading"></div>

To continue our review, let's revisit the **style element**, located in the `<head>` of an HTML document.


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
  The style element allows for simple style definitions to be established in a single HTML page without having to link to external documents.</p>
</div>


We will get into using the method later on, but you should consider the facts of styling this way:

<ul style="list-style-type: none">
  <li class="icon-pro"> Benefit: All styling for a page be done within that same page.</li>
  <li class="icon-con"> Problem: You will have to manually add or copy any styling you want to each individual page of the site.</li>
</ul>

<span class="label label-danger">Important</span> On the following pages you will be given styling options to explore. Just remember that any code you use or copy **has to be added inside the page's** `<head>` **element**.

<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Way-Cool Awesome Site</title>
    <style>
      /* “Decorative” styling of page contents... */
    </style>
  </head>

  <body>
    <!-- Page contents that will get styled... -->
  </body>
</html>
```


<div class="divider-pg"></div>


## Adding Style to Page Contents



### Selecting Elements (“Apply to _all elements_ on my page.”)
**Selecting elements** effects large portions of the page, good for backgrounds, image styling, and text, but not for specific instances.

<div id="code-heading">HTML</div>
```html
<style>
  body {
    /* Will affect the ENTIRE body of the page. */
  }
  h1 {
    /* Will affect EVERY heading 1 on the page. */
  }
  img {
    /* Will affect ALL images on the page. */
  }
</style>
```


### Selecting Classes (“Apply to _any element_ I say to.”)
Creating and **selecting classes** is good for styling distinct portions of the page, to better differentiate them from each other.

<div id="code-heading">HTML</div>
```html
<style>
  .a-class {
    /* Will affect ANY element with this class. */
  }
  .content-block {
    /* Will affect ANY element with this class. */
  }
  .page-title {
    /* Will affect ANY element with this class. */
  }
</style>
```


<div class="divider-pg"></div>


### Example
We can combine these selections to style elements, both overall and individually.

For example, we can say we want _all_ tables in our site to have black borders, but the _first_ table will have orange text, and the _second_ table will have green text:
- element selector: `div` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(“Do _____ to ALL divs on the page.”)
- class selector: `.box-one` &nbsp;(“Do _____ to ANY element with class 'box-one.'”)
- class selector: `.box-two` &nbsp;(“Do _____ to ANY element with class 'box-two.'”)


<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="MzWYOM" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="Basic Style Selectors in HTML" class="codepen"></p>
</div>
