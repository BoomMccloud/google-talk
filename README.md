# The Story of PrepPal

Talk by Jason Xu (ex-Google, ex-Alibaba) — a year-long solo journey building a voice AI product with AI.

Single static HTML file. No build step. No framework.

## Run locally

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

Or just double-click `index.html` to open in your browser.

## Keyboard shortcuts

| Key | Action |
|---|---|
| `→` / `Space` / `PageDown` | Next slide |
| `←` / `PageUp` | Previous slide |
| `Home` / `End` | First / last slide |
| `F` | Toggle fullscreen |
| `O` | Toggle overview (all slides as grid) |
| `Esc` | Exit overview |

## Deploy

Pushes to `main` auto-deploy to GitHub Pages via `.github/workflows/deploy.yml`.

To enable: in the repo's **Settings → Pages**, set **Source** to "GitHub Actions".
