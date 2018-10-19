---
title: Tags
module: topic-03
permalink: /topic-03/html-tags/
tags: tags, html, markdown, paragraph
---

<div class="divider-heading"></div>

Elements are identified in a document through tags. A **tag** is code that is syntactically unique from the text content of the document. In HTML, all tags include a less-than (**<**) and greater-than (**>**) sign, with the tag typed between.

Most elements include an “opening” and “closing” tag that the processor uses to identify the beginning and end of the element with. Closing tags are identical to opening tags, except that they contain a forward-slash (**/**) between the less-than (**>**) sign and the tag text.


<div id="code-heading">HTML</div>
```html
<p>This is a paragraph element.</p>
<p>This element is created with an opening "<p>" tag and a closing "</p>" tag. We call this "wrapping."</p>
```


Compare this to Markdown:


<div id="code-heading" style="margin-top: 0 !important;">Markdown</div>
```markdown
This is a paragraph.

In markdown, paragraphs requires no extra markup to signify it as such. An empty line between text blocks signifies a new paragraph.
```