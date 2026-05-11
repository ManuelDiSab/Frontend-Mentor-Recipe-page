# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8s60o). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-learned)
- [Author](#author)

## Overview

### The challenge

The challenge was to build a responsive recipe page that looks as close to the original design as possible. The page features a clean layout with specific typography, lists, and a nutritional table.

### Screenshot

![Desktop(1440px) design preview](./design/desktop-design.jpg)
![Mobile(375px) design preview](./design/desktop-design.jpg)


### Links

- Solution URL:(https://github.com/ManuelDiSab/Frontend-Mentor-Recipe-page)
- Live Site URL: (https://recipe-page-frontendmentorbymanueldis.netlify.app/)


### Built with

- Semantic HTML5 markup
- SASS/SCSS
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

During this project, I significantly improved my understanding of CSS layout and structure. Some key takeaways include:

1. **Semantic HTML**: Using `<article>`, `<section>`, and `<table>` to create a meaningful document structure.
2. **Pseudo-elements**: Learning how to use `::before` and `::marker` to customize list bullets and align them perfectly using Flexbox.
3. **CSS Specificity**: Understanding how nesting in SASS affects specificity and how to resolve conflicts without relying on `!important`.
4. **Mobile-First Workflow**: Managing the "full-bleed" image effect on mobile vs. the padded card layout on desktop.

### author

- Manuel Di Sabatino
- My website: http://www.manueldisabatino.it

Example of a custom bullet implementation in SCSS:
```scss
li {
    display: flex;
    align-items: center;
    gap: 20px;
    &::before {
        content: '';
        width: 4px;
        height: 4px;
        background-color: var(--rose-800);
        border-radius: 50%;
        flex-shrink: 0;
    }
}


