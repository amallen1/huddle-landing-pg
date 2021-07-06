# Frontend Mentor - Huddle landing page with a single introductory section

![Design preview for the Profile card component coding challenge](./design/desktop-preview.jpg)


## Welcome! 👋

This is a solution to the [Huddle landing page with a single introductory section challenge on Frontend Mentor.
[Frontend Mentor](https://www.frontendmentor.io) challenges help developers to improve their coding skills by building realistic projects.

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

The challenge was to build out the huddle landing page and get it looking as close as the provided design as possible. 
This challenge was done without access to the design files and rather by estimating sizes of elements. However, the style guide provided by Frontend Mentor helped by providing colors, font-sizes, font-family, etc. 

### Screenshot

Mobile Version:
<img src="/design/mobile-design.jpg" width="300"/>

Desktop Version:
<img src="/design/desktop-design.jpg" width="500">


### Links

- Solution URL: []
- Live Site URL: []


## My process

### Built with

- HTML
- SCSS
- Mobile first workflow



### What I learned

At first I tried to make the background image an HTML tag, but had a few issues positioning the content on top. So I decided to make the background image apart of the body's background image. The image repeated a little bit, but after researching background-size property on MDN, I was able to fix this problem.

I added a width on the grid container so that everything doesn't touch the sides

I also ran into a small issue when it came to styling the call to action "register button" because I made it a link and tried to give a height and width but it didn't display. After researching, I remembered that HTML link tags are inline elements, so they only take up as much width as necessary. Setting the link's display property to block solved my problem.

I also learned while creating the box shadow for the call to action button that the offset x affects the shadow to the left and right of the element and the y offset affects the top and bottom.
### Continued development

~~

### Useful resources

Solution to background img issue
- https://developer.mozilla.org/en-US/docs/Web/CSS/background-size

Solution to link height/width issue
- https://stackoverflow.com/questions/5990223/how-to-set-alink-height-width-with-css
- https://www.w3schools.com/html/html_blocks.asp

Solution to box shadow issue
- https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow
- https://www.w3schools.com/cssref/css3_pr_box-shadow.asp





## Author
- Frontend Mentor - [@amallen1](https://www.frontendmentor.io/profile/amallen1)


