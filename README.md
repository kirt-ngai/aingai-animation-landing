# AingA.I. Animation Studios — Landing

Static landing page for AingA.I. Animation Studios.

## Stack
- Plain HTML / CSS — no build step
- Manrope via Google Fonts
- SVG-generated 3D perspective grid
- HEVC-alpha MP4 character videos (WebM fallback)
- AingA.I. Animation logo embedded as inline base64

## Files
- `index.html` — the page (served by Cloudflare Pages at `/`)
- `hero.html` — duplicate kept for local editing reference
- `assets/character-left-transparent.mp4` / `.webm` — girl character
- `assets/character-right-transparent.mp4` / `.webm` — boy character

## Local preview
Just open `index.html` in a browser, or run a quick static server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy
Connected to Cloudflare Pages — every push to `main` redeploys automatically.
