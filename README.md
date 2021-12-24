# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

To create a stats preview card component as close to the design files provided.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](screenshot.JPG)

### Links

- Solution URL: [here](https://github.com/Ishi1834/stats-preview-card-component)
- Live Site URL: [here](https://ishi1834.github.io/stats-preview-card-component/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

How to use an svg background:

```html
<article class="image">
  <img src="images/image-header-mobile.jpg" alt="" />
  <div class="overlay"></div>
</article>
```

```css
.image {
  position: relative;
}
.image img {
  max-width: 100%;
  border-radius: 10px 10px 0 0;
  z-index: -1;
}
/* overlay color on image here */
.overlay {
  background-color: var(--Soft-violet);
  position: absolute;
  border-radius: 10px 10px 0 0;
  top: 0;
  z-index: 1;
  height: 99.5%;
  width: 100%;
  opacity: 0.5;
}
```

## Author

- Github - [@Ishi1834](https://github.com/Ishi1834)
- Frontend Mentor - [@Ishi1834](https://www.frontendmentor.io/profile/Ishi1834)
- CodePen - [@sadiq1834](https://codepen.io/sadiq1834)
