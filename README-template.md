# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot of the responsive product preview card
<img width="573" alt="Screenshot 2022-11-19 at 5 59 52 PM" src="https://user-images.githubusercontent.com/67844566/202876452-7901dc68-85ec-4664-8418-671d7cfcd879.png">
<img width="1619" alt="Screenshot 2022-11-19 at 6 00 45 PM" src="https://user-images.githubusercontent.com/67844566/202876455-3108c110-9473-4382-b89b-9ecdb8b90873.png">

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

How to get closer to a replication of the original image pixel x pixel. I also learned how to utilize the @media for more responsiveness at multiple sceen sizes, see below:

```
@media only screen and (max-width: 375px){
    .container {
        margin: 15px auto;
        padding: 0 15px;
    }
    .img img {
        max-height: 290px;
    }
    .card-info{
        padding: 24px;
    }
    h6.product-category, h2.product-name, .price {
        padding-bottom: 16px;
    }
    h2.product-name {
        font-size: 28px;
    }
    p.product-description{
        font-size: 12px;
    }
    p.current-price {
        font-size: 23px;
    }
    button.cart-btn {
        padding: 12px 0;
        font-size: 13px;
    }
}
```
