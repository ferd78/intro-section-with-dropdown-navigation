# Quiz 2 - Intro section page with interactive dropdown menu solution

This is a solution to the [Intro section page with interactive dropdown menu Quiz 2 challenge]

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

### The challenge

Users should be able to:

- View the relevant dropdown menus on desktop and mobile when interacting with the navigation links
- View the optimal layout for the content depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/quiz.png)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

I have learned some advance techniques in JavaScript that helped me form a functional drop-down button using .addEventListener. In addition, the @media in css helped me create a responsive website.

```css
@media(min-width:375px){
    body{
        background: var(--AlmostWhite);
    }
    body .default{
        display: none;
        opacity: 0;
    }
    header{
        padding: 1.5rem 3rem;
        justify-content: center;
    }
    header .logo{
        margin-top: .5rem;;
}
```
```js
dropdown.forEach(function(item){
    item.addEventListener('click',function(){
        item.parentElement.classList.toggle('link-open');
    })
})
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development
Ever since I have known front-end development, I wanted to explore more javascript techniques that could ultimately increase the functionality of my website. In the futurem I would like to implement my javascript file with jQuery and also React JS

### Useful resources

- [W3Schools](https://www.w3schools.com/) - This website helped me create a functional hover and also drop-down button

## Details 

- FullName - Felix Ferdinand
- StudentID - 2602108842
- BINUS Email - felix.ferdinand001@binus.ac.id

## Acknowledgments

W3Schools is a really good website for beginners to explore their coding potential. Even if there are better websites that explains the way front-end development work better.
