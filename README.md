- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)



## Overview
small landing whith parallax effect when scrolling

### Screenshot

Main Theme
![](/screens/1.png)

scrolling
![](/screens/2.png)


### Links

- Live Site URL: (https://mrisee.github.io/creative-scroll/)


### Built with

- HTML
- CSS
- Flexbox
- JS
- gsap

### What I learned

using gsap,
```js
let itemsL = gsap.utils.toArray('.gallery__left .gallery__item')

itemsL.forEach(item => {
    gsap.fromTo(item, {x: -50, opacity: 0}, {
        opacity: 1, x: 0,   
        scrollTrigger: {
            trigger: item,
            start: '-850',
            end: '-100',
            scrub: true
        }
    })
});
```

first time used 
```css
@font-face {
    font-family: raleway-c;
    src: url(../fonts/raleway-regular.woff2);
}
```


## Author
Nikita Kholodov 

- Website - [Mrisee](https://github.com/Mrisee)
- inst - @feelskhold

Russia, Krasnodar.


