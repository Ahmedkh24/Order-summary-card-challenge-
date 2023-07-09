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

## Overview

My challenge was to build out this order summary card component using HTML5 and CSS.

### The challenge

Users should be able to:

- See hover states for interactive elements

### Links

- Solution URL: https://github.com/Ahmedkh24/Order-summary-card-challenge-/tree/main
- Live Site URL: https://ahmedkh24.github.io/Order-summary-card-challenge-/

## My process

- I set the universal selector to make the margin 0, padding 0, and the box-sizing to border-box
  and changed to font size in the html selector to 10px to make it easy for me to use the rem unit.

- I made a section and gave it a fixed width and centered it using flex-box and gave it a height of 100Vh

- Inside the section, there are 2 parts, one for the image and the second for the Heading, pricing, links, and other information.

-I made the image fit into the first part of the section by setting the width property to 100%

- Inside the header element there is a div container for the H1 and the first paragraph, I changed the color for both of them and also the font size for the paragraph and made it 16px=1.6rem and also the font weight, and included them in another div and used the flex-box property to center them vertically and gave a gap to make a space between them instead of using margin property.

- The second part, I included the rest of the elements in an article element and started working on them, for the pricing part, I made a div container for the icon, pricing information, and the change link and made another div container for the pricing container and used the flex-box property to align them horizontally and also included the span and p elements which include the pricing information in another div container and used the flex-box property to align them vertically, and changed the background color of the container and the font size of the span, paragraph and the change link.

- I made another div for the other links and gave them padding and margin and also changed the background color and the color of them and used some pseudo-classes such as hover, active, visited, and link to change the hovering state of them and used the transition property to make them change smoothly while hovering over them.

- I used the box-shadow property to give the card a shadow and also on one of the links which is acting like a button now.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

In this challenge, I learned how to use flex-box and many new CSS properties such as "max-width", "text-decoration", "over-flow", "box-shadow", "transition" and some Pseudo classes such as ": hover, active, link, visited ".

### Continued development

This is my second project and I'm very excited to learn more and more about CSS and make my foundation more solid in HTML5 and CSS by doing more projects.
