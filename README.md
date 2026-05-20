# Bermen March

Landing page for Bermen March — a technology partner for asset managers and financial services firms.

## Deploy

This is a single self-contained `index.html` with all CSS and JS inline. The only external files are the three brand assets in `assets/`.

### GitHub Pages
1. Push the contents of this folder to the root of a GitHub repo.
2. In the repo's Settings → Pages, set source to the `main` branch.
3. Wait for the green check and visit the URL.

### Vercel / Netlify
Drag the folder onto Vercel or Netlify — it deploys as a static site with no build step.

### Local preview
Open `index.html` directly in a browser, or run a local server from this folder:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Files

```
.
├── index.html                    Single-file landing page
├── assets/
│   ├── bermen-logo.png           Header + footer logo
│   ├── bermen-favicon.png        Browser tab icon
│   └── bermen-animation.mp4      Hero background video
└── README.md
```
