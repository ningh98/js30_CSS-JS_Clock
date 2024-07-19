# js30_CSS-JS_Clock

This is a 30-days javascript grinding
2. Clock [https://ningh98.github.io/js30_CSS-JS_Clock/]

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)


## Overview

This project creates a functional, analog clock using HTML, CSS, and JavaScript. The clock updates every second to show the current time.

### Screenshot

![](./screenshot.png)

### Links

- Live Site URL: [https://ningh98.github.io/js30_CSS-JS_Clock/]

## My process

### Built with

- HTML
- CSS
- Javascript



### What I learned


```css
  .hand {
    transform-origin: 100%;
    transform: rotate(90deg) ;
    transition: all 0.5s;
    transition-timing-function: cubic-bezier(0, 2.76, 0.28, 0.27)
  }
```
learn more about tranfform and transition


### Continued development

Minutes and hours hand in real live should be move differently from this one. The size of minutes and hours hand should look differently from the seconds hand as well. The are some glitches happen every 60 seconds entering to next minutes. Those are some things we could improve in the future.
