# The Gem — Roster Demo

Static demo of a custom rostering app built for **The Gem**, a convenience + ice cream shop in Howth Harbour, Co. Dublin.

Live: see GitHub Pages link in the repo's About section.

## What's inside (single-page HTML, no backend)

- **Dashboard** — live Howth weather forecast (Open-Meteo), KPIs, today's shifts
- **Roster** — 12-staff weekly grid with 3-zone colour palette, click-to-edit shifts with custom time inputs, ✨ Auto-generate using real shop rules (Helena mornings only, Gavin Thu–Sun lock, Rushikesh/Mark paired-only, anchor days for Joan/Helena)
- **Availability** — tap-to-cycle 4-state grid, saved to localStorage
- **Swaps** — open marketplace + direct peer swaps, claim → manager approval flow
- **Leave** — pending requests with approve/reject
- **Staff** — 12 active staff with capability chips and full detail modal (phone, address, emergency contact, RTW, bank, tenure)
- **Payslip** — real Irish PRSI + USC math, day-by-day breakdown, CSV export
- **Print / PDF** — landscape A4 export of the roster and payslip

## Tech

Single self-contained `index.html`. No build step, no dependencies, no backend. Persists demo state in `localStorage`. Loads Google Fonts + Open-Meteo at runtime.

## Built by

Rushikesh Bodkhe — MSc Business Analytics, Dublin City University. Floor staff at The Gem.
