# HITL / NOT PUBLISHED — Stripe Payment Link success + cancel page paste copy (USA Spending Candidate 1)

**Status:** HITL draft. Not published. Not live. **Do not create the live Stripe product, Price, or Payment Link overnight.** Paste-ready success + cancel page copy only. Atlas drops these into Stripe Dashboard later when creating the USA Spending Payment Link from `drafts/notes-first-usa-spending-stripe-clickpath-2026-09-01.md` / checkout `drafts/notes-first-usa-spending-checkout-2026-08-30.md` (commit SHA `ff2374f1` / blob `5bf3ff540ff7901c58caa201108575d34b32259b` or live path). No Stripe login. No live SKU. No `buy.stripe.com` URL. No Ko-fi. No Gumroad. No GitHub paid storefront.

**Overnight rule (Atlas, 10:29 PM PT Sep 1, 2026):** Atlas does **not** create the live Stripe product overnight. Success + cancel paste copy only. Lands on `cursor/notes-surface-a3e9` only. Not main. Not merged. Other files untouched (click-path, checkout sheet, COT success-cancel stay as-is). Do **not** rewrite `drafts/notes-first-usa-spending-stripe-clickpath-2026-09-01.md`, `drafts/notes-first-usa-spending-checkout-2026-08-30.md`, or `drafts/notes-first-cot-success-cancel-2026-09-01.md` already on this branch.

**SKU:** Candidate 1 only — USAspending Weekly NAICS 541512 Prime Awards (DoD / HHS / DHS). Not candidates 2–3. Not Friday COT Pack. Not NCUA. Not the $40 hospital MRF extract. Not Ko-fi. Not GitHub storefront. Not a muonarc.com live path.

**AI disclosure (Rogue):** An AI (Rogue + helper bots) prepared this success + cancel paste copy. Benjamin / Atlas reviews before any Payment Link or Note goes live. Any live Note would state it is AI-built.

**Sources (read-only — do not rewrite):**
- COT success + cancel shape (already on this branch): `drafts/notes-first-cot-success-cancel-2026-09-01.md` blob `6fd1045767a207308aa5ba4774afcd63fe615f72`; Atlas SHA `4a43bfc3` (muonarc) and/or hospital-price-series `075bb136`. Do **not** rewrite that file.
- USA Spending checkout paste-fields (already on this branch): `drafts/notes-first-usa-spending-checkout-2026-08-30.md` Atlas SHA `ff2374f1`, blob `5bf3ff540ff7901c58caa201108575d34b32259b`
- USA Spending click-path (already on this branch): `drafts/notes-first-usa-spending-stripe-clickpath-2026-09-01.md` SHA `2897654f`
- Fulfillment email: not on this branch; not created; not rewritten. Atlas emails Markdown/HTML Note + CSV **after a real Payment Link exists** — not overnight.

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
Thanks — USAspending Weekly pack received
```

### Success page body

Stripe field: Confirmation page custom message (`after_completion.hosted_confirmation.custom_message`). Atlas emails the brief **after a real Payment Link exists** (not overnight). After a paid link exists, Atlas emails Markdown/HTML Note + CSV. No live checkout URL.

```
Thanks — this purchase is recorded.

Atlas will email this week's Markdown/HTML Note and CSV (USAspending Weekly: NAICS 541512 Prime Awards, DoD / HHS / DHS; week 2026-08-24–08-30 ET) after a real Payment Link exists. Not overnight. No live URL in this draft.

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

Try again / return path without a live URL. No charge. Pack not delivered. Close tab, or try again later from the same Payment Link Atlas shares when it is live. No live cancel URL.

```
Checkout canceled. No charge.

The USAspending Weekly NAICS 541512 pack was not delivered. You can close this tab, or try again later from the same Payment Link Atlas shares when it is live.

This cancel page is a placeholder, not a live muonarc.com path. There is no live checkout URL in this draft. Do not bookmark a buy.stripe.com or muonarc.com cancel path from this file — none exists.
```

No live cancel URL. Atlas may paste a cancel URL later **if** the Dashboard exposes one.

---

## 3) Paste-ready Stripe Dashboard fields (later — not overnight)

Copy each labeled block into the matching Stripe Payment Link field **later**, when creating the USA Spending Payment Link from `drafts/notes-first-usa-spending-stripe-clickpath-2026-09-01.md` SHA `2897654f` / checkout SHA `ff2374f1` (or live checkout path `drafts/notes-first-usa-spending-checkout-2026-08-30.md`). Atlas does **not** paste these overnight. **Do not click Create link. Do not create the live product.**

Price bands stay **UNLOCKED**. Success/cancel stay placeholders — not live URLs.

### Product name

Stripe field: Product name.

```
USAspending Weekly: NAICS 541512 Prime Awards (DoD, HHS, DHS)
```

### Price band (UNLOCKED — do not lock a live amount)

**Band from USA checkout SHA `ff2374f1` / blob `5bf3ff54`:** **$8–$20 / note**, or **$12–$40 / month retain**.

Atlas picks a number later. Do **not** invent a live locked price in Stripe. Do **not** paste a single dollar amount from this file as if it were live.

- Per-note = one Monday pack (Markdown/HTML Note + CSV).
- Monthly retain = four consecutive Monday packs (same NAICS, same three agencies, same field set).

**SUGGESTION (not live, in-band only — Atlas may ignore):** $12 / note, or $24 / month retain. Suggestion only. Not a Stripe price. Not a live SKU.

Stripe field: Price. Leave unset or enter Atlas’s pick later.

### Description / what the buyer gets

Stripe field: Product description / Payment Link description.

```
This week's USAspending NAICS 541512 prime-award pack (DoD, HHS, DHS; ≥$250k; prior 7 days).

Week 2026-08-24–08-30 ET: 62 primes ≥$250k; ~$2.28B awarded (HHS 32 / ~$1.15B, DHS 30 / ~$1.13B, DoD 0 / $0). Markdown/HTML Note + CSV. Not a GitHub issue form.

HITL source (not a storefront):
- drafts/notes-first-usa-spending-2026-08-30.md
- drafts/usaspending-541512-dod-hhs-dhs-2026-08-31.csv

Public USAspending data only. AI-built (Rogue); human-reviewed before any live sale.
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

- File: `drafts/notes-first-usa-spending-success-cancel-2026-09-01.md` on `cursor/notes-surface-a3e9` only. Not main. Not merged.
- Success + cancel paste copy only. Not a live Stripe product. **Do not create the live Stripe product overnight.**
- Price band **unlocked** ($8–$20/note or $12–$40/month retain). Success/cancel stay placeholders. Checkout URL: NOT LIVE / PLACEHOLDER.
- USA checkout `drafts/notes-first-usa-spending-checkout-2026-08-30.md` SHA `ff2374f1` is **untouched**.
- USA click-path `drafts/notes-first-usa-spending-stripe-clickpath-2026-09-01.md` SHA `2897654f` is **untouched**.
- COT success-cancel `drafts/notes-first-cot-success-cancel-2026-09-01.md` blob `6fd1045767a207308aa5ba4774afcd63fe615f72` / Atlas SHA `4a43bfc3` is **untouched**.
- STOP holds: no $40 hospital MRF extract, no GitHub paid storefront, no extract-request, no cold email, no r/datasets, DIP, OpenFEMA, NHC. No publish, post, email, chase, or listing UI. No live Stripe overnight.

AI-drafted by Rogue. Benjamin / Atlas reviews before any Payment Link or Note goes live.
