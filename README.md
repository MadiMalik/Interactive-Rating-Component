# Frontend Mentor - Interactive rating component solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Select and submit a number rating
- See the "Thank you" card state after submitting a rating

### Screenshot

![](images\Screenshot.png)
## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow


### What I learned

```JS
function submitForm(e){
    e.preventDefault();
    
  const resultsPage = document.querySelector("[data-result]");
  const ratingsForm = document.querySelector("[data-form]");
  ratingsForm.classList.add("hide");
  resultsPage.classList.remove("hide");
}
 ```
 I take pride in the submitForm() function of my code because it prevents the default behavior of the form submission by using e.preventDefault(). It also effectively selects and hides the ratings form using ratingsForm.classList.add("hide") and reveals the results page using resultsPage.classList.remove("hide"). This function ensures a smooth user experience and enhances the functionality of the form.
`

### Continued development
As a newcomer to JavaScript, I found it quite challenging to write the JavaScript portion of the code. However, I recently discovered that HTML elements can be selected using attributes, which has been helpful in my coding.

### Useful resources

- [resource 1](https://developer.mozilla.org/en-US/docs/web/html/attributes/disabled) This article taught me about the disabled attribute. I gained an understanding of how it can be used in HTML to disable form elements or buttons and prevent user interaction
- [resource 2](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) -I came across an excellent article that helped me gain a better understanding of arrays. It was very informative and I highly recommend it to anyone who is still learning this concept.

## Author

- Website - [Add your name here](https://madimalik.netlify.app/)
- Frontend Mentor - [@MadiMalik](https://www.frontendmentor.io/profile/MadiMalik)
- Twitter - [@MadiidevMad](https://twitter.com/MadiidevMad)

