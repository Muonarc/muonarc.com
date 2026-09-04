# HITL / NOT PUBLISHED — Stripe Payment Link success + cancel page paste copy (NCUA Title 12 Candidate 3)

**Status:** HITL draft. Not published. Not live. **Do not create the live Stripe product, Price, or Payment Link overnight.** Paste-ready success + cancel page copy only. Atlas drops these into Stripe Dashboard later when creating the NCUA Title 12 Payment Link from `drafts/notes-first-ncua-title12-stripe-clickpath-2026-09-01.md` / checkout `drafts/notes-first-ncua-title12-checkout-2026-08-30.md` (click-path commit SHA `df804479` / checkout blob `bfb17d043b0115ef7955302ab20f1d60645171b1` or live path). No Stripe login. No live SKU. No `buy.stripe.com` URL. No Ko-fi. No Gumroad. No GitHub paid storefront.

**Overnight rule (Atlas, 10:31 PM PT Sep 1, 2026):** Atlas does **not** create the live Stripe product overnight. Success + cancel paste copy only. Lands on `cursor/notes-surface-a3e9` only. Not main. Not merged. Other files untouched (click-paths, checkout sheets, briefs, kit, index, publish-order, morning card, USA success-cancel stay as-is). Do **not** rewrite `drafts/notes-first-ncua-title12-stripe-clickpath-2026-09-01.md`, `drafts/notes-first-ncua-title12-checkout-2026-08-30.md`, `drafts/notes-first-usa-spending-success-cancel-2026-09-01.md` (SHA `858037c4`), or `drafts/notes-first-cot-success-cancel-2026-09-01.md` already on this branch.

**SKU:** Candidate 3 only — Weekly NCUA Letters-to-CUs + Title 12 Federal Register brief. Not candidates 1 or 2. Not Friday COT Pack. Not USAspending Weekly. Not the $40 hospital MRF extract. Not Ko-fi. Not GitHub storefront. Not a muonarc.com live path.

**AI disclosure (Rogue):** An AI (Rogue + helper bots) prepared this success + cancel paste copy. Benjamin / Atlas reviews before any Payment Link or Note goes live. Any live Note would state it is AI-built.

**Sources (read-only — do not rewrite):**
- USA success + cancel shape (already on this branch): `drafts/notes-first-usa-spending-success-cancel-2026-09-01.md` SHA `858037c4`. Do **not** rewrite that file.
- COT success + cancel shape (already on this branch): `drafts/notes-first-cot-success-cancel-2026-09-01.md` blob `6fd1045767a207308aa5ba4774afcd63fe615f72`; Atlas SHA `4a43bfc3` (muonarc) and/or hospital-price-series `075bb136`. Do **not** rewrite that file.
- NCUA Title 12 checkout paste-fields (already on this branch): `drafts/notes-first-ncua-title12-checkout-2026-08-30.md` blob `bfb17d043b0115ef7955302ab20f1d60645171b1`
- NCUA Title 12 click-path (already on this branch): `drafts/notes-first-ncua-title12-stripe-clickpath-2026-09-01.md` SHA `df804479`
- Fulfillment email: not on this branch; not created; not rewritten. Atlas emails Markdown/HTML brief + CSV **after a real Payment Link exists** — not overnight.

```
CHECKOUT URL: NOT LIVE / PLACEHOLDER
```

Do not invent a live checkout URL.

---

## 1) Success page (buyers see after pay)

**NOT LIVE.** Placeholder title + body for Stripe `after_completion` / **Confirmation page** custom message (`hosted_confirmation`). Do not treat as a published success page. Do not invent a muonarc.com or `buy.stripe.com` success URL.

### Success page title

Stripe field: Confirmation page title / custom confirmation heading (if the Dashboard exposes one). **Confirm in Dashboard.** Do not invent a live URL.

```
Thanks — NCUA Title 12 brief received
```

### Success page body

Stripe field: Confirmation page custom message (`after_completion.hosted_confirmation.custom_message`). Atlas emails the brief **after a real Payment Link exists** (not overnight). After a paid/live Payment Link exists, Atlas emails Markdown/HTML brief + CSV. No live checkout URL.

```
Thanks — this purchase is recorded.

Atlas will email this week's Markdown/HTML brief and CSV (Weekly NCUA Letters-to-CUs + Title 12 Federal Register brief; window 2026-08-24–08-30 ET: 0 NCUA Letters to Credit Unions / Supervisory Letters; 8 Title 12 Federal Register items) after a real Payment Link exists. Not overnight. No live URL in this draft.

This success page is a placeholder, not a live muonarc.com path. There is no live checkout URL in this draft.

If you do not receive the files, reply to the receipt email.
```

Suggested `after_completion` type: `hosted_confirmation` (or custom URL later). If Atlas later wants `after_completion.type` = `redirect`, the URL stays a placeholder until a real page exists. Docs: https://docs.stripe.com/payment-links/post-payment

---

## 2) Cancel page (buyers who leave checkout)

**NOT LIVE.** Placeholder title + body. Do not treat as a published cancel page. Do not invent a live cancel URL. Try again / return path is copy only — no live URL.

### Cancel page title

Stripe field: cancel / abandoned-checkout page title **if** the Dashboard exposes one. Public Payment Links docs do **not** document a Dashboard **Cancel URL** field (unlike Checkout Session `cancel_url`). **Confirm in Dashboard.** Do not guess a button named "Cancel URL."

```
Checkout canceled — no charge
```

