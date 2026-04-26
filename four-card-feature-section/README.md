# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

[Desktop View (Zoomed out)](https://snipboard.io/HED7rb.jpg)
[Tablet View (Zoomed out)](https://snipboard.io/6GNORw.jpg)
[Mobile View 1 (Zoomed out)](https://snipboard.io/oxBeN9.jpg)
[Mobile View 2 (Zoomed out)](https://snipboard.io/HM1rp6.jpg)

### Links

- Live Site URL: [Github Pages](https://bluffset7340.github.io/four-card-feature-section/)

## My process

### Built with

- HTML 
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- SCSS

### What I learned

This was one of the more tougher projects that I had to deal with, so much so that I had to rely on YouTube tutorials for a good chunk of this project, I will provide the link to the channel below. Despite the challenge, I learnt a lot more about CSS Grid and its utility when it comes to ordering your layouts of the cards in this project. 

In this code snippet below:

```css
main{
    .content{
        display: grid;
        grid-template-columns: repeat(1, 1fr); //set to repeat once with one fractional column each
        gap: 1.5rem;
    }
}
```

So in this snippet, all the columns are organized in a way that they take up 1 fractional column each. I also applied the display of grid so that the template could be applied to the columns. Here the .content represents the individual cards. 

Here is another snippet of code:

```css
main .content .card:nth-child(odd){
        transform: translateY(50%);
    }
```

This snippet is taken from the tutorial and the point of it is that the leftmost and rightmost cards are translated in such a way that they both are lined up horizontally centred in relation to the two cards that are vertically stacked.

### Continued development

I definitely need to focus on applying the Grid layout lots more. Just as how I gained a deeper undeerstanding of CSS flex property through continous practice, the same will also have to be done to be proficient in CSS Grid

## Author

- Frontend Mentor - [@BluffSet7340](https://www.frontendmentor.io/profile/BluffSet7340)

## Acknowledgments

[Tutorial that I used](https://www.youtube.com/watch?v=29SSTkQtWcg)
