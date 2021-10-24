---
title: Styling Backgrounds
module: topic-08
permalink: /topic-08/basic-styling-backgrounds/
---

<div class="divider-heading"></div>

We will get more into styling backgrounds when we formally talk about CSS, but for now, you can do basic color styling using various **background** properties.

Many structural elements can have background property values. If you have a busy page background, it is helpful to add a neutral background to a container (like a div) to keep your content legible and clean.  We just did this in the previous section!


## Adding a Background Color
A color fill can be created using the **background-color property**. You can use many English CSS color names, such as “white,” “orange,” “black,” etc. Check out available color names on <a href="https://www.w3schools.com/cssref/css_colors.asp" target="_blank">W3Schools</a>.

<div class="code-heading">
  <span class="html">HTML</span>
</div>

```html
<div style="background-color: green;">
```

<p class="codepen" data-height="600" data-theme-id="dark" data-default-tab="html,result" data-slug-hash="LYZVVRv" data-editable="true" data-user="retrog4m3r" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/retrog4m3r/pen/LYZVVRv">
  Basic HTML Div Styling</a> by Michael Cassens (<a href="https://codepen.io/retrog4m3r">@retrog4m3r</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>


## Adding a Background Image
You can easily generate a pattern on your background by adding a small image (less than 150px or so) and the **background-image property**, where you can use a _relative URL_ to an image in your directory.

<div class="code-heading">
  <span class="html">HTML</span>
</div>

```html
  <body style="background-image: url("#");">
```
**Note** Keep in mind that the image can be something on your site or something external. Just a relative link if it's on your site use a absolute link if it's external (i.e. should start with http or https).

<p class="codepen" data-height="600" data-theme-id="dark" data-default-tab="html,result" data-slug-hash="gOMppWr" data-editable="true" data-user="retrog4m3r" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/retrog4m3r/pen/gOMppWr">
  background-image</a> by Michael Cassens (<a href="https://codepen.io/retrog4m3r">@retrog4m3r</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>

<div class="divider-pg"></div>


### Example
See how you can add pizazz ( I know, I know, it's busy!) with **background-color** and **background-image** styling!


<p class="codepen" data-height="600" data-theme-id="dark" data-default-tab="html,result" data-slug-hash="VwjLLWZ" data-editable="true" data-user="retrog4m3r" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/retrog4m3r/pen/VwjLLWZ">
  Basic HTML Background Styling with Color and Image</a> by Michael Cassens (<a href="https://codepen.io/retrog4m3r">@retrog4m3r</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>


Like you saw on the previous page, adding a pixel amount to the `padding: ;` property within your chosen element can give cushion between the boundary of the container and the contents inside.
