# Live Marketplace About cleanup — 7:00 AM PT HITL card (not overnight)

**When:** 7:00 AM PT paste for Benjamin. One card. Sequence only. Do not hunt SHAs.

**Status:** HITL paste-ready. AI-drafted. Overnight: do **not** open the Marketplace listing UI. Do **not** create tags. Do **not** create releases. Do **not** publish the pending nws/usgs/openfda trio. Lands on `cursor/notes-surface-a3e9` only. Not main. Not merged.

**What this is:** Morning click-path to **edit About / short description** on the **three LIVE published Marketplace cards only**. Free utilities / Continuous integration. **No paid SKU. No Ko-fi. No hospital MRF-change extract. No extract-request.**

**What this is not:** The pending trio publish runbook (`drafts/notes-first-marketplace-trio-morning-publish-2026-09-02.md`, SHA `2dff3266`) — leave it. Not NCUA CSV. Not muonarc.com Notes publish. Not Stripe. Not email. Not a post.

**AI disclosure (Rogue):** An AI (Rogue) prepared this 7am sequence. Benjamin clicks. Atlas does not edit listing UI overnight.

Source files on `main` are already stripped. Live **card About is a separate Marketplace field** and still had leftover paid CTAs overnight. Do **not** retag so the card “picks up” `action.yml` — **edit the listing text**.

---

## Benjamin must click (this order)

Do **1 → 2 → 3**. Finish each card (Save) before the next. Do **not** retag. Do **not** Draft a new release. Do **not** check “Publish this Action to the GitHub Marketplace” again.

For **each** live card below:

1. Open the **live Marketplace URL** (not a 404 slug).
2. Click **Edit listing** (publisher control on that card). If GitHub only offers edit from the release: repo → **Releases** → **Latest** → edit the attached Marketplace listing. **Do not** change the tag name.
3. Replace **Short description** with the paste line for that card. Do **not** lead with a paid signal.
4. Replace **About / long description** paid blocks (anything `$40`, Ko-fi commissions, extract-request, offer.html storefront, “How to order”) with the About paste. Keep free-Action usage. Keep AI disclosure. Keep “not endorsed by CMS / any hospital”.
5. **Save listing.** Do not create `v0.1.7` / `v0.1.1`. Do not retag `v0.1.6` or `v0.1.0`.
6. Confirm the public card no longer shows `$40`, Ko-fi, or extract-request.

Then the next card.

---

### 1) hospital-mrf-index (first)

- Live card: https://github.com/marketplace/actions/hospital-mrf-index (HTTP 200, Latest **v0.1.6**)
- Source repo: https://github.com/bennyj121/hospital-price-series HEAD `0e91d02c0eaddad33e5062b51e8813dcaec80c64`
- Do **not** retag `v0.1.6`
- Overnight leftover About: `$40 hospital MRF-change extract. Free index: fetch cms-hpt.txt…` plus extract-request / offer.html
- Short description paste:

```
Fetch a hospital cms-hpt.txt and write published MRF URLs, optional CPT extract.
```

- About paste (free utilities; no paid SKU):

```
Free GitHub Action hospital-mrf-index: fetch a hospital cms-hpt.txt (45 CFR 180.50) and write published mrf-url lines. Optional shoppable extract from a CMS wide CSV already in the workspace (no zip download).

uses: bennyj121/hospital-price-series@v0.1.6

Built by Rogue, an AI agent, not a human. Not endorsed by CMS or any hospital. Do not email hospital staff listed in an index.
```

### 2) cms-hpt-validate (second)

- Live card: https://github.com/marketplace/actions/cms-hpt-validate (HTTP 200)
- Source repo: https://github.com/bennyj121/cms-hpt-validate HEAD `06125aa0cc9b6c21adc7c4089b8c897962a48b69`
- Do **not** retag `v0.1.0`
- Overnight leftover About: `Validate hospital cms-hpt.txt… $40 monthly compliance digest via Ko-fi`
- Short description paste:

```
Validate hospital cms-hpt.txt and HEAD-check mrf-url targets.
```

- About paste:

```
Free GitHub Action that validates a hospital cms-hpt.txt (45 CFR 180.50) and optionally HEAD-checks each mrf-url. Writes cms-hpt-validate.json. Redacts contact-email.

uses: bennyj121/cms-hpt-validate@v0.1.0

Built by Rogue, an AI agent, not a human. Not endorsed by CMS or any hospital. Do not email hospital staff listed in an index.
```

### 3) cms-hpt-validator (third)

- Live card: https://github.com/marketplace/actions/cms-hpt-validator (HTTP 200)
- Source repo: https://github.com/bennyj121/hpt-validator-action HEAD `007270db02cda4085fb290c0ca1a119d057e1006`
- HITL slug https://github.com/marketplace/actions/hpt-validator-action is **404** — do **not** publish a new card there
- Do **not** retag `v0.1.0`
- Overnight leftover About: `$40 multi-hospital HPT report. Free Action wraps @cmsgov/hpt-validator-cli`
- Short description paste:

```
Wrap @cmsgov/hpt-validator-cli to validate hospital MRF CSV/JSON in CI.
```

- About paste:

```
Free GitHub Action that wraps the official CMS Hospital Price Transparency CLI (@cmsgov/hpt-validator-cli) so CI can validate one MRF CSV/JSON file.

uses: bennyj121/hpt-validator-action@v0.1.0

Built by Rogue, an AI agent, not a human. Not affiliated with or endorsed by CMS.
```

---

## Out (do not do on this card)

- Open listing editor **overnight**
- Create tags / releases / retag `v0.1.6` or `v0.1.0`
- Publish pending nws / usgs / openfda (that is a **different** 7am card: `2dff3266`)
- Redo `drafts/notes-first-marketplace-trio-morning-publish-2026-09-02.md`
- Retry NCUA CSV (`drafts/ncua-title12-2026-08-30.csv` still 404; git/trees Auto-review blocked)
- Merge Muonarc/muonarc.com PR #1 / PATCH `muonarc.com` `main`
- Live Stripe / invented checkout URL / email / post / cold outreach
- r/datasets, DIP, OpenFEMA, NHC
- First live Note on muonarc.com (still waits on Benjamin)

**STOP holds.**
