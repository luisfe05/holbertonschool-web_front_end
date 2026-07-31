# Holberton School - Web Front-End

## Description
This repository contains projects for the **Web Front-End** curriculum at Holberton School. It focuses on the core building blocks of modern web development, taking a deep dive into semantic HTML5 structure and advanced CSS3 styling techniques. Through hands-on exercises, these modules cover building web layouts from scratch, establishing custom CSS design systems, creating responsive card components, and implementing dynamic UI transitions.

---

## Projects Overview

| Directory | Description | Key Technologies & Topics |
| :--- | :--- | :--- |
| [HTML_advanced](./HTML_advanced/) | Structuring complex web documents using modern HTML5 elements without CSS styling. | Semantic HTML5, document skeletons, multimedia embedding, accessibility, content hierarchy. |
| [CSS_advanced](./CSS_advanced/) | Advanced styling, custom design systems, responsive grid layouts, and interactive UI animations. | CSS Variables, typography, grid/floats, theme toggling, transitions, pseudo-elements, `normalize.css`. |

---

## Technical Highlights

### 1. HTML Advanced (`HTML_advanced/`)
* **Semantic Structure:** Utilization of HTML5 semantic tags such as `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, and `<footer>`.
* **Content Hierarchy:** Correct heading progression (`<h1>` through `<h6>`) ensuring document outline readability and SEO optimization.
* **Accessibility:** Embedding clean image tags, accessible link attributes, and text alternatives.

### 2. CSS Advanced (`CSS_advanced/`)
* **Design Systems & Custom Properties:** Implementation of root-level CSS variables (`:root`) for color palettes, font families, custom line heights, and padding scale.
* **Cross-Browser Normalization:** Standardizing base styles across rendering engines using `normalize.css`.
* **Universal Box Model:** Applying `box-sizing: border-box` across all elements and pseudo-elements (`::before` / `::after`).
* **Custom Layout System:** Custom-built multi-column grid (`.col-1-2`, `.col-1-3`) using floats, attribute selectors (`[class*="col-"]`), and clearfix mechanisms (`::after`).
* **Theming & Components:** Dark mode support using custom attributes (`[data-section-theme="dark"]`), interactive buttons, rounded avatars, service cards, and quotation mark decorations.
* **Micro-Interactions & Animations:** Custom hover effects, transform scaling, and fluid transitions using `cubic-bezier` timing functions.

---

## Repository Structure

```text
holbertonschool-web_front_end/
├── HTML_advanced/
│   └── index.html
├── CSS_advanced/
│   ├── index.html
│   ├── images/
│   └── styles/
│       ├── 1-style.css
│       ├── ...
│       └── 32-style.css
└── README.md

## Author
* **Luis Gonzalez** - Holberton School
