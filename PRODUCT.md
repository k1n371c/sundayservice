# The Sunday Service
### *Somewhere between oil and obsession.*

---

Every car has a history written in torque specs and part numbers, in the services you kept and the shortcuts you didn't take. The Sunday Service exists because that history matters. We built a place to track every service, log every part, and keep every record — so the ritual of maintaining your car is documented with the same precision you put into the work itself.

This isn't a chore app. This is for the ones who check the torque twice, who know their part numbers by heart, who treat a Sunday morning in the garage like the most important appointment of the week.

**Your car remembers everything you've done to it. Now so do you.**

---

## Brand

### Voice

Direct. Precise. A little obsessive. We write for people who understand what it means to actually do the work — not people who take their car to a dealer and hand over a credit card. There's a quiet pride in this community. We speak to it directly without over-explaining it.

> *"Your car's complete service history, part numbers, and maintenance schedule — all in one place. Built for the ones who actually do the work."* — App Store
>
> *"Oil change due in 200 miles. Sunday's calling."* — Push notification
>
> *"We got tired of losing receipts, forgetting part numbers, and guessing when the last service was. So we built the tool we wanted."* — About page
>
> *"No records yet. Every obsession starts somewhere."* — Empty state

### Taglines

| Line | Use |
|------|-----|
| Somewhere between oil and obsession. | Merch · Social · About |
| The garage is open. | Launch · Social · Notification |
| Some cars are just maintained better. | Merch · Ad · Landing page |
| Your car remembers everything. Now so do you. | App Store · About page |
| Not every car gets this treatment. | Merch · Sticker |
| We keep what we care for. | Brand statement |

### Pillars

**OBSESSION** — We build for people who can't stop thinking about their cars. The ones who research parts at midnight, who know every rattle and hum, who treat maintenance not as a task but as a craft. That obsession is the engine of everything we do.

**PRECISION** — Right part. Right torque. Right interval. We respect the details because the details are what separate a maintained car from a neglected one. No guesswork. No shortcuts. Every record matters.

**RITUAL** — The Sunday morning garage session is sacred time. We honor the rhythm of ownership — the weekly checks, the seasonal prep, the quiet satisfaction of a job done right. The process is the point.

**MEMORY** — Every car deserves a complete history. We make sure nothing is forgotten — every service, every mod, every part number — so the story of your car lives as long as the car does.

---

## Product Philosophy

### The car is the hero.

The app opens to your car — not a chat prompt, not a notification feed, not a dashboard of abstract stats. Your car's full picture: what's been done, what's coming due, what's on the shelf, what the procedure says. Think of it as a dossier, not a conversation.

Everything in the experience radiates out from the car. You're not a user managing a database. You're a custodian maintaining a machine.

### AI is the craftsman's assistant, not the product.

AI lives underneath the experience. It pre-fills procedure templates when you describe a job. It notices when your oil is darkening faster than usual. It writes the narrative summary when you export a dossier to sell the car. You don't have to summon it, prompt it, or manage it. It surfaces when it's useful and gets out of the way when it isn't.

This is a deliberate departure from competitors who have made the AI chatbot the centerpiece of their product. A chatbot is a feature trying to be a product — and it's one that ages poorly. Foundation models will answer car questions better than any custom-trained wrapper in 18 months. You cannot build a moat on that.

### The data is the moat.

A user who has logged four years of services, built twelve procedure templates, photographed every receipt, and catalogued their parts shelf has something irreplaceable. That history is theirs. The app becomes more valuable the longer someone uses it — which is the opposite of a chatbot.

---

## Competitive Landscape

The iOS car maintenance category has roughly three tiers, and Sunday Service lives in a space none of them occupy.

**Tier 1 — Glorified reminder apps.** This is most of the market. Fuelly, Drivvo, Simply Auto, CARFAX Car Care, MyAutoLog. They log a date, log a mileage, and set a reminder for next time. Some track fuel economy. The UI is functional and forgettable. They are built for someone who wants to know when their oil is due, not someone who cares about *what oil* or *how much* or *why it matters*. No procedure depth, no parts inventory, no photos, no torque specs.

