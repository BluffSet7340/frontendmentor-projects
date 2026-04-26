# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- SCSS
- Mobile-first workflow
- [Icons](https://fontawesome.com/icons/cart-shopping?f=classic&s=solid) - Font Awesome

### What I learned

The most valuable thing I learnt was using the picture and source tag where the picture tag acted as a placeholder for the image and the source tag acted as another image that only came up with a specfic width was reached. All of this was done directly on the HTML itself and didn't require any additions to the media query on CSS, which I thought was pretty cool. Another lesser thing that I learnt was that when you set the width to 100vw, some browsers may add on to it, causing it flow horizontally, a pressing issue on mobile devices. It's more optimal to leave the width as is. Last but not least, I used SCSS for this project, suggested by frontendmentor themselves. I learnt how to use variables for fonts and colours, and sandwiching inner CSS selectors inside of their out CSS selector. So far it has helped me in writing code that is more understandable. 


```html
<picture class="pict_container">
    <source srcset="images/image-product-desktop.jpg" media="(min-width:605px)">
    <img src="images/image-product-mobile.jpg" alt="Perfume" />
</picture>
```

### Continued development

Since this was first time starting with a mobile first workflow, I ended up having issues trying to port it over desktop. I am aware that the point of doing the above is that it becomes easier to implement for desktop so it's clear that I need to work more on it. So one issue that I faced in desktop mode was the content was taking up more width than the image when both the image and content should have equal widths. My workaround was simply to implement widths of 300px for both the content and the image. Another issue was the fact that the image is desktop view was taking up the full height and the only workaround I could up with was forcing the image to take a height of 450px, which I know is haram. 

The issues I faced is what I hope to work on in later projects. 

### Useful resources

- [Taking on a Frontend Mentor challenge | Responsive Product Preview Card Component](https://www.youtube.com/watch?v=B2WL6KkqhLQ) - Skip to the section where he talks about switching the image from mobile to desktop depending on the width. 
- [Horizontal Scroll Bar?](https://stackoverflow.com/questions/26722340/horizontal-scroll-bar?rq=1) - This seemed to fix my issue with the horizontal scroll bar on mobile screens.

## Author

- Frontend Mentor - [@BluffSet7340](https://www.frontendmentor.io/profile/BluffSet7340)

## Acknowledgments

Special thanks to Kevin Powell for introducing the concept of picture and source tags and to the people of Stack Overflow who cleared my doubts regarding the horizontal scroll bar. 