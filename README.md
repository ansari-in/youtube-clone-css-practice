# YouTube Clone — CSS Styling Practice

A simple front‑end project to practice HTML and CSS by recreating key layouts from YouTube. Includes multiple static pages and page‑specific styles/scripts to experiment with layout, spacing, typography, and basic UI interactions.

## Overview
- Purpose: Hands‑on CSS layout practice (header, sidebar, feed grid, video page, etc.).
- Stack: Pure HTML/CSS with light vanilla JS for page behaviors.
- Scope: Static pages, no backend or build tools required.

## Project Structure
```
default page.html
explore.html
history.html
index.html
library.html
subscription.html
feed/
  library/
    library.html
  subscription/
    subscription.html
img/
  You Tube/
js/
  explore.js
  history.js
  Home.js
  library.js
  subscription.js
  video page.js
style/
  explore_style.css
  history_style.css
  Home_style.css
  library_style.css
  subscription.css
  video page.css
video/
video page/
  video page.html
```

## Pages
- `index.html`: Main home/feed layout entry (start here).
- `default page.html`: Alternate/legacy landing layout.
- `explore.html`: Explore section layout.
- `history.html`: Watch history layout.
- `library.html` and `feed/library/library.html`: Library layouts.
- `subscription.html` and `feed/subscription/subscription.html`: Subscription feeds.
- `video page/video page.html`: Individual video watch page layout.

## Styles & Scripts
- Styles live under `style/` and are generally page‑specific:
  - `Home_style.css`, `explore_style.css`, `history_style.css`, `library_style.css`, `subscription.css`, `video page.css`
- Optional scripts live under `js/` (used for basic interactions only):
  - `Home.js`, `explore.js`, `history.js`, `library.js`, `subscription.js`, `video page.js`

## Getting Started
No build step required. Open any HTML file directly in your browser.

- Windows (PowerShell):
  - Open the home page: `Start-Process .\index.html`
  - Open the video page: `Start-Process "./video page/video page.html"`

- VS Code (recommended):
  - Install the “Live Server” extension.
  - Open `index.html` and click “Go Live” to serve with auto‑reload.

## Assets
- Images: `img/You Tube/` (placeholder location for thumbnails/icons)
- Videos: `video/` (if you add local demo assets)

## Notes
- This is a CSS practice project; focus is on layout, spacing, and component styling rather than functionality.
- Filenames contain spaces in some places (e.g., `video page/`); that’s fine for practice, but typically avoided in production.
- Keep relative paths consistent if you move files between folders.

## Roadmap Ideas (Practice Prompts)
- Make layouts responsive with CSS Grid/Flexbox breakpoints.
- Add hover, focus, and active states for interactive elements.
- Improve accessibility: semantic HTML, landmarks, alt text, focus order.
- Extract shared variables (colors, spacing) with CSS custom properties.
- Add a dark theme toggle and persist preference.

## Disclaimer
This project is for learning purposes only. All trademarks and brand assets related to YouTube are the property of their respective owners and are used here solely for practice.
