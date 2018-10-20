---
title: Structural Markup
module: topic-04
permalink: /topic-04/structural-markup/
categories: html
tags: markup, structural
---

<div class="divider-heading"></div>

**Structural markup** embeds _information_ about the structure of a document. Structure includes elements such as:

- Headings
- Paragraphs
- Breaks
- Lists

These elements will help guide a user visually and provide information about the type of content through a document. These elements are also used by the browser and DOM to understand the content of a document. A browser will use this structural markup to assist [screen readers](http://www.afb.org/prodBrowseCatResults.aspx?CatID=49) and other accessibility-based software.


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
  The most basic of structured documents should include tags identifying headings and paragraphs. These two markup elements are used in almost every document editing application and are crucial in authoring web content.</p>
</div>


## Headings and Paragraphs
You are already familiar with headings, paragraphs, and breaks.

**Headings** are defined with the `<h1>` to `<h6>` tags, where `<h1>` defines the most important heading and `<h6>` defines the least important heading. `<h1>` headings are considered to be _Main Headings_, while `<h2>` headings are usually considered _sub-headings_ and so forth through `<h6>`.

Any text between the **paragraph** tags `<p>...</p>` belongs to the same paragraph. Almost all non-heading text will be placed within a paragraph element in a web document.


<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="qxXaxa" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="HTML Structural Body Elements" class="codepen"></p>
</div>
