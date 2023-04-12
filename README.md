# Frontend Mentor - Stats Preview Card Component Solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).  
Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

\*Me\* : I agree 👍

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Hardest Part](#hardest-part)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
- [Tools](#tools)
- [Author](#author)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![My Fabulous Work!](./screenshot.png)

### Links

- Solution URL: <https://www.frontendmentor.io/solutions/garlic-squirrel-KqMJYsiuNz>
- Live Site URL: <https://stats-preview-card-component-sol-1234.netlify.app>

## My Process

### Hardest Part

Getting the `picture` to behave as I want. It was quite frustrating. But I'm happy with the result now.

### What I Learned

Container queries are extremely astounding!

Also, if your browser supports container queries, you might notice that removing <code>isolation:&nbsp;isolate;</code> from `.card` won't alter anything at all. Looks like `container-type` can create a new stacking context by itself. Yet, `isolation` is still needed for browsers that don't support container queries. So it's not there for no purpose --like, of course. But it would still break in IE either ways, though.&nbsp;🙃

### Continued Development

I need to spend more time studying CSS's fundamental principles and concepts.

## Tools

- [Dev Docs](https://devdocs.io) - The resource I was constantly referring to throughout the process. It's an offline web app that has a huge collection of documentations.
- [Brackets](https://brackets.io) - My text editor. Not as powerful as VS Code, but still my favorite.
- Chrome - This web page was only tested on Chrome. 

## Author

- GitHub - [Mahdi Aljaza'iri](https://github.com/MahdiAljazairi)
- Frontend Mentor - [@MahdiAljazairi](https://www.frontendmentor.io/profile/MahdiAljazairi)