**Tier 2 — Moderate loggers.** Road Trip MPG, Car Minder Plus, ServiceLog. Richer data capture, sometimes better-designed, still fundamentally passive. You record what happened. You don't plan, execute, or learn from it.

**Tier 3 — The one real competitor.** GarageHub launched in 2025 with parts inventory, a build plan section, and an AI mechanic called "Rev." The feature set is the most ambitious in the category. But as of early 2026: essentially no user base (App Store rating count below Apple's display threshold), no Reddit presence, no YouTube coverage, no community. Built by a small dev shop in Bulgaria, subscription-gated at the AI layer, and organized around the chatbot as the home screen. Well-designed. Completely undistributed. And would you wear a GarageHub t-shirt? Exactly.

**The gap:** There is no product built for the person who actually enjoys doing the work. Nothing that a 911 GT3 owner, an E30 restorer, or a track day regular would reach for and trust. Sunday Service is the first product built from that perspective rather than retrofitted toward it.

---

## Who We're Building For

### The Weekend Wrench

Mid-30s to mid-50s. Owns one or two cars and does all his own work. Knows his torque specs. Keeps a notebook somewhere with part numbers and fluid types but can never find it. Gets frustrated when he has to look up the same drain plug torque for the third time. Obsessive about doing things right. Won't take shortcuts. Would happily pay for a tool that makes the ritual feel as deliberate as the work itself.

**Core needs:** Procedure templates, torque specs, Lessons Learned notes, service history log.

### The Project Car Builder

Mid-20s to mid-40s. Mid-restoration or active build, possibly multiple cars. Has a mental map of every part he's ordered, modified, or is waiting on — but it exists only in his head and a scattered collection of browser tabs. Needs to track build stages, parts on the shelf, and what's still outstanding. The car is a project, not just a vehicle.

**Core needs:** Parts Shelf inventory, build plan tracking, Spec & Source Vault with reorder links, cross-reference part numbers.

### The Collector / Custodian

40s to 60s. Owns two to four cars including something significant — a classic, a limited-production car, something that will be sold eventually at a premium. Cares deeply about documented provenance. Has a shoebox of receipts somewhere and wishes the history of the car were organized in a way he could hand to a buyer. Precision and documentation are the point.

**Core needs:** Visual Ledger with photos, Dossier Export, complete service history, AI narrative summary.

### The Track Day Driver

Late 20s to late 40s. Performance-focused. Runs track days and canyon sessions and knows those events put more wear on the car than the odometer shows. Brake fluid, tires, brake pads — they're all on a degraded timeline that a mileage-only app can't track. Needs to log intensity sessions and have the maintenance schedule respond accordingly.

**Core needs:** Intensity Session logging, dual-trigger intervals (mileage + time), pre/post-event checklists, real-time Garage Mode access during work.

---

## Features & Differentiators

### 1. Procedure Templates

The centerpiece of the execution experience. You build a reusable procedure template — "Annual Oil & Filter Change," "Brake Fluid Flush," "Annual Tire Rotation & Inspection." Inside that template you store everything that never changes: socket sizes, fluid capacities, torque specs, step sequence, and the procedural quirks the factory manual leaves out.

When it's time to do the job, you tap **Run Procedure**. Everything you need is on screen. You don't look anything up. You just work.

This shifts the app from a passive diary to an active tool you rely on while you wrench.

### 2. Spec & Source Vault

Instead of logging *that* you changed the oil, you log the exact *recipe*: the specific fluid weight, the exact capacity, the part numbers for the filter and crush washer, and the URL where you sourced everything. Next season, you don't dig through old forum posts. You tap the link and reorder.

The Spec & Source Vault turns the app into a personal service manual that gets more useful with every procedure you complete.

### 3. Parts Shelf

A running inventory of what's physically in your garage right now. When a procedure fires — "You need 10.5 quarts of 0W-40. You have 1.5 on the shelf. Order 9." Prevents over-ordering, surfaces what you already have, and keeps the workshop organized.

Toggleable per-item when you use something up. Simple, precise, indispensable for anyone who pre-buys parts or runs a multi-car garage.

### 4. Torque Specs & Lessons Learned

Factory torque specs attached directly to each task. And alongside them: a dedicated **Lessons Learned** field for the things the factory manual doesn't tell you.

*"Needs a 6-inch wobble extension to reach the drain plug."*
*"Remove the undertray first — three 8mm bolts, watch the clips near the firewall."*
*"Don't overfill past 10.5 quarts. The dipstick reads full at 10 but it's not."*

Every time you finish a job, you leave a breadcrumb for your future self. Next time, you don't make the same mistake twice. This turns a simple log entry into institutional knowledge about your specific car.

### 5. Visual Ledger

Every service event can carry photos. A picture of the odometer when you changed the oil. The empty Motul bottles. The physical receipt from the parts store. The underside of the car before and after.

This transforms a text log into undeniable, verified history — valuable to a future buyer and satisfying to you as evidence of the work done right.

### 6. The Dossier Export

One-click export of the car's complete history as a beautiful PDF or a secure shareable web link.

When you list a well-sorted machine, you don't just say "well maintained." You hand the buyer a dossier: every torque spec met, every OEM cross-reference used, every photo of the work documented. AI writes the narrative summary — a plain-language account of the car's life under your care. It justifies a premium asking price and builds instant credibility.

*"This vehicle has been maintained to OEM spec throughout ownership, with zero deferred services and fourteen documented procedures performed by the owner."*

### 7. Cross-Reference Part Numbers

A Ferrari sensor is often a Bosch sensor at 30% of the price. A Porsche cooling hose is frequently an OEM BMW hose in a different box. Log OEM alternatives and cross-references alongside the branded part number so you never overpay for a badge again — and so future services are faster, cheaper, and better sourced.

This is a massive pain point in the enthusiast community and almost entirely unaddressed by existing apps.

### 8. Garage Mode

A dedicated UI state built for the environment where you actually use it. Massive text. High-contrast dark display. Numbers large enough to read from a workbench three feet away while you're holding a torque wrench and your hands are covered in grease.

Most apps are designed to be used at a desk. This one is designed to be used in a garage on a Sunday morning.

### 9. Dual-Trigger Intervals + Intensity Decay

Standard apps track mileage. That's not enough.

Set maintenance intervals by mileage AND time: "Change oil every 5,000 miles OR 12 months, whichever comes first." Brake fluid absorbs moisture and degrades whether the car moves or not. Time-based triggers catch what mileage misses.

Log **Intensity Sessions** — a track day, a canyon run, a mountain pass. The app recognizes that these events accelerate wear and adjusts the maintenance schedule accordingly. A track day counts for more than 200 miles of commuting. The app knows the difference.

### 10. AI Procedure Intelligence

Describe a job in plain English — "oil change on a 2003 BMW M5 V10" — and AI pre-fills the template: torque specs, fluid capacity, common gotchas for that specific engine, socket sizes, known quirks. You review, adjust, and save it as your procedure. Turns a blank template into a head start.

This is AI doing something genuinely useful — not answering questions, but filling in the work that makes your personal record system better over time.

### 11. AI Anomaly Detection

Passive pattern recognition across your service history. When something looks off — oil darkening faster than your last three changes, brake intervals shortening unexpectedly, a part failing early — the app surfaces it. Not as an alarm, but as a quiet note from a mechanic who's been watching.

The longer you use the app, the more useful this becomes. The data is the moat.

> **A note on AI:** Both AI features are embedded tools, not interfaces. There is no chatbot, no chat window, no "ask the AI" button. AI works in the background — pre-filling templates, surfacing anomalies, writing export narratives. The product is car-first. AI is the craftsman's assistant embedded in the product, not the product itself.

---

## The Feature Loop

```
PROCUREMENT          EXECUTION              DOCUMENTATION        ASSET VALUE
─────────────        ─────────────────      ─────────────────    ──────────────
Parts Shelf      →   Garage Mode        →   Visual Ledger    →   The Dossier
Spec & Source        Procedure Templates    Photo evidence       AI narrative
Cross-references     Torque specs           Service history      Provenance proof
                     Lessons Learned        Anomaly alerts       Premium resale
```

---

## Platform Strategy

**Web app — primary product.** Sunday Service is a responsive web application that works on phone and laptop equally. The use case splits naturally across devices: phone for quick logging in the garage, torque spec lookups, and checking what's due; laptop for detailed data entry, planning upcoming work, reviewing history, and high-level views across multiple cars. A web app serves both without compromise — and eliminates App Store dependency on pricing, distribution, and approvals.

The app can be added to an iOS or Android home screen as a PWA, giving a native-like experience without requiring App Store approval.

**Landing page — brand and waitlist.** Not a feature list. A feeling. The brand voice, the pillars, a few strong images, and a way to get on the list. Clean. Confident. Not trying to explain the whole product.

**Merch store — culture, not commerce.** Limited runs. "The garage is open." "Not every car gets this treatment." "Somewhere between oil and obsession." Hats, tees, stickers, maybe a patch. The merchandise isn't a revenue strategy — it's a signal that this is a community, not just an app. Merch buyers wear the brand into garages and become the best word-of-mouth we have. Launch quietly when the app is real.

**Native iOS / Android — later.** If the web app proves the product and the community grows to warrant it. Not the priority in v1.

---

## Monetization

Sunday Service is a web app — no App Store cut, no one-time purchase constraint, no platform dependency on Apple's approval.

**Model:** Free tier limited to 1 car with full feature access. **Pro subscription** at $4.99/month or $39/year (save 35%) unlocks unlimited vehicles, photo uploads, Dossier Export, AI features, and future platform additions. Payments handled by Stripe at ~2.9% + $0.30 per transaction.

**Why subscription:**
- Recurring revenue funds ongoing AI feature costs and continued development
- Enthusiasts add cars over time — Pro pays for itself with 2+ cars
- Better LTV: an average subscriber at 2.5 years generates ~$94 net vs. $39 one-time
- No App Store cut — economics are materially better than a native purchase model

Avoid gating the core experience behind the paywall. The free tier should feel like the real product, not a demo. The goal is to build trust first; conversion follows from that.

---

## Roadmap

### Phase 1 — Foundation
*Get the core right. Nothing else matters until this is excellent.*

- Vehicle profile: year, make, model, VIN, mileage, photo
- Service log with date, mileage, notes, and photo attachment
- Dual-trigger maintenance reminders (mileage + time)
- Basic procedure templates with notes fields
- Parts log (simple, non-inventory)

### Phase 2 — Depth
*Make it indispensable for the people who care most.*

- Full Procedure Templates with torque specs, socket sizes, and Lessons Learned
- Parts Shelf with inventory tracking and quantity management
- Spec & Source Vault with reorder URLs
- Cross-reference part numbers
- Garage Mode UI
- Intensity Session logging with schedule acceleration

### Phase 3 — Intelligence & Export
*Let the data work for you.*

- AI Procedure Intelligence (pre-fill from plain-language job description)
- AI Anomaly Detection (passive pattern recognition)
- Dossier Export: PDF and shareable web link with AI narrative
- Pre/post-event checklists for track days and long trips

### Phase 4 — Platform
*Build the community.*

- Merch store launch
- Procedure template sharing between users
- Native iOS / Android apps (if warranted after web proves out)

---

## What Success Looks Like

A 911 GT3 owner who has used the app for two years hands a buyer a 60-page dossier on their car and gets $8,000 more than asking because the history is undeniable.

A weekend wrench taps "Run Procedure" for his E30 oil change, reads the torque spec off his phone from across the garage, and doesn't have to look anything up — because he already did that the first time.

A project car builder knows exactly what's on his shelf, exactly what he's waiting for, and exactly what the car needs to be done. No spreadsheets. No forum bookmarks. No memory required.

That's what we're building.

---

*The Sunday Service. The garage is open.*
