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

## Overview

### The challenge

Create an responsive stats preview card base design requirements.

### Screenshot

![mobile view](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Linear Gradient
- Background Image with blur

### What I learned

I learn how to best use image as background as well as add some blur effect on top of the image with linear gradient. I used following code to add the bg image and the overlay.

```css
background-image: linear-gradient(var(--accent)),
  url("images/image-header-mobile.jpg");
background-repeat: no-repeat;
background-position: center;
background-size: cover;
```

- `background-repeat: no repeat`: prevent the image to be repeated if the doesn't fit the container height and width.
- `background-position: center`: is self explanatory i guess 😅.
- `background-size: cover` adjust the size to cover the whole container.
- `linear-gradient(var(--accent))` add an overlay on top over the bg image.
