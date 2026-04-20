# Pack 3 — Market Research Pack (Document Synthesis Task)

## What's here

Eight unstructured sources about the home-goods competitive landscape:

1. **`01-2026-home-goods-market-trends.md`** — Coastal Research Partners analyst report on the U.S. home goods market
2. **`02-direct-to-consumer-home-goods-2025.md`** — Caravan Insights DTC industry year-in-review
3. **`03-competitor-restwell-landing-page-scrape.md`** — scraped homepage copy from RestWell, our closest subscription-bedding competitor
4. **`04-customer-interview-jessica-k.md`** — 24-minute Zoom transcript, loyal customer, discusses subscription awareness
5. **`05-customer-interview-michael-t.md`** — 18-minute Zoom transcript, lapsing customer, discusses product-quality inconsistency
6. **`06-press-release-restwell-series-b.md`** — RestWell's $60M Series B announcement
7. **`07-retail-foot-traffic-internal-notes.md`** — internal analyst notes on Q1 retail store performance
8. **`08-q4-2025-user-survey.xlsx`** — 200-row survey data + summary tab skeleton

## The prompt

Download this folder (or the whole repo ZIP), point Claude Cowork at it, and paste:

```
Inside /pack-3-research-pack are eight sources: two analyst reports,
a competitor landing page scrape, two customer interview transcripts,
a press release, internal analyst notes, and a 200-row user survey.

Read all eight, then produce a market research brief as a formatted
PDF with these sections:

1. Executive Summary — three bullets max
2. Competitive Positioning — how the players differentiate, with
   particular focus on RestWell (our closest competitor)
3. Customer Pain Points — ranked by frequency, with direct quotes
   from the interviews and survey verbatim comments
4. Recommendations — three concrete bets we could make

Cite each finding by source filename so I can verify.
Save as market-research-brief.pdf in the parent folder.
```

## What good output looks like

A 3-5 page PDF that:
- Correctly identifies the subscription awareness gap (surfaces in both interviews + survey)
- Flags the RestWell $89-starter pricing threat
- Catches the towel quality complaints as a concrete product issue
- Ties the retail foot-traffic conversion win to the Denver expansion recommendation
- Cites sources by filename so every claim is traceable

## One-pattern, many-uses

The synthesis pattern is where Cowork earns its keep. Run it against interview transcripts for customer discovery. Against competitor intel for positioning briefs. Against review-site scrapes for voice-of-customer work. Against analyst reports for investment memos. Same three moves: point at folder, describe desired output, ask for citations.
