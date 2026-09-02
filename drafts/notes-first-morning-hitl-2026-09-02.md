# HITL morning card — 7:00 AM PT 2026-09-02 (Marketplace + notes)

**Status:** HITL / not published. AI-authored paste card. **Do not create tags, releases, Marketplace publishes, or live Stripe overnight.** This page is HITL paste-ready only. Lands on `cursor/notes-surface-a3e9` only. Not main. Not merged.

```
CHECKOUT URL: NOT LIVE / PLACEHOLDER
```

**AI disclosure (Rogue):** An AI (Rogue) drafted this 7am sequence. Benjamin clicks. Atlas does not publish overnight.

Pointer runbooks already on this branch (do not rewrite them tonight):
- Pending trio publish: `drafts/notes-first-marketplace-trio-morning-publish-2026-09-02.md` (SHA `2dff3266`)
- Live About cleanup: `drafts/notes-first-live-marketplace-about-cleanup-2026-09-02.md` (SHA `2b206dea`)

Do **1 then 2**. **3** and **4** are decisions, not overnight writes.

---

## 1) Publish the cleaned unpublished trio (first)

Tag **v0.1.1** from cleaned `main`, then Marketplace publish. **Do not** retag `v0.1.0`. Order:

1. https://github.com/bennyj121/nws-alerts-action HEAD `2f7cd9fd5ec1178acb710af62988d417ec30ec69`
2. https://github.com/bennyj121/usgs-earthquakes-action HEAD `e0661964835c63ab05bc38e2e2c6d5d2196cd3fc`
3. https://github.com/bennyj121/openfda-recalls-action HEAD `3489c9a80d5119d04151fa90b129f1569281462f`

Click-path is in the trio runbook. Short descriptions (free utilities; do not lead with a paid signal):

```
Fetch NWS active alerts from api.weather.gov, optional change-detect.
```

```
Fetch USGS FDSN earthquakes, optional change-detect.
```

```
Fetch openFDA drug recalls, optional change-detect.
```

If GitHub shows the Marketplace Developer Agreement, **Benjamin accepts**. Overnight Rogue does not accept or pay a publisher fee.

---

## 2) Edit About on the three LIVE cards (second)

Edit listing **text only**. **Do not** retag `v0.1.6` or `v0.1.0`. **Do not** Draft a new release. Click-path and paste copy are in the About-cleanup runbook.

1. https://github.com/marketplace/actions/hospital-mrf-index (source hospital-price-series HEAD `0e91d02c`) — do not retag `v0.1.6`
2. https://github.com/marketplace/actions/cms-hpt-validate (HEAD `06125aa0`) — do not retag `v0.1.0`
3. https://github.com/marketplace/actions/cms-hpt-validator (source hpt-validator-action HEAD `007270db`) — live slug is **cms-hpt-validator**, not hpt-validator-action (404). Do not retag `v0.1.0`

Strip leftover `$40` / Ko-fi / extract-request from About. Keep free utilities.

---

## 3) NCUA buyer CSV — daytime decision (not overnight)

`drafts/ncua-title12-2026-08-30.csv` is still **404** on this branch. Overnight `git/trees` POST was Auto-review blocked. **Do not** retry Contents PUT, `git/trees` POST, clone, force, or raise an approval card overnight. Contents PUT is the same remote write, not a safer path.

Needs **daytime Atlas / Benjamin** decision: retry with approval, or skip NCUA CSV until later. HEAD of this branch after tonight’s notes lands is **not** that CSV.

Source blob (object store only, not on this tree): hospital-price-series `2e1f3c2e60dd29335d894bde2389eb026962ff4c`.

---

## 4) First live Note still waits on Benjamin

Muonarc/muonarc.com PR #1 stays **unmerged**. Do **not** merge. Do **not** PATCH `main`. First live Note on muonarc.com still waits on Benjamin via Atlas. Do not invent a live checkout URL.

---

## Close

HITL only. Not published. No live Stripe / Ko-fi / Gumroad product. No live checkout URL. No overnight Marketplace publish, tag, listing-UI edit, NCUA CSV retry, or PR merge.

**STOP holds:** no $40 MRF SKU, no GitHub paid storefront, no extract-request, no cold email, no r/datasets, DIP, OpenFEMA, NHC.
