# Expanding-cards


This is apart of the 50 projects in 50 days challenge and this is the first project.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

- To create expanding cards which would expand when clicked. The challenge involves HTML, CSS and Javascript.

### Screenshot

# Mobile Preview 

![screenshot]()

# Desktop Preview 

![screenshot]()


### Links

 - Source code: [https://github.com/romila2003/Expanding-cards](https://github.com/romila2003/Expanding-cards)
 - Live website: [https://romila-expanding-cards.netlify.app/](https://romila-expanding-cards.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Plain CSS
- Vanilla Javascript
- Flexbox

### What I learned

I improved on my flexbox skills regarding centering the elements. I also learned new concepts with javascript such as `forEach`.

CSS - Flexbox: 

```css

body {
    font-family: 'Muli', sans-serif;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
}

```

Javascript - forEach:

```javascript

panels.forEach((panel) => {
    panel.addEventListener("click", () => {
        removeActiveClasses()
        panel.classList.add("active");
    })
})

```

### Continued development

For future developments, I should learn more concepts of javascript and implement those within new projects.


## Author

- Twitter - [@romila003](https://www.twitter.com/romila003)
