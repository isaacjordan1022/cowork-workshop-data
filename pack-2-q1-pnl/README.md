# Pack 2 — Q1 Marketing P&L (Spreadsheet Analysis Task)

## What's here

- **`Q1-2026-Marketing-PNL.xlsx`** — the main workbook, 5 tabs: Summary, Revenue, Costs, Budget, Vendors
- **`board-memo-q1-preliminary.md`** — a 1-page board memo from the Director of Growth Marketing giving narrative context
- **`vendor-invoices-q1.xlsx`** — raw vendor invoice log backing the Costs tab
- **`paid-media-jess-wip.xlsx`** — Jess's messy working version of paid media numbers, not reconciled
- **`channel-attribution-raw.csv`** — 90 days of ad-channel attribution data (impressions, clicks, orders, revenue, spend)

## The prompt

Download this folder (or the whole repo ZIP), point Claude Cowork at it, and paste:

```
I've just downloaded Q1-2026-Marketing-PNL.xlsx — a raw Q1 marketing P&L
with revenue, cost categories (paid media, creative, tools, headcount),
and monthly columns. Do three things:

1. Analyze it — find the 3 biggest cost variances month-over-month
   and flag anything that increased by more than 25%.

2. Build a dynamic Dashboard tab next to the raw data:
   - KPI cards at top: Total Revenue, Total Spend, Net Margin
   - A chart showing spend by category
   - A conditional-format column on the raw data that highlights
     every over-budget line in terra red

3. Save it back as Q1-2026-Marketing-PNL-dashboard.xlsx with real
   working formulas, not static values. I want to change a cell
   and watch the KPIs update.

Cross-reference with the board memo (board-memo-q1-preliminary.md)
and the Jess WIP spreadsheet if anything looks off.
```

## What good output looks like

A new workbook with a Dashboard tab that has live formulas, conditional formatting applied to the raw tabs, and a written summary that correctly identifies:
- The March paid-media overage (~40% vs. budget)
- The Anthropic Enterprise tools overage (one-time annual pre-pay)
- The mystery "Brightside Media" $45K vendor with no PO
- The creative underrun (a genuine win)

## One-pattern, many-uses

The prompt shape works for any numbers-heavy role. Pipeline reports with win-rate dashboards. Ad-spend-vs-revenue blended dashboards. Budget-vs-actuals with drill-down. Comp benchmarking. SLA tracking. NPS trending. Point Claude at raw data, describe the analysis, ask for a dashboard with working formulas.
