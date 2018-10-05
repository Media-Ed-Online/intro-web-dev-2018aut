---
title: Indentation
module: topic-04
permalink: /topic-04/indentation/
---

<div class="divider-heading"></div>

There isn't total protocol for indent depth, although standard procedure is to indent one tab (or 2 spaces) for each new element that is a child of the one above it.

Indentation doesn't effect how the page renders, but makes a **huge** difference in the readability of the code.


<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>
<html>
  <body>

    <!-- This is a mess, and considered in poor taste: -->
    <menu id="hot-mess">
            <ul>
    <li><a href="#">Home</a>
      </li><li><a href="/about">About</a></li><li>
                    <a href="/contact">Contact Me</a></li></ul>
    </menu>

    <!-- Rather, this is considered best practice: -->
    <menu id="class-act">
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="/about">About</a></li>
        <li><a href="/contact">Contact Me</a></li>
      </ul>
    </menu>

  </body>
</html>
```


Here's an example with nested lists:


<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="ZXbPar" data-default-tab="html" data-user="Media-Ed-Online" data-pen-title="HTML Nested Lists 2" class="codepen"></p>
</div>
