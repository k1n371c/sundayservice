# The Sunday Service — Product North Star

> *Somewhere between oil and obsession.*

---

## What This Is

This is the north star document for **The Sunday Service** — a premium iOS app for serious car enthusiasts and DIY mechanics. It covers brand, philosophy, differentiators, target users, monetization, platform strategy, and the product roadmap.

If you're reading this to understand what we're building, read it straight through. If you're questioning a product decision, come back here first. The answer is usually already in here.

---

## The Problem

Every serious car person has the same pile: receipts they can't find, forum threads they bookmarked three years ago, a notes app with torque specs they're not sure are right, a shelf of parts they may or may not have already used. They know more about their car than any mechanic they've ever paid — but that knowledge lives in their head, scattered across apps that were never built for them.

The apps that exist are glorified reminder widgets. Log a date, set a mileage alert, done. Useful for the person who treats their car like an appliance. Useless for the person who treats it like a project.

There's no tool built for the person who checks the torque twice.

The Sunday Service is that tool.

---

## Brand

### Voice & Tone

Direct. Precise. A little obsessive. The Sunday Service doesn't talk down to its users — it talks *with* them, from inside the same mindset. No corporate hedging. No wellness-app softness. This is a tool for people who take the work seriously, and the writing reflects that.

We're not trying to make car maintenance approachable for everyone. We're trying to make it excellent for the people who already care.

**App Store listing:**
> "Your car's complete service history, part numbers, and maintenance schedule — all in one place. Built for the ones who actually do the work."

**Push notification:**
> "Oil change due in 200 miles. Sunday's calling."

**Onboarding:**
> "Welcome to The Sunday Service. Let's start with your car."

**Empty state:**
> "No records yet. Every obsession starts somewhere."

**About page:**
> "We got tired of losing receipts, forgetting part numbers, and guessing when the last service was. So we built the tool we wanted."

### Taglines

- *Somewhere between oil and obsession.*
- *The garage is open.*
- *Some cars are just maintained better.*
- *Your car remembers everything. Now so do you.*
- *We keep what we care for.*
- *Not every car gets this treatment.*

### Brand Pillars

**OBSESSION** — This app is built for people who can't stop thinking about their cars. The research at midnight. The spreadsheet tracking fluid viscosity across temperature ranges. The forum thread from 2009 that's still the best source on the subject. We understand that mindset because we share it.

**PRECISION** — Right part, right torque, right interval. No shortcuts. The app is designed to capture and surface exactly the right information at exactly the right moment. Not close enough — correct.

**RITUAL** — The Sunday morning garage session is sacred. Unhurried, deliberate, methodical. The app should feel like an extension of that ritual, not an interruption of it. Every screen should feel considered.

**MEMORY** — Every car deserves a complete history. The work done by serious mechanics is worth documenting. Not just for resale value — though it absolutely helps — but because care deserves to be recorded. We keep what we care for.

---

## Product Philosophy

### The Car Is the Hero

The app opens to your car. Not a chat prompt. Not a dashboard of aggregate stats. Not a feed. The car — its profile, its full picture: what's been done, what's coming due, what's on the shelf, what the procedure says. This is a dossier, not a conversation.

The structure flows from the car outward. Everything in the app lives under a vehicle. When you open The Sunday Service, you're standing in front of your car. That's the mental model we're building.

### AI Is the Craftsman's Assistant, Not the Product

AI lives underneath this experience. It surfaces when it's useful. It's invisible when it's not. You don't need to talk to it to get value from the app — and that's by design.

It pre-fills procedure templates when you describe a job in plain English. It passively monitors your service history for anomalies. It writes the narrative section of the Dossier when you're ready to sell. These are genuine force-multipliers that don't require a chatbot interface.

This matters strategically. Competitors who are building chatbot-first products are building on a foundation that depreciates as base models improve. Any car-specific Q&A a chatbot does today, a general-purpose LLM will do better in 18 months. A procedure template library you've spent four years refining? That's yours. It can't be downloaded.

The moat isn't the AI. The moat is the user's data.

### The Data Is the Moat

The longer someone uses The Sunday Service, the more irreplaceable it becomes. Four years of service records. Twelve custom procedure templates with your own lessons-learned notes. A parts shelf that knows exactly what's in your garage. Cross-referenced OEM part numbers you sourced yourself. A photo log of every major job.

