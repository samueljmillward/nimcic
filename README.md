# NIMCIC - Static Site

A simple, static website built with HTML and SCSS.

**NIMCIC** are the New Islington Marina Community Interest Company, a collective representing the residents of New Islington Marina and their future improvement plans for their residence.

### BEM

I wanted to try something new for writing CSS with this project. I had read about the way in which Block Element Modifier notation handles specificity and the form of 'scope' it provides with unique CSS classes.

It's unfortunately let down by how bloated it can become... I recognise there is currently no solution for this due to there being no way to get around inheritance other than writing unique classes for an element.

### Linting and Formatting

The code is formatted using **[Prettier](https://github.com/prettier/prettier)** and linted using **[ESLint](https://eslint.org/)**.

### Continuous Deployment

As changes are merged into the `master` branch, the page will automatically build using **[Netlify](https://netlify.com/)**. It is then deployed using the Netlify CDN.
