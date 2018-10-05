---
title: To a Specific Part of the Same Page
module: topic-04
permalink: /topic-04/same-page/
---

<div class="divider-heading"></div>

Sometimes pages are partcularly long, or you're using a one-page site layout. We can use the **ID attribute** in HTML to create links to specific portions of a page.

_One attribute that can be assigned to almost any HTML element is_ `id`. This attribute is used to assign unique identifiers to each element, so that those specific elements can be referenced through HTML, CSS, or JavaScript.


<h2 id="first-heading">Part 1 - Identify where the link will go:</h2>

To assign an element an unique identifier, you should include the following code in the opening tag.

<span class="label label-danger">Important</span> When assigning ids on the same page, no two elements should have the same values (ie, names).

<div id="code-heading">HTML</div>
```html
<menu>
  To Part 1
  To Part 2
</menu>

<main>
  <h3 id="first-heading">Part 1</h3>
  <h3 id="second-heading">Part 2</h3>
</main>
```


<h2 id="second-heading"> Part 2 - Assign the reference:</h2>

<span class="label label-info">Note</span> You may be familar with "anchors", which were used in HTML4. This practice is defunct in HTML5, but the end-result is very similar.

To link to an HTML element with an assigned id, simply use the id in the hyper-reference (`href`), prepended with a hashtag character (`#`).

In the following code, the link in line 1, would connect to the `h2` element in line 3.

<div id="code-heading">HTML</div>
```html
<menu>
  <a href="#first-heading">To Part 1</a>
  <a href="#second-heading">To Part 2</a>
</menu>

<main>
  <h2 id="first-heading">Part 1</h2>
  <h2 id="second-heading">Part 2</h2>
</main>
```


See it in action!
- Up to the <a href="#first-heading">Part 1</a>.
- Up to the <a href="#second-heading">Part 2</a>.
-	<a href="#">Up to Top</a>