That is not something you walk away from for a competitor with a slightly better UI. That's a complete record of your relationship with a machine you care about. The app earns loyalty not by locking data away, but by making the data so complete and so personal that leaving would mean starting over.

That's the opposite of a chatbot. And it's a much better business.

---

## Competitive Landscape

Research across 13 iOS apps in the category: Fuelly, Road Trip MPG, Car Minder Plus, CARFAX Car Care, Drivvo, Simply Auto, ServiceLog, Loggy, GarageHub, MyAutoLog, Motorist, OBD Fusion, Carista.

### The Commodity Tier

**Fuelly, Drivvo, Simply Auto, CARFAX Car Care** — These are reminder apps. Log a date, log mileage, set an alert. Clean enough UIs, fine for the person who wants to track when they last changed their oil. Zero procedure depth. No parts inventory. No photos. No torque specs. No templates. Passive record-keeping for casual owners, not tools for people who wrench.

Fuelly has a large user base because it's been around since 2008 and is genuinely good at fuel economy tracking. But fuel economy is one metric. It is not a service record system.

### The Middle Tier

**Road Trip MPG, Car Minder Plus, ServiceLog** — Slightly richer. Some support for multiple vehicles, custom reminder types, and fuel tracking. Better than the commodity tier but still fundamentally passive. You log what happened. The app stores it. End of loop. No torque specs, no procedure templates, no inventory, no photos attached to events in any meaningful way.

These apps are fine. None of them would survive contact with a real enthusiast's workflow.

### The Only Real Competitor

**GarageHub** (launched 2025) is the only app in this category genuinely reaching for the enthusiast market. They have parts inventory tracking, build plan management, and an AI assistant called "Rev." They deserve credit for the attempt.

But: GarageHub has almost no users. No Reddit presence. No YouTube presence. Their App Store rating count is too low to display. They're chatbot-first, which means they're building their moat in the wrong place — Rev is the product, and Rev will be commoditized. Their subscription model gates core AI features behind a paywall, which creates friction exactly where they need to earn trust. They were built by a small development shop with no apparent connection to the culture they're serving. No procedure templates with torque specs. No Garage Mode. No community.

Would you wear a GarageHub t-shirt? No. You wouldn't. That's the whole answer.

### The White Space

No app treats a car like serious equipment deserving a real record system. Nothing a Porsche 911 GT3 owner, an E30 restorer, or a canyon runner would actually trust and rely on as a primary tool.

Sunday Service is the first product built from that perspective — not as an outsider trying to sell into the enthusiast market, but as the thing the enthusiast market has been missing and not quite known how to ask for.

---

## Core Differentiators

These eleven features define the gap between Sunday Service and everything currently on the market. Each one is a standalone reason to switch. Together, they're a different category.

### 1. Procedure Templates ("Run Procedure")

Build reusable procedure templates for every job you do regularly: socket sizes, fluid capacities, torque specs, step-by-step procedural notes, required tools, lessons learned. The next time you run the job, tap "Run Procedure" — everything you need is already on screen. No looking anything up. No forum tabs. No second-guessing the spec from two services ago.

This is the feature that separates a record-keeping app from a *working* app. Most apps document what you did after the fact. Procedure Templates are there with you at the workbench.

Templates are built once and run every time. The first oil change takes ten minutes to document; every subsequent one takes thirty seconds to initiate and produces a complete, timestamped record. Eventually, templates can be shared by the community — one user's sourced procedure becomes a head start for everyone running the same car.

### 2. Spec & Source Vault

Log not just *that* you did a service, but the exact *recipe* behind it: specific fluid weights (not "5W-30" — the Motul 8100 X-cess Gen2 5W-40), exact part numbers, and direct source URLs. Next season, you're not digging through forum threads hoping your browser history still has the link. You tap the saved URL and reorder.

This is the feature for the person who spent three hours sourcing the right coolant for a European-spec cooling system and never wants to do that research again. Not "coolant replaced." "Zerex G-48, Pelican Parts #ZER-10106, $32.99, 1.5 gallons used." That's the difference.

### 3. Parts Shelf (Inventory)

Track what's physically in your garage right now — quantity, product name, part number, source, assigned vehicle. When a procedure fires and lists its required materials, the app cross-references your shelf: "You need 10.5 quarts. You have 1.5 on the shelf. Order 9."

This closes the loop between planning and procurement. It prevents the Sunday morning discovery that you're two quarts short. It prevents over-ordering the part you already bought in March. It turns your garage shelf into something organized and legible.

