# Copilot instructions for TReact-project

## Project snapshot
- Static landing page (no build system). Entry point is `index.html` with all sections inline.
- Styling lives in `style.css`; class naming is BEM-ish (e.g., `.header__title`, `.plan__btn--featured`).
- Behavior is minimal and in `script.js` (mobile menu open/close toggles `menu--open` on `body`).
- Assets are served from the oddly named `assets 3/` directory; keep paths consistent with that folder name.

## Key structure & data flow
- HTML defines all sections and content blocks (Features, Quality, Steps, Values, Pricing, Testimonials, CTA, Footer).
- CSS is a single file with sectioned comment headers and shared utility classes like `.purple` and `.btn`.
- JS is purely DOM class toggling; no framework, bundler, or module system.

## Workflow (local)
- Simplest: open `index.html` directly in the browser.
- Recommended: run a static server (e.g., VS Code Live Server or `python -m http.server 5173`) for reliable asset loading.

## Conventions to keep
- Keep section markup in `index.html` aligned with existing CSS class names; styles are tightly coupled to class names.
- Prefer editing existing blocks instead of introducing new structural patterns; follow the sectioned CSS layout.
- Keep external icon usage via Font Awesome (`<script>` kit + CSS link in `<head>`).

## Examples
- Menu toggle: `openMenu()`/`closeMenu()` in `script.js` add/remove `menu--open` on `document.body`.
- Featured pricing plan uses `.plan--featured` with corresponding `--featured` element modifiers in `style.css`.
