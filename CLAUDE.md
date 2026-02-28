# sughu-personal-website

Single-page personal site for Sughanthan Sekar (sughu).

## Stack

- Single `index.html` file — no build step, no framework
- Fonts: DM Sans (body) + Source Serif 4 (display) via Google Fonts
- Hosted on GitHub Pages from `main` branch

## Design Rules

- **All text is lowercase** — name, section labels, descriptions, links, dates. This is intentional.
- Hover zoom: 7% scale on all clickable elements (articles, projects, contact links, bio)
- Scroll-linked animations: hero zoom (1.35 -> 1.0 -> 0.85), section fold reveal (rotateX + scale + opacity)
- Sticky hero header with gradient fade
- Lerp-based smooth animation (smoothing factor: 0.22)
- Respects `prefers-reduced-motion`

## Color Palette

- Background: `#faf9f7`
- Text: `#1c1917`
- Text secondary: `#57534e`
- Text muted: `#a8a29e`
- Accent (active tags): `#4caf82`
- Borders: `#e7e5e4` / `#f5f5f4`

## Deployment

- Repo: private on GitHub (`1stprinciples/sughu-personal-website`)
- Deployed via GitHub Pages (static, from `main` branch root)
- No build step — just push and it's live

## Files

- `index.html` — the site
- `index_codex.html` — earlier draft (keep for reference)
