# Frontend Mentor - QR Code Component Solution

This is my solution for the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges are designed to help improve coding skills by building real-world projects.

## Table of Contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)

## Overview

### Screenshot

![Screenshot](./screenshot.jpg)

### Links

- [Solution URL](https://your-solution-url.com)
- [Live Site URL](https://your-live-site-url.com)

## My Process

### Built With

- Semantic HTML5
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I Learned

Working on this project reinforced several important concepts:

1. **Semantic HTML5 Markup**  
   Using semantic elements like `<header>`, `<body>`, and `<div>` improved the structure and accessibility of my code.

   ```html
   <body>
     <div class="qr-code">
       <img src="images/qr-code.png" alt="QR Code" />
     </div>
   </body>
   ```

2. **CSS Custom Properties**  
   I used CSS variables to maintain and update the color scheme easily.

   ```css
   :root {
     --primary-color: hsl(212, 45%, 89%);
     --secondary-color: hsl(218, 44%, 22%);
   }

   .container {
     background-color: var(--primary-color);
     color: var(--secondary-color);
   }
   ```

3. **Flexbox**  
   Flexbox made it simple to center the QR code component both horizontally and vertically.

   ```css
   .container {
     display: flex;
     justify-content: center;
     align-items: center;
     height: 100vh;
   }
   ```

4. **Mobile-first Workflow**  
   Designing with mobile-first principles ensured that the layout looks good on all devices.

   ```css
   @media (min-width: 1440px) {
     .container {
       max-width: 400px;
       padding: 20px;
     }
   }
   ```

### Continued Development

To improve my skills, I plan to focus on:

1. **Accessibility**  
   Implementing ARIA roles and attributes to ensure my projects are accessible to all users.

2. **Advanced CSS Techniques**  
   Exploring CSS Grid and animations for more dynamic and engaging designs.

### Useful Resources

- [MDN Web Docs](https://developer.mozilla.org/) – Comprehensive resource for HTML, CSS, and JavaScript documentation.
- [CSS-Tricks](https://css-tricks.com/) – Helpful articles and guides on CSS techniques and best practices.
- [A11Y Project](https://www.a11yproject.com/) – Community-driven resource for improving web accessibility.
