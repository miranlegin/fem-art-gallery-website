# Frontend Mentor - Art gallery website solution

This is a solution to the [Art gallery website challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/art-gallery-website-yVdrZlxyA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for each page depending on their device's screen size
- See hover states for all interactive elements throughout the site
- **Bonus**: Use [Leaflet JS](https://leafletjs.com/) to create an interactive location map with custom location pin

### Screenshot

Tablet version
![](/screenshots/tablet.png)

### Links

- Solution URL: [https://github.com/miranlegin/fem-art-gallery-website](https://github.com/miranlegin/fem-art-gallery-website)
- Live Site URL: [https://frontend-mentor-challenge14.netlify.app/](https://frontend-mentor-challenge14.netlify.app/)

## My process

### Built with

- [Astro](https://astro.build/) - Static Site Generator
- [IcoMoon](https://icomoon.io/) - Icon Font &amp; SVG Icon Sets
- [Mapbox](https://www.mapbox.com/) - For creating custom Maps
- CSS custom properties
- CSS Grid
- Flexbox

I've used this challenge to practice building sites with Astro as a Static Site Generator. This was my 3rd site built with Astro and i'm getting confortable with it.

Main layout was created with Grid and although i've worked with Figma files lots of switching components around breakpoints made this challenge more fun to work with.

I've also used Mapbox as i'm somewhat familiar with it to build custom design map based on Figma design and create custom Pin and Popup window.

I've played with animations on buttons with some masking in `::before` pseudo class.

Most images except hero are created with `<picture>` element with various `<source>`s for responsive images.

Typography is mostly done with `clamp` function in css but can be improved a bit.

### What I learned

I'm getting closer to find out perfect workflow with CSS custom properties as most of the time on this challenges is spend measuring stuff and aligning it to closely fit the design provided. I think the only way to go is to create design system upfront with as many properties i can create from Figma files and use them accordingly where needed.

Fonts and colors are done this way but i need to find a better way to space things in components and also on larger level in the layout itself.

### Continued development

Need more work in the future with creating as many as i can custom properties for spacing things because that is the area where i'm spending most of the time.

### Useful resources

- [Modern CSS Reset by Andy Bell](https://piccalil.li/blog/a-modern-css-reset/) - One of the resets that i use.
- [Responsive images explained](https://cloudfour.com/thinks/responsive-images-101-part-6-picture-element/) - 10 part series about responsive images
- [Accessible SVGs](https://css-tricks.com/accessible-svgs/) - Lots of examples for using SVGs in accessible way
- [Clamp size generator](https://clamp.font-size.app/) - Usefull resource for calculating dinamic clamp sizes

## Author

- Frontend Mentor - [@miranlegin](https://www.frontendmentor.io/profile/miranlegin)
