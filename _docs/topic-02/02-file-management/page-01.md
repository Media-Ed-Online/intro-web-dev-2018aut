---
title: Web Files
module: topic-02
permalink: /topic-02/files/
tags: common, design, file
---

<div class="divider-heading"></div>

Web designers use all types of files to create sites, from `.html` to `.css` to `.php` and dozens of others. How files are created and saved will affect how they are processed; a `.css` file will not have the same capabilities of a `.html` file, and vice versa.

### Common File Types Used in Web Design
<ul class="nav nav-tabs">
  <li class="active"><a href="#web-pages" data-toggle="tab">Pages</a></li>
  <li><a href="#web-images" data-toggle="tab">Images</a></li>
  <li><a href="#web-av" data-toggle="tab">Audio & Video</a></li>
  <li><a href="#web-scripts" data-toggle="tab">Scripts</a></li>
</ul>
<div id="myTabContent" class="tab-content">
  <div class="tab-pane fade active in" id="web-pages">
    <p style="font-style: italic;">Pages are the most common inclusion in a web site, simply because pages contain the visible content of that site. Further files (such as images and other media) will most-likely be accessed from pages, through hyperlinks, embeds, and the like.</p>
    <div class="divider-pg"></div>
    <div class="row">
      <div class="col-lg-2">
        <img src="../img/web-pages-html.svg" title="HTML" alt="html icon" width="100"/>
        <p style="margin-top: -10px; text-align: center; font-weight: bold;">page.html</p>
      </div>
      <div class="col-lg-10">
        <h4>Hypertext Markup Language (<b>HTML</b> or <b>HTM</b>)</h4>
        <p>HTML is the standard language known by all web designers and developers. HTML provides the structure of the page, using <i>elements</i> to create headings, paragraphs, lists, tables, links, etc. Properly-laid-out HTML is designed to enhance accessibility, and provide structured content outside of decorative styling.</p>
        <h4>Pros and Cons of Use:</h4>
        <ul style="list-style-type: none">
          <li class="icon-pro">Easy-to-learn, free or low-cost.</li>
          <li class="icon-pro">Widely-used; standard practice.</li>
          <li class="icon-pro">Extensive; has a large library and support community.</li>
          <li class="icon-con">Requires a browser to correctly interpret the code.</li>
          <li class="icon-con">HTML Lexicon is in American English, and may require extra interpretation for non-English speakers.</li>
        </ul>
      </div>
    </div>
    <div class="divider-pg"></div>
    <div class="row">
      <div class="col-lg-2">
        <img src="../img/web-pages-css.svg" title="CSS" alt="css icon" width="100"/>
        <p style="margin-top: -10px; text-align: center; font-weight: bold;">page.css</p>
      </div>
      <div class="col-lg-10">
        <h4>Cascading Style Sheet (<b>CSS</b>)</h4>
        <p>CSS is used to control how the page looks and functions. CSS is used to “decorate” the site; this is, provide layout, color, interactive elements, fonts, and other formatting. While HTML provides the contents of the page, CSS specifies to the browser how the site will look. Using a stylesheet greatly speeds up development time, as a single sheet can affect all pages in the site.</p>
        <h4>Pros and Cons of Use:</h4>
        <ul style="list-style-type: none">
          <li class="icon-pro">Speed and consistency in styling pages site-wide.</li>
          <li class="icon-pro">Supported by nearly all browsers.</li>
          <li class="icon-pro">Extensive; has a large library and support community.</li>
          <li class="icon-con">CSS syntax is different from HTML, and requires users to learn both languages.</li>
          <li class="icon-con">Interpreted differenly across browsers; requires testing.</li>
        </ul>
      </div>
    </div>
    <div class="divider-pg"></div>
    <div class="row">
      <div class="col-lg-2">
        <img src="../img/web-pages-php.svg" title="PHP" alt="php icon" width="100"/>
        <p style="margin-top: -10px; text-align: center; font-weight: bold;">page.php</p>
      </div>
      <div class="col-lg-10">
        <h4>Hypertext Preprocessor (<b>PHP</b>)</h4>
        <p>While we won't get into PHP, you've likely seen or heard of PHP files. PHP is a widely-used, open-source scripting language which is well-suited for use in web design as it can be combined with HTML. A server-side language, PHP can generate dynamic pages, modify databases, encrypt data, and many other processes HTML cannot do alone. In fact, it is the core of many services, such as <a href="http://blog.teamtreehouse.com/php-for-wordpress-1" target="_blank">WordPress</a> and <A href="https://developers.facebook.com/docs/reference/php/" target="_blank">Facebook</a>.</p>
        <h4>Pros and Cons of Use:</h4>
        <ul style="list-style-type: none">
          <li class="icon-pro">Moderately easy-to-learn, free or low-cost.</li>
          <li class="icon-pro">Can collect data, like from site forms.</li>
          <li class="icon-pro">Can control user-access.</li>
          <li class="icon-con">Limited control.</li>
          <li class="icon-con">Can take time to master frameworks.</li>
        </ul>
      </div>
    </div>
  </div>
  <div class="tab-pane fade" id="web-images">
    <p style="font-style: italic;">Images are the media lifeblood of web design. Sites can contain many images in different file types, and how that image will be used dictates what file type it should be, and vice versa.</p>
    <div class="divider-pg"></div>
    <div class="row">
      <div class="col-lg-2">
        <img src="../img/web-images-jpg.svg" title="JPG" alt="jpg icon" width="100"/>
        <p style="margin-top: -10px; text-align: center; font-weight: bold;">image.jpg</p>
      </div>
      <div class="col-lg-10">
        <h4>Joint Photographic Experts Group (<b>JPEG</b> or <b>JPG</b>)</h4>
        <p>The JPEG is the most-utilized image format in digital publishing. JPEGs can be compressed to low-, medium, and high-quality and, because of this, can showcase images on screens at relatively small file sizes without sacrificing the integrity of the image. File types like JPG, PNG, and GIF are “rastered” and have defined dimensions. This means the image will lose quality when resized, and should not be manipulated beyond its original dimensions (width and height).</p>
        <h4>Pros and Cons of Use:</h4>
        <ul style="list-style-type: none">
          <li class="icon-pro">Good for photographs, artwork, or other detailed images.</li>
            <li class="icon-pro">When the image has many colors.</li>
            <li class="icon-pro">Medium to small file size.</li>
            <li class="icon-con">Rastered file.</li>
        </ul>
      </div>
    </div>
    <div class="divider-pg"></div>
    <div class="row">
      <div class="col-lg-2">
        <img src="../img/web-images-png.svg" title="PNG" alt="png icon" width="100"/>
        <p style="margin-top: -10px; text-align: center; font-weight: bold;">image.png</p>
      </div>
      <div class="col-lg-10">
        <h4>Portable Network Graphics (<b>PNG</b>)</h4>
        <p>PNGs allow for transparency, an important tool in graphic and web design. Unlike JPGs, there is no compression with PNGs; these files will not lose quality when saved. However, this means PNGs are a rather large file type, and should be used sparingly or on small images.</p>
        <h4>Pros and Cons of Use:</h4>
        <ul style="list-style-type: none">
          <li class="icon-pro">Good for graphics like logos and icons.</li>
          <li class="icon-pro">When the image has areas of full- or partial-transparency (like drop shadows).</li>
          <li class="icon-con">Large file size.</li>
          <li class="icon-con">Rastered file.</li>
        </ul>
      </div>
    </div>
    <div class="divider-pg"></div>
    <div class="row">
      <div class="col-lg-2">
        <img src="../img/web-images-gif.svg" title="GIF" alt="gif icon" width="100"/>
        <p style="margin-top: -10px; text-align: center; font-weight: bold;">image.gif</p>
      </div>
      <div class="col-lg-10">
        <h4>Graphics Interchange Format (<b>GIF</b>)</h4>
        <p>Similar to PNGs, GIFs have certain properties that allow for image effects. This format is most-often attributed to animated files, as it allows for several consecutive frames to be included in a single image file. Due to this, GIFs can be quite large, and may require heavy compression to be feasible in site design.</p>
        <h4>Pros and Cons of Use:</h4>
        <ul style="list-style-type: none">
          <li class="icon-pro">Required for animated images.</li>
          <li class="icon-pro">Good for simple icons with low-color density (few colors).</li>
          <li class="icon-con">Large file size.</li>
          <li class="icon-con">Rastered file.</li>
        </ul>
      </div>
    </div>
    <div class="divider-pg"></div>
    <div class="row">
      <div class="col-lg-2">
        <img src="../img/web-images-svg.svg" title="SVG" alt="svg icon" width="100"/>
        <p style="margin-top: -10px; text-align: center; font-weight: bold;">image.svg</p>
      </div>
      <div class="col-lg-10">
        <h4>Scalable Vector Graphics (<b>SVG</b>)</h4>
        <p>SVGs are an integral component of web design. SVGs, as stated in their name, are scaleable and can be manipulated and styled without sacrificing quality or file size. SVGs are, in effect, “drawn” by the browser in that they are actually packets of coordinates written in a markup language (XML, or Extensible Markup Language). This code is editable, and SVGs can have colors, effects, and animations applied to them.</p>
        <h4>Pros and Cons of Use:</h4>
        <ul style="list-style-type: none">
          <li class="icon-pro">Good for vector graphics like logos and icons.</li>
          <li class="icon-pro">Resolution-independent.</li>
          <li class="icon-pro">Manipulating does not change file size.</li>
          <li class="icon-con">Not good for detailed images, or beyond 2D needs.</li>
          <li class="icon-con">Requires an understanding on how to properly use and implement the code.</li>
        </ul>
      </div>
    </div>
  </div>
  <div class="tab-pane fade" id="web-av">
    <p style="font-style: italic;">You will come across <b>many</b> types of media files in websites. Below are just some common variables, but by no means the only file types available. This list also excludes streaming media, which is the prevailing method of using media on the web.</p>
    <div class="divider-pg"></div>
    <div class="row">
      <div class="col-lg-2">
        <img src="../img/web-av-mp3.svg" title="MP3" alt="mp3 icon" width="100"/>
        <p style="margin-top: -10px; text-align: center; font-weight: bold;">file.mp3</p>
      </div>
      <div class="col-lg-10">
        <h4>MPEG-1 Audio Layer 3 (<b>MP3</b>)</h4>
        <p>MP3 technology has been around for decades, and revolutionized how music was stored and shared during the 1990's. MP3s offer an accessible ratio of playback quality to file size, although it is still subject to patents, meaning users must have MP3-ready software in order to play the file.</p>
        <h4>Pros and Cons of Use:</h4>
        <ul style="list-style-type: none">
          <li class="icon-pro">Small file size.</li>
          <li class="icon-pro">Widely-used; standard practice.</li>
          <li class="icon-con">Proprietary; browsers must pay to support this file type.</li>
        </ul>
      </div>
    </div>
    <div class="divider-pg"></div>
    <div class="row">
      <div class="col-lg-2">
        <img src="../img/web-av-ogg.svg" title="OGG" alt="ogg icon" width="100"/>
        <p style="margin-top: -10px; text-align: center; font-weight: bold;">file.ogg</p>
      </div>
      <div class="col-lg-10">
        <h4>Ogg Vorbis (<b>OGG</b>)</h4>
        <p>An OGG file is even more compressed than an MP3, but not necessarily at any lower quality. This compression is at a varying bit rate, meaning moments of silence, for example, will have less storage weight than those in an MP3, as MP3s compress at a constant bit rate. The OGG is open-source and free-to-all.</p>
        <h4>Pros and Cons of Use:</h4>
        <ul style="list-style-type: none">
          <li class="icon-pro">Good for internet streaming.</li>
          <li class="icon-pro">In the public domain, free-for-use.</li>
          <li class="icon-con">Limited official development.</li>
          <li class="icon-con">Not as widely recognized as other audio formats.</li>
        </ul>
      </div>
    </div>
    <div class="divider-pg"></div>
    <div class="row">
      <div class="col-lg-2">
        <img src="../img/web-av-mp4.svg" title="MP4" alt="mp4 icon" width="100"/>
        <p style="margin-top: -10px; text-align: center; font-weight: bold;">file.mp4</p>
      </div>
      <div class="col-lg-10">
        <h4>MPEG-4 Part 14 (<b>MP4</b>)</h4>
        <p>Like MP3, MP4 is a granddaddy file type with a rich history. A multimedia container used to store video and audio, MP4 supports a variety of video coding formats, like H.264. MP4s are usable on most devices, platforms, and browsers.</p>
        <h4>Pros and Cons of Use:</h4>
        <ul style="list-style-type: none">
          <li class="icon-pro">Good video quality.</li>
          <li class="icon-pro">Widely-used; standard practice.</li>
          <li class="icon-con">Online MP4 files requires pre-buffering.</li>
          <li class="icon-con">Proprietary; browsers must pay to support this file type.</li>
        </ul>
      </div>
    </div>
    <div class="divider-pg"></div>
    <div class="row">
      <div class="col-lg-2">
        <img src="../img/web-av-webm.svg" title="WebM" alt="webm icon" width="100"/>
        <p style="margin-top: -10px; text-align: center; font-weight: bold;">file.webm</p>
      </div>
      <div class="col-lg-10">
        <h4>Web Media (<b>WebM</b>)</h4>
        <p>A relatively new format, WebM is a container created especially for internet streaming by Google as a standard supported format in HTML5. It is less high-quality than MP4, but this allows for quicker access and download speeds. Unlike MP4, WebM is open-source and free-to-all.</p>
        <h4>Pros and Cons of Use:</h4>
        <ul style="list-style-type: none">
          <li class="icon-pro">Designed for internet streaming.</li>
          <li class="icon-pro">Open-source, free-for-use.</li>
          <li class="icon-con">Poor compatibility with mobile devices and players.</li>
          <li class="icon-con">Not widely supported by Windows or Apple.</li>
        </ul>
      </div>
    </div>
  </div>
  <div class="tab-pane fade" id="web-scripts">
    <p style="font-style: italic;">Scripts add functionality to websites. They can be run client- or server-side, and can do some really heavy lifting in terms of making sites interesting and dynamic.</p>
    <div class="divider-pg"></div>
    <div class="row">
      <div class="col-lg-2">
        <img src="../img/web-scripts-js.svg" title="JavaScript" alt="js icon" width="100"/>
        <p style="margin-top: -10px; text-align: center; font-weight: bold;">script.js</p>
      </div>
      <div class="col-lg-10">
        <h4>JavaScript (<b>JS</b>)</h4>
        <p>JavaScript is the third leg of the Web-Dev triad, along with HTML and CSS. These three languages work exceptionally well together to provide structured, styled, and interactive sites. JavaScript is ubiquitous; anytime you open up a page that does more than offer static information like animations or timely updates, JavaScript is most-likely the culprit. </p>
        <h4>Pros and Cons of Use:</h4>
        <ul style="list-style-type: none">
          <li class="icon-pro">Easy-to-learn, free or low-cost.</li>
          <li class="icon-pro">Incredibly popular; wide-usage with community knowledgebase.</li>
          <li class="icon-pro">Versatile. Basic JS can be used inline in HTML, and developing entire applications.</li>
          <li class="icon-con">Because the code executes on the client's computer, it can be a security risk.</li>
          <li class="icon-con">Interpreted differently across browsers; requires testing.</li>
        </ul>
      </div>
    </div>
    <div class="divider-pg"></div>
    <div class="row">
      <div class="col-lg-2">
        <img src="../img/web-scripts-cgi.svg" title="CGI" alt="cgi icon" width="100"/>
        <p style="margin-top: -10px; text-align: center; font-weight: bold;">script.cgi</p>
      </div>
      <div class="col-lg-10">
        <h4>Common Gateway Interface (<b>CGI</b>)</h4>
        <p>Another way to add dynamic content to a site is through a CGI. CGI programs (or scripts) are the most common way for web servers to interact with users. These files are good for processing data sets, for example, like those used in forms and counters. CGIs can be made using many programming languages like Python, PERL, or Java.</p>
        <h4>Pros and Cons of Use:</h4>
        <ul style="list-style-type: none">
          <li class="icon-pro">Work on a variety of servers.</li>
          <li class="icon-pro">Can be written in nearly any language.</li>
          <li class="icon-pro">Provides simple interfaces for the clients to interact with the web servers.</li>
          <li class="icon-con">Can be memory-intensive, especially on sites with high-level traffic.</li>
          <li class="icon-con">Creation is not entry-level; can require extensive programming knowledge to be effective.</li>
        </ul>
      </div>
    </div>
    <div class="divider-pg"></div>
  </div>
</div>

<br/>

<span class="label label-success">Neat-O</span> Most file types and their languages are designed to work _together,_ not singularly, and need to be directed to each other to function properly.
