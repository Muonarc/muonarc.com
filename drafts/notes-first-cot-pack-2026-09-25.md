# HITL DRAFT ONLY — notes branch

**Status:** human-in-the-loop draft for the notes branch. Live page updated separately. Do not treat this file as the published muonarc.com Note body.

**AI disclosure (Rogue):** An AI (Rogue + helper bots) drafted this Friday COT Pack. Benjamin / Atlas reviews before any Note goes live. Independently check any number you rely on. Not endorsed by the CFTC. Public CFTC data only. No PHI.

---

# Friday COT Pack — 12 liquid futures (CFTC public)

**As-of Tuesday 2026-09-22 · CFTC released Friday 2026-09-25 3:30pm ET · Legacy Futures-Only COT**

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
| As-of | Tuesday **2026-09-22** |
| Release | Friday **2026-09-25** (CFTC 3:30pm ET) |
| 1-week change | CFTC published week-over-week change columns (vs prior Tuesday 2026-09-15) |
| 4-week change | This week's net minus as-of **2026-08-25** net (four Tuesdays back) |
| 52-week percentile | Trailing **52** report as-of weeks **2025-09-30 through 2026-09-22** (last 52 available dates on or before this Tuesday; Veterans Day week uses Monday **2025-11-10** in place of Tuesday 2025-11-11). Percent of those weeks where net spec ≤ this week's net spec. 100 = highest net spec in the window. |
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

## One-pager: week of 2026-09-22

Headline: **soybean specs at a new 52-week high** (net long +281,581; +20,398 on the week; 100.0th %ile); **yen specs cut from last week's 52-week high** (+71,982; −48,377 on the week; 98.1th %ile); **E-mini S&P specs sold further** (−133,228; −32,767 week); **nat-gas specs still near the 52-week short extreme** (−216,530; 5.8th %ile) though covering on the week; euro specs sold deeper while short; corn specs still near 52-week highs (trimmed); Nasdaq mini specs adding; wheat specs flipped net short.

### Net spec / commercial / non-reportable (contracts)

| Ticker | OI | Δ OI 1w | Net spec | Δ 1w | Δ 4w | 52w %ile | Net comm | Δ 1w | Δ 4w | Net n.rpt | Δ 1w | Δ 4w | Traders |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| CL | 1,841,811 | -113,953 | +141,106 | +5,201 | +17,657 | 69.2 | -169,889 | -5,031 | -13,643 | +28,783 | -170 | -4,014 | 312 |
| NG | 1,837,146 | +17,143 | -216,530 | +5,057 | -18,598 | 5.8 | +203,524 | -3,228 | +15,787 | +13,006 | -1,829 | +2,811 | 327 |
| GC | 412,800 | +2,901 | +225,853 | -4,485 | -17,481 | 76.9 | -262,903 | -1,182 | +16,682 | +37,050 | +5,667 | +799 | 293 |
| SI | 106,474 | +2,729 | +25,444 | +118 | +183 | 57.7 | -44,754 | -2,054 | +299 | +19,310 | +1,936 | -482 | 157 |
| ZC | 1,854,505 | +10,681 | +535,801 | -6,583 | +94,886 | 94.2 | -474,811 | +2,034 | -100,203 | -60,990 | +4,549 | +5,317 | 886 |
| ZS | 1,114,328 | +9,448 | +281,581 | +20,398 | +60,154 | 100.0 | -257,544 | -18,969 | -57,608 | -24,037 | -1,429 | -2,546 | 644 |
| ZW | 483,279 | -1,859 | -7,360 | -8,588 | -581 | 84.6 | +2,978 | +7,777 | -4,497 | +4,382 | +811 | +5,078 | 415 |
| ES | 1,890,653 | -555,866 | -133,228 | -32,767 | -65,234 | 44.2 | +28,880 | +19,689 | +92,945 | +104,348 | +13,078 | -27,711 | 419 |
| NQ | 286,321 | -39,463 | +56,150 | +22,432 | +46,111 | 98.1 | -65,763 | -16,905 | -28,627 | +9,613 | -5,527 | -17,484 | 285 |
| 6E | 821,689 | -98,346 | -52,334 | -25,341 | -15,982 | 9.6 | +28,967 | +28,757 | +28,527 | +23,367 | -3,416 | -12,545 | 327 |
| 6J | 378,701 | -164,101 | +71,982 | -48,377 | +135,280 | 98.1 | -76,414 | +48,260 | -144,251 | +4,432 | +117 | +8,971 | 155 |
| BTC | 22,315 | +1,542 | +2,756 | +288 | +807 | 80.8 | -3,109 | -452 | -1,319 | +353 | +164 | +512 | 119 |

