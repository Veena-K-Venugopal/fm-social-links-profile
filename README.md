# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

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

A social links profile card resembling the one provided in the preview for the challenge from frontendmentor.io

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Desktop](./screenshot1.png)

![Hover Screen](./screenshot2.png)

### Links

- Live Site URL: (https://veena-k-venugopal.github.io/fm-social-links-profile/#)

## My process

I added the semantic elements first. I finished styling the links list first. Then did the name, location, paragraph, etc. I included and styled the image towards the end.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

To set up the hover state on the list of social profiles

```css
li:hover {
  background-color: var(--green);
  color: var(--grey-900);
  cursor: pointer;
}
```

To add the grey 900 color to the `<a>` element on hover

```css
li:hover a {
  color: inherit;
}
```

### Continued development

The social media profile links could be populated with real links that would redirect to the appopriate pages.

### Useful resources

- [Unordered list without any bullets](https://sentry.io/answers/i-need-an-unordered-list-without-any-bullets-html-css/) - This helped me to style the unordered list as required.
- [CSS Hover Effects](https://css-tricks.com/css-link-hover-effects/) - This article helped me expand my understanding about hover effects.
- [CSS Functions](https://css-tricks.com/complete-guide-to-css-functions/) - This article is a great reference for CSS functions.

## Author

- Frontend Mentor - [Veena-K-Venugopal](https://www.frontendmentor.io/profile/Veena-K-Venugopal)
