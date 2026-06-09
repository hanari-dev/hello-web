# Hello Web - Personal Portfolio

A professional, responsive, and accessible personal portfolio website built with modern CSS techniques.

## Live Site
[View Portolio on GitHub Pages](https://hanari-dev.github.io/hello-web/)

## Project Overview
This project showcases my development and design skills. The core focus was to create a clean, high-performance interface that leverages modern CSS layout systems while maintaining strict semantic standards.

## Key Features & Technical Rubric Compliance
* **Semantic HTML5:** Built using standard document structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) to ensure accessibility and SEO compliance.
* **Modern Layouts:**
    * **Flexbox:** Used for one-dimensional layouts (Navigation bar, header alignment, and form components).
    * **CSS Grid:** Utilizes `grid-template-columns: repeat(auto-fit, minmax(260px, 1fr))` to create a fully responsive, two-dimensional project gallery that adapts automatically to screen size.
* **Responsive Design:**
    * Mobile-first design approach.
    * **Fluid Typography:** Uses `clamp()` to scale fonts and spacing smoothly across devices.
    * **Media Queries:** Breakpoints implemented at `768px` (tablet) and `1024px` (desktop) to ensure optimal reading widths.
    * **Accessibility:** All interactive elements (buttons/inputs) maintain a minimum 44px tap target size.
* **Bonus Features:**
    * **OS-Aware Theme Detection:** Includes a `prefers-color-scheme: light` media query to automatically toggle the site's theme based on the user's system preferences.
    * **Modern Aesthetics:** Designed with a refined dark-mode-first aesthetic, utilizing CSS variables for maintainability and consistency.

## Technologies Used
* HTML5
* CSS3 (Variables, Flexbox, Grid, Media Queries, `clamp()`)
* Deployed via GitHub Pages
