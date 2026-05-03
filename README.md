# Wix Site Portfolio Inventory

Operational source archive for auditing, organizing, and managing the selected Wix site portfolio.

## Purpose

This repo stores portable source files for the Wix Site Portfolio Inventory project: CSV exports, schema documentation, workflow notes, and highlighted-site scope.

## Operating Flow

```text
Wix Connector → ChatGPT review → local CSV/Markdown snapshot → Notion database → GitHub archive
```

## Notion Assets

- Master page: `Wix Site Portfolio Inventory`
- Database: `Wix Sites Inventory`
- Inline dashboard views:
  - `All Wix Sites`
  - `Flagship + High SEO Priority`
  - `Rebuild / Merge / Kill Queue`

## Repository Structure

```text
README.md
data/
  wix_site_portfolio_inventory.csv
  snapshots/
    wix_site_portfolio_inventory_2026-05-03.csv
docs/
  schema.md
  workflow.md
  highlighted-sites.md
exports/
  wix_site_inventory_schema_and_workflow.md
```

## Current Scope

Initial inventory scope is limited to the Wix sites highlighted in the provided Wix Studio screenshots. Moonshine Capital is the first starter row.

## Source of Truth

- Working database: Notion
- Portable source file: CSV
- Version-controlled archive: GitHub
- Raw upstream source: Wix connector/API
