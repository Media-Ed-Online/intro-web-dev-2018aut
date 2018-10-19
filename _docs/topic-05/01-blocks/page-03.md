---
title: Styling with Classes
module: topic-05
permalink: /topic-05/html-classes/
categories: html
tags: attribute, best&nbsp;practice, class, naming
---

<div class="divider-heading"></div>

In addition to the id attribute, the **class attribute** is another attribute that is valid in every HTML element.

<div class="container-row">
  <img src="../img/legos-classes.png" alt="stacked building blocks with similar class names" title="Similar blocks can have the same class!" style="float: right; width:300px; margin-top: 0; " />

  <p>Like the ID attribute, the class attribute is an identifier and selector value for HTML elements. The class attribute groups similar types of elements together by using the same unique name value. This allows for easy styling of these elements with same CSS code.</p>
</div>

## Naming
The class attribute follows the same technical naming conventions as the ID attribute. As with the ID attribute, the class attribute value should be as descriptive as possible about the function or element types groups, while prioritizing both brevity and readability.

Unlike the ID attribute which should contain a single unique ID value, elements may have more than one class assignment. In this case, a space separates each class.

<span class="label label-info">NOTE:</span> This means that while every element should have a unique id, several elements can reference the _same_ class.

<div id="code-heading">HTML</div>
```html
<div id="example-1" class="class-name-1 class-name-2 notice-the-space">
    <p>Notice the space between each of the three class names.</p>
</div>

<div id="example-2" class="class-name-2">
    <p>This paragraph has a unique id, but the same "class-name-2" as the one above it.</p>
</div>
```
