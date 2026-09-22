# Pouya Karimi — Personal Landing Page

A bilingual Persian/English personal-brand landing page for Pouya Karimi.

## Files

- `index.html` — page structure and content
- `style.css` — responsive visual system
- `script.js` — language switcher and scroll progress
- `assets/profile.webp` — portrait
- `assets/location-intelligence.png` — GIS / retail location project
- `assets/national-retail-network.png` — national network map
- `assets/performance-planning.png` — sales planning visual
- `assets/market-performance-map.png` — market/store intelligence visual
- `assets/pooya-karimi-cv.pdf` — source CV

## GitHub Pages

1. Create a new GitHub repository, e.g. `pooya-karimi`.
2. Upload **all files and the `assets` folder**, keeping the folder structure unchanged.
3. In GitHub go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. After deployment, open the generated GitHub Pages URL.

### Important

Do not move `profile.webp` out of `assets/`.

The portrait is referenced as:

`assets/profile.webp`

All other project images use the same relative-path convention, so the site works on GitHub Pages without absolute local paths.

## Bilingual mode

The page starts in English. Use `EN / FA` in the header to switch languages.  
You can also open the Persian version directly by adding `#fa` to the page URL.

## Editing

The main content is stored in `script.js` inside the `translations` object.  
Visual styling is in `style.css`.

The page is intentionally static: no backend, build step, framework, or npm installation is required.