The Parts Shelf connects Procurement to Execution in a way no other app has done. That connection is the feature.

### 4. Torque Specs & Lessons Learned

Factory torque specifications attach directly to tasks inside a procedure. Drain plug: 25 ft-lbs. Filter housing: 18 ft-lbs. Sump bolts: hand-tight plus a quarter turn. No app has done this cleanly for the consumer enthusiast market. This alone eliminates a category of ambient anxiety for anyone who's rebuilt a suspension component or reinstalled a wheel bearing.

The Lessons Learned field is the other half. Factory manuals tell you the spec. They don't tell you that you need a 6-inch wobble extension to reach the drain plug, or that the O-ring on that filter housing tends to stick and requires a plastic pry tool, or that you should never fill past 10.5 quarts on this engine even though the spec says 11. These notes accumulate over years of ownership. Future you thanks present you. A subsequent owner thanks you too.

### 5. Visual Ledger (Provenance)

Attach photos to every service event: the odometer reading at the time of service, the empty oil bottles proving the fluid used, the torque wrench set to spec, the physical receipt from the parts counter. Turn a text log into verified, timestamped, photographed history.

A service record without photos is a claim. A service record with photos is evidence. The Visual Ledger turns every entry into provenance — which matters at point of sale, in warranty disputes, and for any subsequent owner who wants to understand the car's life before them.

### 6. The Dossier Export

One-click export of the car's complete service history as a beautifully formatted PDF or a secure, shareable web link. Every torque spec met. Every OEM cross-reference. Every photo attached. Every procedure run. AI synthesizes the raw data into a coherent ownership narrative: when the car was acquired, what work was done, what condition it's in, what's coming due.

The Dossier is the payoff for every piece of data entered into the app. When you sell a well-maintained machine, you hand the buyer a document that does two things simultaneously: it justifies the premium asking price, and it signals that this car was owned by someone who took it seriously. Serious buyers recognize serious sellers. The Dossier is the handshake.

For a collector car, it is the difference between a transaction and an inheritance.

### 7. Cross-Reference Part Numbers

Log OEM part numbers alongside the aftermarket and alternative part numbers you've sourced and verified. A Ferrari coolant temperature sensor is often a Bosch sensor — the same part, different box, at 30% of the price. The app stores both, with sourcing notes. The next service, the lookup is done.

Over time, the app becomes a personalized parts knowledge base built from your own research. Eventually, when users share procedure templates, those cross-references become collective assets — one user's sourced Bosch part number available to everyone running the same car. This feature respects the user's intelligence. The people using this app are already doing this research manually. The app makes it systematic.

### 8. Garage Mode UI

A dedicated UI mode for active service: massive text, high-contrast dark theme, tap targets large enough to hit with a gloved hand. The procedure checklist, torque values, and step notes readable from a workbench three feet away under shop lighting. Designed for the actual environment where the app gets used — not a phone held in clean hands on the couch.

Most maintenance app interfaces were designed for comfortable indoor use. Garage Mode is designed for the garage floor, the creeper, the engine bay. That distinction is the difference between an app you reference before you start and an app that's genuinely useful while you're working.

### 9. Dual-Trigger Intervals + Intensity Decay

Service intervals triggered by mileage *and* elapsed time — whichever comes first. "Every 5,000 miles or 12 months." Standard behavior for any serious maintenance schedule; shockingly absent from most apps.

Intensity Sessions add a third dimension: log a high-stress driving event — a track day, a canyon run, a timed rally — and the maintenance schedule accelerates accordingly. An engine that ran at sustained high RPMs for three hours has experienced something different than an engine that covered the same mileage in highway commuting. Brake fluid doesn't care about mileage — it absorbs moisture over time and under heat cycles. The app understands these distinctions. No other app does.

### 10. AI Procedure Intelligence

Describe a job in plain language — "oil change on a 2003 BMW M5 V10" — and AI pre-fills the procedure template: torque specs for that year and model, fluid type and capacity, common failure points, recommended tools, known gotchas. A head start, not a finished product. The user reviews, corrects, and refines — but starts from something rather than nothing.

AI does the research. The user brings the judgment. The result is a procedure template that would have taken an hour to build from spec sheets and forum threads, completed in two minutes. The first time you do a job on a car you've never worked on before, this feature pays for itself immediately.

