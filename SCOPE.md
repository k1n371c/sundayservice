# Sunday Service — Product Scope

*This document defines what Sunday Service is as a product: the platform, the structure, the v1 feature set, and what comes later.*

---

## Platform

Sunday Service is a **responsive web application**. It works on phone and laptop equally. No native app in v1.

- **Phone:** Quick logging in the garage, torque spec lookups, checking what's due
- **Laptop:** Adding cars, detailed service entry, planning upcoming work, reviewing history, high-level views across multiple cars
- **Deployment:** Hosted web app, accessed via browser; can be added to iOS/Android Home Screen as a PWA
- **Stack:** Next.js + React, Tailwind CSS, Supabase (auth + database), Vercel (hosting)

---

## Product Structure

Sunday Service is organized around **cars, not tasks**.

### Core Objects

**The Garage**
The top-level view. All your cars. At a glance: each car, its last service, what's due next, and a health indicator.

**The Car**
Everything lives inside a car. A car has:
- Identity: Year, Make, Model, trim, color, VIN (optional), photo
- Current mileage (manually entered; updated on each log)
- A Dossier (the full record)

**Service Record**
A single logged service event. Contains:
- Date
- Mileage at service
- What was done (from a template or freeform)
- Parts used (linked to Parts Shelf or freeform)
- Cost (parts + labor if applicable)
- Notes / lessons learned
- Photos (receipts, parts, the work itself)
- Who did the work (self / shop)

**Spec Vault**
Per-car specs that never change: oil type and capacity, tire pressures, torque specs, fluid types, belt intervals. Editable. Pulled into procedure templates automatically when available.

**Parts Shelf**
Parts you have on hand for a car. Each part: name, part number, source, quantity, date purchased, cost. When logging a service, you pull from the shelf.

**Due Items**
What the car needs next. Two trigger types:
- Mileage-based (oil every 5,000 miles)
- Time-based (registration every 12 months)

Items surface automatically based on last service + interval. Can be customized per car.

**Procedure Templates**
Pre-built step-by-step guides for common services. Include spec lookups (torque values, fluid quantities). Can be customized and saved per car. AI helps generate these from make/model/year.

---

## v1 Feature Set

What ships first. Everything else is later.

| Feature | Notes |
|---|---|
| Add / manage cars | Make, model, year, mileage, photo |
| Service log | Log a service: type, date, mileage, notes, cost |
| Due items | Mileage + time-based intervals, surfaces what's next |
| Spec vault | Per-car: oil type, tire pressure, key specs |
| Procedure templates | Pre-built for common services, spec-linked |
| Multi-car garage | Up to 1 car free; unlimited on Pro |
| Auth | Email + Google sign-in |
| Mobile-responsive | Full functionality on phone browser |

---

## What's Not in v1

| Feature | When |
|---|---|
| Parts Shelf | v2 |
| Receipt / photo uploads | v2 |
| AI Procedure Intelligence | v2 (after core loop is solid) |
| AI Anomaly Detection | v3 |
| Dossier Export (PDF) | v2 |
| Garage Mode (simplified phone view) | v2 |
| Shop / mechanic tier | Later |
| Android PWA optimization | Post-launch |

---

## Monetization

**Free tier:** 1 car, full feature set, no time limit. Enough to feel the product.

**Pro:** $4.99/month or $39/year (save 35%). Unlimited cars, photo uploads, PDF dossier export, AI features (when available). No App Store cut — Stripe handles payment.

**Why subscription over one-time:**
- Recurring revenue funds ongoing development
- Enthusiasts add cars over time — Pro pays for itself if you have 2+ cars
- Enables AI features that have ongoing API costs
- LTV is better: avg 2.5-year subscriber at $39/year = ~$94 LTV vs. $39 one-time

---

## Key User Flows

### First Run
1. Sign up → Add first car (year/make/model/mileage) → Prompted to set up Spec Vault → Add first service record or set up Due Items → Land in Garage view

### Logging a Service (phone, in garage)
1. Open app → tap car → tap "Log Service" → select procedure type → fill mileage + notes + cost → save → Due Items update automatically

### Planning upcoming work (laptop)
1. Open app → select car → view Due Items sorted by urgency → click into a procedure → review steps and specs → add to a planned date

### Setting up a new car
1. Add car → enter identity fields → populate Spec Vault (oil type, tire pressures, torque specs) → add historical service records → system calculates what's due based on history

---

## Design Principles

- **Car-first navigation.** You're always inside a car's context. The car is the hero.
- **Dense but readable.** Desktop views show real data — not oversimplified cards. Think: instrument panel, not lifestyle app.
- **Earn the dark palette.** The visual identity is near-black with warm accent. Every element needs to justify itself against that background.
- **No onboarding bloat.** Get to a car in under 60 seconds. Don't ask for things you don't need yet.
- **Mobile is a first-class citizen, not an afterthought.** The phone experience is optimized for quick input and quick reference. The desktop experience is optimized for depth.
