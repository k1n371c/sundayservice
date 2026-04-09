# The Sunday Service — Market Sizing & ARR Projections

*Research-based analysis. All assumptions labeled. Updated April 2026.*

---

## The Core Question

Sunday Service is explicitly not for casual car owners. That constraint is a feature, not a bug — but it requires an honest accounting of how large the actual market is.

---

## Total Addressable Market (TAM)

### Starting Point: US Registered Vehicles
- **298.7 million** registered vehicles in the US (Hedges & Company, 2024)
- ~232 million licensed drivers

### Filtering to the Real Customer

SEMA's 2024 enthusiast segmentation breaks car owners into five groups. The two that match Sunday Service:

| SEMA Segment | % of Owners | Est. Count |
|---|---|---|
| Builders (modify & restore) | ~3% | ~8.9M |
| Drivers (performance-focused DIY) | ~6% | ~17.9M |
| **Subtotal** | **~9%** | **~26.8M** |

From this 26.8M, a further cut to genuine primary-DIY mechanics who: (a) do their own servicing, not just modifications, (b) care about precision and records, and (c) would pay for a dedicated tool.

**TAM: 6–10 million. Central estimate: 8 million.**

### Cross-Checks
- SCCA membership: 67,000 organized competitors
- r/projectcar: 1.4M members; r/MechanicAdvice: 1.7M; enthusiast subreddits collectively 7M+
- SEMA reports $52.65B in specialty equipment sales at ~$2,025/enthusiast/year
- DIY auto maintenance participation: 47% of US car owners do some DIY — but most is wiper blades, not precision wrenching

---

## Serviceable Addressable Market (SAM)

Sunday Service is a web app accessible on any device — iOS, Android, and desktop. The iOS filter no longer applies.

| Filter | Rate | Result |
|---|---|---|
| Smartphone / web penetration (25–54 demo) | ~99% | Negligible adjustment |
| US-only (v1 focus) | — | 8M |
| **SAM** | | **~8 million** |

The removal of the iOS constraint meaningfully expands reach — roughly 35% of the enthusiast audience was previously excluded by platform.

---

## Serviceable Obtainable Market (SOM)

### Year 1 Signup Benchmarks

Comparable reference: Torque Pro — a premium OBD2/diagnostics app, $4.95, ~20K downloads/month at steady state (~$40K gross/month per Sensor Tower). Torque Pro is utility-focused with no brand or community. Sunday Service starts with a brand advantage but lower initial discovery surface as a web product.

| Scenario | Year 1 Signups | Basis |
|---|---|---|
| Conservative | 3,000 | Minimal community seeding, organic search only |
| Base | 8,000 | Active Reddit/Instagram community, some press |
| Optimistic | 15,000 | Viral community moment, strong launch |

Paid conversion assumed at 15–20% of total signups in Year 1 (web signups skew intent-driven but free tier creates a wider top of funnel). Conversion improves in Years 2–3 as the product matures.

---

## ARR / Revenue Projections

### Pricing & LTV Assumptions
- **$39/year** or **$4.99/month** (annual is the primary offer)
- Net per annual subscription after Stripe fee (2.9% + $0.30): **$37.57**
- Annual churn: **40%** (conservative for an engaged enthusiast audience)
- Average subscriber lifespan: **2.5 years** (= 1 / 0.40)
- **LTV per subscriber: ~$94** ($37.57/year × 2.5 years)

Active subscribers at end of each year = prior year active × 0.60 + new paid subs acquired.

### 3-Year Model

**Conservative**

| Year | New Paid Subs | Active Subs (EOY) | Annual Revenue | Cumulative |
|---|---|---|---|---|
| 1 | 450 | 450 | $16,900 | $16,900 |
| 2 | 750 | 1,020 | $38,300 | $55,200 |
| 3 | 850 | 1,462 | $54,900 | $110,100 |

**Base Case**

| Year | New Paid Subs | Active Subs (EOY) | Annual Revenue | Cumulative |
|---|---|---|---|---|
| 1 | 1,400 | 1,400 | $52,600 | $52,600 |
| 2 | 2,100 | 2,940 | $110,500 | $163,100 |
| 3 | 2,400 | 4,164 | $156,500 | $319,600 |

**Optimistic**

| Year | New Paid Subs | Active Subs (EOY) | Annual Revenue | Cumulative |
|---|---|---|---|---|
| 1 | 3,100 | 3,100 | $116,500 | $116,500 |
| 2 | 5,200 | 7,060 | $265,300 | $381,800 |
| 3 | 8,600 | 12,836 | $482,400 | $864,200 |

---

## Merch Revenue

| Year | Paid Users (base) | Drops | Conversion | Net |
|---|---|---|---|---|
| 1 | ~1,400 | 1 | 5% | ~$2,940 |
| 2 | ~3,500 | 2 | 5% | ~$14,700 |
| 3 | ~5,900 | 2 | 5% | ~$24,800 |

---

## The Honest Summary

| Scenario | 3-Year Cumulative | What It Requires |
|---|---|---|
| Conservative | ~$110K | Organic web/community only |
| Base | ~$320K | Active community seeding |
| Optimistic | ~$864K | Strong launch + community flywheel |

**This is an excellent indie product — wrong size for VC, right size for one person who loves cars.**

The subscription model changes the math significantly: recurring revenue compounds year over year as the retained subscriber base grows. The user spends ~$2,025/year on their car. Asking $39/year for the best maintenance tool they've ever used is not a hard sell. The bottleneck is discovery, not conversion. LTV of ~$94 per subscriber gives real room for community-building investment.

---

## What Would Change the Math

- **International:** UK, Germany, Japan, Australia — same customer profile, no additional platform work required
- **Native iOS / Android apps:** Eliminates PWA friction for users who prefer native; could improve conversion 10–20%
- **B2B / Shop tier:** Independent performance shops — different product, much higher ARPU
- **Content / SEO:** Procedure guides, torque spec databases, cross-reference posts — compounding organic discovery

---

## Sources

- SEMA 2024 Market Report — $52.65B specialty equipment sales
- Hedges & Company — 298.7M registered vehicles; 26M DIYers
- DataIntelo DIY Auto Maintenance Market 2024 — 47% DIY participation
- SCCA August 2024 — 67K members
- iOS US Market Share Q4 2024 — 62–65%
- Torque Pro via Apptopia — benchmark app revenue
- RevenueCat State of Subscription Apps 2025
