# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshots

![mobile screenshot](images/mobile-screenshot.JPG)
![desktop screenshot](images/desktop-screenshot.JPG)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This is the first time I've used the `<picture>` and `<source>` elements.

```html
<picture class="product__img">
  <source
    media="(min-width: 600px)"
    srcset=
      "images/image-product-mobile.jpg 375w,
      images/image-product-desktop.jpg 600w"
    sizes="(min-width: 375px), (min-width: 600px)"
  />
  <img
    src="images/image-product-mobile.jpg"
    alt="perfume bottle laying down among green leaves"
  />
</picture>
```

I've also starting using the `:root {}` element in css as well to set global styles.

```css
:root {
  --clr-primary-900: hsl(158, 36%, 37%);
  --clr-primary-200: hsl(30, 38%, 92%);

  --clr-neutral-900: hsl(212, 21%, 14%);
  --clr-neutral-400: hsl(228, 12%, 48%);
  --clr-neutral-100: hsl(0, 0%, 100%);

  --ff-regular: "Montserrat", sans-serif;
  --ff-accent: "Fraunces", serif;

  --fw-regular: 500;
  --fw-bold: 700;
}
```

### Continued development

BEM has been an enjoyable methodology to employ for better CSS organization and scalability. I will continue to use it for future projects.

There are still elements in HMTL and CSS I want to become more familiar with. Particularly, CSS Grid and `@media` queries.

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- GitHub - [pMacadoo](https://github.com/pmacadoo)
- Frontend Mentor - [@pMacadoo](https://www.frontendmentor.io/profile/pmacadoo)

## Acknowledgments

This solution was inspired by Kevin Powell. I've been following his content and found Frontend Mentor as a result.