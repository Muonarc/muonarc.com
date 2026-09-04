# HITL / NOT PUBLISHED — Stripe Dashboard click-path only (USA Spending Weekly Payment Link)

**Status:** HITL draft. Not published. Not live. **Do not create the live Stripe product, Price, or Payment Link from this file.** This is a Dashboard click-path Atlas / Benjamin would use later. No Stripe login, no live SKU, no `buy.stripe.com` URL, no Ko-fi, no Gumroad, no GitHub paid storefront.

**Overnight rule (Atlas, 10:16 PM PT Sep 1, 2026):** Atlas does **not** create the live Stripe product overnight. Click-path only. Do **not** rewrite already-landed files: COT kit, notes-index, three checkouts, three product briefs, publish-order, COT stripe clickpath (`drafts/notes-first-cot-stripe-clickpath-2026-09-01.md`), NCUA brief (`drafts/notes-first-ncua-title12-2026-08-30.md` SHA `bd393a0d`). Other files untouched. This file lands on `cursor/notes-surface-a3e9` only. Not main. Not merged. Not a live checkout.

**SKU:** Candidate 1 only — **USAspending Weekly NAICS 541512 Prime Awards (DoD / HHS / DHS)**. Not candidates 2–3. Not Friday COT Pack. Not NCUA. Not the $40 hospital MRF-change extract. Not Ko-fi. Not GitHub storefront. Not a muonarc.com live path.

**AI disclosure (Rogue):** An AI (Rogue + helper bots) prepared this click-path. Benjamin / Atlas reviews before any Payment Link or Note goes live. Any live Note would state it is AI-built.

**Paste-fields source (read-only, already on this branch, commit SHA `ff2374f1`, blob `5bf3ff540ff7901c58caa201108575d34b32259b`):** `drafts/notes-first-usa-spending-checkout-2026-08-30.md`  
Copy product name, description, price band, and success/cancel placeholders from that file. Do not lock a live amount. Do not invent live URLs. Do not rewrite that checkout draft.

**Shape source (read-only, already on this branch, commit SHA `f4a6833f`, blob `f7157a39dbe21a8da95ebea5394d950282891bb2`):** `drafts/notes-first-cot-stripe-clickpath-2026-09-01.md`  
Same Dashboard click-path sections and public Stripe docs URLs. Do not rewrite that COT click-path.

**Public Stripe docs used (fetched Sep 1, 2026; do not invent menu names):**

- Create a payment link: https://docs.stripe.com/payment-links/create
- Payment Links overview: https://docs.stripe.com/payment-links
- After a payment link payment (`after_completion`): https://docs.stripe.com/payment-links/post-payment
- Manage products and prices (Product catalog): https://docs.stripe.com/products-prices/manage-prices
- No-code Payment Links: https://docs.stripe.com/no-code/payment-links

If a click label is uncertain, this draft quotes the docs URL and says **confirm in Dashboard** rather than guessing a button.

---

## PASTE fields (from SHA `ff2374f1` / blob `5bf3ff54` — not live)

Copy each labeled block into the matching Stripe Payment Link field **later**. Nothing here is live. Atlas does not paste these overnight.

### Product name

Stripe field: Product name.

```
USAspending Weekly: NAICS 541512 Prime Awards (DoD, HHS, DHS)
```

### Price band (UNLOCKED — do not lock a live amount)

**Band from SHA `ff2374f1`:** **$8–$20 / note**, or **$12–$40 / month retain**.

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

Delivery: Markdown/HTML Note + CSV of the week’s awards. Not a GitHub issue form. Not Marketplace. Not Ko-fi.

### Success placeholder (`after_completion` / confirmation — NOT a live URL)

**NOT LIVE.** Placeholder copy only. Do not treat as a published success page. Do not invent a muonarc.com or `buy.stripe.com` success URL.

