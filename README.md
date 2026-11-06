# PlayTogether — 2 Player Games

A Poki-inspired two-player game discovery page with an original PlayTogether brand, responsive catalogue, category filters, search, feature shelves, SEO guide content, FAQs, and in-page local mini-game demos.

## Page structure

- Sticky header with search and responsive category navigation.
- “Popular this week” horizontal game shelf.
- Dedicated “2 Player Games” heading and featured game selection.
- Category chips for action, co-op, platform, sports, racing, arcade, classics, and party games.
- Responsive game catalogue with search and show-more behavior.
- Editorial sections for co-op games, versus games, game genres, win mechanics, and FAQs.
- Modal game player that runs the local mini-game prototypes in the same page.

## Important note about the catalogue

Game titles are used as catalogue labels to make the discovery page familiar. The game window launches original, lightweight genre-based prototypes from this repository; it does **not** reproduce or redistribute the commercial Poki games themselves. The design, typography, cards, and decorative artwork are independently implemented, and the project is not affiliated with Poki.

## Run locally

Open `index.html` in a modern browser, or start a server:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Cloudflare Pages deployment

- Framework preset: **None**
- Build command: leave blank
- Build output directory: `. ` is not correct; use `.` (repository root)
- Production branch: `main`

The site is static HTML, CSS, and JavaScript. No build step or framework is required.

## Files

- `index.html` — the complete responsive page, game catalogue, filters, SEO content, and local canvas mini-game player.
- `README.md` — project notes and deployment instructions.
