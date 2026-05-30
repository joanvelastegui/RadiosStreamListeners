# Radio Stream Listener Tracker

Live listener monitoring dashboard for 8 radio streams. Auto-fetches data every 30 minutes, stores history in the browser, and lets you export CSV reports.

## Stations monitored
- Rumba · 88-5 · Continental · Amor · Alegria · Caracol · Xtrema · Centro

## Features
- Auto-refresh every 30 minutes (runs automatically once the page loads)
- Selectable stations — toggle any stream on/off in the chart
- Time windows: 1h · 3h · 6h · 12h · All
- CSV export filtered to the selected time window
- Persistent history stored in `localStorage` (up to 24h retained)
- Recent data log table
- Works on Icecast and Shoutcast servers

## Deploy to GitHub Pages

1. Push this repo to GitHub (make sure it contains `index.html` and `.github/workflows/deploy.yml`)
2. Go to **Settings → Pages**
3. Under **Source**, select **GitHub Actions**
4. Push any change to `main` — the workflow auto-deploys

The site will be live at `https://<your-username>.github.io/<repo-name>/`

## Local use
Open `index.html` directly in any browser — no server or build step needed.
