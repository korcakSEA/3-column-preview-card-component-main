# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./![alt text](image.png))


### Links

- Solution URL: (https://github.com/korcakSEA/3-column-preview-card-component-main.git)
- Live Site URL: (https://korcaksea.github.io/3-column-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I guss the most difficult part is to write code for each botton and their hover effects

You can see code snippets, see below:


```css
/* Botton animation classes */
.btn--sedans{
    color:var(--Bright-orange);
}
.btn--sedans:hover,
.btn--sedans:focus{
    background-color: var(--Bright-orange);
    color: var(--Very-light-gray);
}

.btn--suvs{
    color:var(--Dark-cyan);
}
.btn--suvs:hover, 
.btn--suvs:focus{
    background-color: var(--Dark-cyan);
    color: var(--Very-light-gray);
}

.btn--luxury{
    color:var(--Very-dark-cyan);
}
.btn--luxury:hover, 
.btn--luxury:focus{
    background-color: var(--Very-dark-cyan);
    color: var(--Very-light-gray);
}
```

## Author

- Frontend Mentor - [@korcakSEA](https://www.frontendmentor.io/profile/korcakSEA)
