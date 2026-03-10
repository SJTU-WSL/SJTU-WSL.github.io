# Personal Website Starter

Simple static starter for a personal website on GitHub Pages.

## Structure

```
.
├── index.html
└── assets
    ├── css
    │   └── styles.css
    └── js
        └── main.js
```

## Customize

1. Edit text in `index.html`:
   - `Your Name`
   - About section
   - Project cards
   - Contact email
2. Adjust colors and spacing in `assets/css/styles.css`.
3. Add your project links in the `href="#"` placeholders.

## Local Preview

Open `index.html` directly in your browser, or run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy with GitHub Pages

1. Push to your GitHub repository.
2. In repository settings, open `Pages`.
3. Select deploy source:
   - Branch: `main` (or your default branch)
   - Folder: `/ (root)`
4. Save and wait for deployment.
