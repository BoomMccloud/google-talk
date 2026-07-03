# Jason Xu — Presentations & Talks

A collection of lightweight, slide-based HTML presentations built using a clean, custom "Founder's Journal" design system (Washi cream, warm ink-black, and vermillion hanko seal red).

No build step, no complex frameworks, just pure semantic HTML, vanilla CSS, and vanilla JS.

## Available Decks

1. **10 lessons I learned at Google** ([index.html](file:///Users/jasonbxu/Documents/GitHub/misc/google-talk/index.html))
   * A presentation summarizing 10 personal leadership and engineering lessons adapted from Addy Osmani's *21 Lessons From 14 Years at Google*.
   * **Structure:** Starts with *User Obsession* as a standalone foundation, followed by three sections: *Attitude*, *Collaboration*, and *Execution*.

2. **The Story of PrepPal** ([preppal-story.html](file:///Users/jasonbxu/Documents/GitHub/misc/google-talk/preppal-story.html))
   * A talk detailing a year-long solo founder journey building a real-time voice AI prep coach with LLMs.

## How to Run Locally

Start a simple web server:

```bash
python3 -m http.server 8080
# then open http://localhost:8080 or http://localhost:8080/preppal-story.html
```

Or just double-click either HTML file to open it directly in your browser.

## Interactive Shortcuts

Within any presentation, you can use the following controls:

| Key / Control | Action |
| :--- | :--- |
| `→` / `Space` / `PageDown` | Go to next slide |
| `←` / `PageUp` | Go to previous slide |
| `Home` / `End` | Jump to first / last slide |
| `F` (or ⛶ button) | Toggle fullscreen |
| `O` (or ⊞ button) | Toggle slide sorter / overview grid |
| `Esc` | Exit overview mode |
| Click in Overview | Jump directly to clicked slide |

## Auto Deployment

Commits pushed to the `main` branch auto-deploy to GitHub Pages via the workflow defined in `.github/workflows/deploy.yml`.

Ensure that in the repository **Settings → Pages**, the **Source** is set to "GitHub Actions".
