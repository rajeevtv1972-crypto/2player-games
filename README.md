# Neon Rivals — 2 Player Games

A polished, free, browser-based **two-player arcade racing game**. Play head-to-head on the same keyboard — no install, account, server, external library, ads, or tracking required.

## Play locally

Open `index.html` in a modern browser, or run a tiny local server:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Controls

| Action | Player 1 · Cyan | Player 2 · Pink |
|---|---|---|
| Accelerate | W | ↑ |
| Brake / reverse | S | ↓ |
| Steer left | A | ← |
| Steer right | D | → |
| Pause / resume | Esc or P | Esc or P |

Choose 1, 3, or 5 laps and Chill, Arcade, or Turbo engine power. Stay on the asphalt to keep your speed. First to finish the selected laps wins.

## Deploy free with Cloudflare Pages

1. Open [Cloudflare Dashboard](https://dash.cloudflare.com/) → **Workers & Pages**.
2. Select **Create** → **Pages** → **Connect to Git**.
3. Choose this repository: `2player-games`.
4. Set the production branch to `main`.
5. As this is a static site, leave the build command empty and set the build output directory to `/` (the repository root).
6. Deploy. Cloudflare will provide a public `pages.dev` URL.

Every push to `main` can trigger a fresh deployment.

## Files

- `index.html` — the complete game, styles, canvas renderer, controls, and game loop in one dependency-free file.
- `README.md` — this guide.

## Notes

This version is local multiplayer on one device and keyboard. Online play across separate devices would require a room service and real-time networking, which are intentionally not needed for this lightweight static build.
