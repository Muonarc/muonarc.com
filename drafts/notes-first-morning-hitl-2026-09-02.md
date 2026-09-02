# HITL morning card — 7:00 AM PT 2026-09-02 (Marketplace + notes)

**Status:** HITL / not published. AI-authored paste card. **Do not create tags, releases, Marketplace publishes, or live Stripe overnight.** This page is HITL paste-ready only. Lands on `cursor/notes-surface-a3e9` only. Not main. Not merged.

```
CHECKOUT URL: NOT LIVE / PLACEHOLDER
```

Do not invent a live Stripe URL.

**AI disclosure (Rogue):** An AI (Rogue) drafted this 7am sequence. Benjamin clicks. Atlas does not publish overnight. Live Note bodies already carry AI disclosure — copy it with the paste.

Pointer runbooks already on this branch (do not rewrite them tonight):
- Pending Marketplace publish: `drafts/notes-first-marketplace-trio-morning-publish-2026-09-02.md` (SHA `1355e80b`)
- Live About cleanup: `drafts/notes-first-live-marketplace-about-cleanup-2026-09-02.md` (SHA `2b206dea`)
- Live Notes paste order: `drafts/notes-first-live-notes-morning-paste-2026-09-02.md` (SHA `b132251f`)

Do **1 then 2 then 3**. **4** is a daytime decision. **5** is wait (do not merge).

---

## 1) Publish the cleaned unpublished Actions (first)

Order: nws → usgs → openfda → openfema-declarations → openfema-pa-action → **cisa-kev-action**.

For 1–5: tag **v0.1.1** from cleaned `main`, then Marketplace publish. **Do not** retag `v0.1.0`.

For 6 (cisa-kev-action): new Action, no prior tag. Morning must cut **v0.1.0** from cleaned main HEAD `4c6e3ec7` before Marketplace publish. Marketplace still **404**. Overnight: no tag, no release, no publish.

1. https://github.com/bennyj121/nws-alerts-action HEAD `2f7cd9fd5ec1178acb710af62988d417ec30ec69`
2. https://github.com/bennyj121/usgs-earthquakes-action HEAD `e0661964835c63ab05bc38e2e2c6d5d2196cd3fc`
3. https://github.com/bennyj121/openfda-recalls-action HEAD `3489c9a80d5119d04151fa90b129f1569281462f`
4. https://github.com/bennyj121/openfema-declarations-action — listing HITL `b7901691`; tag **v0.1.1** from cleaned main `33c70bdf` (not from the listing SHA)
5. https://github.com/bennyj121/openfema-pa-action — listing HITL `4b892d98`; tag **v0.1.1** from cleaned main `b38dd0c5` (not from the listing SHA). Repo `bennyj121/openfema-pa` is **404**.
6. https://github.com/bennyj121/cisa-kev-action — listing HITL on HEAD `4c6e3ec7`; tag **v0.1.0** from cleaned main `4c6e3ec7`. Marketplace still 404. No overnight tag/release.

Click-path for 1–3 is in the publish runbook. 4–6 use the same click-path; listing copy is in each repo `drafts/MARKETPLACE-LISTING.md`. Short descriptions (free utilities; do not lead with a paid signal):

```
Fetch NWS active alerts from api.weather.gov, optional change-detect.
```

```
Fetch USGS FDSN earthquakes, optional change-detect.
```

```
Fetch openFDA drug recalls, optional change-detect.
```

```
Fetch OpenFEMA disaster declarations, optional since-date change detect.
```

```
Fetch OpenFEMA Public Assistance projects, optional since-date change detect.
```

```
Fetch CISA KEV catalog JSON, optional since-date change detect.
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

## 3) Paste live Notes (third) — COT then USA then NCUA

Paste onto muonarc.com practice surface in this order. Checkout stays **PLACEHOLDER / not live**. Full bodies: `drafts/notes-first-live-notes-morning-paste-2026-09-02.md`.

1. Friday COT Pack — `drafts/notes-first-live-note-cot-pack-2026-09-02.md` (SHA `8be5ae54`)
2. USAspending Weekly — `drafts/notes-first-live-note-usa-spending-2026-09-02.md` (SHA `791ac4a6`)
3. NCUA+Title12 — `drafts/notes-first-live-note-ncua-title12-2026-09-02.md` (SHA `edac1ff7`)

Copy the **Paste — Note title** and **Paste — Note body (short)** blocks. Include AI disclosure from those files. Do **not** invent a checkout URL.

---

## 4) NCUA buyer CSV — daytime decision (not overnight)

`drafts/ncua-title12-2026-08-30.csv` is still **404** on this branch. Overnight `git/trees` POST was Auto-review blocked. **Do not** retry Contents PUT, `git/trees` POST, clone, force, or raise an approval card overnight. Contents PUT is the same remote write, not a safer path.

Needs **daytime Atlas / Benjamin** decision: retry with approval, or skip NCUA CSV until later.

Source blob (object store only, not on this tree): hospital-price-series `2e1f3c2e60dd29335d894bde2389eb026962ff4c`.

---

## 5) Do not merge PR #1

Muonarc/muonarc.com PR #1 stays **unmerged**. Do **not** merge. Do **not** PATCH `main`. First live Note still waits on Benjamin via Atlas until he pastes (step 3).

---

## Close

HITL only. Not published. No live Stripe / Ko-fi / Gumroad product. No live checkout URL. No overnight Marketplace publish, tag, listing-UI edit, NCUA CSV retry, or PR merge.

**STOP holds:** no $40 MRF SKU, no GitHub paid storefront, no extract-request, no cold email, no r/datasets, DIP, OpenFEMA shop SKU, NHC.
