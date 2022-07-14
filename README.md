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
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: (https://www.frontendmentor.io/solutions/responsive-order-summary-component-EbZt1iSJqr)
- Live Site URL: (https://frontendmentor-ordersummarycomponent-solution.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned that sometimes it takes layering of "boxes" to achieve the desired layout that you are looking for. Some elements are nested in a div, that is within another div. This allows me to properly place items and align them to how it's supposed to look. 

```html
<div class="order">
          <img src="/images/icon-music.svg" alt="Music icon">
          <div class="pricing">
            <h4>Annual Plan</h4>
            <p>$59.99/year</p>
          </div>
          <a href="">Change</a>
        </div>
```

Also, with the styling, used max-width to ensure responsiveness when the screen width changes. Implemented clamp() functions to change font-sizes when the screen width change

```css
.box {
      background-color: white;
      max-width: 375px;
      height: 600px;
      border-radius: 20px;
    }
h2 {
      text-align: center;
      margin: 2rem 1rem 0.5rem;
      font-weight: 900;
      font-size: clamp(1.5rem, 2.5vw, 2rem);
    }
```

### Continued development

In the future, I want to improve css styling. There are many aspects to css styling and it can get confusing to figure out what style you need to achieve your desired result.

## Author

- Website - [Jekari Rawls](https://jekarirawlsportfolio.netlify.app/)
- Frontend Mentor - [@yJekari99](https://www.frontendmentor.io/profile/Jekari99)