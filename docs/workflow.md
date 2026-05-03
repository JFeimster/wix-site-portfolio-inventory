# Wix Site Portfolio Inventory Workflow

## Operating Flow

```text
Wix Connector → ChatGPT review → local CSV/Markdown snapshot → Notion database → GitHub archive
```

## Step-by-Step Process

1. Pull core Wix site metadata with the Wix connector.
2. Confirm the site is inside the approved inventory scope.
3. Draft a single row with connector-confirmed values.
4. Add strategic/inferred fields only when clearly grounded.
5. Ask for review or approval before moving to the next site.
6. Append approved rows to the CSV source file.
7. Add approved rows to the Notion database.
8. Commit updated CSV and docs to GitHub.

## Approval Gate

Each site should be handled one at a time. After each site row is generated, stop for review before proceeding.

## Storage Roles

- Notion: live working database and dashboards
- CSV: portable source file and import/export layer
- GitHub: version-controlled archive
- Wix: upstream source data
