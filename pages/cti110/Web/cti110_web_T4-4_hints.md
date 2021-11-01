---
title: Tutorial 4 Coding Challenge 4
tags: [programming]
keywords: notes, tips, cautions, warnings, admonitions
last_updated: October 23, 2021
# summary: "You can insert notes, tips, warnings, and important alerts in your content. These notes are stored as shortcodes made available through the linksrefs.hmtl include."
sidebar: cti110_sidebar
permalink: cti110_web_T4-4_hints.html
folder: cti110/web
---
<!-- # Tutorial 4: Coding Challenge 4 -->

## Links to helpful sites

---

### [text-shadow - CSS: Cascading Style Sheets | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow)

The text-shadow CSS property adds shadows to text. It accepts a comma-separated list of shadows to be applied to the text and any of its decorations. Each shadow is described by some combination of X and Y offsets from the element, blur radius, and color.

---

### [box-shadow - CSS: Cascading Style Sheets | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow)

The box-shadow CSS property adds shadow effects around an element's frame. You can set multiple effects separated by commas. A box shadow is described by X and Y offsets relative to the element, blur and spread radius, and color.

#### Syntax

```css
/* offset-x | offset-y | blur-radius | spread-radius | color */
box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2);
```

---

### [border-image - CSS: Cascading Style Sheets | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/border-image)

The border-image CSS property draws an image around a given element. It replaces the element's regular border.

#### Syntax

```css
/* source | slice */
border-image: linear-gradient(red, blue) 27;
```

---

### [background - CSS: Cascading Style Sheets | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/background)

The background shorthand CSS property sets all background style properties at once, such as color, image, origin and size, or repeat method.

---

### [radial-gradient() - CSS: Cascading Style Sheets | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/radial-gradient())

The radial-gradient() CSS function creates an image consisting of a progressive transition between two or more colors that radiate from an origin. Its shape may be a circle or an ellipse. The function's result is an object of the \<gradient> data type, which is a special kind of \<image>.

#### Syntax

```css
radial-gradient(shape size at position, start-color, ..., last-color);
```

---

### [circle() - CSS: Cascading Style Sheets | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape/circle())

The circle() CSS function is one of the \<basic-shape> data types.

#### Syntax

```css
shape-outside: circle(50%);
clip-path: circle(6rem at 12rem 8rem);
```

---

### [url() - CSS: Cascading Style Sheets | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/url())

The url() CSS function is used to include a file. The parameter is an absolute URL, a relative URL, or a data URI. The url() function can be passed as a parameter of another CSS functions, like the attr() function. Depending on the property for which it is a value, the resource sought can be an image, font, or a stylesheet. The url() functional notation is the value for the \<url> data type.

#### Syntax

```css
/* Simple usage */
url(https://example.com/images/myImg.jpg);
url(data:image/png;base64,iRxVB0…);
url(myFont.woff);
url(#IDofSVGpath);
```

#### [Link to slideshow](../Tutorial_Hints/export/export/index.html)
