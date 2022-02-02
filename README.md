# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

This is a project that I wanted to complete using nothing but HTML and CSS. I started with a framework but wanted to solidify my CSS learning but doing vanilla CSS only. It has proven to be an excellent challenge. 

### The challenge
My challenge was to build out the order summary card component and get it looking as close to the design as possible.

Users should be able to:

- See hover states for interactive elements

### Screenshot

[Desktop Screenshot]()
[Mobile Screenshot]()

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
  
I built out the HTML semantic markup first, creating my classes, then moving into the CSS stylesheet where I worked each component completely before moving onto the next one. Some hiccups arose, as they do, but with the help of my mentor and code reviewer we were able to work past those together. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

To see how you can add code snippets, see below:

This was with the help of Nikki, my code reviewer and mentor. What I found on W3schools.com had the card before the container but that did not 
result in the desired outcome.
```html
<div class="container">
    <div class="card">
      <img src="/images/illustration-hero.svg" class="main-image" alt="dancing to music">
        <div class="text-container">
```

I learned this as <br> was not allowing my main paragraph to line up as intended.
```css
p {
   white-space: pre-line;
}
```
### Continued development

I working on more CSS based projects as my goal is to ensure I have a firmer understaning in how child and psuedo elements work. I also need to contiue to learning with mobile first worflow, as the background was not working properly but showing only the mobile on desktop. 

### Useful resources

- [The mysterious 4px gap in between images](https://www.codeblocq.com/2016/09/The-mysterious-4px-gap-in-between-images/) - I ran into a mysterious gap between the main image and my container for the card. After researching together, Nikki found this article and it really helped me understand that the was due to the default display: inline block that occurs with images. To remove this, some changing of HTML classes was done and then putting the image in a display: block, resolved the issue. This is vital and something that I want to remember going forward.

## Author

- Frontend Mentor - [@CraftyBecky](https://www.frontendmentor.io/profile/CraftyBecky)
- Twitter - [@BeckyMCD7](https://www.twitter.com/BeckyMcD7)

## Acknowledgments

I want to acknowledege the help of my friend and mentor, Nikki Morely. She and I sat down over Google Meets and she helped me figure out this strange mystery gap in between the card and container elements that was really bothering me the most with this project. She wrote out some code to make for less code, and explained one of the important pieces I was missing, the display:block. 

