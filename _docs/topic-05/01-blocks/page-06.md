---
title: Building a Page (Step-by-Step)
module: topic-05
permalink: /topic-05/grouping-elements/
categories: html
tags: class, div, id, page, span, structure
---

<div class="divider-heading"></div>

When thinking about page structure and layout, a good plan is to start with **divs** and begin identifying and grouping elements within:

1. “How many _divisions_ (or sections) of my page do I want?” Create these `<div></div>` elements accordingly.
2. Name important divs using the `id=""` attribute.
3. Add `class=""` attributes to divs that need styling.
4. Within the divs, add [structural html](../../topic-04/structural-markup/) content, like [headings](../../topic-03/using-headings/), [paragraphs](../../topic-03/paragraphs), etc.
5. Within the divs, add illustrative elements like [images](../img-element-review), [audio](../audio-element-review), or [video](../video-element-review).
6. Use the `<span></span>` element around structural elements that need inline styling, like specific words of a paragraph.
7. Rinse and repeat.


<div class="divider-pg"></div>


## Step-By-Step
Below is a page with two descriptions of popular sports. Here are the steps taken to create this page:

- Created two empty **divs**, `<div>...</div>`
- Added **ids** to those divs, `id="football-block"` and `id="racing-block"`, to make them unique.
- Applied the **class** of `class="content-block"` to _both_ divs, as they should visually appear the same (color, font-size, etc).
- Added structural **content** to both divs, including headings and paragraphs.
- Added a **span** to the first sentence of each paragraph, with the class `class=fist-line`. With the applied styling stated in the `<head>`, each sentence with this span will be italic.
- Repeated with content additions.


<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="MPqywp" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="HTML Block-Level and Inline Elements" class="codepen"></p>
</div>



<div class="divider-pg"></div>
