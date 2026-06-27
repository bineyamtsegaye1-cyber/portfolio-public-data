# Portfolio Public Data Package

This repository is the public citation and source-coverage package for a portfolio of address-based public-service answer sites.

It is not an official government data source and does not replace official records. Each site links to official source pages and labels confidence, reviewed dates, and fallback limits.

Generated: 2026-06-27T02:54:00.702Z

## Current Priority Assets

| Site | Public Data | Source Coverage | Answer API Docs | Widget |
|---|---|---|---|---|
| TrashDayNow | [Data](https://www.trashdaynow.com/data/) | [Source coverage](https://www.trashdaynow.com/data/source-coverage/) | [API docs](https://www.trashdaynow.com/data/answer-api/) | [Widget](https://www.trashdaynow.com/widgets/trash-day-widget/) |
| Build Permit Radar | [Data](https://www.buildpermitradar.com/data/) | [Source coverage](https://www.buildpermitradar.com/data/source-coverage/) | [API docs](https://www.buildpermitradar.com/data/answer-api/) | [Widget](https://www.buildpermitradar.com/widgets/permit-lookup-widget/) |

## Data Files Published By Each Site

- `/data/source-coverage.json`
- `/data/source-coverage.csv`
- `/data/priority-answers.json`
- `/api/answer`
- `/widgets/embed.js`
- `/llms.txt`
- `/source-summary/`

## Priority Pages

### TrashDayNow

- [Trash pickup by address](https://www.trashdaynow.com/trash-pickup-by-address/)
- [Trash pickup tomorrow](https://www.trashdaynow.com/trash-pickup-tomorrow/)
- [San Antonio trash pickup tomorrow](https://www.trashdaynow.com/cities/san-antonio-tx-trash-pickup-tomorrow/)
- [San Antonio trash day](https://www.trashdaynow.com/cities/san-antonio-tx-trash-day/)
- [Miami trash pickup tomorrow](https://www.trashdaynow.com/cities/miami-fl-trash-pickup-tomorrow/)
- [Miami garbage pickup schedule](https://www.trashdaynow.com/cities/miami-fl-trash-pickup/)

### Build Permit Radar

- [Building permits by address](https://www.buildpermitradar.com/building-permits-by-address/)
- [Open permits on property](https://www.buildpermitradar.com/open-permits-on-property/)
- [Building permit history](https://www.buildpermitradar.com/building-permit-history/)
- [San Jose permit lookup](https://www.buildpermitradar.com/cities/san-jose-ca-permit-lookup/)
- [San Jose building permit history](https://www.buildpermitradar.com/cities/san-jose-ca-building-permit-history/)
- [Houston building permit search](https://www.buildpermitradar.com/cities/houston-tx-building-permits/)
- [Chicago permit search by address](https://www.buildpermitradar.com/cities/chicago-il-building-permit-lookup-by-address/)
- [Phoenix open permits](https://www.buildpermitradar.com/cities/phoenix-az-open-permits-on-property/)
- [Seattle SDCI permit lookup](https://www.buildpermitradar.com/cities/seattle-wa-permit-lookup/)
- [Boston Permit Finder](https://www.buildpermitradar.com/cities/boston-ma-permit-lookup/)

## Trust Policy

- This repository publishes public citation metadata only.
- Official source owners retain their own data rights.
- This staged external-authority pilot currently covers only TrashDayNow and Build Permit Radar.
- Do not treat source coverage as a final official decision.
- Never invent trash schedules, street rules, school assignments, permit records, or confidence labels.
- Use the linked official source and canonical page for final records.

## Suggested External Use

- Cite a specific city/district answer page instead of a homepage.
- Link to `/data/source-coverage/` when referencing source coverage.
- Use widgets only where they genuinely help local users.
- Prefer local guides, HOA/community resources, real estate resource pages, civic-tech references, and open-data directories where the link helps users.
- Do not mass-submit, spam-bookmark, or present portfolio sites as official agencies.

## Machine-Readable Files

- `catalog.json`: complete public catalog.
- `data.json`: endpoint and dataset index.
- `coverage-index.json`: compatibility alias of the catalog.
- `priority-pages.json`: high-priority citation and discovery URLs.
- `external-discovery-targets.json`: no-spam target categories and review rules.
