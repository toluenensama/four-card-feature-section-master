# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

### Screenshot

![Mobile View](/Screenshots/Screenshot-mobile.png)
![Desktop View](/Screenshots/Screenshot-desktop.png)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Tailwind Flexbox
- Tailwind CSS Grid
- Mobile-first workflow




### What I learned

For the mobile view, flex was used using `flex flex-col` having two `<div></div>` containers one which is text and the other the group of cards. 

The desktop view, the container of the group of cards was made to a grid, using `grid lg:grid-cols-3` the second and third where grouped into a container and made a grid `grid grid-cols-1` the first and third is placed at the center of the container using `row-span-2` to make them span the full height of the container and `items-center` and `grow-0` so as to prevent them from stretching and keeping them at the middle of the container.



## Author

-Github [toluenesama](https://github.com/toluenensama)