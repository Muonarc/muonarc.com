# Marketplace trio morning publish — 7:00 AM PT HITL card (not live)

**When:** 7:00 AM PT paste for Benjamin. One card. Sequence only. Do not hunt SHAs.

**Status:** HITL paste-ready. AI-drafted. Overnight: do **not** create tags, do **not** create releases, do **not** publish Marketplace. Lands on `cursor/notes-surface-a3e9` only. Not main. Not merged.

**What this is:** Morning publish runbook for the **cleaned unpublished trio only**. Free utilities / Continuous integration. **No paid SKU. No Ko-fi. No hospital MRF-change extract. No $40 CTAs.**

**What this is not:** hospital-mrf-index, cms-hpt-validate, cms-hpt-validator (live HPT cards stay as-is; leftover $40 About text is a **separate** morning HITL). Not NCUA CSV. Not muonarc.com Notes publish. Not Stripe. Not email. Not a post.

**AI disclosure (Rogue):** An AI (Rogue) prepared this 7am sequence. Benjamin clicks. Atlas does not publish overnight.

---

## Benjamin must click (this order)

Do **1 → 2 → 3**. Finish each Action (tag + Marketplace) before the next repo. Do **not** retag `v0.1.0`. Do **not** skip the new tag.

For **each** of the three repos below:

1. Open the repo URL.
2. Confirm `main` is still the cleaned HEAD named here (or a later commit that keeps the $40-CTA strip). If `main` rewound to the pre-strip SHA, **stop that repo** and ping Atlas. Do not publish `v0.1.0`.
3. **Releases → Draft a new release.**
4. Create **new** tag **`v0.1.1`** targeting that cleaned `main` SHA. **Do not** move or retag `v0.1.0` (it still peels the pre-strip commit with leftover paid CTAs).
5. Release title: `v0.1.1`. Body: one line — free GitHub Action; built by Rogue (AI); not an official NWS/USGS/FDA product.
6. Check **Publish this Action to the GitHub Marketplace**.
7. If GitHub shows the Marketplace Developer Agreement, **Benjamin accepts** (required click). Overnight Rogue does not accept or pay a publisher fee.
8. Primary category: **Continuous integration** (Monitoring if CI is not offered).
9. Paste **Short description** from that repo’s `drafts/MARKETPLACE-LISTING.md` (free utilities; do **not** lead with a paid signal). Confirm branding from `action.yml`.
10. **Publish release.** Confirm the Marketplace card is HTTP 200 (unpublished slugs were 404 overnight). If the slug 404s, the live card is the GitHub-generated slug from `action.yml` `name:` — still 200, not a redo.

Then the next repo.

---

### 1) nws-alerts-action (first)

- Repo: https://github.com/bennyj121/nws-alerts-action
- Cleaned HEAD: `2f7cd9fd5ec1178acb710af62988d417ec30ec69`
- Listing: `drafts/MARKETPLACE-LISTING.md` on that HEAD
- Short description: `Fetch NWS active alerts from api.weather.gov, optional change-detect.`
- Branding: cloud / blue
- `v0.1.0` still peels pre-strip `7972f448` — do **not** publish from it
- Expected unpublished slug overnight: https://github.com/marketplace/actions/nws-alerts-action (404). Name-slug: `nws-active-alerts`

### 2) usgs-earthquakes-action (second)

- Repo: https://github.com/bennyj121/usgs-earthquakes-action
- Cleaned HEAD: `e0661964835c63ab05bc38e2e2c6d5d2196cd3fc`
- Listing: `drafts/MARKETPLACE-LISTING.md` on that HEAD
- Short description: `Fetch USGS FDSN earthquakes, optional change-detect.`
- Branding: activity / yellow
- `v0.1.0` still peels pre-strip `513ea9f4` — do **not** publish from it
- Expected unpublished slug overnight: https://github.com/marketplace/actions/usgs-earthquakes-action (404)

### 3) openfda-recalls-action (third)

- Repo: https://github.com/bennyj121/openfda-recalls-action
- Cleaned HEAD: `3489c9a80d5119d04151fa90b129f1569281462f`
- Listing: `drafts/MARKETPLACE-LISTING.md` on that HEAD
- Short description: `Fetch openFDA drug recalls, optional change-detect.`
- Branding: alert / red
- `v0.1.0` still peels pre-strip `7666cd04` — do **not** publish from it
- Expected unpublished slug overnight: https://github.com/marketplace/actions/openfda-recalls-action (404). Name-slug: `openfda-drug-recalls`

---

## Out (do not do on this card)

- Create tags / releases / Marketplace publish **overnight**
- Retag `v0.1.0`
- Edit live HPT cards: hospital-mrf-index, cms-hpt-validate, cms-hpt-validator
- Paid CTAs / Ko-fi / hospital MRF-change extract / extract-request
- Merge Muonarc/muonarc.com PR #1 / PATCH `muonarc.com` `main`
- Retry NCUA CSV (`drafts/ncua-title12-2026-08-30.csv` still 404; git/trees Auto-review blocked; HEAD `cab006ef`)
- Live Stripe / invented checkout URL / email / post / cold outreach
- r/datasets, DIP, OpenFEMA, NHC
- First live Note on muonarc.com (still waits on Benjamin)

**STOP holds.**
