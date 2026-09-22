# Las Vegas RE+ 2026 — Trip Planner

Self-contained English HTML trip page for **Krystian & brother**: RE+ 26 at Las Vegas Convention Center, Mon Nov 16 – Wed Nov 18, 2026.

## Files

- `index.html` — full app (CSS + JS inline, Leaflet/OSM from CDN)
- `images/` — hotel room photos downloaded from official CDNs (paths `images/*` — do not swap to remote URLs)
- `README.md` — this guide
- `.nojekyll` — empty helper for GitHub Pages

## Open locally

1. Clone or copy this folder.
2. Open `index.html` in a browser, **or**
3. Local server (useful if `file://` blocks some assets):

```bash
cd vegas-re-2026
python3 -m http.server 8080
# then http://localhost:8080
```

Map needs network (OpenStreetMap tiles + Leaflet from unpkg). Photos load locally from `images/`.

## GitHub Pages

Published from branch `main` at repo root:

```bash
# already done for krystianwalec/vegas-re-2026
# Settings → Pages → Source: Deploy from a branch → main → / (root)
```

Live URL: **https://krystianwalec.github.io/vegas-re-2026/**

No build step or Node — static HTML only.

## Page contents

- **Critical Uber/Loop notice** — Loop airport ~10am–9pm fails Mon ~11pm arrival and Wed ~4–4:30am departure
- **Itinerary** — Mon arrive / Tue Expo 10am–6pm / Wed early exit
- **Hotels (equal 5)** — Hilton Resorts World, Las Vegas Marriott, Westgate, Fontainebleau, Sahara — TLDRs, firm-bed notes, amenities, room photos, estimate rates only
- **Leaflet map** — hotels, LVCC, Loop stations, Harry Reid T1/T3
- **Loop hours & fares** + official links
- **Vendors** — St. Thomas 3×~4k sqft solar+batteries; book Tesla N527 ahead; Enphase; Sol-Ark/FranklinWH/Enstall walk-up OK
- **Tickets** — Tue Expo One-Day $225/$275 + how to ask exhibitors for Customer Invitation codes
- **Checklist** — outreach, passes, hotel, brother’s EWR times, pre-schedule Uber

Research sources: `/workspace/vegas-re-2026/research.md`, `vendors.md`, `hotel-extras.md` (Sep 21, 2026 PT). Nothing booked.
