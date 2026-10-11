# STV Product Website

Static website for the STV (Seismic Trace Viewer) product, designed for GitHub Pages.

## Deploying to GitHub Pages

### Option 1: From the stv-release repository

1. Copy the contents of this folder (`index.html`, `manual.html`, `screenshots.html`, `tutorials.html`, `download.html`, `css/`, `images/`) to your `stv-release` repository.
2. Go to the repository Settings → Pages.
3. Set Source to "Deploy from a branch" and select the branch (e.g., `main`) and folder (`/` root or `/docs`).
4. The site will be live at `https://<username>.github.io/stv-release/`.

### Option 2: Project Pages

Push the contents to the `gh-pages` branch of the `stv-release` repository.

## Pages

- `index.html` — Product homepage with features and download CTA
- `manual.html` — Complete user manual (converted from doc/readme.md)
- `screenshots.html` — Screenshot gallery (placeholders — replace with real screenshots)
- `tutorials.html` — Step-by-step tutorials
- `download.html` — Download links pointing to GitHub Releases

## Images

The `images/` folder contains:
- `stv_app.png` — STV application icon (used in header and as favicon)
- `ghc_logo.png` — GHC Consulting logo

For the manual page, copy the full `doc/images/` folder contents into `images/` so the toolbar icons and other manual images resolve.

For screenshots, replace the placeholders in `screenshots.html` with real `<img>` tags pointing to your screenshot files in `images/`.

## Customization

- Brand color is `#00994C` (GHC green), defined as `--green` in `css/style.css`.
- Download links point to `https://github.com/DonPei/stv-release/releases`. Update if the repo URL changes.
