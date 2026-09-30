# 🌾 Fertilizer Management — The Path to Bloom
Self-contained interactive landing page for the Ministry of Agriculture briefing (Sep 2026).

## Deploy in 3 steps
1. Create a repo (e.g. `path-to-bloom`) and push `index.html` + `.github/workflows/deploy.yml`.
2. Repo → **Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. Push to `main`. The workflow deploys automatically to `https://<user>.github.io/<repo>/`.

## Icons
- **Favicon**: inline golden rice-panicle SVG (data URI) — zero external requests.
- **Apple touch icon**: save the attached “Bangladesh Before All” JPG as
  `apple-touch-icon.jpg` (180×180) in the repo root. The page works fine without it.

## No-JS / accessibility
Graceful noscript fallback, ARIA tabs/accordions, `prefers-reduced-motion` respected.
