# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

This project gathers testimonials of some full stack developers that learned code through **TAs teaching on Bootcamp**.

They have been encouraged to join this community by students already in. Ensuring them of how amazing and improving are the program. Though some of them  didn't have a clues how to write a single line of code. Once in, the team support and the quality of program make the newbies improve theirs skills to code rapidly, as if they got *a secret weapon or fight training* you know. 

This ensurance lead them to be now grateful to the team of Bootcamp, and to recommend this platform to everyone willing to grow like a programmer, because, according to what they say: the journey is fascinating , make you reach a better level without the need of tutorial, make you build a steady curriculum and also grant you access to some of the recognized Tech companies like themselves have done.
  

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./Scr Frontend Me [Testimonials Grid Section])


### Links

- Solution URL: [https://github.com/BeinRain06/Testimonials-grid-section.git]
- Live Site URL: [https://beinrain06.github.io/Testimonials-grid-section/]

## My process

### Built with

- Semantic HTML5 markup

- Flexbox
- CSS Grid


### What I learned

Grid is a Powerful tool when comes to deal with articles or images displayed in cards. I reviewed css grid corner properties as **grid column** and **grid row**.
I also added some css transform Properties to animate both picture's and name's witnessing.
here we could see below my animation small snippets code: 

```css
.witnessing .name h4{
  transition: all 1.2s ease-in;
  
}

.witnessing .n_light h4:hover{
  transform:  scale(1.1) translateX(10px) skewX(-15deg);
  color: #5ea056;
}
.witnessing .n_dark h4:hover{
  transform:  scale(1.1) translateX(10px) skewX(-15deg);
  color: #b165a7;
}

.witnessing .witness:hover{
  transform: scale(1.1) skewX(-5deg) translateX(-5px);
}
```

### Continued development

Grid is in some case the tool to manage to organize videos and contents altogether like in small apps. I think it's suitable to become accustomed to it.


## Author

- Website - [Ngouend Raoul Gerard](https://github.com/BeinRain06)
- Frontend Mentor - [@BeinRain06](https://www.frontendmentor.io/profile/BeinRain06)
- Twitter - [@nest_Ngoueni](https://www.twitter.com/yourusername)




