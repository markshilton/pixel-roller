# Pixel Roller

A retro arcade-style estimation game where players try to unroll spirals to land exactly on the goal line.

**Play now:** https://markshilton.github.io/pixel-roller/

## How to Play

1. Select the number of players (1-4)
2. Each player drags their spiral left along the track to position it
3. Click **ROLL** to unroll all spirals simultaneously
4. The spiral that lands closest to the goal line wins

The challenge: each spiral has a different size and coil spacing, so you need to estimate how far it will unroll.

## Features

- 1-4 player local multiplayer
- Procedurally generated spirals with varying sizes
- Retro arcade aesthetic with neon glow effects and CRT scanlines
- Touch support for mobile devices
- No dependencies - single HTML file

## Setup

This is a static single-page game with no build process required.

```
pixel-roller/
├── index.html    # Complete game (HTML + CSS + JS)
└── README.md
```

### Run locally

Open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

### Deploy

The game is deployed via GitHub Pages from the `main` branch. Any push to `main` automatically updates the live site.

### Contributing

Direct pushes to `main` are blocked. All changes must go through a pull request:

```bash
# Create a feature branch
git checkout -b my-feature

# Make changes, then commit
git add . && git commit -m "My changes"

# Push the branch
git push -u origin my-feature

# Create a PR
gh pr create --fill

# Merge when ready
gh pr merge --squash
```

## Analytics

PostHog is configured for basic web analytics.

## License

MIT
