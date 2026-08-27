# 🔧 (GOSA_Auto)

> Smarter tools for modern automotive garages.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-222?logo=github)](https://leonkariukii.github.io/Garage_plus/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**GOSA_Auto** is a SaaS concept designed to help automotive garages manage customers, vehicles and daily workshop operations from a single platform.

This repository contains the project's **marketing / landing page**, built as part of a web development learning journey at ***Zindua Coding School***. It focuses on **semantic HTML5, accessible markup, responsive CSS, forms, embedded media, and Git/GitHub workflows**.

## 📖 Table of Contents

* [Project Overview](#project-overview)
* [Live Demo](#live-demo)
* [Features](#features)
* [Tech Stack](#tech-stack)
* [Project Structure](#project-structure)
* [Getting Started](#getting-started)
* [Form Validation](#form-validation)
* [Accessibility](#accessibility)
* [Roadmap](#roadmap)
* [Learning Objectives](#learning-objectives)
* [Contributing](#contributing)
* [License](#license)
* [Author](#author)

## Project Overview

GOSA_Auto aims to give modern automotive garages digital tools to manage their operations, customers and vehicle service information. This landing page provides a professional web presence for the product, introduces visitors to the problem Garage_plus solves, and explains how the platform works through a step-by-step walkthrough.

## Live Demo

The project is deployed using **GitHub Pages**:

🔗 **[https://leonkariukii.github.io/Garage_plus/](https://leonkariukii.github.io/Garage_plus/)**

## Features

* Responsive, semantic HTML5 layout
* Accessible skip-to-content link for keyboard/screen-reader users
* Sticky navigation bar with in-page anchor links
* Hero section with a clear call-to-action
* About section describing the product
* Features grid (Job Card Management, Customer Management, Service History)
* "How It Works" step-by-step section
* Team section
* Embedded video demo (`<iframe>`)
* Contact form with client-side HTML5 validation
* Footer with quick links, social media links and copyright notice

## Tech Stack

* **HTML5** — semantic page structure
* **CSS3** — layout, styling and responsive design
* **Git & GitHub** — version control and collaboration
* **GitHub Pages** — static site hosting/deployment

## Project Structure

```text
GOSA_Auto/
│
├── index.html    # Main landing page markup
├── style.css     # Site styling and responsive rules
├── README.md     # Project documentation
└── LICENSE       # MIT license
```

### HTML5 Concepts Demonstrated

The project uses semantic HTML5 elements to create a meaningful document structure, including:

`<header>` · `<nav>` · `<main>` · `<section>` · `<article>` · `<footer>` · `<form>` · `<label>` · `<input>` · `<textarea>` · `<button>` · `<iframe>`

The goal is to separate **content and structure** from presentation and behaviour.

## Getting Started

No build tools or dependencies are required — this is a static HTML/CSS site.

1. **Clone the repository**

   ```bash
   git clone https://github.com/leonkariukii/Garage_plus.git
   cd Garage_plus
   ```

2. **Open the site locally**

   Simply open `index.html` in your browser, or serve it with a lightweight local server, e.g.:

   ```bash
   # Using VS Code's Live Server extension, or:
   npx serve .
   ```

## Form Validation

The contact form uses built-in HTML5 validation features such as:

* `required`
* `type="email"` / `type="tel"`
* `minlength`

This allows the browser to perform basic validation without any JavaScript.

## Accessibility

* A visually hidden **skip link** lets keyboard users jump straight to `#main-content`.
* Navigation and footer landmarks use `aria-label` for clearer screen-reader context.
* All external links (social media) use `target="_blank" rel="noopener noreferrer"` for security.
* Form inputs are paired with explicit `<label>` elements and `autocomplete` attributes.

## Roadmap

Planned improvements as the project evolves:

* [ ] Enhanced responsive design and mobile navigation
* [ ] JavaScript interactivity (e.g. mobile menu toggle, form feedback)
* [ ] Backend API integration
* [ ] Database integration for customers, vehicles and job cards
* [ ] User authentication
* [ ] Full garage management functionality (job cards, invoicing, scheduling)

## Learning Objectives

This project has helped build practical skills in:

* Semantic HTML5 and web page structure
* Responsive CSS layout
* Form creation and validation
* Web accessibility fundamentals
* Git version control and GitHub workflows
* Static website deployment via GitHub Pages
* Project documentation

## Contributing

This is currently a personal learning project, but suggestions and feedback are welcome. To propose a change:

```bash
git checkout -b feature/your-feature-name
git add .
git commit -m "Describe your change"
git push origin feature/your-feature-name
```

Then open a pull request describing your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

**Leon Kariuki**

GOSA_Auto — Building smarter tools for modern automotive garages.