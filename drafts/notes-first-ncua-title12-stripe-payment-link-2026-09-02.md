# HITL morning checklist — create NCUA+Title12 Stripe Payment Link

**Status:** HITL checklist only. **Do not create a Stripe product or Payment Link from this file overnight.** Do **not** invent a live checkout URL. Do **not** call the Stripe API. Do **not** paste a live Note. Do **not** open Stripe UI beyond drafting this md. Lands on `cursor/notes-surface-a3e9` only. Not main. Not merged.

```
CHECKOUT URL: NOT LIVE / PLACEHOLDER
```

**Wait rule (7am card SHA `fb830d06`, same as USA):** NCUA Payment Link **waits until COT has a real live Payment Link.** Do not walk this checklist in the Dashboard before the Friday COT Pack Payment Link exists. Overnight Rogue does not log in to Stripe.

**AI disclosure (Rogue):** An AI (Rogue) drafted this checklist. Benjamin creates the Payment Link only after COT is live. Overnight Rogue does not create Stripe.

**SKU:** Weekly NCUA Letters-to-CUs + Title 12 Federal Register brief only. Not Friday COT Pack. Not USAspending Weekly. Not the $40 hospital MRF-change extract.

Same 7am Benjamin checklist shape as `drafts/notes-first-cot-stripe-payment-link-2026-09-02.md` (SHA `898bbfe2`) and `drafts/notes-first-usa-spending-stripe-payment-link-2026-09-02.md` (SHA `f13b658d`).

Paste-fields and click-path already on this branch (do not rewrite them):
- Click-path: `drafts/notes-first-ncua-title12-stripe-clickpath-2026-09-01.md`
- Checkout paste-fields: `drafts/notes-first-ncua-title12-checkout-2026-08-30.md`
- Live Note (parked until COT has a real link, then until this Payment Link exists): `drafts/notes-first-live-note-ncua-title12-2026-09-02.md` (SHA `edac1ff7`)
- COT Payment Link checklist (goes first): `drafts/notes-first-cot-stripe-payment-link-2026-09-02.md` (SHA `898bbfe2`)
- USA Payment Link checklist (also waits on COT): `drafts/notes-first-usa-spending-stripe-payment-link-2026-09-02.md` (SHA `f13b658d`)
- 7am card (cash-first; this is the 7am card): `drafts/notes-first-morning-cash-first-index-2026-09-02.md` (SHA `fb830d06`). Do **not** open stale `drafts/notes-first-morning-hitl-2026-09-02.md` at SHA `9bc569a3`.

Buyer CSV `drafts/ncua-title12-2026-08-30.csv` is still **404**. Do **not** retry Contents PUT / `git/trees` overnight. Fulfillment CSV is a daytime decision.

---

## Product (copy from existing paste-fields)

**Name**

```
Weekly NCUA Letters-to-CUs + Title 12 Federal Register brief
```

**Price band (UNLOCKED — Atlas / Benjamin picks at the Dashboard; do not lock overnight)**

- **$15–$40 / month retain** (weekly Note).
- Suggestion only (not live): $25 / month. May ignore.

**What the buyer gets:** Markdown/HTML brief + CSV. Window Monday 2026-08-24 through Sunday 2026-08-30 inclusive, US Eastern: 0 NCUA Letters to Credit Unions / Supervisory Letters; 8 Title 12 Federal Register items. Public NCUA + FR data. AI-built (Rogue); human-reviewed before sale.

---

## Morning checklist (Benjamin — after COT has a real Payment Link)

Do **not** start until Friday COT Pack has a real `buy.stripe.com` link from `drafts/notes-first-cot-stripe-payment-link-2026-09-02.md`. Overnight Rogue stops before step 1.

1. Confirm COT live Note is pasted with a **real** Payment Link (not PLACEHOLDER). If COT is still PLACEHOLDER, **stop**. Do not create the NCUA link yet.
2. Open Stripe Dashboard. Open **Payment Links** (docs: https://docs.stripe.com/payment-links/create). Confirm labels in Dashboard if the nav differs.
3. **+New** Payment Link. Use **Products or subscriptions**, not “customers choose what to pay.”
4. **+Add a new product** (or pick an existing one only if it is already this SKU). Paste **Product name** and **Description** from `drafts/notes-first-ncua-title12-checkout-2026-08-30.md`.
5. **Price:** enter Atlas’s pick inside **$15–$40 / month**. Do not invent a number outside the band. Suggestion $25 is not locked.
6. **After the payment:** paste the success placeholder from the checkout draft (`hosted_confirmation`). Do **not** invent a muonarc.com success URL.
7. Cancel URL: **confirm in Dashboard**. Do not guess a button. Keep the cancel placeholder as copy only.
8. Click **Create link**. Copy the real Payment Link URL Stripe shows (`buy.stripe.com/...`). That URL did not exist overnight. This repo must not invent it.
9. Open `drafts/notes-first-live-note-ncua-title12-2026-09-02.md`. Replace `CHECKOUT URL: NOT LIVE / PLACEHOLDER` with the **real** Payment Link URL from step 8. Paste **Paste — Note title** and **Paste — Note body (short)** onto muonarc.com practice surface. Keep the AI disclosure. **Do not paste this Note overnight.**
10. **Post-pay (first paid NCUA checkout):** fulfill with `drafts/notes-first-ncua-title12-fulfillment-email-2026-09-01.md`. Template only. Do **not** send the email overnight. Wait for a real paid checkout, then Atlas / Benjamin sends. Mirrors COT `898bbfe2` and USA `f13b658d`.
11. Buyer CSV is still 404. Do **not** retry NCUA CSV overnight. Daytime Atlas / Benjamin decision.

---

## Out (overnight and this window)

- Create a Stripe product / Price / Payment Link (COT, USA, or NCUA) overnight
- Call Stripe API / open Stripe UI beyond this md
- Invent a `buy.stripe.com` or muonarc.com checkout URL
- Paste a live Note
- Redo COT `898bbfe2`, USA `f13b658d`, or cash-first index `fb830d06` / open stale morning-hitl `9bc569a3`
- Scaffold another unpublished Action (nist-nvd parked)
- Tag / release / Marketplace publish / live-card About UI
- Retry NCUA CSV / Contents PUT / `git/trees`
- Merge PR #1 / PATCH `muonarc.com` `main`
- Send email / post / cold email / second emails on killed rails (r/datasets, DIP, OpenFEMA, NHC) (including the NCUA fulfillment template)
- Walk this checklist in the Dashboard before COT has a real Payment Link

**STOP holds.**