```
Thanks — this purchase is recorded. Atlas will email the week’s Markdown/HTML Note and CSV (USAspending Weekly: NAICS 541512 Prime Awards, week 2026-08-24–08-30 ET). This success page is a placeholder, not a live muonarc.com path. If you do not receive the files, reply to the receipt email.
```

Suggested `after_completion` type from SHA `ff2374f1`: `hosted_confirmation` (or custom URL later). No live URL in this file.

Stripe API names (for Atlas, not to call overnight): `after_completion.type` = `hosted_confirmation` or `redirect`; if redirect, `after_completion.redirect.url` stays a placeholder until a real page exists. Docs: https://docs.stripe.com/payment-links/post-payment

### Cancel placeholder (NOT a live URL)

**NOT LIVE.** Placeholder copy only. Do not treat as a published cancel page. Do not invent a live cancel URL.

```
Checkout canceled. No charge. You can close this tab. This cancel page is a placeholder, not a live muonarc.com path. The USAspending Weekly NAICS 541512 pack was not delivered.
```

No live cancel URL. Atlas may paste a cancel URL later **if** the Dashboard exposes one (see step 7 — do not guess a button).

### CHECKOUT URL

**NOT LIVE / PLACEHOLDER.** Do not invent a `buy.stripe.com` or muonarc.com checkout URL.

```
CHECKOUT URL: NOT LIVE / PLACEHOLDER
```

---

## Numbered Dashboard click-path (later — not overnight)

Use the **Products or subscriptions** path (fixed product + price Atlas picks later). Do **not** use **Customers choose what to pay** unless Atlas later chooses a pay-what-you-want band; the USA Spending paste-fields are a priced pack, not a donation.

**Atlas does not walk this path overnight. Do not click Create link. Do not create the live product.**

### 1. Open the Stripe Dashboard (later, human)

Sign in only when Atlas / Benjamin is ready to create the live link. This draft does not log in.

### 2. Open the Payment Links page

Docs: https://docs.stripe.com/payment-links/create

> In the Dashboard, open the Payment Links page

Desktop sidebar label beyond “Payment Links page” is not spelled out on that docs page. **Confirm in Dashboard.** iOS app (same docs): Payments > Payment Links.

