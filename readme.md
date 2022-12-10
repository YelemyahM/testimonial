# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Testimonials grid section solution](#frontend-mentor---testimonials-grid-section-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Here](https://www.frontendmentor.io/solutions/testimonials-grid-section-r1F8kuVhmj)
- Live Site URL: [Here](https://testimonial-jet.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I learn to use CSS Grid and combine it to responsive design.

```css
@media screen and (min-width: 768px) {
  .container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-gap: 20px;
    margin: 5% auto 0 auto;
  }
  .post {
    margin-bottom: 0;
    height: auto;
  }
  .one {
    grid-column: span 2;
    background-position: top right 80px;
  }

  .five {
    grid-column: span 2;
  }

  .three {
    grid-row: span 2;
  }

  .three,
  .five {
    order: 0;
  }
}

```

## Author

- Frontend Mentor - [@YelemyahM](https://www.frontendmentor.io/profile/YelemyahM)
- Twitter - [@yele_m715](https://twitter.com/yele_m715)
