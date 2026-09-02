# Marketplace morning publish — 7:00 AM PT HITL card (not live)

**When:** 7:00 AM PT paste for Benjamin. One card. Sequence only. Do not hunt SHAs.

**Status:** HITL paste-ready. AI-drafted. Overnight: do **not** create tags, do **not** create releases, do **not** publish Marketplace. Lands on `cursor/notes-surface-a3e9` only. Not main. Not merged.

**What this is:** Morning publish runbook for the **cleaned unpublished Actions**. Queue matches the 7am card: nws → usgs → openfda → openfema-declarations → openfema-pa-action → **cisa-kev-action**. Free utilities / Continuous integration. **No paid SKU. No Ko-fi. No hospital MRF-change extract. No $40 CTAs. No OpenFEMA shop SKU.**

**What this is not:** hospital-mrf-index, cms-hpt-validate, cms-hpt-validator (live HPT cards stay as-is; leftover $40 About text is a **separate** morning HITL). Not NCUA CSV. Not muonarc.com Notes publish. Not Stripe. Not email. Not a post.

**AI disclosure (Rogue):** An AI (Rogue) prepared this 7am sequence. Benjamin clicks. Atlas does not publish overnight.

---

## Benjamin must click (this order)

Do **1 → 2 → 3 → 4 → 5 → 6**. Finish each Action (tag + Marketplace) before the next repo. Do **not** skip the new tag.

For **each** of the six repos below:

1. Open the repo URL.
2. Confirm `main` is still the cleaned HEAD named here (or a later commit that keeps the CTA strip / this scaffold). If `main` rewound to a pre-strip SHA, **stop that repo** and ping Atlas.
3. **Releases → Draft a new release.**
4. Create the **new** tag named for that repo targeting the **cleaned `main` SHA named here**. Repos 1–5: **`v0.1.1`**. Repo 6 (cisa-kev-action): **`v0.1.0`** (first tag; there is no prior tag). **Do not** move or retag existing `v0.1.0` on repos 1–5 (those still peel pre-strip paid CTAs).
5. Release title matches the tag. Body: one line — free GitHub Action; built by Rogue (AI); not an official NWS/USGS/FDA/FEMA/CISA product.
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

### 4) openfema-declarations-action (fourth)

- Repo: https://github.com/bennyj121/openfema-declarations-action
- **Tag `v0.1.1` from cleaned main `33c70bdf`** (CTA strip). Do **not** tag from listing HITL `b7901691`.
- Listing HITL: `b7901691` — `drafts/MARKETPLACE-LISTING.md` (morning-must: tag 33c70bdf before publish)
- Short description: `Fetch OpenFEMA disaster declarations, optional since-date change detect.`
- Branding: cloud / blue
- `v0.1.0` still peels pre-strip `40b4b3e6` — do **not** publish from it
- Expected unpublished slug overnight: https://github.com/marketplace/actions/openfema-declarations-action (404). Name-slug: `openfema-disaster-declarations`

### 5) openfema-pa-action (fifth)

- Repo: https://github.com/bennyj121/openfema-pa-action — use this name. **`bennyj121/openfema-pa` is 404.**
- **Tag `v0.1.1` from cleaned main `b38dd0c5`** (CTA strip). Do **not** tag from listing HITL `4b892d98`.
- Listing HITL: `4b892d98` — `drafts/MARKETPLACE-LISTING.md` (morning-must: tag b38dd0c5 before publish)
- Short description: `Fetch OpenFEMA Public Assistance projects, optional since-date change detect.`
- Branding: cloud / blue
- `v0.1.0` still peels pre-strip `d9864291` — do **not** publish from it
- Expected unpublished slug overnight: https://github.com/marketplace/actions/openfema-pa-action (404). Name-slug: `openfema-public-assistance-projects`
- Do **not** dump the full ~848k-row file from CI. Live cap stays.

### 6) cisa-kev-action (sixth)

- Repo: https://github.com/bennyj121/cisa-kev-action
- **Tag `v0.1.0` from cleaned main `4c6e3ec7`** (scaffold HEAD). First tag — there is no prior tag to retag.
- Listing: `drafts/MARKETPLACE-LISTING.md` on `4c6e3ec7` (morning-must: tag v0.1.0 from 4c6e3ec7 before publish)
- Short description: `Fetch CISA KEV catalog JSON, optional since-date change detect.`
- Branding: shield / red
- Marketplace still **404** overnight. Overnight: no tag, no release, no publish.
- Expected unpublished slug overnight: https://github.com/marketplace/actions/cisa-kev-action (404). Name-slug: `cisa-known-exploited-vulnerabilities`

---

## Out (do not do on this card)

- Create tags / releases / Marketplace publish **overnight**
- Retag existing `v0.1.0` on repos 1–5
- Edit live HPT cards: hospital-mrf-index, cms-hpt-validate, cms-hpt-validator
- Paid CTAs / Ko-fi / hospital MRF-change extract / extract-request / OpenFEMA shop SKU revival
- Merge Muonarc/muonarc.com PR #1 / PATCH `muonarc.com` `main`
- Retry NCUA CSV (`drafts/ncua-title12-2026-08-30.csv` still 404; git/trees Auto-review blocked)
- Live Stripe / invented checkout URL / email / post / cold outreach
- r/datasets, DIP, OpenFEMA shop, NHC
- First live Note on muonarc.com (still waits on Benjamin)

**STOP holds.**
