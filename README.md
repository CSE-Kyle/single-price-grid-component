# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

Desktop :

![desktop screenshot](screenshot1.png)

Mobile : 

![mobile screenshot](screenshot2.png)

### Links

- Solution URL: [GitHub repo](https://github.com/CSE-Kyle/single-price-grid-component)
- Live Site URL: [Netlify.com live site](https://curious-bavarois-35446e.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox
- CSS Grid
- Media Queries 

### What I learned :

how to make a website responsive by the use of "media queries" to style how the structure of a website should look depending on its screen size. :
```css
  @media only screen and (max-width: 425px) {
  }
```
positioning elements on a webpage using grid-template-areas. : 
```css
.content {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-areas: 
    "item1 item1"
    "item2 item3"
  ;
}
```

### Continued development

- How to better position/align elements in an efficient way and not over using too many properties and creating too many unnecessary classes/id's.
- setting font size for text by using rem to keep consistent font styling. 
- setting a default css reset before starting any project.

### Useful resources

- [w3schools](https://www.w3schools.com/) - The main resource that I've used to figure out how to style and position elements on the webpage.

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout) - another useful resource that's more in-depth of its documentation. Providing references, guides, specifications, and more.

- [Wes Bos CSS Grid](https://cssgrid.io/) - A video series that has helped me be more comfortable of using CSS Grid, I was very rusty on grid before jumping into watching the video series and it has aided me a lot to have a better understanding of how grid works and how to use it.

- [Youtube](https://www.youtube.com/) - For me to visually see how other developers add certain properties to specific classes/selectors to get a better understanding and visualization of how each css property works. 

## Author

- GitHub - [Kyle Deguzman (CSE-Kyle)](https://github.com/CSE-Kyle)
- Frontend Mentor - [@CSE-Kyle](https://www.frontendmentor.io/profile/CSE-Kyle)
- Linkedin - [Kyle Deguzman](https://www.linkedin.com/in/kyle-deguzman-aa8a2b194/)

## Acknowledgments

Big thanks to the following people for their assistance : 

- Grace-Snow (Moderator of Frontend Mentor)
- AlexKMarshall (Moderator of Frontend Mentor)
- The Frontend Mentor community 🙌🏼