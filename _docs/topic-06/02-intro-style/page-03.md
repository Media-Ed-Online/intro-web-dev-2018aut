---
title: Styling Backgrounds
module: topic-06
permalink: /topic-06/basic-styling-backgrounds/
categories: html
tags: background, color, image, style
---

<div class="divider-heading"></div>

We will get more into styling backgrounds next topic with CSS, but for now, you can do basic styling using various **background** properties.

Many structural elements can have background property values. If you have a busy page background, it is helpful to add a neutral background to a container (like a div) to keep your content legible and clean.


## Adding a Background Color
A color fill can be created using the `background-color: ` property. You can use many English CSS color names, such as “white,” “orange,” “black,” etc. Check out available color names on [W3Schools](https://www.w3schools.com/cssref/css_colors.asp).


<div id="code-heading">HTML</div>
```html
.a-class-name {
  background-color: white;
}
```


## Adding a Background Image
You can easily generate a pattern on your background by adding a small image (less than 150px or so) and the `background-image: url(``)` property.


<span class="label label-info">NOTE:</span> Like you did when styling tables, you can add a pixel amount to the `padding: ` property within your chosen element. This can give cushion between the boundary of the container and the contents inside.



<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="WzxOYJ" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Topic-07: Basic Backgrounds" class="codepen"></p>
</div>
