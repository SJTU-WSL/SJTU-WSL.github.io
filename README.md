# Personal Website

Static personal website for GitHub Pages.

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
   - bio in `#home` and `#about`
   - research cards in `#research`
   - ICPC award details in `#awards`
2. Replace avatar image:
   - current path: `assets/avatar.jpg`
3. Adjust colors and spacing in `assets/css/styles.css`.

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
