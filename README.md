# Frontend Mentor - Single price grid component solution

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/single-price-component-using-css-grid-cvNZeGgr5R)
- Live Site URL: [Add live site URL here](https://fxanz.github.io/Frontendmentor-Product-Preview-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

have a better understanding of responsive card design

```html
<div class="container">
  <main>
    <div class="img">
      <img src="" alt="" />
    </div>
    <div class="card-content">
      <h1></h1>
      <h2></h2>
      <p></p>
      <ul>
        <li class="price-1"></li>
        <li class="price-2"></li>
      </ul>
      <button class="button"><img src="" alt="" /></button>
    </div>
  </main>
  <footer>
    <p class="attribution">
      Challenge by <a href="" target="">Frontend Mentor</a>.
      <br />
      Coded by <a href="#">Fxanz</a>.
    </p>
  </footer>
</div>
```

have a better understanding of using grids to separate images and text

```css
@media only screen and (max-width: 650px) {
  main {
    grid-template-columns: 1fr;
  }
}
```

### Continued development

i will try learn more about when is the best for using grid / flex and need more understanding for flexbox


## Author

- Frontend Mentor - [@fxanz](https://www.frontendmentor.io/profile/fxanz)
- Twitter - [@IFxanz](https://twitter.com/IFxanz)
