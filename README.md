# Frontend Mentor - Workit landing page solution

This is a solution to the [Workit landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/workit-landing-page-2fYnyle5lu). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./preview.jpg)

### Links

- Solution URL: [Github](https://github.com/delroscol98/Workit-Landing-Page)
- Live Site URL: [Github Pages](https://delroscol98.github.io/Workit-Landing-Page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The HTML below shows semantic HTML and the use of ARIA to make the website accessible for all users and assist screen readers.

```html
<section class="hero_banner">
  <h1 class="hero_banner-title">
    Data
    <span aria-role="heading" class="hero_banner-title-highlight"
      >tailored</span
    >
    to <br />
    your needs.
  </h1>
  <button type="button" class="hero_banner-button">
    <p class="button-text">Learn more</p>
  </button>
</section>
```

The CSS below was fun to test and implement. It was my first time implementing a curved background.

```css
.hero {
  position: relative;
  height: 48.171rem;
  background-color: var(--dark-purple);
  clip-path: ellipse(140% 55% at 50% 45%);
  z-index: 2;
}
```

### Continued development

The larger the project, the more difficult it is to keep track of which section is to the standard. For future projects, it is important to pay attention to the little details for each section.

### Useful resources

- [Clippy](https://bennettfeely.com/clippy/) - This helped me to understand clip-path CSS.

## Author

- Frontend Mentor - [@delroscol98](https://www.frontendmentor.io/profile/delroscol98)