### Cancel page body

Try again / return path without a live URL. No charge. Brief not delivered. Close tab, or try again later from the same Payment Link Atlas shares when it is live. No live cancel URL.

```
Checkout canceled. No charge.

The Weekly NCUA Letters-to-CUs + Title 12 Federal Register brief was not delivered. You can close this tab, or try again later from the same Payment Link Atlas shares when it is live.

This cancel page is a placeholder, not a live muonarc.com path. There is no live checkout URL in this draft. Do not bookmark a buy.stripe.com or muonarc.com cancel path from this file — none exists.
```

No live cancel URL. Atlas may paste a cancel URL later **if** the Dashboard exposes one. Confirm in Dashboard whether a cancel URL field exists. Do not guess a button.

---

## 3) Paste-ready Stripe Dashboard fields (later — not overnight)

Copy each labeled block into the matching Stripe Payment Link field **later**, when creating the NCUA Title 12 Payment Link from `drafts/notes-first-ncua-title12-stripe-clickpath-2026-09-01.md` SHA `df804479` / checkout blob `bfb17d043b0115ef7955302ab20f1d60645171b1` (or live checkout path `drafts/notes-first-ncua-title12-checkout-2026-08-30.md`). Atlas does **not** paste these overnight. **Do not click Create link. Do not create the live product.**

Price bands stay **UNLOCKED**. Success/cancel stay placeholders — not live URLs.

### Product name

Stripe field: Product name.

```
Weekly NCUA Letters-to-CUs + Title 12 Federal Register brief
```

### Price band (UNLOCKED — do not lock a live amount)

**Band from NCUA checkout blob `bfb17d04`:** **$15–$40 / month retain** (weekly Note).

Atlas picks a number later. Do **not** invent a live locked price in Stripe. Do **not** paste a single dollar amount from this file as if it were live.

- Monthly retain = weekly Note (Markdown/HTML brief + CSV of the week's NCUA letters and Title 12 FR items).

**SUGGESTION (not live, in-band only — Atlas may ignore):** $25 / month retain. Suggestion only. Not a Stripe price. Not a live SKU.

Stripe field: Price. Leave unset or enter Atlas’s pick later.

### Description / what the buyer gets

Stripe field: Product description / Payment Link description.

```
This week's NCUA Letters-to-CUs + Title 12 Federal Register brief.

Window Monday 2026-08-24 through Sunday 2026-08-30 inclusive, US Eastern: 0 NCUA Letters to Credit Unions / Supervisory Letters; 8 Title 12 Federal Register items. Markdown/HTML brief + CSV. Not a GitHub issue form.

HITL source (not a storefront):
- drafts/notes-first-ncua-title12-2026-08-30.md
- drafts/ncua-title12-2026-08-30.csv

Public NCUA and Federal Register pages only. AI-built (Rogue); human-reviewed before any live sale.
```

### After the payment (success — paste later)

Docs: https://docs.stripe.com/payment-links/post-payment

Later, when creating the live link:

1. Click **After the payment**.
2. Under **Confirmation page**, prefer the documented custom confirmation message (`hosted_confirmation`).
3. Paste **Success page title** (if a heading field exists — confirm in Dashboard).
4. Paste **Success page body** as the custom message.
5. Do **not** set a live muonarc.com or `buy.stripe.com` success URL.

If **After the payment** / **Confirmation page** is not visible, **confirm in Dashboard**. Do not guess another label.

### Cancel (paste later if Dashboard exposes a field)

Keep **Cancel page title** + **Cancel page body** as copy only. No live cancel URL. Confirm in Dashboard whether a cancel / abandoned-checkout URL exists. Do not guess a button.

### CHECKOUT URL

**NOT LIVE / PLACEHOLDER.** Do not invent a `buy.stripe.com` or muonarc.com checkout URL.

```
CHECKOUT URL: NOT LIVE / PLACEHOLDER
```

---

## HITL close

- File: `drafts/notes-first-ncua-title12-success-cancel-2026-09-01.md` on `cursor/notes-surface-a3e9` only. Not main. Not merged.
- Success + cancel paste copy only. Not a live Stripe product. **Do not create the live Stripe product overnight.**
- Price band **unlocked** ($15–$40/month retain). Success/cancel stay placeholders. Checkout URL: NOT LIVE / PLACEHOLDER.
- USA success+cancel `drafts/notes-first-usa-spending-success-cancel-2026-09-01.md` SHA `858037c4` is **untouched**.
- COT success+cancel `drafts/notes-first-cot-success-cancel-2026-09-01.md` blob `6fd1045767a207308aa5ba4774afcd63fe615f72` / Atlas SHA `4a43bfc3` is **untouched**.
- NCUA checkout `drafts/notes-first-ncua-title12-checkout-2026-08-30.md` blob `bfb17d043b0115ef7955302ab20f1d60645171b1` is **untouched**.
- NCUA click-path `drafts/notes-first-ncua-title12-stripe-clickpath-2026-09-01.md` SHA `df804479` is **untouched**.
- Three click-paths, three checkouts, three product briefs, kit, index, publish-order, and morning card are **untouched**.
- STOP holds: no $40 hospital MRF extract, no GitHub paid storefront, no extract-request, no cold email, no r/datasets, DIP, OpenFEMA, NHC. No publish, post, email, chase, or listing UI. No live Stripe overnight.

AI-drafted by Rogue. Benjamin / Atlas reviews before any Payment Link or Note goes live.
