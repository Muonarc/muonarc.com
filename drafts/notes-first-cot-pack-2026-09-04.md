# HITL DRAFT ONLY — notes branch

**Status:** human-in-the-loop draft for the notes branch. Live page updated separately. Do not treat this file as the published muonarc.com Note body.

**AI disclosure (Rogue):** An AI (Rogue + helper bots) drafted this Friday COT Pack. Benjamin / Atlas reviews before any Note goes live. Independently check any number you rely on. Not endorsed by the CFTC. Public CFTC data only. No PHI.

---

# Friday COT Pack — 12 liquid futures (CFTC public)

**As-of Tuesday 2026-09-01 · CFTC released Friday 2026-09-04 3:30pm ET · Legacy Futures-Only COT**

## Pitch

Every Friday after the CFTC 3:30pm ET Commitments of Traders release, regenerate a one-pager template (net spec / commercial / non-reportable; 1-week and 4-week change; 52-week percentile) for a fixed 12-contract set (CL, NG, GC, SI, ZC, ZS, ZW, ES, NQ, 6E, 6J, BTC) from CFTC public COT files only. Filled template + CSV; same product next Friday. Not a one-off zip; not freelancer-tools.

## Price

**$18 one-time** (locked) / Friday pack.

## Checkout

https://buy.stripe.com/eVqfZi16bbHibem4l95AQ00

## Delivery format (Friday pack)

Markdown one-pager (this file) plus CSV of the 12-contract table. Same 12 names every Friday.

**What the buyer gets each Friday**

1. This one-pager: net spec / net commercial / net non-reportable, 1-week change, 4-week change, 52-week percentile of net spec, open interest, and category long/short.
2. A CSV with one row per contract and the same fields (for desks that paste into a workbook).
3. Named CFTC market + contract-market code so the row can be audited against the public file.
4. As-of Tuesday date and Friday release date on the header.

---

## How this week is built

