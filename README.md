# JavaScript30-5
This is a JavaScript 30 Challenge. Challenge #5 - Flex Panel Gallery
 
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

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![Project Screenshot](./Screenshot.png)


### Links

- Solution URL: [https://github.com/kryde507/JavaScript30-5](https://github.com/kryde507/JavaScript30-5)

## My process

### Built with

- Vanilla JavaScript
- CSS Flexbox

### What I learned

In this project I practiced using flexbox, especially in nested situations. I learned how to transition items from off screen, and I also learned how to time things to happen after other transitions have finished.


The following JavaScript snippet is used to ensure that the active class is applied only after the initial transition has occured:
```js
 function toggleActive(e) {
            if (e.propertyName.includes('flex')) {
                this.classList.toggle('active');
            }
        }
```


### Continued development

I would like to get better at knowing when to next flexbox containers inside one another. I would also like to continue practising transitions. 

### Useful resources

- [CSS Tricks Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is a resource I often refer to when I need flexbox assistance.

## Author

- GitHub - [KRyde507](https://github.com/kryde507)

