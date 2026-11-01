# PlayTogether — Browser Games

A Poki-inspired game discovery homepage with an original PlayTogether identity and locally playable mini-game prototypes. The interface is designed for desktop, tablet, and mobile browsers.

## Features

- Compact search header and category navigation.
- Featured game mosaic and popular-games grid.
- Horizontal collections for fresh picks, co-op/party, racing, action/adventure, and puzzles/classics.
- Search, category filtering, and show-more behavior.
- In-page modal game player; clicking a card does not navigate to another game website.
- Original canvas mini-game demos with keyboard and basic touch controls.
- No framework, build step, external game-site redirect, ads, or tracking.

## About the playable games

The catalogue uses familiar game titles as discovery-style examples, but the playable content in this repository is **an original set of small genre-based demos**, not the full licensed Poki games or exact recreations. Current demo modes include paddle play, obstacle dodging, arena movement, co-op collection, reaction timing, and tic-tac-toe. The project is independently branded and is not affiliated with Poki.

## Run locally

Open `index.html` in a modern browser, or start a local server:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Deploy with Cloudflare Pages

1. Open Cloudflare Dashboard → **Workers & Pages**.
2. Connect the GitHub repository `rajeevtv1972-crypto/2player-games`.
3. Set the production branch to `main`.
4. Select **None** as the framework preset.
5. Leave the build command empty.
6. Set the build output directory to `.` (the repository root).
7. Deploy.

Every push to `main` can trigger a new deployment when the Pages project is connected to GitHub.

## Project files

- `index.html` — homepage, styles, filtering/search logic, and canvas mini-game prototypes.
- `README.md` — this guide.

## Next step

To host a real catalogue of distinct games, add original games or games whose developers explicitly permit embedding/redistribution, and connect each catalogue card to its approved game build. Many commercial game pages block third-party iframe embedding, so an iframe alone is not a reliable substitute for a game integration.
