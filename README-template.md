# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

 
## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/desktop-screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/Amoru-Bek/testimonials-cards)
- Live Site URL: [Add live site URL here](https://amoru-bek.github.io/testimonials-cards/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Bootsrap](https://getbootstrap.com/) - CSS Framework
- [Font awsome](https://fontawesome.com/) - Icon libery
- [google fonts](https://fonts.google.com/) - For text fonts


### What I learned

I've learned how to create a responsive landing page by using media queries Flexbox and Grid . 

```html
<div class="card" style="background-color: hsl(217, 19%, 35%); grid-area: jonathan;">
    <div class="autor-info">
      <img src="./images/image-jonathan.jpg" alt="Jonathan">
      <div class="autor-detail">
        <h3>Jonathan Walters</h3>
        <h5>Verified Graduate</h5>
      </div>
    </div>
    <h1 class="title">The team was very supportive and kept me motivated</h1>
    <p class="description">
      " I started as a total newbie with virtually no coding skills. I now work as a mobile engineer for a big company.
        This was one of the best investments I've made in myself. "
    </p>
  </div>

```

```css
@media(min-width:1024px){
    .card#daniel {
        background-image: url(./images/bg-pattern-quotation.svg);
        background-repeat: no-repeat;
        position: relative;
        background-size: 25% auto;
        background-position: center right ;
        background-position: top 10px right 100px;
    }
    .card-container{
        display: grid;
        grid-template-columns: repeat(2,1fr);
        grid-template-areas: "daniel jonathan"
                    "patrick jeanette"
                    "kira kira";
    }
}
```


### Useful resources

- [Web.dev](https://web.dev/) - A useful website that can help you build beautiful, accessible, fast, and secure websites that work cross-browser .
- [w3schools](https://www.w3schools.com/) - A great place to learn web development and coding .


## Author

- Github - [@Amrou-Bek](https://github.com/Amoru-Bek)
- Frontend Mentor - [@Amrou-Bek](https://www.frontendmentor.io/profile/Amoru-Bek)
- Linkedin - [@Amrou-Bek](https://www.linkedin.com/in/amrou-bekhedda-99b314341/)


## Acknowledgments

Thanks God and Thanks Frontend mentor .
