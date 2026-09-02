# HITL morning checklist — create USAspending Weekly Stripe Payment Link

**Status:** HITL checklist only. **Do not create a Stripe product or Payment Link from this file overnight.** Do **not** invent a live checkout URL. Do **not** call the Stripe API. Do **not** paste a live Note. Do **not** open Stripe UI beyond drafting this md. Lands on `cursor/notes-surface-a3e9` only. Not main. Not merged.

```
CHECKOUT URL: NOT LIVE / PLACEHOLDER
```

**Wait rule (morning card SHA `9bc569a3`):** USA Payment Link **waits until COT has a real live link.** Do not walk this checklist in the Dashboard before the Friday COT Pack Payment Link exists. Overnight Rogue does not log in to Stripe.

**AI disclosure (Rogue):** An AI (Rogue) drafted this checklist. Benjamin creates the Payment Link only after COT is live. Overnight Rogue does not create Stripe.

**SKU:** USAspending Weekly NAICS 541512 Prime Awards (DoD / HHS / DHS) only (Candidate 1). Not Friday COT Pack. Not NCUA+Title12. Not the $40 hospital MRF-change extract.

Same 7am Benjamin checklist shape as `drafts/notes-first-cot-stripe-payment-link-2026-09-02.md` (SHA `14e19f28` / blob `bc80a4fc`).

Paste-fields and click-path already on this branch (do not rewrite them):
- Click-path: `drafts/notes-first-usa-spending-stripe-clickpath-2026-09-01.md`
- Checkout paste-fields: `drafts/notes-first-usa-spending-checkout-2026-08-30.md`
- Live Note (parked until COT has a real link, then until this Payment Link exists): `drafts/notes-first-live-note-usa-spending-2026-09-02.md` (SHA `791ac4a6`)
- COT Payment Link checklist (goes first): `drafts/notes-first-cot-stripe-payment-link-2026-09-02.md` (SHA `14e19f28`)
- 7am card (cash-first, do not redo): `drafts/notes-first-morning-hitl-2026-09-02.md` (SHA `9bc569a3`)

---

## Product (copy from existing paste-fields)

**Name**

```
USAspending Weekly: NAICS 541512 Prime Awards (DoD, HHS, DHS)
```

**Price band (UNLOCKED — Atlas / Benjamin picks at the Dashboard; do not lock overnight)**

- **$8–$20 / note**, or **$12–$40 / month retain**.
- Suggestion only (not live): $12 / note or $24 / month. May ignore.
- One-time weekly note first. Do not also create the monthly retain SKU this morning unless Atlas says so.

**What the buyer gets:** Markdown/HTML Note + CSV. Week 2026-08-24–08-30 ET: 62 primes ≥$250k; ~$2.28B awarded (HHS 32 / ~$1.15B, DHS 30 / ~$1.13B, DoD 0 / $0). Public USAspending data. AI-built (Rogue); human-reviewed before sale.

---

## Morning checklist (Benjamin — after COT has a real Payment Link)

Do **not** start until Friday COT Pack has a real `buy.stripe.com` link from `drafts/notes-first-cot-stripe-payment-link-2026-09-02.md`. Overnight Rogue stops before step 1.

1. Confirm COT live Note is pasted with a **real** Payment Link (not PLACEHOLDER). If COT is still PLACEHOLDER, **stop**. Do not create the USA link yet.
2. Open Stripe Dashboard. Open **Payment Links** (docs: https://docs.stripe.com/payment-links/create). Confirm labels in Dashboard if the nav differs.
3. **+New** Payment Link. Use **Products or subscriptions**, not “customers choose what to pay.”
4. **+Add a new product** (or pick an existing one only if it is already this SKU). Paste **Product name** and **Description** from `drafts/notes-first-usa-spending-checkout-2026-08-30.md`.
5. **Price:** enter Atlas’s pick inside the band. Do not invent a number outside $8–$20 / note. Leave monthly retain for later unless Atlas already chose it.
6. **After the payment:** paste the success placeholder from the checkout draft (`hosted_confirmation`). Do **not** invent a muonarc.com success URL.
7. Cancel URL: **confirm in Dashboard**. Do not guess a button. Keep the cancel placeholder as copy only.
8. Click **Create link**. Copy the real Payment Link URL Stripe shows (`buy.stripe.com/...`). That URL did not exist overnight. This repo must not invent it.
9. Open `drafts/notes-first-live-note-usa-spending-2026-09-02.md`. Replace `CHECKOUT URL: NOT LIVE / PLACEHOLDER` with the **real** Payment Link URL from step 8. Paste **Paste — Note title** and **Paste — Note body (short)** onto muonarc.com practice surface. Keep the AI disclosure. **Do not paste this Note overnight.**
10. Confirm **NCUA stays wait.** Do **not** paste `drafts/notes-first-live-note-ncua-title12-2026-09-02.md` (`edac1ff7`) and do **not** create an NCUA Stripe product until USA has a real Payment Link.

---

## Out (overnight and this window)

- Create a Stripe product / Price / Payment Link (COT or USA) overnight
- Call Stripe API / open Stripe UI beyond this md
- Invent a `buy.stripe.com` or muonarc.com checkout URL
- Paste a live Note (COT already has its own morning card; USA stays parked)
- Redo COT checklist SHA `14e19f28` or morning-card SHA `9bc569a3`
- Scaffold another unpublished Action (nist-nvd etc.)
- Tag / release / Marketplace publish / live-card About UI
- Retry NCUA CSV / Contents PUT / `git/trees`
- Merge PR #1 / PATCH `muonarc.com` `main`
- Send email / post / cold email / second emails on killed rails
- Walk this checklist in the Dashboard before COT has a real Payment Link

**STOP holds.**