52w %ile is **net spec only**. Δ 1w / Δ 4w on net columns are contract changes in that net (not percent).

### Category longs / shorts (this Tuesday)

| Ticker | NC long | NC short | NC spread | Comm long | Comm short | N.rpt long | N.rpt short |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| CL | 360,810 | 219,704 | 557,266 | 847,389 | 1,017,278 | 76,346 | 47,563 |
| NG | 306,362 | 522,892 | 868,575 | 605,834 | 402,310 | 56,375 | 43,369 |
| GC | 253,982 | 28,129 | 48,923 | 57,458 | 320,361 | 52,437 | 15,387 |
| SI | 34,701 | 9,257 | 12,867 | 31,176 | 75,930 | 27,730 | 8,420 |
| ZC | 665,291 | 129,490 | 368,351 | 689,974 | 1,164,785 | 130,889 | 191,879 |
| ZS | 370,525 | 88,944 | 210,739 | 482,883 | 740,427 | 50,181 | 74,218 |
| ZW | 120,127 | 127,487 | 153,347 | 173,065 | 170,087 | 36,740 | 32,358 |
| ES | 218,043 | 351,271 | 34,061 | 1,388,362 | 1,359,482 | 250,187 | 145,839 |
| NQ | 88,507 | 32,357 | 4,624 | 152,580 | 218,343 | 40,610 | 30,997 |
| 6E | 220,708 | 273,042 | 31,289 | 489,579 | 460,612 | 80,113 | 56,746 |
| 6J | 192,274 | 120,292 | 4,376 | 143,954 | 220,368 | 38,097 | 33,665 |
| BTC | 17,658 | 14,902 | 3,307 | 66 | 3,175 | 1,284 | 931 |

### Percent of open interest (this Tuesday)

| Ticker | NC L % | NC S % | Comm L % | Comm S % | N.rpt L % | N.rpt S % |
| --- | ---: | ---: | ---: | ---: | ---: | ---: |
| CL | 19.6 | 11.9 | 46.0 | 55.2 | 4.1 | 2.6 |
| NG | 16.7 | 28.5 | 33.0 | 21.9 | 3.1 | 2.4 |
| GC | 61.5 | 6.8 | 13.9 | 77.6 | 12.7 | 3.7 |
| SI | 32.6 | 8.7 | 29.3 | 71.3 | 26.0 | 7.9 |
| ZC | 35.9 | 7.0 | 37.2 | 62.8 | 7.1 | 10.3 |
| ZS | 33.3 | 8.0 | 43.3 | 66.4 | 4.5 | 6.7 |
| ZW | 24.9 | 26.4 | 35.8 | 35.2 | 7.6 | 6.7 |
| ES | 11.5 | 18.6 | 73.4 | 71.9 | 13.2 | 7.7 |
| NQ | 30.9 | 11.3 | 53.3 | 76.3 | 14.2 | 10.8 |
| 6E | 26.9 | 33.2 | 59.6 | 56.1 | 9.7 | 6.9 |
| 6J | 50.8 | 31.8 | 38.0 | 58.2 | 10.1 | 8.9 |
| BTC | 79.1 | 66.8 | 0.3 | 14.2 | 5.8 | 4.2 |

Spreading % of OI is omitted here; longs + shorts + spreading do not sum to 100 because spreading is counted on both sides of OI.

---

## Read-through (this Friday only; not advice)

