# Tesla 3 Performance – Highland (Unofficial Fan Page)

One‑page showcase with Apple‑style reveal animations and key specs. Static site, no build step.

## Structure
- index.html – content & sections (Hero, Gallery, Specs, CTA)
- styles.css – responsive layout + animations
- script.js – IntersectionObserver for reveals
- assets/ – put your images here (optional)

## Images
Replace placeholders by adding files under `assets/`:
- assets/hero-1.jpg
- assets/hero-2.jpg
- assets/hero-3.jpg

## Local preview
Just open `index.html` in a browser, or serve with a simple server:

```bash
python3 -m http.server -d . 8080
```

## Deploy (GitHub Pages)
Pages is configured to serve from the `main` branch root. First publish may take 1–3 minutes.