### 11. AI Anomaly Detection

Passive pattern recognition running against the user's service history — not a chat interface, but a quiet alert when something in the data doesn't match the expected pattern. Oil running darker faster than the previous three changes. Coolant consumption trending upward over six months. Brake fluid moisture accelerating sooner than typical. Tire wear suggesting an alignment issue based on rotation records.

The user doesn't ask for this. The app notices it. That is the correct role for AI in a tool like this: a second set of eyes on the longitudinal data, surfacing when it's useful, invisible the rest of the time. This feature is only possible because of the data foundation — and the data foundation is only possible because of the years of use that precede it. Anomaly detection is the payoff for long-term engagement.

---

## The Feature Loop

Every feature in Sunday Service lives somewhere in a four-stage loop:

```
PROCUREMENT → EXECUTION → DOCUMENTATION → ASSET VALUE
```

**Procurement** (Parts Shelf, Spec & Source Vault, Cross-Reference Part Numbers) — Know what you have, know what you need, know exactly where to get it and what it costs. Never over-order. Never get caught short mid-job.

**Execution** (Garage Mode, Procedure Templates, Torque Specs, Lessons Learned, Dual-Trigger + Intensity Decay) — Stand at the workbench with everything you need on screen. Run the procedure. Hit the specs. Note what you learned for next time.

**Documentation** (Visual Ledger, Service Log, AI Anomaly Detection) — Record what happened, with photos, with the exact spec used, with the date and mileage. Let the app watch the patterns across time.

**Asset Value** (The Dossier Export, Provenance Photos) — When it's time to sell, or when you want to show what the car actually is, export the complete record. Everything documented. Everything verified. AI writes the narrative.

This loop is the product. Features that don't live somewhere in this loop don't ship.

---

## Target Personas

### The Weekend Wrench

Mid-30s to late-40s. Owns one or two cars and does all his own maintenance, most of his own repairs. Not primarily to save money — though it helps — but because he'd rather know the work was done right. Has a decent socket set, a jack stand collection that cost more than he admits, and opinions about torque wrenches. He knows his torque specs by make and model.

**His problem:** The knowledge lives in his head and his browser history. He's done the oil change on this car eleven times and still pulls up the forum thread to confirm the capacity and spec. He has a notes app full of half-finished procedures he started and never completed. He's exactly the person who would build perfect procedure templates if someone handed him the scaffolding.

**What he wants:** A home for the knowledge that lives outside his head. Procedure templates he built himself, torque specs attached to tasks, a parts shelf that knows what he has, a complete service record with photos. After two years, he has something genuinely irreplaceable.

**The moment it clicks:** The first time he runs a procedure he built six months ago and everything is already on screen — the correct spec, the correct part number, the lessons-learned note about the stubborn O-ring. He didn't have to think. He just did the work.

### The Project Car Builder

Actively building or restoring something. Maybe an E30, a classic truck, a track car, a drift build. Possibly multiple projects at different stages. Spending money on parts faster than he can track them — has a spreadsheet somewhere that isn't quite right. He needs to know what he's ordered, what's on the shelf, what's been installed, what's next, and how much he's spent, and they're currently all in different places.

**His problem:** The build is a project management problem and he doesn't have the right tool. His build log lives in a Discord conversation from four months ago. His parts list is split between a spreadsheet and memory. He has no systematic record of what work was done at what stage of the project.

**What he wants:** The Parts Shelf for tracking what's in stock and what's been consumed. Procedure templates for the major jobs, so the next build benefits from this one. Cross-referenced part numbers he sourced the hard way. A timeline of the build that tells the story coherently. The Dossier when it's finished or when it sells.

**The moment it clicks:** At the parts counter, pulling up the app to confirm the part number he sourced three months ago, then checking the shelf inventory to confirm he doesn't already have it sitting in the garage. Two steps. No duplicate order. No wasted trip.

### The Collector/Custodian

Owns two to four cars, at least one of which is something special — a vintage sports car, a low-production run, something with a story and a community. May have a trusted independent shop for the work he doesn't do himself. Cares deeply about provenance — the documented history of the car is part of what makes it worth caring for, and worth what it's worth.

**His problem:** He takes the car seriously, but the record-keeping is scattered. Shop receipts in a folder. Some things he did himself, some the shop did, with no unified document spanning both. When it's time to sell — and he always sells eventually — he reconstructs the history from memory and old paperwork. He knows the next buyer wants exactly this information. He never has it organized.