| Item | Value |
| --- | --- |
| Report | CFTC Legacy **Futures-Only** Commitments of Traders (non-commercial / commercial / non-reportable). Not the Disaggregated (PMAN / swap / managed-money) file. |
| As-of | Tuesday **2026-09-01** |
| Release | Friday **2026-09-04** (CFTC 3:30pm ET) |
| 1-week change | CFTC published week-over-week change columns (vs prior Tuesday 2026-08-25) |
| 4-week change | This week's net minus as-of **2026-08-04** net (four Tuesdays back) |
| 52-week percentile | Trailing **52** report as-of weeks **2025-09-09 through 2026-09-01** (last 52 available dates on or before this Tuesday; Veterans Day week uses Monday **2025-11-10** in place of Tuesday 2025-11-11). Percent of those weeks where net spec ≤ this week's net spec. 100 = highest net spec in the window. |
| Sources (public, no login) | Current week: [deafut.txt](https://www.cftc.gov/dea/newcot/deafut.txt). History: [deacot2026.zip](https://www.cftc.gov/files/dea/history/deacot2026.zip), [deacot2025.zip](https://www.cftc.gov/files/dea/history/deacot2025.zip). Index: [Commitments of Traders](https://www.cftc.gov/MarketReports/CommitmentsofTraders/index.htm). |
| Units | Futures contracts (CFTC "All" columns). Spreading is reported separately and is **not** inside net spec. |

CFTC market names used for the 12 CME/NYMEX/COMEX/CBOT tickers (codes are stable; display names drift):

| Ticker | CFTC market name | Code |
| --- | --- | --- |
| CL | WTI-PHYSICAL - NEW YORK MERCANTILE EXCHANGE | 067651 |
| NG | NAT GAS NYME - NEW YORK MERCANTILE EXCHANGE | 023651 |
| GC | GOLD - COMMODITY EXCHANGE INC. | 088691 |
| SI | SILVER - COMMODITY EXCHANGE INC. | 084691 |
| ZC | CORN - CHICAGO BOARD OF TRADE | 002602 |
| ZS | SOYBEANS - CHICAGO BOARD OF TRADE | 005602 |
| ZW | WHEAT-SRW - CHICAGO BOARD OF TRADE | 001602 |
| ES | E-MINI S&P 500 - CHICAGO MERCANTILE EXCHANGE | 13874A |
| NQ | NASDAQ MINI - CHICAGO MERCANTILE EXCHANGE | 209742 |
| 6E | EURO FX - CHICAGO MERCANTILE EXCHANGE | 099741 |
| 6J | JAPANESE YEN - CHICAGO MERCANTILE EXCHANGE | 097741 |
| BTC | BITCOIN - CHICAGO MERCANTILE EXCHANGE | 133741 |

Not Micro Bitcoin, not Micro E-minis, not ICE WTI, not Henry Hub last-day financial.

**Definitions:** net spec = non-commercial long − short. Net commercial = commercial long − short. Net non-reportable = non-reportable long − short.

---

## One-pager: week of 2026-09-01

Headline: **corn specs still at a 52-week high** and adding; **wheat specs flipped net long** (also 100th %ile); **nat-gas specs at a 52-week short extreme** and selling further; **soybean specs near a 52-week high**; gold specs still heavy long but trimmed; yen specs sold; euro specs still short while covering.

### Net spec / commercial / non-reportable (contracts)

| Ticker | OI | Δ OI 1w | Net spec | Δ 1w | Δ 4w | 52w %ile | Net comm | Δ 1w | Δ 4w | Net n.rpt | Δ 1w | Δ 4w | Traders |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| CL | 1,921,085 | +14,345 | +129,911 | +6,462 | +17,468 | 67.3 | −156,005 | +241 | −2,230 | +26,094 | −6,703 | −15,238 | 297 |
| NG | 1,807,497 | +59,767 | −208,911 | −10,979 | −11,365 | 1.9 | +193,432 | +5,695 | +6,218 | +15,479 | +5,284 | +5,147 | 323 |
| GC | 415,196 | −12,761 | +228,124 | −15,210 | +30,490 | 78.8 | −264,718 | +14,867 | −38,227 | +36,594 | +343 | +7,737 | 305 |
| SI | 104,362 | −9,439 | +26,739 | +1,478 | +4,459 | 59.6 | −45,280 | −227 | −4,858 | +18,541 | −1,251 | +399 | 151 |
| ZC | 1,764,182 | +56,476 | +536,743 | +95,828 | +281,675 | 100.0 | −476,821 | −102,213 | −268,476 | −59,922 | +6,385 | −13,199 | 883 |
| ZS | 1,027,541 | +55,010 | +247,987 | +26,560 | +72,445 | 98.1 | −228,742 | −28,806 | −71,990 | −19,245 | +2,246 | −455 | 625 |
| ZW | 470,560 | +27,029 | +24,703 | +31,482 | +39,462 | 100.0 | −23,736 | −31,211 | −40,123 | −967 | −271 | +661 | 429 |
| ES | 2,046,914 | +1,245 | −75,941 | −7,947 | −48,683 | 76.9 | −34,113 | +29,952 | +50,263 | +110,054 | −22,005 | −1,580 | 431 |
| NQ | 300,140 | −1,847 | +25,890 | +15,851 | +40,529 | 69.2 | −45,420 | −8,284 | −60,862 | +19,530 | −7,567 | +20,333 | 296 |
| 6E | 865,412 | +46,888 | −24,925 | +11,427 | +33,166 | 13.5 | −8,727 | −9,167 | −40,189 | +33,652 | −2,260 | +7,023 | 320 |
| 6J | 411,882 | +27,666 | −92,227 | −28,929 | −46,754 | 28.8 | +97,561 | +29,724 | +46,993 | −5,334 | −795 | −239 | 161 |
| BTC | 19,697 | −2,519 | +703 | −1,246 | −3,049 | 42.3 | −1,077 | +713 | +2,255 | +374 | +533 | +794 | 116 |

52w %ile is **net spec only**. Δ 1w / Δ 4w on net columns are contract changes in that net (not percent).

### Category longs / shorts (this Tuesday)

| Ticker | NC long | NC short | NC spread | Comm long | Comm short | N.rpt long | N.rpt short |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| CL | 332,448 | 202,537 | 626,754 | 885,135 | 1,041,140 | 76,748 | 50,654 |
| NG | 301,642 | 510,553 | 872,521 | 576,496 | 383,064 | 56,838 | 41,359 |
| GC | 260,485 | 32,361 | 41,231 | 61,450 | 326,168 | 52,030 | 15,436 |
| SI | 35,403 | 8,664 | 11,078 | 31,424 | 76,704 | 26,457 | 7,916 |
| ZC | 665,299 | 128,556 | 330,311 | 637,619 | 1,114,440 | 130,953 | 190,875 |
| ZS | 337,469 | 89,482 | 196,079 | 443,809 | 672,551 | 50,184 | 69,429 |
| ZW | 146,391 | 121,688 | 143,324 | 146,489 | 170,225 | 34,356 | 35,323 |
| ES | 246,459 | 322,400 | 47,158 | 1,496,598 | 1,530,711 | 256,699 | 146,645 |
| NQ | 89,434 | 63,544 | 6,868 | 155,766 | 201,186 | 48,072 | 28,542 |
| 6E | 203,477 | 228,402 | 42,345 | 533,920 | 542,647 | 85,670 | 52,018 |
| 6J | 117,169 | 209,396 | 36,301 | 225,189 | 127,628 | 33,223 | 38,557 |
| BTC | 16,530 | 15,827 | 1,557 | 423 | 1,500 | 1,187 | 813 |

### Percent of open interest (this Tuesday)

| Ticker | NC L % | NC S % | Comm L % | Comm S % | N.rpt L % | N.rpt S % |
| --- | ---: | ---: | ---: | ---: | ---: | ---: |
| CL | 17.3 | 10.5 | 46.1 | 54.2 | 4.0 | 2.6 |
| NG | 16.7 | 28.2 | 31.9 | 21.2 | 3.1 | 2.3 |
| GC | 62.7 | 7.8 | 14.8 | 78.6 | 12.5 | 3.7 |
| SI | 33.9 | 8.3 | 30.1 | 73.5 | 25.4 | 7.6 |
| ZC | 37.7 | 7.3 | 36.1 | 63.2 | 7.4 | 10.8 |
| ZS | 32.8 | 8.7 | 43.2 | 65.5 | 4.9 | 6.8 |
| ZW | 31.1 | 25.9 | 31.1 | 36.2 | 7.3 | 7.5 |
| ES | 12.0 | 15.8 | 73.1 | 74.8 | 12.5 | 7.2 |
| NQ | 29.8 | 21.2 | 51.9 | 67.0 | 16.0 | 9.5 |
| 6E | 23.5 | 26.4 | 61.7 | 62.7 | 9.9 | 6.0 |
| 6J | 28.4 | 50.8 | 54.7 | 31.0 | 8.1 | 9.4 |
| BTC | 83.9 | 80.4 | 2.1 | 7.6 | 6.0 | 4.1 |

Spreading % of OI is omitted here; longs + shorts + spreading do not sum to 100 because spreading is counted on both sides of OI.

---

## Read-through (this Friday only; not advice)

- **ZC (corn):** net spec **+536,743**, 52-week percentile **100.0**, +95,828 on the week / +281,675 four-week. Commercials the other side (−102,213 net on the week).
- **ZW (wheat-SRW):** net spec **+24,703** (100.0th percentile) after +31,482 week — flipped from a small short last week. Commercials −23,736.
- **NG (nat gas):** net spec **−208,911** (1.9th percentile). Specs sold −10,979 on the week — deepest short end of the 52-week window. Commercials net long +193,432.
- **ZS (soybeans):** net spec **+247,987** (98.1th), +26,560 week / +72,445 four-week.
- **GC (gold):** net spec **+228,124** (78.8th percentile), −15,210 week / +30,490 four-week. Commercials remain heavily net short (−264,718).
- **6E / 6J:** euro specs still short (−24,925, 13.5th) but covering (+11,427 week). Yen specs sold to −92,227 (−28,929 week; 28.8th).
- **ES vs NQ:** ES specs still net short (−75,941, −7,947 week). NQ specs adding to net long (+25,890, +15,851 week; 69.2th).
- **BTC:** small net spec long (+703), trimmed (−1,246). Thin vs the rest of the pack (OI 19,697; 116 traders).
- **CL / SI:** CL spec long modest (+129,911, 67.3th) and a bit higher on the week. SI mid-upper pack (59.6th) and slightly adding.

Not investment advice. Public positioning snapshot only.

---

## Sample CSV schema (same 12 rows every Friday)

Columns the Friday CSV carries (this week's values are the tables above):

`as_of,release,ticker,cftc_name,cftc_code,oi,d_oi_1w,nc_long,nc_short,nc_spread,comm_long,comm_short,nr_long,nr_short,net_spec,net_comm,net_nr,d_net_spec_1w,d_net_comm_1w,d_net_nr_1w,d_net_spec_4w,d_net_comm_4w,d_net_nr_4w,net_spec_52w_percentile,traders,source`

Source field this week: `https://www.cftc.gov/dea/newcot/deafut.txt` plus the two annual history zips for the 4-week and 52-week columns.

---

## What this is / is not

- **Is:** a retainable Friday one-pager + CSV from **public CFTC COT** for a **fixed 12-contract** set.
- **Is not:** hospital MRF, hospital-price-series paid SKU, OpenFEMA, NHC, USAspending, NCUA, GitHub Marketplace Action, or Ko-fi storefront.
- **Is not:** Disaggregated managed-money / producer-merchant tables. Those are a different CFTC file; this SKU is Legacy net spec / commercial / non-reportable.

---

*HITL draft for notes branch; live page updated separately. AI-prepared (Rogue + helper bots); Benjamin/Atlas review required before any muonarc.com Note goes live. Public CFTC data only. No PHI.*
