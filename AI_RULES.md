# AI Development Rules

This document outlines the technical stack and development guidelines for this web application.

## Tech Stack

- **Core Technologies:** The application is built using fundamental web technologies: HTML, CSS, and JavaScript.
- **Frameworks:** This is a "vanilla" project. It does not use any front-end frameworks like React, Vue, or Angular.
- **Styling:** All CSS is contained within a single `<style>` block in the `index.html` file. No CSS pre-processors or utility-first frameworks are used.
- **JavaScript:** All application logic is written in plain JavaScript (ES6+) and resides within a `<script>` tag in `index.html`.
- **Build Process:** There is no build process or package manager (like npm). The `index.html` file is served directly.
- **State Management:** Application state is managed through global variables within the main script scope.
- **Dependencies:** The project has no external dependencies.

## Development Guidelines

- **Keep it Vanilla:** All new features and modifications must be implemented using only plain HTML, CSS, and JavaScript. Do not introduce any external libraries or frameworks (like jQuery, Lodash, React, etc.).
- **Single File Structure:** This is a single-page HTML application. All code (HTML, CSS, JS) must remain within the `index.html` file. Do not create separate `.js` or `.css` files.
- **DOM Manipulation:** Use standard Web APIs like `document.getElementById`, `document.createElement`, and `element.addEventListener` for all DOM interactions.
- **Styling:** Apply styles by adding new rules to the existing `<style>` block. Maintain the existing styling conventions.
- **Code Organization:** Write new JavaScript logic in well-named, single-purpose functions to maintain readability and organization within the single script tag.