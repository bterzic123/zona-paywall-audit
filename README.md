# Paywall Audit — Zona

**Live:** https://bterzic123.github.io/zona-paywall-audit/
**Prototype directly:** https://bterzic123.github.io/zona-paywall-audit/?open=proto

Hey Zona team: four ideas for your paywall, each backed by data from State of Paywalls 2026 (78,000+ paywalls, 30,000+ apps), plus a clickable rebuild of your paywall and Welcome Offer in your own design. Use the Today / Proposed switch to compare it with what ships now, and tap the numbered dots for the report finding behind each change.

## The four ideas

| # | Idea | Report anchor | Outcome |
| :-- | :-- | :-- | :-- |
| 1 | Put your 4.7 from 16K ratings on the paywall | 3.1: 27% of top paywalls show social proof · 5.3: social proof on the paywall | CR +10–30% (observed in winning A/B tests) |
| 2 | Show the yearly plan as a weekly price | 3.3: 4% of top paywalls show a weekly price | Finding only; the report publishes no lift range |
| 3 | Hold the close button for three seconds | 3.7: 22% of apps delay it, half by 3–5 s · 5.3: delay before the close button | CR +8–15% (observed in winning A/B tests) |
| 4 | Test a smaller welcome discount | 4.5: typical second-chance discount 38% · 2.7: up to 30% off keeps 90% of full-price revenue, 31–60% keeps 70% | Finding only; the report publishes no lift range |

## Benchmarks used

All categories (the report has no Music category), US, App Store data, Oct 2025–Sep 2026.

Read the report: [State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=zona)

## Grounding

Prices (69,99 € yearly, 9,99 € weekly, €34.99 Welcome Offer) come from Zona's own in-app screens on a euro storefront. The 4.7 rating, 16K ratings and the review excerpt come from the US App Store listing. The weekly figures (1,35 € and €0.67) and the 86% saving are arithmetic on those prices. Screens are rebuilt from a screen recording of the live app; the TR and DE versions are our translation.

Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026 and Adapty's own data, not measured results for Zona.

## Run locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

Prepared by Adapty.