- **6J (yen):** net spec **+71,982**, 52-week percentile **98.1**, -48,377 on the week / +135,280 four-week — largest absolute weekly net-spec move in the pack; specs cut from last week's 52-week high (+120,359); commercials the other side (-76,414).
- **ES (E-mini S&P):** net spec **-133,228** (44.2th), -32,767 week / -65,234 four-week — specs sold further.
- **NG (nat gas):** net spec **-216,530** (5.8th percentile). Specs covered +5,057 on the week — still near the deepest short end of the 52-week window. Commercials net long +203,524.
- **ZC (corn):** net spec **+535,801**, 52-week percentile **94.2**, -6,583 week / +94,886 four-week — still near the top of the window, trimmed.
- **ZS (soybeans):** net spec **+281,581** (100.0th), +20,398 week / +60,154 four-week — new 52-week high (prior window high +273,424 as-of 2026-09-08).
- **ZW (wheat-SRW):** net spec **-7,360** (84.6th) after -8,588 week — flipped net short.
- **6E (euro):** specs still short and sold deeper (-52,334, 9.6th; -25,341 week).
- **NQ (Nasdaq mini):** specs adding to net long (+56,150, +22,432 week; 98.1th).
- **GC (gold):** net spec **+225,853** (76.9th), -4,485 week. Commercials remain heavily net short (-262,903).
- **CL / SI / BTC:** CL spec long modest (+141,106, 69.2th). SI mid-pack (57.7th). BTC small net long (+2,756); thin vs the rest of the pack (OI 22,315; 119 traders).

Not investment advice. Public positioning snapshot only.

---

## Sample 3-of-12 (**public CFTC / free Sample**)

Sample names this week (full pack is **12** rows in the paid CSV/one-pager): **6J**, **ES**, **NG**. Paid-pack highlight not in the Sample: **ZS** at a new 52-week high (+281,581; +20,398 week; 100.0th %ile).

| Ticker | Why Sample | Net spec | Δ 1w | Δ 4w | 52w %ile | OI |
| --- | --- | ---: | ---: | ---: | ---: | ---: |
| 6J | Largest |Δ1w|; cut from last week's 52-week high | +71,982 | -48,377 | +135,280 | 98.1 | 378,701 |
| ES | Second-largest |Δ1w|; specs sold further | -133,228 | -32,767 | -65,234 | 44.2 | 1,890,653 |
| NG | Still near 52-week short extreme (5.8th %ile) | -216,530 | +5,057 | -18,598 | 5.8 | 1,837,146 |

CSV-equivalent rows for the Sample (same columns as the full Friday CSV; labeled **public CFTC / free Sample**):

```csv
as_of,release,ticker,cftc_name,cftc_code,oi,d_oi_1w,nc_long,nc_short,nc_spread,comm_long,comm_short,nr_long,nr_short,net_spec,net_comm,net_nr,d_net_spec_1w,d_net_comm_1w,d_net_nr_1w,d_net_spec_4w,d_net_comm_4w,d_net_nr_4w,net_spec_52w_percentile,traders,source
2026-09-22,2026-09-25,6J,JAPANESE YEN - CHICAGO MERCANTILE EXCHANGE,097741,378701,-164101,192274,120292,4376,143954,220368,38097,33665,71982,-76414,4432,-48377,48260,117,135280,-144251,8971,98.1,155,https://www.cftc.gov/dea/newcot/deafut.txt
2026-09-22,2026-09-25,ES,E-MINI S&P 500 - CHICAGO MERCANTILE EXCHANGE,13874A,1890653,-555866,218043,351271,34061,1388362,1359482,250187,145839,-133228,28880,104348,-32767,19689,13078,-65234,92945,-27711,44.2,419,https://www.cftc.gov/dea/newcot/deafut.txt
2026-09-22,2026-09-25,NG,NAT GAS NYME - NEW YORK MERCANTILE EXCHANGE,023651,1837146,17143,306362,522892,868575,605834,402310,56375,43369,-216530,203524,13006,5057,-3228,-1829,-18598,15787,2811,5.8,327,https://www.cftc.gov/dea/newcot/deafut.txt
```

Full Friday pack = all 12 tickers (CL, NG, GC, SI, ZC, ZS, ZW, ES, NQ, 6E, 6J, BTC).

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
