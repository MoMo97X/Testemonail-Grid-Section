# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](screenshot.png)

### Links

- Solution URL: [Front-End mentor](https://www.frontendmentor.io/solutions/testimonials-card---grid-layout-ORLxQ6X5Uw)
- Live Site URL: [Front-End mentor](https://momo97x.github.io/Testemonail-Grid-Section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

#### using grid template areas to make complex layout

```css
.card-container {
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(3, auto);
  grid-template-areas:
    "purple purple"
    "grey white-1"
    "black black"
    "white-2 white-2";
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

## Author

- Website - [Github](https://github.com/MoMo97X/Testemonail-Grid-Section)
- Frontend Mentor - [@MuhammedArrjbani](https://www.frontendmentor.io/profile/MoMo97X)
