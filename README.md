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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](images/myDesktop.JPG)
![](images/myMobile.JPG)

### Links

- Solution URL: [https://github.com/Glorit74/product-preview-card-component-main](https://github.com/Glorit74/product-preview-card-component-main)
- Live Site URL: [https://glorit74.github.io/product-preview-card-component-main/](https://glorit74.github.io/product-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

to display a suitable image on both wide screen and narrow screen

```html
<picture>
  <source media="(max-width: 375px)" srcset="images/image-product-mobile.jpg" />
  <source
    media="(min-width: 376px)"
    srcset="images/image-product-desktop.jpg"
  />
  <img src="/images/image-product-mobile.jpg" alt="Bottle of CHANEL perfume" />
</picture>
```

### Useful resources

- [Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) - Here I found the solution to switch between images depending on the size of device.

## Author

- Frontend Mentor - [@Glorit74](https://www.frontendmentor.io/profile/Glorit74)

## Acknowledgments

Thanks to my school, **Codecool**!
