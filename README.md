# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![screenshot-mobile](./images/screenshot-mobile.png)
![screenshot-desktop](./images/screenshot-desktop.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/product-preview-card-using-mobilefirst-workflow-lbS5u0A5_y](https://www.frontendmentor.io/solutions/product-preview-card-using-mobilefirst-workflow-lbS5u0A5_y)
- Live Site URL: [https://yingjhen-su.github.io/frontend-mentor-product-preview-card/](https://yingjhen-su.github.io/frontend-mentor-product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox
- CSS Grid
- Mobile-first workflow
- RWD

### What I learned

- Use "CSS Grid" to evenly distribute space
```css
.product {
    width: 37.5rem;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
}
```

- Use "Media Query"
```css
@media screen and (min-width: 768px) {
    /* || MAIN */
    .product__pic {
        height: initial;
        min-height: 100%;
        background-image: url(./images/image-product-desktop.jpg);
    }
}
```

### Useful resources

- [金魚都能懂網頁設計入門 : RWD試排版](https://www.youtube.com/watch?v=tEavVrEPBlA&list=PLqivELodHt3iL9PgGHg0_EF86FwdiqCre&index=21&t=308s) - A great video course to learn RWD.

## Author

- Frontend Mentor - [@YingJhen-Su](https://www.frontendmentor.io/profile/YingJhen-Su)