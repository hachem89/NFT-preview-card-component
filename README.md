# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [solution](https://github.com/hachem89/NFT-preview-card-component.git)
- Live Site URL: [live site](https://hachem89.github.io/NFT-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

```css
.image-container::before{
    content: "";
    position: absolute;
    height: 300px;
    width: 300px;
    border-radius: 10px;
    background-color: var(--Cyan);
    opacity: 0;
    transition: opacity 200ms ease;
}
```

## Author

- Frontend Mentor - [@hachem89](https://www.frontendmentor.io/profile/hachem89)