**What he wants:** A clean, complete record spanning both his work and the shop's. The Visual Ledger for photos attached to major events. Multi-vehicle support for the whole collection. The Dossier export when it's time to sell. The app primarily as a record system, less as an execution tool.

**The moment it clicks:** Exporting the Dossier before the sale and seeing the complete history — every service, every photo, every part number, every specialist who touched it — formatted cleanly and ready to hand to a buyer. He knows what that document does to the transaction because he's been on the other side of it. He knows it's worth money.

### The Track Day Driver

Performance-focused. Takes the car to HPDE events, autocross, track days — somewhere between four and twelve events a year depending on the season. Knows that a full track day does more to brake fluid than 5,000 normal miles. Has a pre-event checklist he runs in his head. Post-event, things need to get checked and the schedule needs to update. Running harder brake pads, fresher fluid, and tighter service intervals than most of his friends.

**His problem:** Standard maintenance intervals don't apply to his use case and no app accounts for this. He manages it manually — a mental note that the track day "counts as 2,000 miles" or something similarly imprecise. His brake fluid service is based on time and heat cycles, not odometer reading, and he has no tool that understands that distinction.

**What he wants:** Intensity Sessions that actually adjust the schedule. Dual-trigger intervals that account for time alongside mileage. Pre-event and post-event procedure checklists he can run systematically, the same way every time. AI anomaly detection that catches a pattern he might miss across a full season of events. Confidence that the car is genuinely ready for what he's asking of it.

**The moment it clicks:** Logging a track day as an Intensity Session and watching the maintenance schedule tighten accordingly — brake fluid, oil, pads — calculated against actual duty cycle, not a generic interval that wasn't designed for his use case. The app finally understands how he uses the car.

---

## Monetization

### Philosophy

The monetization model has to fit the brand. The person who reads "somewhere between oil and obsession" and immediately recognizes themselves is not the person who wants to subscribe to their car maintenance app. They want to own their tools.

A subscription model says: *we'll keep charging you forever for something you rely on.* That's not the relationship we're building. A one-time purchase says: *this is yours.* That's the right message for this user. You buy a torque wrench once. You buy quality tools and keep them. You don't rent them.

GarageHub gates its core AI feature behind a subscription paywall. The result is that the feature most likely to convert a skeptic is the feature a skeptic can't try. That's a self-defeating structure. We're not doing that.

### Model

**Preferred — One-time purchase at a premium price point.** The full product, no artificial limits, no recurring charge. The price should reflect the quality — this is not a race to the bottom. Serious users respect tools that cost something and don't apologize for it. A $29 app purchased once is a different relationship than $5/month in perpetuity.

**Alternative — Free core with one-time Pro unlock.** Core includes vehicle profile, service log, basic reminders, and procedure templates. Pro unlocks Dossier export, AI features (procedure intelligence, anomaly detection, AI narrative), Garage Mode, Intensity Sessions, and unlimited procedures. The free tier must be genuinely useful — not a teaser, not crippled. The Pro unlock is for the features that serious users will naturally want once the core has proven its value.

**Not this:** Subscription-first. Freemium that gates basic functionality behind a paywall. Advertising. In-app purchases for individual features. Any model that makes users feel like tenants instead of owners.

---

## Platform Strategy

### iOS App — Primary Product

Native iOS. Best-in-class UX. This is where the entire investment goes at launch. Nothing is cross-platform until iOS is excellent. The design should feel more like a premium tool than a consumer app. Dense information hierarchy where the data warrants it; clean and deliberate everywhere else. Garage Mode as a distinct, purpose-built UI state. The interface should feel like it was designed by someone who uses it.

### Landing Page — Pre-Launch

The landing page exists before the app. It captures email addresses from the people who would be day-one users and establishes brand credibility from the moment anyone finds it. The landing page is not a marketing site — it's a statement of intent. It should feel like the app: direct, precise, serious, with a voice that immediately tells the right person they've found the right thing.

The landing page is honest about what it is: a place to get in line before the app ships.

### Merch Store — Culture Play

Limited runs. Considered pieces. "The garage is open." "Not every car gets this treatment." "Some cars are just maintained better." Hats, tees, long-sleeves, stickers. Quality materials — not fast fashion, not a logo slapped on a Gildan.

