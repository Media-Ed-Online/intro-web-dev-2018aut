---
title: Styling Divs
module: topic-06
permalink: /topic-06/basic-styling-divs/
categories: html
tags: div, style
---

<div class="divider-heading"></div>

Divs are _block-level_ elements, meaning they fill the page edge-to-edge. If this isn't necessarily what we want, we can easily force changes to the div itself, and how it relates to the elements inside.

## Changing Width
You can easily change the width of a div from 100% using the **width property**. Width values can be in percentages (changing) or pixels (unchanging). For example:
- to be half of the page _at any size_ of the brower window, set to `width: 50%;`
- to be 300 pixels wide _no matter the size_ of the browser window, set to `width: 300px;`

<div id="code-heading">HTML</div>
```html
.a-class {
  width: ;
}
```

## Centering on the Page
Have a div less than full-page and want it placed in the middle? Add the **margin property**, set to `auto` (`margin: auto`).

<div id="code-heading">HTML</div>
```html
.a-class {
  margin: auto;
}
```


## Cushioning From the Edge
Text inside of a div will set right aside its edges. To override this and give the text some “cushion” for easier-reading, add the **padding property**. Pixel values are best-suited here.

<div id="code-heading">HTML</div>
```html
.a-class {
  padding: ;
}
```


<div class="divider-pg"></div>


### Example
See how you can style divs into interesting content blocks using **width**, **margin: auto**, and **padding**!


<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="YRKNBp" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="Basic HTML Div Styling" class="codepen"></p>
</div>
