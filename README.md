# Lusaka Business Advisory — Lead-Generation Demo

> **Concept demo — not a client project.** This site was built to show
> consultancy prospects what a lead-generation-focused website looks like
> when it's done properly. It is not a live business.

---

## What this is

A single-page, mobile-first demo website for a fictional management
consultancy in Lusaka. Its job is to demonstrate one thing: **how a
consultancy website converts a visitor into a booked discovery call.**

It is the third demo in a three-part portfolio, built for the highest-value
niche in the set — consultancies, advisory firms, and professional service
providers who sell expertise, not products.

| | |
|---|---|
| **Fictional client** | Lusaka Business Advisory |
| **Niche** | Management & financial consultancy |
| **Primary outcome sold** | Booked discovery calls |
| **Design system** | Stripe DESIGN.md (from `VoltAgent/awesome-design-md`) |
| **Stack** | Single HTML file, embedded CSS, Inter font, no build step |
| **Hosting** | Free tier (Vercel / Netlify) |
| **Status** | Concept demo — placeholder content throughout |

---

## Why this demo exists

Consultancies don't buy websites. They buy **lead flow**. The sales
conversation for this niche is not "do you like the design?" — it's
"will this get me more qualified calls?"

This demo answers that question visually, before the conversation starts.
It is a sales asset you send to a prospect, with the line:

> *"I built a concept for a firm like yours. Imagine this with your name,
> your case studies, and your booking link. Want me to build the real one?"*

The demo replaces the "do you have a portfolio?" objection with a live,
clickable answer.

---

## Key features

### 1. Authority & proof
- Two case studies written in **plain prose**, not consulting jargon.
  Each is ~80 words and tells a story a managing director would recognise.
- One **anonymized testimonial** ("— Group CFO, Lusaka-based retail group"),
  which is how real advisory firms quote clients who can't be named.
- No fake metrics dashboards, no star ratings, no "verified mandate"
  badges. Credibility comes from specificity, not decoration.

### 2. Lead magnet (ROI calculator — to be wired)
- The page structure includes a dedicated section for an interactive
  **ROI / decision-health calculator**.
- In the current build, the calculator is a **placeholder section** with
  the final CTA. Wiring it is the next build step (see *Roadmap* below).
- The purpose of the calculator is to give a cold visitor a reason to
  engage *before* they book — a low-commitment first step in the funnel.

### 3. Clear "Book a strategy call" funnel
- **Primary CTA** in the header, hero, and final section:
  `Book a 15-minute discovery call →`
- Every CTA points to the same booking intent — no "Contact Us" page,
  no generic form. One action, repeated.
- Reassurance copy under the hero CTA: *"No pitch. No obligation."*
  This lowers the perceived cost of the click.

---

## Design decisions

The page is built on the **Stripe DESIGN.md** system. The constraints
that matter most:

| Rule | Why |
|---|---|
| Background `#F8FAFD`, cards white with 1px `#E5EDF5` border | Depth from borders, not shadows — Stripe's signature |
| Headlines **weight 300**, body **weight 400 at 16px** | Restraint reads as confidence; bold reads as marketing |
| Negative letter-spacing on display sizes | Stripe's typographic fingerprint |
| Purple `#533AFD` in **four places only** (CTA, one hero word, case outcome, brand mark) | Color as punctuation, not wallpaper |
| Border radius **6px** maximum | Sharp, editorial, not "SaaS rounded" |
| No icons except a single `→` in the CTA | Icons are the fastest way to look AI-generated |
| One subtle vertical gradient in the hero | Structural, not decorative |

**What was deliberately removed** (and why it matters for the demo):

- Gradient mesh blobs — the single biggest "AI template" tell
- Fake registration numbers and "audited transaction" indicators
- Hero metric strips ($48.6M / 142 clients / 98.4% retention)
- Star ratings and "Verified Mandate" badges on testimonials
- Accreditation logo grids
- Eyebrow labels above every section heading

---

## File structure

```
/
├── index.html        # The entire demo — single file, embedded CSS
└── README.md         # This file
```

No build step. No dependencies beyond the Inter font from Google Fonts.
Open `index.html` in a browser, or deploy the folder to any static host.

---

## How to use this demo in a sales conversation

1. **Identify a consultancy prospect** with a weak or nonexistent site.
2. **Send the link** with a personalised one-liner referencing something
   specific you noticed about their current site.
3. **Say the line:** *"I built a concept for a firm like yours — imagine
   this with your case studies and your booking link."*
4. **If they reply,** book a call and use the demo as the visual brief
   for the real build.

The demo is **not** sent cold to every business. It is sent to
consultancies, and only after you've looked at their current site.

---

## Roadmap (next build steps)

- [ ] **Wire the ROI calculator.** A simple 3-input model
  (monthly revenue, hours spent on admin, hourly cost) with a sliders
  UI and a live output. No backend — compute in JS.
- [ ] **Connect the booking CTA** to a real Calendly / Cal.com link.
- [ ] **Add a third case study** in a different sector (agribusiness or
  logistics) to widen the niche appeal.
- [ ] **Add a real form** behind the final CTA as a fallback for
  prospects who won't book a call directly (logs to a Google Sheet or
  Formspree endpoint).
- [ ] **Build a variant** for financial consultancies specifically
  (different case studies, same structure) to A/B the pitch.

---

## Reusing this demo for other niches

The structure is deliberately generic enough to retarget:

| Element | Change for a new niche |
|---|---|
| Brand name | Swap `Lusaka Business Advisory` |
| Hero H1 | Rewrite around that niche's outcome |
| Case studies | Replace with two stories from that sector |
| Testimonial | Anonymize to the new sector's role |
| ROI calculator inputs | Change to the metrics that niche cares about |

Keep the design system. Change the content. The demo is the **shell**;
the niche is the **fill**.

---

## Honesty note

This is a **concept demo**, not a real business. Every name, case study,
testimonial, phone number, and email address on the page is fictional.
The footer carries the line *"Concept demo — not a client project"* so
that anyone landing on it understands what they're looking at.

If you reuse this demo for a real client, remove that line and replace
every placeholder before publishing.
