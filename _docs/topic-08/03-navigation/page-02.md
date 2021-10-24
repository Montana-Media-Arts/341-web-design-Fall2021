---
title: The Nav Element
module: topic-08
permalink: /topic-08/basic-nav-element/
---

<div class="divider-heading"></div>

With HTML5 came the **nav element**. A `<nav>` block can contain your site's _major_ page or intra-page links, and can be used to declare a menu, table of contents, or site index.

Using the `<nav>` element is considered good practice because of its accessible features, but is also useful for styling purposes.


<span class="label label-danger">Important</span> As with anything you want visible to users, the `<nav>` element must be within the `<body>` of the page.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<nav>
  <!-- Site Links -->
</nav>


<!-- For example... -->
<nav id="main-menu">
  <a href="#">Home</a>
  <a href="#">Gallery</a>
  <a href="#">About</a>
  <a href="#">Contact</a>
</nav>
```


<div class="divider-pg"></div>


## Adding Links to the &lt;nav&gt; Element
To add links using HTML structural elements, you'll need to weigh appearance versus accessibility.


### Flat Text
To get a “horizontal” nav without much styling, you can simply add `<a href="">` contents, separated with a visual signifier like:
- vertical bars ( **\|** , written with escape name `&vert;` )
- interpunct ( **&middot;** , written with escape name `&middot;` )
- additional spaces ( written with escape name `&nbsp;` for each )
- etc

<p class="codepen" data-height="600" data-theme-id="dark" data-default-tab="html,result" data-slug-hash="dyXoYbM" data-editable="true" data-user="retrog4m3r" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/retrog4m3r/pen/dyXoYbM">
  HTML Nav element and flat links</a> by Michael Cassens (<a href="https://codepen.io/retrog4m3r">@retrog4m3r</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>


### Lists
However, lists are preferred by screen-reader technologies as it increases the accessibility of the navigation. The “[Styling Text](../basic-styling-text)” page in the previous subtopic showed you how to display these items horizontally, if preferred.

<p class="codepen" data-height="600" data-theme-id="dark" data-default-tab="html,result" data-slug-hash="NWrqGKY" data-editable="true" data-user="retrog4m3r" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/retrog4m3r/pen/NWrqGKY">
  HTML Nav element and List Links</a> by Michael Cassens (<a href="https://codepen.io/retrog4m3r">@retrog4m3r</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
