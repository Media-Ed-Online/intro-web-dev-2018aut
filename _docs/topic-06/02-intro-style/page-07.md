---
title: Styling Lists
module: topic-06
permalink: /topic-06/basic-styling-lists/
categories: html
tags: display, list, style
---

<div class="divider-heading"></div>

Lists can be styled like most text-based block elements, like headings and paragraphs. You can style the list as a whole (`<ul>`, `<ol>`) and/or the list items inside (`<li>`).


## Adding a Background Color
If you want your lists to stand out from other page contents, you can use the **background-color property** to color behind the list, list items, or both.

<div id="code-heading">HTML</div>
```html
ul {
  background-color: ;
}
li {
  background-color: ;
}
```


## Coloring Text
Just like with other text elements, you can add the **color property** to the list items.

<div id="code-heading">HTML</div>
```html
li {
  color: ;
}
```


## Aligning Horizontally
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
  Lists and list items are <a href="../../topic-05/extra-markup#block-level" target="_blank">block-level elements</a>, meaning each will get a full-page line all to themselves.</p>
</div>


 This can be problematic if you want to do a list of links to your site pages. Without extra styling, they will appear vertically down the page, a design layout that isn't often done. We can change this appearance using the **display property**, set to `inline`.

 <div id="code-heading">HTML</div>
 ```html
 li {
   display: inline;
 }
 ```


 <div class="divider-pg"></div>


### Example
See how you can make a list stand-out by changing its **background color**, text **color**, and item **display**!


<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="aQboNw" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="Basic HTML List Stying" class="codepen"></p>
</div>
