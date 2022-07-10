# Scrimba - Travel Journal solution

This is a solution to the [Travel Journal solo project on Scrimba](https://scrimba.com/learn/learnjavascript/). Scrimba helps you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Requirements](#requirements)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Getting Started with Create React App](#getting-started-with-create-react-app)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Requirements

- Data array in a separate .js file
  - Title, description, price, cover image, rating, review count, location, open spots
- Use .map() and props
- Style & polished
- Mobile designed

### Screenshot

![screenshot](/src/screenshots/screenshot.png)

### Links

- Solution URL: [@GitHub](https://github.com/xdelmo/travel-journal)

### Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- React.JS
- Flexbox

### What I learned

This is my way to display dynamic divider between the second, third (and so on) card but not on the last one:

```css
.card {
  padding: 2em 0;
}

.cards-list > .card + .card {
  padding: 2em 0;
  border-top: 1px solid var(--clr-text-light);
}

.cards-list .card:first-child {
  padding-top: 0;
}

.cards-list .card:last-child {
  padding-bottom: 0;
}
```

### Useful resources

- [ReactJS](https://reactjs.org/tutorial/tutorial.html) - How to set up a local development environment on your computer
- [FontAwesome](https://fontawesome.com/v5/docs/web/use-with/react) - How to install FontAwesome packages for React

## Author

- Website - [Emanuele Del Monte](https://www.emanueledelmonte.it)
