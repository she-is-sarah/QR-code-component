# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

  - [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [My Process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

A simple and responsive QR code component that centers a card containing a QR code image and descriptive text. The component features a clean design with appropriate spacing, shadow effects, and typography.

### Screenshot

./img/desktopshot.png
./img/mobileshot.png

### Links

- Solution URL: [Add solution URL here]
- Live Site URL: [Add live site URL here]

## My Process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox (via absolute positioning and transform)
- Mobile-first workflow
- Google Fonts - Outfit font family
- CSS Box Shadow for depth

### What I learned

This project helped reinforce several key concepts:

- Center alignment using absolute positioning and transform:
```css
.component {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
```

- Responsive design using em units:
```css
.component {
    max-width: 16.2em;
}
```

- Adding subtle depth with box-shadow:
```css
.component {
    box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
}
```

### Continued development

Areas I want to focus on in future projects:

- Exploring alternative centering techniques like CSS Grid and Flexbox
- Implementing more accessible features
- Optimizing for different screen sizes
- Working with CSS custom properties for better maintainability

### Useful resources

- [CSS Box Shadow Examples](https://getcssscan.com/css-box-shadow-examples) - Helped in selecting the right shadow effect for the card
- [Google Fonts](https://fonts.google.com) - For implementing the Outfit font family
- [CSS Units Guide](https://www.w3schools.com/cssref/css_units.asp) - Helped understand when to use em vs px

## Author

- Website - [https://she-is-sarah.github.io/portfolio/]
- Frontend Mentor - [@she-is-sarah]
- Linkedin - [Sarah Ebiesuwa]