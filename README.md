# Trichome: decision intelligence for cannabis dispensaries

**Trichome** is Vector1 Research's analytics engine for licensed cannabis operators. It reads a dispensary's POS sales, seed-to-sale inventory, promotions, marketing spend and staff schedule, and returns a dollar-ranked list of what to change this week.

**[Try the live demo](https://vector1.ai/demos/trichome/)** · **[vector1.ai](https://vector1.ai)** · **Pilots: brian@vector1.ai**

> This repository is a public showcase: documentation, sample outputs and a link to the interactive demo on vector1.ai. The engine itself is proprietary and available only through a Vector1 engagement.

## What it finds in a typical store

On a two-year synthetic Missouri-style dispensary (about $7.8M a year in revenue, 11% medical), Trichome identified $293K a year in profit opportunities. Because the store is synthetic, every line can be graded against the known answer, and the marketing line is overstated, so a fair total is **about $243K a year**, plus $80K of aging stock recovered and $48K of cash released:

| Area | Finding | Annual value |
|---|---|---:|
| Marketing | Shift the same budget toward SMS and menu listings, away from saturated billboards and events | $115K estimated, $66K true |
| Inventory | Stockouts on top sellers before the next delivery | $63K |
| Finance | 280E relief on medical sales since the April 2026 Schedule III order | $61K |
| Operations | Staffing to traffic: fewer paid hours, 82% to 89% of customers served within two minutes | $27K |
| Marketing | 17 of 21 promotions lost margin once sales that would have happened anyway are counted | $26K |
| Inventory | Markdowns that clear aging lots before their freshness window closes | $80K recovered |
| Inventory | Cash in stock that can't sell in 90 days | $48K one-time |
| Compliance | Sales over Missouri's 3 oz adult-use limit and medical 30-day limit | license risk |

## What it covers

**Inventory.** A forecast for every product that accounts for weekdays, cannabis holidays and the promo calendar. A weekly reorder list that never buys more than will sell while fresh. A markdown list for lots that will age out at full price, and the cash tied up in slow stock.

**Marketing.** Which promotions made money and which gave margin away. What each compliant channel (SMS, email, menu listings, billboards, events) actually added, with a range, and a better split of the same budget. Loyalty segments, lifetime value and a win-back list. A screen for ad copy against health-claim, minor-appeal and state imagery rules.

**Operations.** Budtenders needed each hour for a service standard you choose, compared with the schedule you run, plus a 4/20 plan from your own past traffic. A purchase-limit audit in flower-equivalent grams. Store KPIs: GMROI, turns, basket, item price trend.

**Finance.** Federal tax under 280E today, before April 2026 and after full rescheduling, under each expense allocation method, for dual-license stores working with their CPA.

## How an engagement works

1. A 30-minute call about your systems, licenses and the problem that costs you most.
2. A pilot agreement, then 12 to 24 months of exports (POS, seed-to-sale, promotions, marketing, schedule).
3. In two to three weeks: the sized opportunity report, reorder and markdown lists, a staffing grid and a 280E memo.
4. Optional weekly refresh as a managed service, single store or multi-location.

Your data stays private and is deleted at the end of the engagement.

## Documentation

- [How results are validated](docs/validation.md)
- [What data we need](docs/data-we-need.md)
- [Live demo on vector1.ai](https://vector1.ai/demos/trichome/)

## About

Vector1 Research is an applied machine learning, causal inference and economics lab in Kansas City. Contact brian@vector1.ai.

Demo data is synthetic. Outputs are estimates for decision support, not legal, tax or compliance advice. © 2026 Vector1 Research. All rights reserved.
