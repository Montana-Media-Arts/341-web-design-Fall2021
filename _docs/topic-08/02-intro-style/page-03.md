---
title: Inline Styles
module: topic-08
permalink: /topic-08/basic-styling-divs/
---

<div class="divider-heading"></div>

Divs are _block-level_ elements, meaning they fill the page edge-to-edge. If this isn't necessarily what we want, we can easily force changes to the div itself, and how it relates to the elements inside.

What if we want to affect just one `div` tag and leave the others the same?

Let's look at how this might work.

## Changing Width
You can easily change the width of a div from 100% using the **width property**. Width values can be in percentages (changing) or pixels (unchanging). For example:
- to be half of the page _at any size_ of the brower window, set to `width: 50%;`
- to be 300 pixels wide _no matter the size_ of the browser window, set to `width: 300px;`

<div class="code-heading">
  <span class="html">HTML</span>
</div>

```html
  <div style="width: 50%;">
```

<p class="codepen" data-height="600" data-default-tab="html,result" data-slug-hash="dyXooGE" data-editable="true" data-user="retrog4m3r" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/retrog4m3r/pen/dyXooGE">
  div width</a> by Michael Cassens (<a href="https://codepen.io/retrog4m3r">@retrog4m3r</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>

## Centering on the Page
Have a div less than full-page and want it placed in the middle? Add the **margin property**, set to `auto` (`margin: auto`).

<div class="code-heading">
  <span class="html">HTML</span>
</div>

```html
<div style="margin: auto;">
```
<p class="codepen" data-height="600" data-default-tab="html,result" data-slug-hash="WNxvvxp" data-editable="true" data-user="retrog4m3r" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/retrog4m3r/pen/WNxvvxp">
  div margin auto</a> by Michael Cassens (<a href="https://codepen.io/retrog4m3r">@retrog4m3r</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>

## Cushioning From the Edge
Text inside of a div will set along the edges. To override this and give the text some ???cushion??? for easier-reading, add the **padding property**. Pixel values are best-suited here.

<div class="code-heading">
  <span class="html">HTML</span>
</div>

```html
<div style="padding: 10px;">
```

<p class="codepen" data-height="600" data-theme-id="dark" data-default-tab="html,result" data-slug-hash="dyXooXE" data-editable="true" data-user="retrog4m3r" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/retrog4m3r/pen/dyXooXE">
  div padding</a> by Michael Cassens (<a href="https://codepen.io/retrog4m3r">@retrog4m3r</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>

<div class="divider-pg"></div>

Finally, what if we want to use multiple styles in the same style attribute?

### Example
This final example, puts all of it together using **width**, **margin: auto**, and **padding**.


<p class="codepen" data-height="600" data-theme-id="dark" data-default-tab="html,result" data-slug-hash="LYZVVRv" data-editable="true" data-user="retrog4m3r" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/retrog4m3r/pen/LYZVVRv">
  Basic HTML Div Styling</a> by Michael Cassens (<a href="https://codepen.io/retrog4m3r">@retrog4m3r</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
