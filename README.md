# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-  [Overview](#overview)

-  [The challenge](#the-challenge)

-  [Screenshot](#screenshot)

-  [My process](#my-process)

-  [Built with](#built-with)

-  [What I learned](#what-i-learned)

-  [Continued development](#continued-development)

-  [Useful resources](#useful-resources)

-  [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

Dekstop design:

<p align="center">
  <img src="./screenshots/desktop.png">
</p>

Mobile design:
<p align="center">
  <img src="./screenshots/mobile.png">
</p>

## My process

### Built with

- Flexbox

- Mobile-first workflow

### What I learned

One of the things I learned while working on the challenge was how to overlay colors with CSS, but I'm not sure I did it properly. The color overlay effect on the image was created as follows:  

```html

<div  class="image"></div>

```

```css
.image {
  height: 100%;
  background-image: linear-gradient(rgb(170, 92, 219, 0.65), rgb(170, 92, 219, 0.65)), url("./images/image-header-mobile.jpg");
  background-size: 100%  100%;

  border: 0px  solid  transparent;
  border-radius: 0px  10px  10px  0;
}
```

### Continued development
  
I want to continue improving my skills in HTML and CSS, mainly with a focus on responsive web design and mobile first.

### Useful resources

-  [Two ways to create an image with a colour overlay in CSS](https://dev.to/ellen_dev/two-ways-to-achieve-an-image-colour-overlay-with-css-eio) - Where I learned how to create the color overlay effect.

## Author

- Frontend Mentor - [@avillasilva](https://www.frontendmentor.io/profile/avillasilva)
