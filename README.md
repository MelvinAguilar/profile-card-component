# Frontend Mentor - Profile card component solution

![](./design/desktop-preview.jpg)

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

- Build out the project to the designs provided

## My process

### Built with

- Semantic HTML5 markup
- Flex Layout
- BEM naming convention
- [SASS](https://sass-lang.com/documentation/modules) - Sass modules


### Useful resources

- [CSS Guidelines](https://cssguidelin.es/#bem-like-naming)
- [BEM naming convention](https://css-tricks.com/bem-101/)
- [BEM naming examples](https://getbem.com/naming/)

- [Material Design Box Shadows](https://codepen.io/sdthornton/pen/wBZdXq)
- [CSS background Property](https://www.w3schools.com/cssref/css3_pr_background.asp)
- [CSS Multiple Backgrounds](https://www.w3schools.com/css/css3_backgrounds.asp)
- [How to place background image using ::before pseudo selectors](https://www.geeksforgeeks.org/how-to-place-background-image-using-before-pseudo-selectors-in-css/)

- [Solving Sticky Hover States with @media (hover: hover)](https://css-tricks.com/solving-sticky-hover-states-with-media-hover-hover/)

## Author

- Frontend Mentor - [@melvinaguilar](https://www.frontendmentor.io/profile/melvinaguilar)

## Acknowledgments

When using `sass` in order to build this solution

- Install `sass` if not yet installed:

```bash
npm install -g sass
```

- Run build command from command line:

```bash
sass assets/sass/main.scss assets/css/style.css
```

- If you want to edit the code and test, in the root folder of this repository, run this command from the command line:

```bash
sass --watch assets/sass/main.scss assets/css/style.css
```

## File structure

```
.
├── assets
│   ├── css
│   │   ├── style.css
│   │   └── style.css.map
│   ├── images
│   │   ├── bg-pattern-bottom.svg
│   │   ├── bg-pattern-card.svg
│   │   ├── bg-pattern-top.svg
│   │   ├── favicon-32x32.png
│   │   └── image-victor.jpg
│   └── sass
│       ├── abstracts
│       │   ├── _mixins.scss
│       │   └── _variables.scss
│       ├── base
│       │   ├── _page.scss
│       │   └── _reset.scss
│       ├── component
│       │   ├── _heading.scss
│       │   └── _screen-reader.scss
│       ├── layout
│       │   └── _profile-card.scss
│       └── main.scss
├── design
│   ├── desktop-design.jpg
│   ├── desktop-preview.jpg
│   └── mobile-design.jpg
├── index.html
└── README.md
```