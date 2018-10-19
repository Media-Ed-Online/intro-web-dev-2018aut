---
title: Extra Markup
module: topic-05
permalink: /topic-05/extra-markup/
categories: html
tags: markup, page, structure, naming
---

<div class="divider-heading"></div>

At this point, we have covered the main tags that fit nicely into groups and sections.
In this chapter, we will focus on some helpful topics that are not easily grouped together. You will learn about:
● The different versions of HTML and how to indicate which version you are using
● How to add comments to your code
● Global attributes, which are attributes that can be used on
any element, including the class and id attributes
● Elements that are used to group together parts of the page
where no other element is suitable
● How to embed a page within a page using iframes
● How to add information about the web page using the <meta> element
● Adding characters such as angled brackets and copyright symbols

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
  There are very important <a href="../../topic-02/naming-practices" target="_blank">naming conventions</a> that you should know by now.</p>
</div>


## Block-Level Elements

To describe the example images you've been seeing, these elements work much like building blocks - separate bricks that come together to create the structure of the page.

Block elements appear on their own block on a new line. Other examples of block elements include:

- Images `<img>`
- Headings `<h1>`-`<h6>`
- Paragraphs `<p>`


Each of these, unless told otherwise through styling, appears on a new line in HTML pages.


## Inline Elements

In the below example, the `<span>` element identifies specific parts of the paragraph statement, and then alter the appearance of those elements in the rendered page.
