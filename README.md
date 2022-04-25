# Frontend Mentor - Testimonials Grid Section Solution

This is my solution to the [Testimonials Grid Section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

Thank you for checking out my solution to this front-end coding challenge!

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I started this challenge by observing the provided design files, which helped me plan out any custom CSS variables and utilities that I would need to create.

Once I had completed that step, I took that information and began to create the HTML mark-up code.  Once that was completed (while utilizing a "mobile-first" approach), I begun to update my CSS file to style each testimonial section individually and one at a time.

After I had completed styling each testimonial: I began to determine my media query breakpoint, so that I could determine at what device viewpoint to implement the code for my CSS Grid.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

In terms of anything new that I learned: I learned background image positioning via the "background-position" property, so that I could take the .svg file containing the double-quotation marks and apply it to the upper-right hand corner of the "Daniel Clifford" testimonial card.


```css
.daniel_container {
  background-color: var(--moderate-violet);
  background-image: url(./images/bg-pattern-quotation.svg);
  background-repeat: no-repeat;
  background-position: 90% 1%;
  grid-area: 1 / 1 / 2 / 3;
}
```

### Continued development

I will note that I have noticed a bit of excess padding within some of the testimonial cards that I was unable to determine the source of (in particular: the "Kira Abrams" testimonial card).

While this resulted in my solution to not be 100% matching the provided design files that this challenge provided: I did not feel that my solution looked "visually broken" and, instead, was still to be viable from a UI aspect.

## Author

- Chris Rumler
- Frontend Mentor - [@crumler](https://www.frontendmentor.io/profile/crumler)