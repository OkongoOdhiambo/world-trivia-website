# World Trivia — Accessible, Responsive Web Page 🌍

Brief: A single-page, accessible, mobile-first trivia site skeleton — semantic HTML, robust ARIA, high-contrast palette and responsive layout. ♿️📱

## File structure 📁

- index.html
- css/styles.css
- README.md

## Features ✅

- Mobile-first, single-page trivia layout 📱
- Semantic HTML5 structure and ARIA attributes for screen readers ♿️
- Keyboard-navigable controls and focus management ⌨️
- High-contrast, accessible color palette 🎨
- Responsive layout with CSS Grid / Flexbox 📐
- No JS build step required — drop into static host 🚀

## Quick start ⚡

1. Put `index.html` and `css/styles.css` in the same project folder.
2. Open `index.html` in a browser to preview locally 👀.
3. For public hosting, deploy the folder to a static host (GitHub Pages, Netlify, Vercel, etc.) 🌐.

## File overview 🔎

- index.html — single-page app markup, semantic sections and ARIA roles 🧭
- css/styles.css — responsive, accessible styles and utility classes 🎛️
- README.md — project documentation 📝

## Accessibility notes ♿️

- All interactive controls include visible focus states — visible outlines and focus rings ✨
- ARIA roles and labels provided for navigational landmarks and widgets 🏷️
- Color contrast meets WCAG AA for normal text; avoid modifying palette without re-checking contrast 🔍
- Keyboard-first interaction and sensible tab order enforced ⌨️

## Deployment 🚀

- No build step required — just upload files to your static host 📦
- For GitHub Pages: push repo to GitHub and enable Pages from main branch root 🧩

## License ⚖️

GNU General Public License (GPL).

## Contact 📣

Issues and pull requests welcomed via the repository. Feedback and contributions encouraged 🙌
Note: Reduced emoji usage throughout this README for clarity and accessibility. Decorative icons were removed; only retained where they add clear meaning.
# World Trivia — Accessible, Responsive Trivia Skeleton

A lightweight, single-page trivia site template focused on accessibility, responsive layout, and straightforward deployment. Designed as a small, production-ready starting point for static hosting with no build step.

## Goals

- Semantic HTML and clear landmarks for assistive tech
- Keyboard-first controls and visible focus styles
- Mobile-first, responsive layout using CSS Grid/Flexbox
- Minimal, maintainable CSS (no JS required for core UX)
- Easy to fork and adapt for quizzes, learning sites, or demos

## Files

- index.html — markup with semantic sections and ARIA landmarks
- css/styles.css — mobile-first, accessible styles and utilities
- README.md — this file

Place index.html and css/ in the same folder before deploying.

## Quick start

1. Clone or copy files into a project folder.
2. Open `index.html` in a browser to preview.
3. Deploy to any static host (GitHub Pages, Netlify, Vercel).

## Usage notes

- The page is a single-page static UI; add or edit question markup directly in `index.html`.
- Keep interactive controls reachable via Tab and operable with Enter/Space.
- For progressive enhancements, add unobtrusive JavaScript in a separate file — avoid coupling JS to CSS for basic accessibility.

## Accessibility checklist

- All interactive items include keyboard focus states (outline or focus-ring).
- ARIA roles and labels used only when native semantics are insufficient.
- Color contrast targets WCAG AA for body text; test changes against contrast tools.
- Logical heading order and skip-link provided for keyboard users.

## Customization

- Colors: update variables in `css/styles.css` (use relative contrast tests).
- Layout: tweak grid/flex breakpoints for different content density.
- Questions: keep question wording concise and group options inside a form/fieldset for semantic grouping.

## Deployment

- No build step required.
- For GitHub Pages: push repository and enable Pages from the main branch (root).
- For Netlify/Vercel: drag-and-drop the folder or connect the repo for automatic deploys.

## Contributing

- File an issue for bugs or accessibility gaps.
- Send small, focused pull requests with one change per PR.
- Include accessibility rationale for UI changes and any contrast/typography adjustments.

## Tests & Validation

- Run Lighthouse (Accessibility) and aXe to validate accessibility.
- Test keyboard navigation (Tab, Shift+Tab, Enter, Space, Arrow keys where relevant).
- Validate HTML with a validator to ensure semantic correctness.

## License

GNU General Public License (GPL). Include your copyright notice in source files.

## Contact

Open issues and pull requests in the repository. Include screenshots and steps to reproduce for UI/behavior reports.