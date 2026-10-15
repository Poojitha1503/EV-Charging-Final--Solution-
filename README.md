# Team 6 — Final EV Charging Site Selection Dashboard

## Publish on GitHub Pages
Upload `index.html` and `data.csv` to the root of `Poojitha1503/EV-Charging-Dashboard` on the `main` branch. In Settings → Pages, deploy from `main` / `(root)`.

## Features
- CSV data loading, basic schema/data validation and upload
- Site filters and six data-analysis charts
- Transparent adjustable suitability scoring for candidate sites
- Ranked candidate table, CSV export, and 3-site comparison
- Illustrative financial scenario calculator
- Founder decision recording in browser localStorage and CSV export
- Enterprise architecture mapping

## Important limitations
- Dataset is synthetic, not live observations.
- Weights are illustrative and normalize to 100% on scoring.
- Site scoring is a relative heuristic, not an empirically validated predictive model.
- Financial values are estimates using editable revenue/operating assumptions, not real ROI.
- Decisions are stored only in the browser. Export to CSV for a durable copy.
- Chart.js and PapaParse load from jsDelivr and require internet access.
- `data.csv` must be alongside `index.html` when hosted on GitHub Pages.