This is not a revenue strategy. This is a culture signal. The person who wears a Sunday Service hat to a Cars and Coffee is broadcasting something about who they are and how they think about their car. They become a brand ambassador not because they were paid but because the message is already theirs. GarageHub doesn't have this. No app in this space has this. Culture is a moat that can't be purchased with a marketing budget.

### Web App — Eventually

Desktop reference during a work session is a legitimate use case — a procedure template open on a monitor while working at the bench. This comes after iOS is excellent, not before. A companion reference view, not a parallel full-featured product.

### Android — Later

After iOS proves the model. Same philosophy, same quality bar. A native product, not a port. If Android happens before iOS is solid, nothing is solid.

---

## Roadmap

### Phase 1 — MVP

*Goal: The core loop works. The app is worth using on day one.*

- Vehicle profile: make, model, year, current mileage, VIN, photo
- Service log with date, mileage, notes, and photo attachments
- Dual-trigger maintenance reminders (mileage + time, whichever comes first)
- Procedure templates with torque specs, fluid specs, and procedural step notes
- Lessons Learned field on procedures

The MVP should be tight. No feature that isn't genuinely excellent makes it in. A smaller excellent product beats a larger mediocre one, every time.

**The test:** Can the Weekend Wrench replace his composition notebook with this app?

### Phase 2 — Depth

*Goal: The app becomes genuinely irreplaceable for serious users.*

- Parts Shelf inventory with quantity tracking and procurement alerts
- Full Spec & Source Vault with saved URLs and product details
- Cross-reference part number logging (OEM + verified alternatives)
- Garage Mode UI with large text, high-contrast dark theme, oversized tap targets
- Multi-vehicle support
- Torque spec storage per fastener, per procedure step

This is where the data moat starts building in earnest. Users who reach Phase 2 depth don't leave.

**The test:** Can the Project Car Builder track an entire engine rebuild, from parts procurement to final torque, in this app?

### Phase 3 — Intelligence & Export

*Goal: The AI makes the data work harder. The Dossier creates a moment worth sharing.*

- AI Procedure Intelligence: describe a job, get a pre-filled template
- AI Anomaly Detection: passive pattern monitoring across the full service history
- Intensity Session logging with automatic maintenance schedule decay
- Dossier PDF export with AI-written ownership narrative
- Secure shareable Dossier web links

Phase 3 is where Sunday Service becomes something you tell people about.

**The test:** Does the Collector/Custodian use the Dossier to justify a higher asking price — and does the buyer immediately understand why it does?

### Phase 4 — Platform

*Goal: Sunday Service becomes a brand, not just an app.*

- Merch store launch (limited run, brand-first, no compromises on quality)
- Web app companion view (procedure reference during bench work)
- Procedure template sharing between users (community library, cross-referenced part numbers become collective assets)
- Android

Community template sharing is the most significant feature in Phase 4. When users share procedure templates, the knowledge base scales beyond any single user's experience. One person's sourced Bosch part number becomes available to everyone running the same car. Network effects on top of an already sticky product.

**The test:** Do people wear the hat?

---

## What This Is Not

A few things worth stating explicitly, because they'll come up as the product grows:

**Not a chatbot.** AI is a craftsman's assistant embedded inside a record system, not the product itself. If someone's primary interaction with the app is prompting an AI, we've built the wrong thing. The product is the procedure templates, the service history, the parts shelf, the dossier. AI serves the product. It doesn't replace it.

**Not for casual owners.** We are not trying to capture the person who gets their oil changed at the dealer and wants a reminder in six months. That's a large market with established competitors who serve it adequately. We're going deep for a specific user, not broad for everyone. Being narrow and excellent is a strategy, not a limitation.

**Not a subscription trap.** The business model has to match the brand. We're building for people who own their tools, not rent them. The monetization structure should feel like a purchase, not a utility bill.

**Not feature bloat.** The feature loop — Procurement, Execution, Documentation, Asset Value — is the filter. Everything we build should live somewhere in that loop and make that loop better. Features that don't serve a real user in a real moment don't ship.

---

## The Standard

When evaluating any decision — feature priority, design direction, copy tone, pricing, marketing channel — the question is:

*Would the person who treats a Sunday morning in the garage like a sacred appointment respect this?*

Not would they tolerate it. Not would it test well in a survey. Would they *respect* it.

That's the standard. Check the torque twice.

---

*Some cars are just maintained better.*

---

*Last updated: April 2026*
