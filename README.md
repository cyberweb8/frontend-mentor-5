# Frontend Mentor - Stats preview card component

This is a solution to the [3-Stats preview card component](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://github.com/cyberweb8/frontend-mentor-5)
- Live Site URL: [Add live site URL here](https://cyberweb8.github.io/frontend-mentor-5/)

## My process

### Built with

- Semantic HTML5 markup
- [CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/) - Reseting default style
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- I have learned about decorative images. While using them I do not need to provide with any description for alt property, since the only purpose of the image to add visual decoration to the page.

- I used mix-blend-mode along with multiply value with the association of opacity property to get filtered image like shown in the desing image.

To write semantic and responsive img tag, I learned using picture tag:

```html
<picture>
  <source srcset="images/image-header-desktop.jpg" media="(min-width: 768px)" />
  <img src="images/image-header-mobile.jpg" alt="" aria-hidden="true" />
</picture>
```

```css
img {
  background-color: var(--clr-secondary);
  opacity: 0.8;
  mix-blend-mode: multiply;
}
```

### Continued development

- When I have time and opportunity I have to investigate further about mix-blend-mode property to utilize it for my further projects.

### Useful resources

- [Images Tutorial/Standards](https://www.w3.org/WAI/tutorials/images/) - This helped me to structure decorative images. I really liked it and will use it going forward.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@cyberweb8](https://www.frontendmentor.io/profile/cyberweb8)

## Acknowledgments

I want to express my gratitude to [@vcarames](https://www.frontendmentor.io/profile/vcarames) from frontendmentor who took his valuable time and shared his feedback and I will make it use in my future projects.
