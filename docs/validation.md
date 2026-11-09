# How results are validated

Every Trichome result is checked before an operator sees it. The engine is proprietary; this page describes how its answers are tested, not how they are produced.

## Graded against a known truth

Trichome ships with a synthetic dispensary generator that builds a full two-year store (sales, loyalty customers, promotions, marketing spend, lots and a staff schedule) whose true answers are known: how much each channel really adds, how customers respond to discounts, which baskets break the purchase limit. Each model is scored against those answers, and the results are published as they are, including where a model is off. In the public demo, the channel estimates sit next to the true values, and the overstated marketing line is reported at its true value.

## Backtested on history

Forecasts are tested the way they are used: trained on the past, scored on weeks the model has not seen, and compared with the 28-day run rate most buyers order from. On the sample store the weekly error is 14.3% against 15.8% for the run rate.

## Reported with ranges and caveats

Estimates that one store's data cannot pin down come with a range and a recommended check, such as a holdout test before moving marketing budget. Figures that rest on a judgment, such as how a one-week stockout snapshot annualizes, are labeled as such.

## Regulatory figures sourced and dated

State rules (Missouri purchase limits and equivalency, advertising restrictions) and federal tax status are recorded with their sources and the date they were checked, and are confirmed again at the start of each engagement. Tax and compliance outputs are estimates to review with a CPA and compliance team, not advice.

Sources checked November 2026:
- Missouri DHSS, [Patient and consumer FAQs](https://health.mo.gov/safety/cannabis/faqs-patient.php) and [Online advertising guidance](https://health.mo.gov/safety/cannabis/pdf/advertising-marijuana-product-online-guidance-063025.pdf)
- DEA, [Marijuana rescheduling regulatory actions](https://www.dea.gov/marijuana-rescheduling-regulatory-actions)
- Federal Register, [document 2026-08176](https://www.federalregister.gov/documents/2026/04/28/2026-08176)
