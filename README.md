# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned more about Flexbox and how to get around things using this tool.

```css
.card{
    flex-basis:33%;
    flex-grow: 1;
    padding:48px;
}
```

I also used CSS variables in a new way, using them as pixels to set the offset of the border added to the button. To get closest pixel size without having to change all values each time.

```css
:root{
    --button-border: 2px;
}

.button{
    border: var(--button-border) solid var(--very-light-gray);
    padding:calc(15px - var(--button-border)) calc(32px - var(--button-border)) calc(15px - var(--button-border)) calc(32px - var(--button-border));
}
```
### Continued development

I want to continue improving the responsive aspect since I am currently just solving them based on the pixel size stated on the challenges. 

### Useful resources

- [Pixel Perfect Bookmarklet](https://dsheiko.github.io/pixel-perfect-bookmarklet/) - This helped me get closer to the pixel perfect design by adding the design on top of my version.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/DarKaRor)
