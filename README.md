# Frozandero's project directory

The homepage at **[frozandero.github.io](https://frozandero.github.io/)**, linking to:

- [VOD Sync](https://frozandero.github.io/twitch-vod-sync-monolith/) — Twitch and Kick recordings on a shared timeline.
- [Mineable Quality Distributions](https://frozandero.github.io/starcitizen-mineable-quality-distributions/) — Star Citizen resource-quality comparisons.

## Run locally

This is a static HTML/CSS site with a top bar and two clickable project cards. No build step or dependencies are required. Open `index.html` directly, or serve this directory:

```sh
python -m http.server 8000
```

Visit `http://localhost:8000`.

## Edit and publish

Edit the project links, descriptions, and inline SVG icons in `index.html`, styling in `styles.css`, and the site icon in `favicon.svg`.

GitHub Pages publishes from the root of `main`. `.nojekyll` keeps the files static. Push to `main` to deploy. The two project sites remain in their own repositories at their existing paths.

The page works without JavaScript or external assets, respects reduced-motion preferences, and includes keyboard focus states.
