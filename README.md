# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: (https://github.com/heisemmanuell/Product-preview-card/)
- Live Site URL: (https://heisemmanuell.github.io/Product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to use media query to change images on a webpage

```css
@media (max-width: 768px) {
  .container {
    flex-direction: column; 
  }

  .images {
    background-image: url('/images/image-product-mobile.jpg');
    width: 100%;
    border-radius: 0.7rem 0.7rem 0 0;
    height: 30vh;
  }
}
```

## Author

- Frontend Mentor - [@heisemmanuell](https://www.frontendmentor.io/profile/heisemmanuell)
