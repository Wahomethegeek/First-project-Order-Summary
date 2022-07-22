# Frontend Mentor - Order summary card solution

This is a solution to the [(https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj)]. Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![./images/screenshot.jpg]


### Links

- Solution URL: [https://github.com/Wahomethegeek/First-project-Order-Summary.git]
- Live Site URL: [https://krivety-order-summary.netlify.app]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow


### What I learned

I was able to properly understand and to apply css grid to responsively align items.



``` css desktop-version
.card {
    max-width: 450px;
    margin: 20px auto; 
    border-radius: 20px;
    box-shadow: 0px 10px 18px rgb(164, 150, 150);
    background-color: white;
}
```
```css mobile-version
@media screen and (max-width: 600px) {
    body {
        min-width:375px;
    }
    .card {
        width: 375px;
    }
    .image img {
         
         width: 375px;
        
    }
}
```

### Continued development

. Responsive design
. css grid

### Useful resources

- [(https://www.w3schools.com/css/css_grid.asp)] - This helped me understand CSS grid.

## Author

- Website - [(https://www.yourhttps://wahomethegeek.github.io/wahome.github.io/-site.com)]
- Frontend Mentor - [www.frontendmentor.io/Wahomethegeek]
- Twitter - [@_wahomekelvin].

## Acknowledgments

I give thanks to [freecodecamp.org] for helping understand the basics of HTML and CSS and much thanks [frontendmentor] for such challenges.


