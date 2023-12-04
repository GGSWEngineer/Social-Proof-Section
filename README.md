# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size


### Links

- Solution URL: https://github.com/GGSWEngineer/Social-Proof-Section
- Live Site URL: https://ggswengineer.github.io/Social-Proof-Section/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This piece of code is helpful for setting the width of your container in a responsive way. I will be taking this pattern and using it alot more in the future. 

.container {
  --max-width: 1110px;
  --padding: 1.5rem;
  width: min(var(--max-width), 100% - (var(--padding) * 2));
  margin-inline: auto;
  margin-top: 5.12rem;
  margin-bottom: 6.19rem;
}

### Continued development

This is my first ACTUAL responsive project, but I know its not perfect and its something I'll continue to work on. 

### Useful resources

 https://www.youtube.com/watch?v=KqFAs5d3Yl8 - This video helped me for building more responsive projects. I really liked the patterns Kevin Powell uses in his projects, so I've taken them to use for my own!


## Author

- Frontend Mentor - [@GGSWEngineer](https://www.frontendmentor.io/profile/GGSWEngineer)
- LinkedIn - [Gerardo Garcia](www.linkedin.com/in/gerardo-garcia-19a794275)
