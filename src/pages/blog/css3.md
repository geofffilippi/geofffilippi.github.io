---
layout: '../../layouts/Post.astro'
title: css3
image: /images/css3
publishedAt: "2023-01-07"
category: 'Web'
---

## [`css3`](https://www.w3.org/Style/CSS/current-work.en.html)
> Cascading Style Sheets (CSS) is a simple mechanism for adding style (e.g., fonts, colors, spacing) to Web documents.

### `clamp`
Specify a range of values `min, computed value, max`
```css
clamp(0.78rem, calc(0.71rem + 0.35vw), 0.96rem);
```

### `ch`
Unit specifying the width of the `0` character.
```css
  max-width: 30ch;
```

### `root`
Define Variables
```css
:root {
  /* Colors */
  --theme-primary: hsl(0, 0%, 5%);
  --theme-on-primary: hsl(0, 0%, 90%);

  --theme-primary-hover: hsl(0, 0%, 10%);

  --theme-primary-light: hsl(0, 0%, 80%);

  --theme-background: hsl(0, 0%, 98%);
  --theme-on-background: hsl(0, 0%, 5%);

  --theme-surface-1: hsl(0, 0%, 93%);
  --theme-on-surface-1: hsl(0, 0%, 10%);

  --theme-footer-background: hsl(0, 0%, 3%);
  --theme-on-footer-background: hsl(0, 0%, 90%);

  /* Typography */
 /* @link https://utopia.fyi/type/calculator?c=320,18,1.2,1140,24,1.25,5,2,&s=0.75|0.5|0.25,1.5|2|3|4|6,s-l */

  --step--2: clamp(0.78rem, calc(0.71rem + 0.35vw), 0.96rem);
  --step--1: clamp(0.94rem, calc(0.84rem + 0.51vw), 1.20rem);
  --step-0: clamp(1.13rem, calc(0.98rem + 0.73vw), 1.50rem);
  --step-1: clamp(1.35rem, calc(1.15rem + 1.02vw), 1.88rem);
  --step-2: clamp(1.62rem, calc(1.34rem + 1.41vw), 2.34rem);
  --step-3: clamp(1.94rem, calc(1.56rem + 1.92vw), 2.93rem);
  --step-4: clamp(2.33rem, calc(1.81rem + 2.59vw), 3.66rem);
  --step-5: clamp(2.80rem, calc(2.11rem + 3.47vw), 4.58rem);

  --font-family-heading: '', sans-serif;
  --font-family-body: 'Open Sans', sans-serif;

  --body-max-width: 1920px;

  /* Container */
  --container-padding: 0 1rem;
  --container-max-width: 860px;

  --header-height: 76px;

  /* Transitions */
  --ease-out-soft: cubic-bezier(0.28, 0, 0.49, 1);
}
```

### [`white-space`](https://developer.mozilla.org/en-US/docs/Web/CSS/white-space)
Control how elements wrap. `pre-wrap` breaks lines at newlines.

```css
white-space: pre-wrap;
```

### [`word-break`](https://developer.mozilla.org/en-US/docs/Web/CSS/word-break)
Control where lines break. `break-all` will break on any character. This is helpful for long words.

```css
word-break: break-all;
```

### `background`
Set background color of an element

```css
background: #ddd;
```

### `border-left`
Set a left border

```css
border-left:0.3rem solid #bbb;
```

