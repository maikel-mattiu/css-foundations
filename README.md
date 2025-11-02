[![Frontend Masters](https://static.frontendmasters.com/assets/brand/logos/full.png)][fem]

# CSS Day Conference Site

CSS Day is a two-page marketing site built while following the [CSS Foundations course][course] on Frontend Masters. It focuses on applying layout fundamentals, responsive design, and component thinking with just HTML, CSS, and a touch of JavaScript.

## Overview
The project ships two static pages: the landing page (`index.html`) and the speaker line-up (`speakers.html`). Shared styles live in `styles/base.css`, while each page adds its own layer of layout rules. A small script powers the mobile navigation toggle and scroll locking.

## Features
- Responsive header with hamburger/close toggle and body scroll locking for the off-canvas menu.
- Hero section that highlights dates, CTA buttons, and iconography pulled from the design system.
- Speaker grid that adapts from a single column to multi-column layouts using CSS Grid.
- Design tokens (colors, fonts, spacing) managed with CSS custom properties in `styles/base.css`.
- Page-specific styles organized into `styles/index.css` and `styles/speakers.css` for maintainability.

## Getting Started
1. Clone the repository and open the folder in your editor.
2. Open `index.html` in a browser to view the landing page; use `speakers.html` for the line-up view.
3. For live reloading, launch either page with a lightweight server such as the VS Code Live Server extension.

## Project Structure
- `index.html` conference home page with navigation and hero content.
- `speakers.html` speaker profiles presented in a responsive grid.
- `styles/base.css` shared variables, resets, and header/navigation styles.
- `styles/index.css` home page specific layout, typography tweaks, and CTA button styles.
- `styles/speakers.css` speaker card layout, typography, and background treatments.

## Design Resources
- Figma file: https://www.figma.com/file/LEzNgBz63KLExeHNUyLCwH/FEM-CSS?type=design&node-id=0-1

## Assets & Credits
- Icons by Flat Icon.
- Photography from Unsplash: https://unsplash.com/photos/WYE2UhXsU1Y, https://unsplash.com/photos/iEEBWgY_6lA, https://unsplash.com/photos/mpDV4xaFP8c, https://unsplash.com/photos/SJvDxw0azqw, https://unsplash.com/photos/QJEVpydulGs, https://unsplash.com/photos/p5BoBF0XJUA

[fem]: https://frontendmasters.com
[course]: https://frontendmasters.com/courses/css-foundations/
