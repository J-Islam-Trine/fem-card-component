# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

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


## Overview
The challenge was to make a responsive product preview card component with a product image and text description.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

| ![desktop](./screenshots/desktop.png) | 
|:--:| 
| *Space* |


| ![mobile](./screenshots/mobile.png) | 
| :--: | 
| *Mobile*|



### Links

- Solution URL: [Card Component Repo](https://github.com/J-Islam-Trine/fem-card-component)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
1. Create a card container of fixed width and height using **CSS grid**.
2. Place two div inside and use Grid to divide them into same width portion.
3. Place image and set it to full height of it's parent.
4. Add an overlay on the image using css `filter` property.
5. Rearrange the text content and apply fonts.
6. Use grid to control the text and use *space-between* to take the full height.
7. Add svg icon on the button and use *vertical-align* to align it with the text of the button. 
8. Set button width to full width. 
9. Add mobile media query.
10. Unset fixed height by setting it to *auto* inside mobile media query.
11. Set `grid-template-columns` to *auto* and use grid-template-rows to arrange the divs vertically. 
12. Use `object-fit`to get the effect.
13. Reduce padding for the text for mobile. 


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned
1. CSS grid is the better solution for same size *divs*.
2. CSS flexbox is so simple and it works better when you need a solution for simple things like inline elements.
3. When dealing with CSS, don't think in term of implementation, but think about the goal. 

### Continued development

* I didn't implement *tablet* layout. So there's a huge leap between media queries. 
* I want to adopt this one into a more advance thing, for example, may be learn Tailwind CSS with it.

### Useful resources

I have left hints about different resources in the *process* section. 

## Author

- Github: [Jahirul Islam](https://github.com/J-Islam-Trine)
- Frontend Mentor - [@j-islam-trine](https://www.frontendmentor.io/profile/J-Islam-Trine)


