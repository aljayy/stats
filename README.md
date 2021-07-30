# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

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

### The challenge

Users should be able to:

- View the optimal layout depending on a desktop and on a mobile device width of 375px.

### Screenshot

![Desktop](/images/stats-desktop-preview.png)
![Mobile](/images/stats-mobile-preview1.png)
![Mobile](/images/stats-mobile-preview2.png)

### Links

- Live Site URL: [Add live site URL here](https://aljayy.github.io/stats/)

## My process

I drew a sketch on paper of an outline of the site. This gave me a higher level overview of possible containers I would want, what elements I would I use, and how I would format it from mobile to desktop. This also gave me a headstart on possible issues I would run into so that when they came along, I was prepared.

### Built with

- Semantic HTML5 markup
- SCSS
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned the huge benefits of a mobile first approach. When I first started this project with a desktop first approach I started by adding flexbox and grid geatures and it went really well.

But then I ran into the issue and pain of having to revert my grid and flexbox to their defaults when making it responsive to mobile. I figured this was not the best way to go about this. It was a huge headache and reverting back to the default settings when coming about this from a desktop first approach seemed like a waste of time and coding.

I restarted my CSS/SCSS from a mobile first approach. This changed it all for me. Not only did I not have to use flexbox OR the grid to style my mobile site, it made it much easier to create the media queries for the desktop. There was no reverting back to the default settings. I definitely understood why the mobile first approach is better to work with, and this is something I will start incorporating in my projects from now on.

The 'position' property was a huge learning lesson as well. From learning the basics to each individual property, to learning how properties such as relative and absolute work in harmony.

### Continued development

Something I want to continue developing is in formatting my images. This is still an area I don't quite comprehend and a concept I find myself confused in quite frequently.

Figuring out how to make an image fit inside a container just right, the differences between laying out the image in HTML with the 'img' tag or in CSS as a background-image, and just in general making an image format and behave the way I want it to. Really understanding this is going to be a priority in my upcoming projects.

Another area is in pseudo selectors, as I used the ::after selector to create an overlay over my image. I had to work around this certain selector adding 5-6 pixels of height to a div box by taking 1% off the ::after selector's height. I know there is a better way to go about this and is another area I want to improve in.

## Author

Thank you for taking the time to read this.

- Website - [Alan Jimenez](https://aljayy.github.io/stats/)
