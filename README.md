# Swiggy (Restaurant UI)

A static responsive restaurant UI inspired by Swiggy. This small project contains a landing page (`index.html`) and styling (`style.css`) with a set of image assets in the `assets/` folder.


## Languages & Libraries used

<!-- Badges / icons for quick visual reference -->

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font%20Awesome-528DD7?style=for-the-badge&logo=font-awesome&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google%20Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)


## Project structure

- `index.html`         — Main HTML page (the UI of the restaurant landing page).
- `style.css`          — Styles for layout and responsiveness.
- `assets/`            — Images and icons used in the page (logo, hero images, footer assets, etc.).



# Swiggy (Restaurant UI) 🍽️

A static, responsive restaurant landing page inspired by the Swiggy app/website. This is a front-end-only prototype built with plain HTML and CSS and a set of image assets in the `assets/` folder. It's intended as a learning/demo project and a starting point for building a production-ready food delivery UI.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font%20Awesome-528DD7?style=for-the-badge&logo=font-awesome&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google%20Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)

## Overview 🚀

This project recreates a restaurant/food-delivery landing page with a clean navigation bar, a horizontally scrollable hero section, a "top restaurants" area, filter buttons, restaurant cards and a footer. It focuses on layout, responsive CSS and using image assets to create a visually pleasing UI.

Key ideas and goals:
- ✅ Keep the implementation simple and dependency-free (no build tools, no JS required for core layout).
- 📱 Demonstrate responsive design patterns (flexbox, horizontal scroll for hero cards, media queries).
- 🎨 Use modern fonts and icons for a polished look.

## Features ✨

- 🔁 Responsive layout (desktop → mobile via CSS media queries).
- 🖼️ Horizontal scrollable hero section for featured categories/dishes.
- 🏷️ Cards for restaurants and top-places with hover states.
- 🔎 Filter/navigation bar for choosing cuisine/filters (UI only).
- 📌 Footer with logo and links (static content).

## Project structure 📁

- `index.html` — Main HTML page (landing page markup).
- `style.css`  — All styles, variables, and responsive rules.
- `assets/`    — Images and icons used across the page (logo, hero images, restaurant thumbnails, etc.).

## How to preview ▶️

1. Open the project folder in your code editor (e.g. VS Code).
2. Open `index.html` in your browser. On Windows you can run:

```powershell
Start-Process index.html
```

Or install the VS Code Live Server extension and click "Go Live" to preview with auto-reload.

## How to customize 🎨

- 🎨 Colors: edit CSS variables near the top of `style.css` (the `:root` selector) to change the primary color and accents.
- ✒️ Fonts: `index.html` includes Google Fonts — swap the font family link or change the `font-family` in `style.css`.
- 🖼️ Images: replace files in `assets/` (keep the path structure) to change brand/logo/photos.
- ⚙️ Add interactions: add a small JavaScript file to implement features like automatic hero carousel scroll, filter behavior, or modals for restaurant details.

## Accessibility & good practices ♿️

- Use semantic HTML elements (header, nav, main, footer) when editing the markup.
- Ensure all images have meaningful `alt` attributes if you add or replace assets.
- Keep color contrast in mind when changing the theme color — test with contrast tools if needed.

## Known limitations & suggested improvements ⚠️

- 🚧 Currently the project is static and UI-only — no backend or real data.
- ⌨️ Add keyboard support and ARIA roles for improved accessibility.
- 🏎️ Optimize images (compress/serve responsive sizes) for faster loading.
- 🧪 Add unit/integration tests if you convert this to a componentized app (React/Vue/etc.).
- 🌐 Deploy easily to GitHub Pages or any static host for sharing.

## Deployment (quick) 📦

To publish on GitHub Pages, push this folder to a repository and enable Pages from the repository settings (branch: `main` or `gh-pages`, folder: `/ (root)`). The `index.html` at the repo root will be served automatically.

## Credits 🙏

- Font: Poppins (Google Fonts) — referenced via CDN in `index.html`.
- Icons: Font Awesome (via CDN).
- Images: placed in `assets/` — verify licenses if you reuse them publicly.

---

Made with ❤️ by Aftab Alam
