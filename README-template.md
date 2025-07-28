# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot-desktop.png)
![](./screenshot-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Responsive design for mobile and desktop

### What I learned

This project was a great opportunity to practice fundamental CSS concepts. I focused on creating a responsive layout that adapts from desktop to mobile.

One key learning was using CSS custom properties to manage the color palette, which made it easy to maintain consistency.

```css
:root {
  --white: hsl(0, 0%, 100%);
  --stone-100: hsl(30, 54%, 90%);
  --brown-800: hsl(14, 45%, 36%);
  --rose-800: hsl(332, 51%, 32%);
}

body {
  background-color: var(--stone-100);
}
```

I also learned how to handle responsive images and layouts using media queries to ensure the page looks great on different screen sizes.

```css
/* Desktop styles */
main {
  max-width: 640px;
  margin: 40px auto;
  padding: 2rem;
  border-radius: 20px;
}

/* Mobile styles */
@media (max-width: 375px) {
  main {
    width: 100%;
    margin: 0;
    border-radius: 0;
  }
}
```

### Continued development

In future projects, I want to focus on:

- Exploring more advanced CSS layout techniques like CSS Grid and Flexbox.
- Implementing CSS animations and transitions to create more engaging user experiences.
- Deepening my understanding of web accessibility (a11y) best practices.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/) - An invaluable resource for any web development question, especially for CSS properties and HTML elements.
- [CSS-Tricks](https://css-tricks.com/) - This site has excellent guides and articles on everything CSS, from the basics to advanced topics.

## Author

- Website - [Your Name](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
