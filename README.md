# greenl8 Portfolio

A static portfolio website showcasing VFX, Motion Graphics, Fractal and AI Art work.

## Features

- Dark theme design
- Responsive layout
- YouTube video embeds
- Contact information
- GitHub Pages deployment ready

## Deployment

This website is designed to be deployed on GitHub Pages. Simply:

1. Push this repository to GitHub
2. Enable GitHub Pages in repository settings
3. Select the main branch as source
4. Your site will be available at `https://yourusername.github.io/repository-name`

## Local Testing

No build step is required — the site is plain HTML + CSS.

### Option 1 — VS Code Live Server (recommended)

1. Install the **Live Server** extension (`ritwickdey.LiveServer`) in VS Code.
2. Right-click `index.html` and select **Open with Live Server**.
3. The site opens at `http://127.0.0.1:5500` and auto-reloads on file changes.

### Option 2 — Python HTTP server

```bash
# Python 3
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

### Option 3 — Node.js

```bash
npx serve .
```

Then open the URL printed in the terminal (usually `http://localhost:3000`).

### Option 4 — Open the file directly

Double-click `index.html` to open it in your default browser. Note that some browsers restrict embedded content (e.g. YouTube iframes) when loading via `file://`, so a local server is preferred.

## Customization

- Replace the YouTube video IDs in `index.html` with your actual video IDs
- Update contact information as needed
- Modify styling in `styles.css`
