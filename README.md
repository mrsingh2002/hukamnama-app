# Hukamnama App

Daily Hukamnama from Sri Harmandir Sahib (the Golden Temple, Amritsar), displayed in Gurmukhi, Punjabi, and English.

## What it shows

- Today's date and Hukamnama metadata (Ang/page number, Raag, Composer)
- Each verse in Gurmukhi (Unicode script)
- English transliteration
- Punjabi meaning
- English translation

## Tech

Single `index.html` — no build step, no dependencies, no framework. Fetches live data from the [BaniDB API](https://www.banidb.com) on page load.

**API used:** `GET https://api.banidb.com/v2/hukamnamas/today`

## Run locally

Just open `index.html` in a browser. No server needed.

## Deploy

Drop `index.html` anywhere — GitHub Pages, Netlify, Render static site, or any web host.

### GitHub Pages (quickest)

1. Push to a GitHub repo
2. Go to Settings → Pages → Source: Deploy from branch → `main` / `root`
3. Done — live at `https://<username>.github.io/<repo-name>`

## Data source

Powered by [BaniDB](https://www.banidb.com) — a free, open Gurbani database maintained by the Sikh community. Hukamnama is sourced daily from Sri Harmandir Sahib.
