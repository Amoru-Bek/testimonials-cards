# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor]. 

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

![](./images/Screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/Amoru-Bek/responsive-landing-page)
- Live Site URL: [Add live site URL here](https://amoru-bek.github.io/responsive-landing-page/)

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

I've learned how to create a responsive landing page by using media queries and responsive layout principals 

```html
<div class="card-img-wrapper">
      <picture>
        <source srcset="./images/image-product-desktop.jpg" media="(min-width: 768px)">
        <source srcset="./images/image-product-mobile.jpg" media="(min-width: 300px)">
        <img src="./images/image-product-mobile.jpg" alt="perfum-image">
      </picture>
      </div>
    </div>
```

```css
@media(min-width: 768px){
    .ncard{
        flex-direction: row;
        gap: 1.5rem;
        width: min(85%,48.5rem);
        margin-top: 2.4rem;
    }
    .card-img-wrapper{
        flex: 1 1 40%;
        aspect-ratio: 3 / 4;
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
