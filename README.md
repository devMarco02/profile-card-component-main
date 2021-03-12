# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- Build out the project to the designs provided

### Screenshot

Mobile: [](./solution-img/mobile.png)
Desktop: [](./solution-img/desktop.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/profile-card-component-using-html-and-sass-R8CIpNlhN)
- Live Site URL: [Add live site URL here](https://devmarco02-profile-card-component-main.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- SASS
- Flexbox
- CSS Grid

### What I learned

I learned how to use CSS Grid Layout by positioning the two background images.

```css
.bg-container {
  position: absolute;
  height: 100vh;
  width: 100vw;
  overflow: hidden;
  display: grid;
  grid-template-columns: 1fr 1fr;
  img {
    overflow: hidden;
  }
  .top-bg {
    grid-column: 1/2;
    grid-row: 1/2;
    justify-self: flex-end;
    align-self: flex-end;
  }
  .bottom-bg {
    grid-column: 2/3;
    grid-row: 2/3;
  }
}
```

## Author

- Frontend Mentor - [@devMarco02](https://www.frontendmentor.io/profile/devMarco02)
