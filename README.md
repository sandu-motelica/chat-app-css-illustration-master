# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

./Screenshot.png

### Links

- Solution URL: https://github.com/sandu-motelica/chat-app-css-illustration-master.git
- Live Site URL: https://sandu-motelica.github.io/chat-app-css-illustration-master/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I discovered that absolute positioning allows elements to be precisely placed within their closest positioned ancestor or the viewport itself. By setting the position property to absolute, I can use top, bottom, left, and right properties to determine the exact positioning. I also learned about the power of background gradients. Instead of using solid colors, I can create smooth transitions between colors using the background-image property with the linear-gradient() function.

.main-container::before {
content: "";
position: absolute;
left: -6rem;
top: -14rem;
height: 82rem;
width: 46rem;
background-image: linear-gradient(
to top,
hsl(264, 100%, 61%),
hsl(293, 100%, 63%)
);
z-index: -2;
border-bottom-right-radius: 25.2rem;
border-bottom-left-radius: 20rem;
}

## Author

- Frontend Mentor - [@sandu-motelica](https://www.frontendmentor.io/profile/sandu-motelica)
- GitHub - [@sandu-motelica](https://github.com/sandu-motelica)
