# Taylormade Title

Modern rebuild of the Taylormade Title website — residential & commercial title insurance across North & South Carolina.

Static site with an Apple-inspired aesthetic: floating glassmorphic cards, soft gradient-mesh backgrounds, scroll-reveal motion, and a sticky glass navbar. No build step required.

## Structure
- `index.html` — Home
- `services.html` — Residential/Land, Closing, Commercial
- `homeowners.html` — Buyers, Sellers, Title Insurance explained
- `assets/css/style.css` — design system
- `assets/js/main.js` — nav, scroll reveal, accordion, parallax
- `assets/img/` — optimized site imagery

## Run locally
Open `index.html` in a browser, or serve the folder:
```
python3 -m http.server 8000
```
Then visit http://localhost:8000

## Deploy
Any static host works (GitHub Pages, Netlify, Vercel, Cloudflare Pages). For GitHub Pages: Settings → Pages → deploy from `main` / root.
