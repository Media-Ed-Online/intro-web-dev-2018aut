---
title: Styling Images
module: topic-06
permalink: /topic-06/basic-styling-images/
categories: html
tags: float, image, style
---

<div class="divider-heading"></div>

Images have certain behaviors within a page, including how and where they appear and react with surrounding and nearby elements. To declare images in the `<style>` element, use the element selector `img {}`.

## Sizing Images
You may have images of all different sizes you want to include in your page, but once there, you'd like them all to be the same width for consistency. Instead of adding width values to all your `<img>` tags, you can do it across <u>all</u> images on the page using the **width property**.

<span class="label label-info">Note</span> This means your image tags <u>do not need</u> width values; for example, `<img src="#" alt="" title="" />`

<div id="code-heading">HTML</div>
```html
img {
  width: ;
}
```


## Floating Images
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
  That images are <a href="../../topic-05/extra-markup#inline" target="_blank">inline elements</a> that appear “within” or adjacent to neighboring elements.</p>
</div>


To override where images appear, you can use the **float property** to effectively direct the flow of adjacent elements, either to the left or right.

For example, using `float: left;` will place the image to the left, and elements below will flow around it. The opposite is true of `float: right;`.

<div id="code-heading">HTML</div>
```html
img {
  float: ;
}
```


<div class="divider-pg"></div>


### Example
See how you can manipulate an image's size and placement with **width** and **float**!


<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="bveMWm" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="Basic HTML Image Styling" class="codepen"></p>
</div>
