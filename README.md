# Alejandro Zenteno — Personal Site

A personal portfolio site with a stellar / astronomical theme. Single-page application built as one self-contained HTML file with no build step or framework dependencies.

## Sections

- **Home** — Bento-grid hero with typing name animation, live Spotify playlist embed, and social link tiles
- **About** — Editorial bio with a drop-capped opening and a "Currently exploring" list
- **Projects** — Filterable project showcase (All / Capital / Operations / Intelligence / Automation)
- **Experience** — Year-grouped timeline of professional and leadership roles with filter pills
- **Contact** — Form wired to [Formspree](https://formspree.io) for real message delivery

## Visual design

- **Color** — Deep plum accent (`#823558` light / `#c890b0` dark) on warm paper / midnight backgrounds
- **Typography** — IM Fell English (display) + Crimson Text (body) + JetBrains Mono (code chips), all loaded from Google Fonts
- **Stellar background** — Live canvas-rendered starfield in night mode (parallax stars, twinkling, a glowing Polaris anchor star, and occasional shooting stars); animated solar system in day mode (sun with rotating sunbeams, three orbiting planets, drifting dust motes, golden haze)
- **Constellation site map** — Small interactive star chart in the top-right corner mapping the five sections; clicking any star navigates to that section
- **Day/night theme** — Smooth toggle in the sidebar that swaps the entire atmosphere

## Tech

- Single `index.html` file — HTML, CSS, and JavaScript all inline
- No frameworks, no build step, no package.json
- Vanilla JS only, ~2,400 lines total including markup, styles, and scripts
- Google Fonts loaded via `<link>` (no self-hosted font files)
- Spotify playlist embedded via `<iframe>` (lazy-loaded)
- Contact form submits to Formspree via `fetch()` so the visitor never leaves the page

## Running locally

No build needed — just open `index.html` in any modern browser.

```bash
# Optionally serve it with any static server
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Deploying

The site is designed for static hosting. Some easy options:

- **GitHub Pages** — push this repo, then in Settings → Pages, select the `main` branch as the source. Your site will live at `https://<username>.github.io/<repo-name>/`.
- **Netlify** — drag the folder onto [netlify.com/drop](https://netlify.com/drop) for an instant deploy.
- **Vercel** — connect the repo and deploy with one click.

## Copyright

© 2026 Alejandro Zenteno. All rights reserved.

This repository is public for transparency and so others can see how I built it, but the code, design, and content are not licensed for reuse. Please don't copy the site wholesale for your own portfolio. You're welcome to study it, learn from it, and draw inspiration — but the specific design, layout, and writing belong to me.

If you'd like to use a piece of this code for something specific, just reach out through the contact form on the live site and we can talk.
