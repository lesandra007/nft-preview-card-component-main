# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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
- See hover states for interactive elements

### Links

- Solution URL: [https://github.com/lesandra007/nft-preview-card-component-main](https://github.com/lesandra007/nft-preview-card-component-main)
- Live Site URL: [https://monumental-dasik-9f9e05.netlify.app/](https://monumental-dasik-9f9e05.netlify.app/)

## My process

### Built with

- Visual Studio Code - To write code
- Netlify - To deploy website

### What I learned

How to overlay images:

To see how you can add code snippets, see below:

```html
<div class="cube">
        <article class="main-img">
          <img src="images/image-equilibrium.jpg" alt="a blue/orange cube with a blue background">
          <div class="overlay">
            <img src="images/icon-view.svg" alt="">
          </div>
        </article>
        
        
      </div>
```
```css
.main-img{
    position: relative;
    overflow: hidden;
    display: block;
}

.overlay{
    position: absolute;
    left: 0;
    top: 0;
    height: 100%;
    width: 100%;
    background-color: hsla(178, 100%, 50%, 0.5);
    display: none;
}

.main-img:hover .overlay{
    display: block;
    cursor: pointer;
}

.overlay img{
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
}
```

### Useful resources

- [Solution by Mr. Coder](https://youtu.be/l6sxh57ifSQ) - This helped me implement the overlay images.
- [Solution by TsbSankara](https://youtu.be/9bGbykdR4T8) - This helped me implement the overlay images.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Github - [lesandra007](https://github.com/lesandra007)

## Acknowledgments

I took inspiration from Mr. Coder and TsbSankara's solution to overlay images.
