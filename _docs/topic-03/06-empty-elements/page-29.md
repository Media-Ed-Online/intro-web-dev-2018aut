---
title: The Image Element
module: topic-03
permalink: /topic-03/intro-img-element/
---

<div class="divider-heading"></div>

We will get into images much later in the course, but by using a little borrowed code, you can already add images to your new HTML files. Like the others in this section, the image tag, `<img />`, creates an empty element. `src=""` tells the browser where the image is located, or the URL to the file.

Please note that instead of wrapping the URL in parentheses (`(...)`) like we do in Markdown, in HTML, we use quotations (`"..."`) to contain the URL to the file.

<div id="code-heading">HTML</div>
```html
<img src="./images/name-of-image.jpg" />
```


Compare this to Markdown:


<div id="code-heading" style="margin-top: 0 !important;">Markdown</div>
```markdown
![My Image](./images/name-of-image.jpg)
```


At this stage in your development journey, you can get an image to embed very similar as you would in Markdown using the element `<img src="..." />`.


<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="MQbOdj" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="HTML Image Element Src Attribute" class="codepen"></p>
</div>
