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
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

This is a simple profile card component built using HTMl and CSS. I used BEM to create my class names.

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./screenshot.jpng)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/simple-profile-card-componenet-using-html-and-css-AA4X4nPE8D](https://www.frontendmentor.io/solutions/simple-profile-card-componenet-using-html-and-css-AA4X4nPE8D)
- Live Site URL: [https://schindlerdumagat.github.io/profile-card-component/](https://schindlerdumagat.github.io/profile-card-component/)

## My process

1. Created a GitHub repository for the project.
2. Inspect the figma design for the needed fonts, colors and spacings. Checked the designs from mobile view to desktop view and played the live prototype.
3. Structured my HTML based on the design.
4. Created CSS resets, CSS variables and element stylings based on the design.
5. Pushed to GitHub and deploy it live using Github pages.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- BEM (Block, Element, Modifier)

### What I learned

Learned how to use some background CSS properties.
```css
body {
    display: flex;
    flex-direction: column;
    justify-content: center;
    font-family: var(--ff-main);
    padding: var(--space-300);
    background-color: var(--clr-blue-600);
    background-image: url('./images/bg-pattern-top.svg'), url('./images/bg-pattern-bottom.svg');
    background-repeat: no-repeat, no-repeat;
    background-position: top -30rem left -50rem, bottom -30rem right -50rem; 
}
```

### Continued development

I needed to master how to handle images properly for my future projects.

## Author

- Website - [Schindler Dumagat](https://schindlerdumagat.github.io/webportfolio/)
- Frontend Mentor - [@schindlerdumagat](https://www.frontendmentor.io/profile/schindlerdumagat)
- LinkedIn - [@schindler-dumagat-015238230](https://www.linkedin.com/in/schindler-dumagat-015238230/)
