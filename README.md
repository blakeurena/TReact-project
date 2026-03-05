# TReact-project

A responsive marketing/landing page inspired by **Treact** UI templates. Built as a static site using **HTML**, **CSS**, and a small amount of **JavaScript** (mobile menu toggle).

## Preview

- Entry point: `index.html`
- Styling: `style.css`
- Scripts: `script.js`
- Assets: `assets 3/`

> Note: This repo currently contains a static HTML implementation (not a React/TypeScript build with `package.json` scripts).

## Features

- Responsive layout (desktop → tablet → mobile)
- Mobile navigation modal (hamburger menu open/close)
- Multiple sections: Features, Quality Work, Steps, Values, Pricing, Testimonials, CTA, Footer
- External icons via Font Awesome

## Getting Started (Local)

### Option A: Open directly (simplest)
1. Clone the repo:
   ```bash
   git clone https://github.com/blakeurena/TReact-project.git
   cd TReact-project
   ```
2. Open `index.html` in your browser.

### Option B: Run with a local dev server (recommended)
Using VS Code **Live Server** extension:
1. Open the project folder in VS Code
2. Right-click `index.html` → **Open with Live Server**

Or using Python:
```bash
# from the project root
python -m http.server 5173
```
Then visit `http://localhost:5173`.

## Project Structure

```text
.
├── assets 3/          # images + SVGs used by the page
├── index.html     # main HTML file
├── style.css          # site styles
├── script.js          # menu open/close logic
└── README.md
```

## Deployment

You can deploy this as a static site using:
- **GitHub Pages**
- **Netlify**
- **Vercel**

After deploying, add your URL here:

- Live Demo: (add link)

## Credits

Design inspired by Treact-style landing page templates (educational/practice implementation).

## License

Add a license if you plan to share/extend this project publicly (e.g., MIT).
