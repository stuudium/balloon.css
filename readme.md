[![npm version](https://badge.fury.io/js/balloon-css.svg)](https://www.npmjs.com/package/balloon-css)

<img src="logo.png" width="272" style="margin:0 auto" align="center" />

## Simple tooltips made of pure CSS
Balloon.css lets you add tooltips to elements without JavaScript and in just a few lines of CSS.

<img src="sample.gif" width="310" />

## Usage

### Installation

**Manually:**
Simply download `balloon.min.css` from this repo and add it to your HTML. e.g.

```html
<link rel="stylesheet" href="path/to/balloon.min.css">
```

### Positioning
For positioning, use `data-balloon-pos` attribute with one of the values: `up`, `down`, `left` or `right`:

```html
<button data-balloon="Whats up!" data-balloon-pos="up">Hover me!</button>
<button data-balloon="Whats up!" data-balloon-pos="left">Hover me!</button>
<button data-balloon="Whats up!" data-balloon-pos="right">Hover me!</button>
<button data-balloon="Whats up!" data-balloon-pos="down">Hover me!</button>
```


### Always show

To always show balloon without `:hover`, add the `data-balloon-always` attribute.


```html
<button data-balloon-always data-balloon="Whats up!" data-balloon-pos="up">Don't hover me</button>
```


### Glyphs and Icon Fonts
You can also add any HTML special character to your tooltips, or even use third-party Icon fonts:

```html
<button data-balloon="HTML special characters: &#9787; &#9986; &#9820;" data-balloon-pos="up">Hover me!</button>
<button data-balloon="Emojis: 😀 😬 😁 😂 😃 😄 😅 😆" data-balloon-pos="up">Hover me!</button>
```

Example using [Font Awesome](https://fortawesome.github.io/Font-Awesome/):

```html
<button class="fa" data-balloon="Font Awesome: &#xf030; &#xf133; &#xf1fc; &#xf03e; &#xf1f8;" data-balloon-pos="up">Hover me!</button>
```

### Credits

Made by Claudio Holanda ([@kazzkiq](https://twitter.com/kazzkiq))
