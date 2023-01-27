# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process) - [What I learned](#what-i-learned) - [Continued development](#continued-development)
    =- [Author](#author)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size
-   See hover and focus states for interactive elements

### Screenshot

![](./images/screenshot.png)

### Links

-   Live Site URL: [Solution](https://ilaganjacob.github.io/product-preview-card/)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS grid
-   Media queries

### What I learned

I learned a lot about media queries, specifically how to use both the mobile and desktop images and making them visible depending on what media device the user is on.
I also learned how to use both css grid and flexbox together.

```html
<picture class="img-container">
    <img
        src="./images/image-product-mobile.jpg"
        alt="Image of Gabrielle Essence Chanel perfume bottle"
        class="mobile-img"
    />
    <img src="./images/image-product-desktop.jpg" alt="" class="desktop-img" />
</picture>
```

```css
.desktop-img {
    display: none;
}
```

### Continued development

I'm still not comfortable with media queries and using their properties to change the layout of websites depending on the media used.

## Author

-   Website - [Jacob Ilagan](https://www.github.com/ilaganjacob)
-   Frontend Mentor - [@ilaganjacob](https://www.frontendmentor.io/profile/ilaganjacob)
