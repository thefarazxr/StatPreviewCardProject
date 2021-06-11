# Frontend Mentor - Stats preview card component solution
# Static Responsive(!tablets) Website using just HTML, CSS

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)



## Overview
This is a pure HTML, CSS based project which helps you understand how to design a mobile friendly website and also using basic HTML tags etc.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- Made this project view good on Desktop, Mobile. I need to still work for the tablet(iPad's) size.

### Screenshot
![Screenshot](./assets/images/screenshot.png)

Pro tip 😎  :Use [Fireshot](https://chrome.google.com/webstore/detail/take-webpage-screenshots/mcbpblocgmgfnpjjppndjkmgjaogfceg?hl=en) (a FREE extension to take screenshots of an entire webpage)
### Links

- Live Site URL: [StatPreviewCard](https://thefarazxr.github.io/StatPreviewCardProject/)

## My process
I started with by adding HTML tags and div's to help in styling the page.
Then moved to the CSS part & I started as Desktop-first design.

Later added **Mobile Media Queries**

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow


### What I learned
Learnt how to use *FontFamily*, *Letter-spacing*, *Text Transform*, *using different images based on screen width* etc..


```html
<!-- HTML for displaying different images based on screen width-->
<picture>
                <source srcset="./assets/images/image-header-mobile.jpg" media="(max-width: 375px)">
                <source srcset="./assets/images/image-header-desktop.jpg">
                <img src="./assets/images/image-header-desktop.jpg" alt="talks" style="width:auto">
            </picture>
        </div>
```
```css
/* CSS to give image a TINTED effect*/
.image {
    float: right;
    margin-bottom: -5px;
    background-color: hsl(277, 73%, 32%);
    border: 0px solid;
}

img {
    opacity: 0.4;
}
}

/*CSS to set elements in same-line and use width to show in 2 lines
used for 10k+ COMPANIES, 314 TEMPLATES, 12M+ QUERIES.
*/
.one,
.two,
.three {
    display: inline-block;
    width: 100px;
}
/* To make image and text part on same line */
.image,
.text {
    display: inline-block;
}
```

### Continued development

I want to modify and make this static page more responisve by adding on Tablet size for making the page more responsive.

Also will later learn js and try to implement in all of my static-page projects.

### Useful resources

- [W3Schools](https://www.w3schools.com/css/css_rwd_images.asp) - This helped me for displaying different image based on screen width.
- [Letzcode](https://www.letzcode.in/HtmlCss/4_script.php) - This is an amazing article which helped me finally add the Image Tinting effect.

## Author

- Website - [Faraz](https://www.thefarazxr.com)
- Frontend Mentor - [@thefarazxr](https://www.frontendmentor.io/profile/thefarazxr)
- Twitter - [@thefarazxr](https://www.twitter.com/thefarazxr)

## Acknowledgments
I would recommend everyone to take a **NOTE** on the go while building the prject and try to write a **JOUNRAL** of your Developmment journey so that it would help others and also you.

Because,
># **Don't compare yourself with other instead compare yourself with your previous version.**
