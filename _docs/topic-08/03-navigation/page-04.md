---
title: Navigating to Sections on the Same Page
module: topic-08
permalink: /topic-08/basic-nav-section/
---

<div class="divider-heading"></div>

When pages are long, or visitors are expected to interested in specific topics, you can section the page using `<div>`s with unique `id`s. A page can then include its own navigation with links to those unique sections.

<p class="codepen" data-height="600" data-theme-id="dark" data-default-tab="html,result" data-slug-hash="mdEJVJG" data-editable="true" data-user="retrog4m3r" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/retrog4m3r/pen/mdEJVJG">
  HTML Nav element, Page Navigation</a> by Michael Cassens (<a href="https://codepen.io/retrog4m3r">@retrog4m3r</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>


<span class="label label-info">Note</span> It is considered good practice to include “back to top” options for the user, to avoid excessive scrolling and confusion. This can be done by using `#` as the [source's placeholder](https://www.w3.org/TR/html5/browsers.html#dom-location-hash), or creating an `id` at the page's beginning.
