# Frontend Mentor - Product preview card component solution

This is a solution from Dimitris Kaffes to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

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

Mobile first design approach was implemented for this challenge.

A modern CSS reset (by Andy Bell) was implemented.

A change to a two-column grid is applied for bigger screens.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Screenshot of the solution](./images/screenshot-solution.jpg)

### Links

- Solution URL: [product-preview-card-component solution on Github](https://github.com/dkaffes/product-preview-card-component)
- Live Site URL: [product-preview-card-component live site](https://dkaffes.github.io/product-preview-card-component/)

## My process

The HTML structure was built using semantic elements.

The `<s>` strikethrough element was used to render the text with the deleted perfume price. However, the presence of the `<s>` element is not announced by most screen reading technology. For this reason a hidden `<p>` element is playing the role of an `aria-label` to compensate for these accessibility issues.

Custom properties were used for the colors.

A media query was used to change the bigger screen layout to a two-column grid.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

First steps with the Accessibility subject.

### Continued development

Learn more on the Accessibility subject.

### Useful resources

- [10 fundamental web accessibility tips for front-end developers](https://www.frontendmentor.io/articles/10-fundamental-web-accessibility-tips-for-frontend-developers-rUurADGxCt) - A useful article wit tips to get you started with web accessibility.

- [MDN reference on the `<s>` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/s) - This helped me learn more on the `<s>` element and its Accessibility concerns.

- [HTML: A good basis for accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML) - This MDN article from the Accessibility Guide is a great intro in the importance of using the correct HTML elements.

## Author

- Frontend Mentor - [@dkaffes](https://www.frontendmentor.io/profile/dkaffes)
