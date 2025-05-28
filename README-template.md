¡Por supuesto! Aquí tienes un README completado y adaptado a tu experiencia personal, resaltando el desafío del diseño desktop y tu satisfacción con tu progreso. Puedes copiarlo y personalizar los enlaces:

---

# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Screenshot of my solution](./screenshots/Captura%20de%20pantalla%20(87).png)

- Solution URL: [https://github.com/LeyaDiaz/Solution-four-card-feature-section-master.git](https://github.com/LeyaDiaz/Solution-four-card-feature-section-master.git)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Bootstrap 5 (for responsive grid)
- Mobile-first workflow

### What I learned

The biggest challenge for me was achieving the desktop layout, especially getting the cards aligned correctly as in the design. At first, it was a bit tricky to get the spacing and alignment of the central cards and the side cards just right. Once I overcame the obstacle of building the HTML structure, everything else flowed much more smoothly.

What I really enjoyed about this project is that I noticed I am starting to do many things instinctively, and they are correct! For example, using utility classes, structuring my CSS with custom properties, and thinking responsively from the start. This realization was very motivating and made me feel that my workflow is improving.

Here’s a small CSS snippet that helped me with the desktop alignment:

```css
@media (min-width: 1200px) {
  .title p {
    max-width: 400px;
    margin-left: auto;
    margin-right: auto;
  }
  .box > .col-xl-4 {
    padding-left: 1rem;
    padding-right: 1rem;
  }
  .box > .col-xl-4:nth-child(2) {
    gap: 1rem;
  }
}
```

### Continued development

In future projects, I want to keep improving my eye for detail, especially when it comes to aligning elements exactly as in the design. I also want to continue practicing with CSS Grid for more complex layouts and maybe start using CSS preprocessors to organize my styles better.

### Useful resources

- [MDN Flexbox Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) - Always helpful for any flexbox-related questions.
- [Frontend Mentor Discord](https://discord.gg/frontendmentor) - For community support and feedback.

## Author

- Frontend Mentor - [@LeyaDiaz](https://www.frontendmentor.io/profile/LeyaDiaz)

## Acknowledgments

Thanks to the Frontend Mentor community for the feedback and inspiration. This challenge really helped me see my own progress!
