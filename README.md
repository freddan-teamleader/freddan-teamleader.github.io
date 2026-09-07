# teamleader.se

Static brand site for **teamleader.se**. Plain HTML/CSS/JS — no build step.

Previously a Hugo (`hyde`) site; that has been retired in favour of the
hand-built landing page (extracted from the lunch-guide repo, which used to serve
it). The lunch guide is now a separate project on
[`lunchguide.teamleader.se`](https://lunchguide.teamleader.se).

## Deploy

GitHub Pages serves from **`main` → `/docs`**. Everything the browser gets lives
in `docs/`:

- `docs/index.html` — the landing page (EN/SV toggle, AI-stack section, a
  client-side simulated MCP-trace demo, contact CTA)
- `docs/variants/`, `docs/canvas.html`, `docs/design-canvas.jsx` — landing-page
  design directions (internal previews)
- `docs/CNAME` — custom domain `teamleader.se`
- `docs/.nojekyll` — serve files as-is (no Jekyll processing)
- favicons + `site.webmanifest`

Edit files under `docs/` and push to `main`; Pages publishes automatically.

## Related projects

- **Lunch Guide** — MCP server + web UI, `lunchguide.teamleader.se` (repo: `dimelords/lunchguide`)
- **Music Roaster** — party-song app, `music.teamleader.se` (repo: `dimelords/music-roaster`)

> `golfquiz/` is a separate app kept in this repo and is not part of the static site.
