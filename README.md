# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshots

![Desktop Design](/Desktop_Design.png)
![Mobile Design](/Mobile_Design.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/clipboard-landing-page-using-css-grid-and-flexbox-Uqj4GWNLC](https://www.frontendmentor.io/solutions/clipboard-landing-page-using-css-grid-and-flexbox-Uqj4GWNLC)
- Live Site URL: [https://sachin9328.github.io/](https://sachin9328.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow
- [Fontawesome](https://fontawesome.com/) - For social media icons

### What I learned

- Flexbox
- CSS Grid

Flexbox:

```css
.flex-container {
    display: flex;
    flex-direction: column;
}

.equalcols {
    display: flex;
}

.equalcols > * {
    flex-basis: 100%;
}

#rowfour {
    display: flex;
    flex-direction: row; 
}

#rowfour > div {
    flex-basis: 100%;  
}

footer{
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

#colone {
    display: flex;
    flex-direction: row;
    flex: 1 1 100%;
}

```

CSS Grid:

```css
#rowfour {
    display: grid; 
    grid-gap: 5px;
}

footer {
    display: grid;
    max-width: 100%;  
}

footer > div {
    justify-items: center;
}
```

### Continued development

Need to understand CSS position property, Flexbox and CSS Grid better. Used a Desktop-first workflow approach, need to use Mobile-first workflow for future projects.

### Useful resources

- [W3Schools](https://www.w3schools.com/) - This helped me with CSS and CSS grid.
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS) - This again helped me understand some CSS concepts.
- [CSS-Tricks](https://css-tricks.com/) - Helped in understanding Flexbox and CSS Grid concepts

## Author

- Sachin Jadhav 
- Frontend Mentor - [@Sachin9328](https://www.frontendmentor.io/profile/Sachin9328)
- Linkedin - [@Sachin Jadhav](https://www.linkedin.com/in/sachin-jadhav-651a71127/)
