# IT-Inventory-asset-tools
A collection of tools I built to track and audit IT hardware in the storeroom — replacing manual counts and manual asset reconciliation with fast, real-time workflows.

## About Me
IT Support Analyst working across hardware asset management, ServiceNow administration, user onboarding, and storeroom operations. I build small internal tools to cut down repetitive manual work wherever I spot it.

## Tools

| Tool | What it does | Impact |
|------|--------------|--------|
| [Storeroom Stock Count](01-storeroom-stock-count) | iPad app for live hardware stock tracking in the storeroom — add/checkout updates the count in real time | Eliminated manual physical stock counts |
| [Storeroom Hardware Audit](02-storeroom-audit-app) | Scan-and-compare web app that reconciles physical storeroom hardware against ServiceNow asset records | Turned a manual audit of 400-500+ assets into a fast scan-and-compare process |

## Tech Stack
- **Power Apps** (canvas app) — storeroom stock count app
- **Custom web app** (HTML/JS, built and customized with Claude AI assistance) — hardware audit tool
- **SharePoint** — data source for live stock levels
- **ServiceNow** — source of truth for hardware asset records, exported as CSV for reconciliation
- **Handheld barcode scanner** — asset input for the audit tool

## Structure
Each tool folder contains:
- `README.md` — problem, solution, tech used, impact
- `screenshots/` — app screens and sample results (sanitized)

---
*Note: These tools were built for internal team use. Screenshots and descriptions are sanitized — no real employee, asset, or company-identifying data is included.*
