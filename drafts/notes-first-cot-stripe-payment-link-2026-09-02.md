# HITL morning checklist — create Friday COT Pack Stripe Payment Link

**Status:** HITL checklist only. **Do not create a Stripe product or Payment Link from this file overnight.** Do **not** invent a live checkout URL. Do **not** call the Stripe API. Benjamin clicks in the Dashboard at 7am. Lands on `cursor/notes-surface-a3e9` only. Not main. Not merged.

```
CHECKOUT URL: NOT LIVE / PLACEHOLDER
```

**AI disclosure (Rogue):** An AI (Rogue) drafted this checklist. Benjamin creates the Payment Link. Overnight Rogue does not log in to Stripe.

**SKU:** Friday COT Pack only (Candidate 2). Not USA Spending. Not NCUA+Title12. Not the $40 hospital MRF-change extract.

Paste-fields and click-path already on this branch (do not rewrite them):
- Click-path: `drafts/notes-first-cot-stripe-clickpath-2026-09-01.md`
- Checkout paste-fields: `drafts/notes-first-cot-pack-checkout-2026-08-30.md`
- Success/cancel: `drafts/notes-first-cot-success-cancel-2026-09-01.md`
- Live Note to paste after the link exists: `drafts/notes-first-live-note-cot-pack-2026-09-02.md` (SHA `8be5ae54`)
- 7am card (cash-first, do not redo): `drafts/notes-first-morning-hitl-2026-09-02.md` (SHA `9bc569a3`)

---

## Product (copy from existing paste-fields)

**Name**

```
Friday COT Pack: 12 liquid futures (CFTC public)
```

**Price band (UNLOCKED — Atlas / Benjamin picks at the Dashboard; do not lock overnight)**

- **$12–$25 / Friday pack**, or **$20–$40 / month retain** (4 packs).
- Suggestion only (not live): $18 / pack or $32 / month. May ignore.
- One-time Friday pack first. Do not also create the monthly retain SKU this morning unless Atlas says so.

**What the buyer gets:** Markdown/HTML one-pager + CSV, 12 rows (CL, NG, GC, SI, ZC, ZS, ZW, ES, NQ, 6E, 6J, BTC). Week as-of Tuesday 2026-08-25 / released Friday 2026-08-28. Public CFTC data. AI-built (Rogue); human-reviewed before sale.

---

## Morning checklist (Benjamin)

Do in order. Overnight Rogue stops before step 1.

1. Open Stripe Dashboard. Open **Payment Links** (docs: https://docs.stripe.com/payment-links/create). Confirm labels in Dashboard if the nav differs.
2. **+New** Payment Link. Use **Products or subscriptions**, not “customers choose what to pay.”
3. **+Add a new product** (or pick an existing one only if it is already this SKU). Paste **Product name** and **Description** from `drafts/notes-first-cot-pack-checkout-2026-08-30.md`.
4. **Price:** enter Atlas’s pick inside the band. Do not invent a number outside $12–$25 / pack. Leave monthly retain for later unless Atlas already chose it.
5. **After the payment:** paste the success placeholder from the checkout draft (`hosted_confirmation`). Do **not** invent a muonarc.com success URL.
6. Cancel URL: **confirm in Dashboard**. Do not guess a button. Keep the cancel placeholder as copy only.
7. Click **Create link**. Copy the real Payment Link URL Stripe shows (`buy.stripe.com/...`). That URL did not exist overnight. This repo must not invent it.
8. Open `drafts/notes-first-live-note-cot-pack-2026-09-02.md`. Replace `CHECKOUT URL: NOT LIVE / PLACEHOLDER` with the **real** Payment Link URL from step 7. Paste **Paste — Note title** and **Paste — Note body (short)** onto muonarc.com practice surface. Keep the AI disclosure.
9. Confirm **USA and NCUA stay wait.** Do **not** paste `drafts/notes-first-live-note-usa-spending-2026-09-02.md` (`791ac4a6`) or `drafts/notes-first-live-note-ncua-title12-2026-09-02.md` (`edac1ff7`) until COT has a real Payment Link. Do **not** create USA or NCUA Stripe products this morning.

Then continue the 7am card: live Marketplace About cleanup, then the Marketplace publish queue, then NCUA CSV as a daytime decision.

---

## Out (overnight and this window)

- Create a Stripe product / Price / Payment Link overnight
- Call Stripe API
- Invent a `buy.stripe.com` or muonarc.com checkout URL
- Redo morning-card SHA `9bc569a3`
- Scaffold another Action (nist-nvd etc.)
- Tag / release / Marketplace publish / live-card About UI
- Retry NCUA CSV / Contents PUT / `git/trees`
- Merge PR #1 / PATCH `muonarc.com` `main`
- Send email / post / cold email
- Paste USA or NCUA live Notes before COT has a real Payment Link

**STOP holds.**
