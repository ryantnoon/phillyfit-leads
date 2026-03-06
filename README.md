# PhillyFit Leads

A lead generation identification platform for gym and fitness equipment sales targeting the Greater Philadelphia area.

## Overview

This dashboard tracks **103 qualified leads** across 5 facility categories that may need to purchase or upgrade gym/fitness equipment:

| Category | Leads | Examples |
|---|---|---|
| Apartment / Multifamily | 26 | New luxury apartments, office-to-residential conversions |
| PT / Rehabilitation | 19 | New clinic openings, rehab hospital construction, practice acquisitions |
| Senior Living / Care | 19 | CCRC expansions, nursing home renovations, new assisted living builds |
| Hotel / Commercial / Club | 18 | Hotel renovations, corporate fitness centers, YMCA expansions, country clubs |
| Education / Recreation | 21 | University rec center upgrades, Philadelphia Rebuild program, school modernizations |

## Features

- **Dashboard Overview** — KPI cards, category distribution chart, priority donut chart, high-priority leads preview
- **Full Leads Table** — Sortable, filterable, searchable across all 103 leads
- **Lead Detail Panel** — Slide-out panel with full facility info, lead signal, contact details, and source links
- **Category Filtering** — Quick filter by sidebar category or dropdown
- **CSV Export** — Download all filtered leads as CSV
- **Global Search** — Search across facility name, company, address, and lead signals
- **Dark/Light Mode** — Full theme support
- **Mobile Responsive** — Sidebar collapses to hamburger menu on mobile

## Lead Signals

Each lead includes a "Lead Signal" explaining why the facility is a potential customer:
- New construction requiring full fitness center equipment
- Renovation/expansion adding or upgrading fitness spaces
- Equipment refresh cycles (7-10 year lifecycle)
- Acquisition/rebrand triggering equipment standardization
- Bond financing explicitly earmarked for capital equipment acquisition
- New ownership triggering facility assessments

## Deploy to Vercel

### Option 1: Direct Deploy
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import the GitHub repo
4. Framework: "Other" (static site)
5. Output directory: `.` (root)
6. Click Deploy

### Option 2: Vercel CLI
```bash
npm i -g vercel
vercel
```

### Option 3: One-Click
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/phillyfit-leads)

## Local Development

```bash
npx serve .
```

Open [http://localhost:3000](http://localhost:3000)

## Tech Stack

- Pure HTML/CSS/JavaScript (no framework dependencies)
- [Chart.js](https://www.chartjs.org/) via CDN for data visualization
- [Inter](https://rsms.me/inter/) typeface via Google Fonts
- CSS Custom Properties for theming
- Responsive grid layout

## Data Sources

All leads were researched from public sources including:
- Commercial real estate development announcements
- Municipal planning and zoning records
- Company press releases and news articles
- Bond financing public hearing notices
- Healthcare facility licensing records
- University campus development plans
- Philadelphia Rebuild program documentation

## License

Private — internal use only.
