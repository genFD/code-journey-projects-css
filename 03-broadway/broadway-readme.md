# Broadway

## Table of contents

- [✅ Project completed](#project-completed-repo)
- [⌛️ Project starter](#project-starter-repo)
- [🧩 Concepts](#concepts-to-review-for-this-project)
- [🎯 Learning goal](#learning-goal)
- [💻 Application Overview](#overview)
  - [📸Screenshot](#screenshot)
  - [🥷🏽 The challenge](#the-challenge)
  - [🔗Links](#links)
- [🪜 Tasks](#tasks)
- [Built with](#built-with)
- [📕 What I learned](#what-i-learned)
- [⏭️ Continued development](#continued-development)
- [📚 Useful resources](#useful-resources)

## Project completed repo

- check out the code here `->` [completed](https://github.com/hermkan/code-journey-projects-css/tree/main/03-broadway/completed)

## Project starter repo

- check out the code here `->` [starter](https://github.com/hermkan/code-journey-projects-css/tree/main/03-broadway/starter)

## Concepts to review for this project

- Display and positioning

## Learning Goal

- Apply knowledge of Display and positioning

## Overview

### Screenshot

![Design preview for Broadway](./broadway-.png)

### The challenge

The challenge is to build out this page and get it looking as close to the design as possible.
Some styling was added to the page in `style.css`

### Links

- Live Site URL: [Broadway](https://code-journey-projects-css-display-positioning.vercel.app/)

## Tasks

- The `<header>` currently scrolls with the rest of the document. Set its position property so that it stays stuck to the top of the window when the document is scrolled.

> We can fix an element to a specific position on the page (regardless of user scrolling) by setting its position to fixed

- The `<header>` has shrunk! Change the width of the same element so that it stretches across its entire parent element.

- List items (`<li>`) inside of the navigation section (`<nav>`) are currently displayed as a list. Set their display property so that they can appear next to each other horizontally (but so that you still set their width in the next task).

<details>
  <summary>Solution</summary>
  
  `<li>` is a block level element

See -> [Block level elements](http://www.devdoc.net/web/developer.mozilla.org/en-US/docs/HTML/Block-level_elements.html)

and

> Block level elements are not displayed in the same line as the content around them. They fill the entire width of the page by default, but their width property can also be set.

-> Inline elements have a box that do not not require a new line after each element. `The height and width of these elements cannot be specified in the CSS document`.

There's a way to combine features of both inline and block elements (display on the same line and keep the ability to set the width) :

-> **Using Inline-block.**

Inline-block elements can appear next to each other. We can specify their dimensions using the width and height.

</details>

- Set the width of the same elements to `80 pixels`.

- After changing the position of the `<header>` element to fixed, the contents of the entire site after it shifted upwards. Set the position of `<main>` so that we can position it relatively.

<details>
<summary>Solution</summary>
Position relative position an element relative to its default static position on the web page. It's possible to add to the position declaration, an offset properties that will move the element away from its default static.
- `top`
- `bottom
- left
- right
</details>

- The `<header>` has disappeared behind the `<main>`. Use z-index to make the`<header>` visible

- Now the navigation bar looks good, but it is blocking the title at the top of the page. Offset `<main>` by 80 pixels from the top.

- Now, fix up the supporting element style below the image. Add a declaration to the `.supporting .col` rule set so that these elements can appear horizontally next to each other but have defined height and width.

- Inspect the `.supporting .col` elements—they don’t seem to be flowing horizontally yet because they have no set width. Set the width and height of .supporting .col elements to 200 pixels.

## Built with

- Semantic HTML5 markup
- CSS

## What I learned

## Continued development

## Useful resources
