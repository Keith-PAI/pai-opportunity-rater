# PAI Opportunity Rater

A mobile-first Progressive Web App for rating PAI AeroNews Opportunity Spotter outputs via Tinder-style swipe cards.

## Features

- **Swipe cards** — Rate opportunities by swiping right (more), left (less), or up (act on this)
- **Weighted users** — Each rater has a role and weight for scoring
- **PWA installable** — Works offline, installable on iOS and Android home screens
- **Persistent storage** — Ratings accumulate in localStorage across sessions
- **Export** — Download all historical ratings as JSON

## Usage

Serve the directory with any static file server:

```bash
npx serve .
# or
python3 -m http.server 8000
```

Open on your phone and tap "Add to Home Screen" to install.

## File Structure

```
├── index.html      # Full app (CSS + JS inline)
├── manifest.json   # PWA manifest
├── sw.js           # Service worker for offline caching
└── README.md
```
