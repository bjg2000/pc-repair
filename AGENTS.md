# Agents.md

## Repo purpose
Business plan + website for a Dartmouth, MA home-based PC repair business.

## Contents
- `business-plan.md` — the running plan (legal, website, ops, pricing, marketing, todo)
- `business-plan.md` bottom section has a "Topics for Next Session" list — start there if it's non-empty

## Internal tools
- AI-assisted diagnostics / tune-ups via portable OpenCode USB — used in-house, never advertised
- Website and marketing must never mention AI — customer demographic is tech-averse

## Conventions
- Update `business-plan.md` in place as decisions are made — append new sections at logical spots, mark checklist items complete
- Website will live on GitHub Pages (`bjg2000.github.io/<repo>`), built with plain HTML (no framework)
- Booking integration: Google Forms, Calendly, or SchedulingKit embed on static site
- No backend, no build tooling for the website
- Optional quote calculator (like `cost_calculator.html` in the pastry shop repo) — dropdown of services, pulls pricing from a Google Sheet

## Key decisions (honor these)
- Operating as sole proprietor initially, may upgrade to LLC later
- Home-based in Dartmouth, MA — parents own the house, not involved in business
- Flat-rate pricing, tiered by service method (drop-off/remote vs in-home on-site)
- Service radius ~10-15 miles (Dartmouth, New Bedford, Fall River, Westport)
- No parts inventory upfront — order per-job at customer's expense (no markup)
- Data recovery not offered — liability risk
- In-home carry kit packed per-visit (diagnostic USB, tools, anti-static mat, thermal paste, cables, business cards)
