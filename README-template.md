# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Screenshot](./images/screenshot1.png)

### Links

- Solution URL: [Solution](https://pedro-cella.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I learned how to use the filter properties of CSS, and how to position text and image side-by-side. Beyond that I learned the advantages of creating a class.

```html
<div class="card">
        <p class="first-text">Get <b class="mark-word">insights</b> that help<br> your business grow.</p>
        <p class="second-text">Discover the benefits of data analytics and make<br>
        better decisions regarding revenue, customer<br>
        experience, and overall efficiency.</p>
        <ul class="list">
            <li>
              <p class="first-item">10k+</p>
              <p class="second-item">companies</p>
            </li>
            <li>
              <p class="first-item">314</p>
              <p class="second-item">templates</p>
            </li>
            <li>
              <p class="first-item">12M+</p>
              <p class="second-item">queries</p>
            </li>
        </ul>
      <div class="right-card">
        <img src="./images/image-header-desktop.jpg" class="image">
      </div>
    </div>
```
```css
.list {
  list-style: none;
}

.list li {
  float: left;
  margin-top: 80px;
  margin-left: 80px;
}
```


- [How to use filter property](https://developer.mozilla.org/pt-BR/docs/Web/CSS/filter-function) - This helped me understand how to use the filter property and witch options i had, not only that but it gave me the insight to use opacity in the image, to create the purple color in the image itself
## Author

- Name - Pedro Vítor de Salles Cella
- Frontend Mentor - [@pedro-cella](https://www.frontendmentor.io/profile/pedro-cella)
- Github - [pedro-cella](https://github.com/pedro-cella)