Checkout studio is documented as another hub for Payment Links (https://docs.stripe.com/payment-links/create). If the left nav does not show Payment Links, **confirm in Dashboard** rather than guessing a menu. Do not open Product catalog solely to pre-create a live product overnight (see step 4).

### 3. Start a new Payment Link — do not finish it overnight

Docs: https://docs.stripe.com/payment-links/create (Products or subscriptions)

1. Click **+New** (or click the plus sign **(+)** and select **Payment link**).
2. Stop. Do **not** click **Create link** overnight.

If **+New** is not visible, **confirm in Dashboard** (https://docs.stripe.com/payment-links/create). Do not guess a different button name.

### 4. Product / price — paste later; do not create the live product now

Docs: https://docs.stripe.com/payment-links/create and Product catalog https://docs.stripe.com/products-prices/manage-prices

On the new Payment Link:

1. Select an existing product **or** click **+Add a new product**.
2. If adding a new product, fill out the product details and click **Add product** — **later only**.
3. Paste **Product name** from PASTE fields above.
4. Paste **Description** from PASTE fields above.
5. **Price:** leave **UNLOCKED**. Band is **$8–$20 / note** or **$12–$40 / month retain**. Atlas picks the number later. Do not lock $12, $24, or any other single amount from this draft.

Do **not** pre-create the SKU in **More > Product catalog** overnight. Catalog path is documented (https://docs.stripe.com/products-prices/manage-prices: Go to **More > Product catalog**, then **+Add product**, **Name**, optional **Description**) but Atlas is not to create the live product in this window. Prefer adding the product from the Payment Link form **when** the live link is actually created, so a catalog row is not sitting live unused.

One-time vs recurring: confirm in Dashboard. Per-note = one-time Monday pack; month retain = four packs — Atlas chooses which SKU form later. Do not create both overnight.

### 5. After the payment / `after_completion` (success placeholder)

Docs: https://docs.stripe.com/payment-links/post-payment

> To change the confirmation behavior on a payment link, click **After the payment** when creating or editing a payment link. Under **Confirmation page**, you can choose to replace the default message with a custom one.

You can also redirect to a website instead of a confirmation page. Redirect URL may include `{CHECKOUT_SESSION_ID}`. **Do not invent a live redirect URL.**

Later, when creating the live link:

1. Click **After the payment**.
2. Under **Confirmation page**, prefer the documented custom confirmation message (`hosted_confirmation`) and paste the **Success placeholder** text above.
3. Do **not** set a live muonarc.com success URL. If Atlas later wants `after_completion.type` = `redirect`, the URL stays a placeholder until a real page exists.

If **After the payment** / **Confirmation page** is not visible, **confirm in Dashboard** (https://docs.stripe.com/payment-links/post-payment). Do not guess another label.

### 6. Click **Create link** — later only, never overnight

Docs: https://docs.stripe.com/payment-links/create step 4: **Create link**.

Overnight: do **not** click it. After a real click, Stripe would mint a Payment Link URL (`buy.stripe.com/...`). This repo must not invent or store that URL until a human creates it.

### 7. Cancel URL / cancel page — confirm in Dashboard; do not invent

Public Payment Links docs document **after_completion** for **successful** payment (hosted confirmation or redirect). They do **not** document a Dashboard **cancel URL** field on Payment Links (unlike Checkout Session `cancel_url`).

- Docs checked: https://docs.stripe.com/payment-links/create, https://docs.stripe.com/payment-links/post-payment, https://docs.stripe.com/payment-links
- **Confirm in Dashboard** whether a cancel / abandoned-checkout URL exists in the current Payment Link form.
- Do **not** guess a button named “Cancel URL.”
- Keep the **Cancel placeholder** text above as copy only. No live cancel URL. Atlas may paste a cancel URL later if the Dashboard exposes one.

### 8. Do not share, copy, or publish the link overnight

Sharing, QR, buy button, and deactivate controls exist on the Payment Links page after a link exists (https://docs.stripe.com/no-code/payment-links). They are irrelevant until a live link is created. Do not copy, email, post, or publish.

---

## Fulfillment (unchanged)

Email via Atlas until Stripe delivery is wired. After a **real** Payment Link exists, Atlas emails the Note + CSV to the buyer. No GitHub issue fulfillment. No automatic attach from this repo. No Stripe file delivery in this draft. Do not send email overnight from this file.

---

## HITL close

- File: `drafts/notes-first-usa-spending-stripe-clickpath-2026-09-01.md` on `cursor/notes-surface-a3e9` only. Not main. Not merged.
- Click-path only. Not a live Stripe product. Atlas does **not** create the live product overnight.
- Paste-fields copied from `drafts/notes-first-usa-spending-checkout-2026-08-30.md` SHA `ff2374f1` (blob `5bf3ff540ff7901c58caa201108575d34b32259b`). That checkout draft is **untouched**.
- COT click-path `drafts/notes-first-cot-stripe-clickpath-2026-09-01.md` SHA `f4a6833f` is **untouched**.
- NCUA brief `drafts/notes-first-ncua-title12-2026-08-30.md` SHA `bd393a0d` is **untouched**.
- Price band **unlocked** ($8–$20/note or $12–$40/month retain). Success/cancel stay placeholders. Checkout URL: NOT LIVE / PLACEHOLDER.
- Candidate 1 only: USAspending Weekly NAICS 541512 Prime Awards (DoD / HHS / DHS). Not a live product.
- STOP holds: no $40 hospital MRF extract, no GitHub paid storefront, no extract-request, no cold email, no r/datasets, DIP, OpenFEMA, NHC. No publish, post, email, chase, or listing UI. No live Stripe overnight.

AI-drafted by Rogue. Benjamin / Atlas reviews before any Payment Link or Note goes live.
