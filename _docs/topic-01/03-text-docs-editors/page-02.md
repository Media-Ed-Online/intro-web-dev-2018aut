---
title: Word Processor Documents
module: topic-01
permalink: /topic-01/word-processors/
categories: development
tags: processor, text
---

<div class="divider-heading"></div>

## "Well, I have Microsoft Word, so..."

You might be tempted to say Microsoft Word Document files (`.doc` or `.docx`) are text files. However, these are actually containers of many smaller files that are ZIP-compressed together into the `.docx` file. This complex file that Microsoft uses allows them to store images, objects, text, and complex formatting instructions all in a single file, which can then be easily saved, shared, or sent between users of the Microsoft productivity applications.

The downside to this format though is that you cannot open this file in a basic text editor to change it. The image below shows a Microsoft Word Document (`.docx`) opened in the Atom text editor. As you can see, this file does not present itself in a way that offers you much understanding of its contents.


<img src="../img/docx-in-atom.jpg" alt="A .docx file loaded into a simple text editor" title="A .docx file viewed in Atom" style="width: 100%; max-width: 700px" />


<!-- Modal Thumb -->
<!--<div class="modal-image" style="margin: auto;">
  <img src="../img/docx-in-atom.jpg" alt="A .docx file loaded into a simple text editor" data-toggle="modal" data-target="#modal-docx-atom">
</div>-->

<!-- Modal -->
<!--<div class="modal fade" id="modal-docx-atom" tabindex="-1" role="dialog" aria-labelledby="" aria-hidden="true">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <div class="modal-title" id="exampleModalLabel">A .docx file loaded into a simple text editor</div>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        <div class="image">
          <p>As you can see, you cannot open a Word document in Atom in order to edit its contents:</p>
          <img src="../img/docx-in-atom.jpg" class="img-responsive" alt="A .docx file loaded into a simple text editor">
          <div class="img-caption">
            Totally legible.
          </div>
        </div>
      </div>
    </div>
  </div>
</div>-->
