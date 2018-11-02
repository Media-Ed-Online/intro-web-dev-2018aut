---
title: Styling Text
module: topic-06
permalink: /topic-06/basic-styling-text/
categories: html
tags: elements, style, text
---

<div class="divider-heading"></div>

At this stage, you should use element selectors to “point” to structural text elements, like `h1`, `p`, or lists. This will style all elements of that type cohesively.


## Coloring Text
Backgrounds are not the only element that can hold a color value. Likewise, you can color text using the **color property**. Again, <a href="https://www.w3schools.com/cssref/css_colors.asp" target="_blank">color names</a> are a great way state color values at this stage.

<div id="code-heading">HTML</div>
```html
* {
  color: ;
}
```


## Centering Text
Additionally, you can align text using **text-align property**. By default, browsers align text to the left of the screen; to center text on the page, simply add "center" to the property.

<div id="code-heading">HTML</div>
```html
* {
  text-align: center;
}
```


<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="PRzKed" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="Basic HTML Text Styling" class="codepen"></p>
</div>

<span class="label label-danger">Important</span> You may remember that you can give an element multiple style properties. In the example above, the headings are both colored and center-aligned. **You must always separate these properties with a semi-colon,** `;`.
