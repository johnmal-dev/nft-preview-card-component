# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
<!-- - [Acknowledgments](#acknowledgments) -->

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/screenshot.png)

### Links

- Solution URL: [github.com/johnmal-dev/nft-preview-card-component](https://github.com/johnmal-dev/nft-preview-card-component)
- Live Site URL: [johnmal-nft-preview-card-component.netlify.app](https://johnmal-nft-preview-card-component.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- PureRef Images App
- Less CSS

### What I learned
- How to implement hover states
```html
<div class="cover-container">
  <div class="img-overlay">
    <img src="/images/icon-view.svg" alt="view">
  </div>
</div>
```
```css
main .card .cover-container {
  cursor: pointer;
  width: 100%;
  aspect-ratio: 1;
  background: url(/images/image-equilibrium.jpg);
  background-size: contain;
  border-radius: 0.5rem;
}
main .card .cover-container .img-overlay:hover {
  background: #00fff7;
  opacity: .6;
  border-radius: 0.5rem;
}
```
### Continued development

Implementing the hover state was difficult. I used the original image as a background, and the view icon as an img element with an initial opacity of 0. I need to spend more time finding a more ideal way to implement this.

### Useful resources

- [PureRef](https://www.pureref.com/) - This helped me compare my work to the provided example images. I really liked this app and will use it going forward.
- [Less CSS](https://lesscss.org/) - Less (which stands for Leaner Style Sheets) is a backwards-compatible language extension for CSS. This made for a quicker, cleaner CSS coding experience.
- [Koala App](http://koala-app.com/) - Koala is a GUI application for Less (and other preprocessors!) that automatically converts my .less files to .css files.

## Author

- Website - [John Malapit](https://www.johnmal.dev)
- Frontend Mentor - [@johnmal-dev](https://www.frontendmentor.io/profile/johnmal-dev)
- Twitter - [@johnmal_dev](https://www.twitter.com/johnmal_dev)

<!-- ## Acknowledgments -->