# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Working on this project helped me reinforce several key concepts:

1. **Semantic HTML5 Markup**:
   Using semantic tags like `<header>`, `<body>`, and `<div>` improved the accessibility and readability of my code.

   ```html
   <body>
     <div class="qr-code">
       <img src="images/qr-code.png" alt="QR Code">
     </div>
   </body>
   ```

2. **CSS Custom Properties**:
  Leveraging CSS variables made it easier to maintain and update the color scheme.

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

3. **Flexbox**:
  Flexbox was used to center the QR code component both horizontally and vertically.

  ```css
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
  }
  ```

4. **Mobile-first Workflow**:
  Designing with a mobile-first approach ensured that the layout was responsive and looked good on all devices.

  ```css
  @media (min-width: 1440px) {
  body {
    font-size: 18px;
  }

  img {
    height: 300px;
    width: 300px;
  }

  h1 {
    font-size: 24px;
    margin-top: 30px;
  }

  .container {
    max-width: 400px;
    padding: 20px;
  }
}


These learnings have been crucial in enhancing my front-end development skills.
### Continued development

Moving forward, I plan to focus on the following areas to further improve my skills:

1. **Accessibility**:
  Ensuring that my projects are accessible to all users, including those with disabilities, by using ARIA roles and attributes.

2. **Advanced CSS Techniques**:
  Exploring CSS Grid in more depth and learning about CSS animations to create more dynamic and engaging user interfaces.

By focusing on these areas, I aim to create more robust and user-friendly web applications.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/) - A comprehensive resource for web developers, providing documentation and tutorials on HTML, CSS, and JavaScript.
- [CSS-Tricks](https://css-tricks.com/) - A website with articles, videos, and guides on various CSS techniques and best practices.
- [A11Y Project](https://www.a11yproject.com/) - A community-driven effort to make web accessibility easier.

These resources have been invaluable in helping me learn and apply new concepts in my projects.