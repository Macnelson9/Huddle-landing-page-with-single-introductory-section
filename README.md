# Huddle-landing-page-with-single-introductory-section
This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

I am overly excited to be able to execute this challenge almost perfectly. it is very close to the original design and I am proud of myself for that. I also made some minor tweaks also. Take a look!

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [FontAwesome] - For the social icons

### What I learned

I implemented custom animations and also how to add a gradient color to a text. You can find the codes below:

```css
h1:hover {
  animation: bounce 1s ease-in infinite;
  background-image: linear-gradient(
    to bottom right,
    hsl(300, 94%, 67%),
    #f8077f
  );
  -webkit-background-clip: text;
  color: transparent;
}

/* Custom Animations */

@keyframes bounce {
  0%,
  20%,
  50%,
  80%,
  100% {
    transform: translateY(0);
  }

  40% {
    transform: translateY(-30px);
  }

  60% {
    transform: translateY(-15px);
  }
}
```

### Continued development

I am going to continue implementing custom css styling and animations in future projects.

## Author

- Frontend Mentor - [@macnelson9](https://www.frontendmentor.io/profile/macnelson9)
- Twitter/X - [@macnelson92](https://www.x.com/macnelson92)

## Acknowledgments

Thanks to Kevin Powell for the Conquering responsive layouts course. It has impacted my journey positively.
