[🔗 Live site](https://product-preview-card-component-eta-nine.vercel.app/)

# Frontend Mentor - Product preview card component solution

This is my solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

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
  - [AI collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

This project is a responsive product preview card for Gabrielle Essence Eau De Parfum by CHANEL. It displays product imagery, a description, the current price, the original price, and an Add to Cart button.

### The challenge

Users should be able to:

- View the product card layout on different screen sizes
- See hover and focus states for interactive elements

### Screenshot

![Screenshot of my product preview card solution](./public/screenshot/Main%20design.png)

### Links

- Live Site: [View the deployed project](https://product-preview-card-component-eta-nine.vercel.app/)
- GitHub Repository: [View the source code](https://github.com/md-nurun-nobi/product-preview-card-component)

## My process

I built the product card with semantic HTML and styled it with Tailwind CSS. I used responsive utility classes to adjust the layout for larger screens and the `<picture>` element to serve a different product image at the desktop breakpoint.

### Built with

- Semantic HTML5 markup
- Tailwind CSS
- CSS custom properties
- Flexbox
- Responsive design
- Mobile-first workflow
- Vite

### What I learned

This project helped me practise building a responsive layout with Tailwind CSS. I learned how to set up custom colors, fonts, and a breakpoint in the Tailwind theme, then use those values in utility classes.“I learned how to use two images in a project. This was a little challenging for me.”

I also practised using the `<picture>` element to show different product images depending on the screen width:

```html
<picture>
  <source
    media="(min-width: 1024px)"
    srcset="images/image-product-desktop.jpg"
  />
  <img
    src="images/image-product-mobile.jpg"
    alt="Gabrielle Chanel perfume bottle"
  />
</picture>
```

I added hover and keyboard focus styles to the Add to Cart button so that its interactive states are visible.

### Continued development

In future projects, I want to keep improving my responsive design skills and become more confident matching typography, spacing, and layouts to a design reference.

I also want to practise making interactive elements accessible and consistent across different screen sizes.

### Useful resources

- [Frontend Mentor](https://www.frontendmentor.io/) - The challenge and design files helped me practise building a page from a visual reference.
- [Tailwind CSS documentation](https://tailwindcss.com/docs) - This helped me understand utility classes and theme configuration.
- [Vite documentation](https://vite.dev/guide/) - This helped me run and build the project.

### AI collaboration

I used ChatGPT to help troubleshoot questions about typography and GitHub deployment.

## Author

- GitHub: [@md-nurun-nobi](https://github.com/md-nurun-nobi)

## Acknowledgments

Thanks to Frontend Mentor for providing the challenge and design resources.