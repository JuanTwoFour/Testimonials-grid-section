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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](/images/Screenshot.png)

### Links

- Solution URL: [Solution]()
- Live Site URL: [Live site](https://juantwofour.github.io/Testimonials-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex-box
- CSS Grid
- Mobile-first workflow

### What I learned

One thing I learned on this lesson was how to use grid in a more flexible way, I also learned a little on how to have cleaner CSS in my code.

```css
.testimonial-grid {
  display: grid;
  gap: 1.5rem;
  grid-auto-columns: 1fr;
  grid-template-areas: 
  'one'
  'two'
  'three'
  'four'
  'five';
}

.testimonial-grid {
    grid-template: 
    'one one'
    'two five'
    'three five'
    'four four';
  }

  .testimonial-grid {
    grid-template: 
    'one one two five'
    'three four four five';
  }
```

### Useful resources

- [W3bSchools](https://www.w3schools.com/) - As always, awesome source for help on coding.
- [Youtube- Kevin Powell](https://www.youtube.com/watch?v=rg7Fvvl3taU) - His follow along on this exact project is probably the simplest way to learn and understand more about grid. He makes it sound so simple and when using the techniques learned from him it is remarkable how over complicated I tend to make things when they really aren't

## Author

- Socials - [Juan Vega](https://juantwofour.github.io/Social-Profiles/)
- LinkedIn - [Juan Vega](https://www.linkedin.com/in/juan-vega-bab395282)
- Frontend Mentor - [@JuanTwoFour](https://www.frontendmentor.io/profile/JuanTwoFour)

## Acknowledgments

Shout out to Kevin Powell on Youtube, his videos on css are some of the most helpful I've come across. He explains everything so well, if I ever want to learn something new in css or need a video explanation for visuals his channel is one of the best places to visit.

- Kevin Powell's Youtube [Kevin Powell](https://www.youtube.com/@KevinPowell)