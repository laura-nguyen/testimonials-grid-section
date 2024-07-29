# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

The challenge to build out this testimonials grid section and get it looking as close to the design as possible.

![Design preview for the Testimonials grid section coding challenge](./design/desktop-preview.jpg)

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Repo](https://github.com/laura-nguyen/testimonials-grid-section)
- Live Site URL: [Live URL](https://laura-nguyen.github.io/testimonials-grid-section/)

## My process

- Set up Sass
- Define variables, mixins, typography, padding, margin
- Start with mobile view
  Adjust desktop view

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to use grid-template-areas to create different sized cards

```css
@include desktop {
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: repeat(2, 1fr);
  grid-template-areas:
    "card--1 card--1 card--2 card--5"
    "card--3 card--4 card--4 card--5";
  gap: 2rem;
  max-width: 1130px;
  margin: 10rem auto;
}
```

### Continued development

Will focus on more grid exercises to make sure components are responsive in all devices

### Useful resources

- [Responsive CSS Grid Tutorial](https://www.youtube.com/watch?v=68O6eOGAGqA) - This helped me adjust the grid layout for desktop. I really liked this pattern and will use it going forward.

## Author

- Website - [Laura Nguyen](https://www.your-site.com)
- Frontend Mentor - [@laura-nguyen](https://www.frontendmentor.io/profile/laura-nguyen)
- Github - [@laura-nguyen](https://www.github.com/laura-nguyen)
- Twitter - [@lauriananguyen](https://www.twitter.com/lauriananguyen)
