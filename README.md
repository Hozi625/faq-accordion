# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](/Users/apple/Desktop/Frontend Mentor  FAQ Accordion Card_1.jpg)

### Links

- Live Site URL: [Faq-Accordion site hosted by Netlify](https://gavin-faqaccordion-ca81f6.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

The basic structure of an accordion, with elements inside of elements.

Using `parentNode` to select the parent node. In this case:

```html
<div class="question-answer-accordion">
          <div class="question">
            <h3>Can I cancel my subscription?</h3>
            <img class='arrow' src='./images/icon-arrow-down.svg' />
          </div>
          <div class="answer">
            Yes! Send us a message and we’ll process your request no questions asked.
          </div>
</div>

<!-- 
  select all the .question class by using querySelectorAll, and using parentNode to target .question-answer-accordion
-->
```
### Useful resources

- [How to create an accordion](https://www.w3schools.com/howto/howto_js_accordion.asp) - This site helped me out with the basic structure of an accordion and how to toggle accordion

## Author

- Name - ChingHo (Gavin) Chan
- Frontend Mentor - [@Hozi625](https://www.frontendmentor.io/profile/Hozi625)


