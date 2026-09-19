# HITL DRAFT ONLY — notes branch

**Status:** human-in-the-loop draft for the notes branch. Live page updated separately. Do not treat this file as the published muonarc.com Note body.

**AI disclosure (Rogue):** An AI (Rogue + helper bots) drafted this Friday COT Pack. Benjamin / Atlas reviews before any Note goes live. Independently check any number you rely on. Not endorsed by the CFTC. Public CFTC data only. No PHI.

---

# Friday COT Pack — 12 liquid futures (CFTC public)

**As-of Tuesday 2026-09-15 · CFTC released Friday 2026-09-18 3:30pm ET · Legacy Futures-Only COT**

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
| As-of | Tuesday **2026-09-15** |
| Release | Friday **2026-09-18** (CFTC 3:30pm ET) |
| 1-week change | CFTC published week-over-week change columns (vs prior Tuesday 2026-09-08) |
| 4-week change | This week's net minus as-of **2026-08-18** net (four Tuesdays back) |
| 52-week percentile | Trailing **52** report as-of weeks **2025-09-23 through 2026-09-15** (last 52 available dates on or before this Tuesday; Veterans Day week uses Monday **2025-11-10** in place of Tuesday 2025-11-11). Percent of those weeks where net spec ≤ this week's net spec. 100 = highest net spec in the window. |
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

## One-pager: week of 2026-09-15

Headline: **yen specs surged to a 52-week high** after another huge weekly add (net long +120,359; +109,563 on the week; 100.0th %ile); **E-mini S&P specs sold further** (−100,461; −24,425 week); **nat-gas specs still at a 52-week short extreme** (−221,587; 1.9th %ile); euro specs covering while still short; corn and soy specs still near 52-week highs (soy trimmed); Nasdaq mini specs adding; wheat specs still net long but cut hard on the week.

### Net spec / commercial / non-reportable (contracts)

| Ticker | OI | Δ OI 1w | Net spec | Δ 1w | Δ 4w | 52w %ile | Net comm | Δ 1w | Δ 4w | Net n.rpt | Δ 1w | Δ 4w | Traders |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| CL | 1,955,764 | +15,853 | +135,905 | -674 | +13,815 | 67.3 | -164,858 | +1,327 | -11,771 | +28,953 | -653 | -2,044 | 326 |
| NG | 1,820,003 | -3,240 | -221,587 | -1,820 | -18,084 | 1.9 | +206,752 | +5,626 | +18,426 | +14,835 | -3,806 | -342 | 326 |
| GC | 409,899 | -1,328 | +230,338 | -1,622 | +8,149 | 80.8 | -261,721 | +8,553 | -3,303 | +31,383 | -6,931 | -4,846 | 296 |
| SI | 103,745 | +495 | +25,326 | -723 | +1,701 | 55.8 | -42,700 | +2,208 | +2,092 | +17,374 | -1,485 | -3,793 | 160 |
| ZC | 1,843,824 | +40,501 | +542,384 | -615 | +240,242 | 98.1 | -476,845 | -6,240 | -231,245 | -65,539 | +6,855 | -8,997 | 894 |
| ZS | 1,104,880 | +34,479 | +261,183 | -12,241 | +70,222 | 98.1 | -238,575 | +12,975 | -68,938 | -22,608 | -734 | -1,284 | 639 |
| ZW | 485,138 | +458 | +1,228 | -9,242 | +19,993 | 96.2 | -4,799 | +7,749 | -21,180 | +3,571 | +1,493 | +1,187 | 423 |
| ES | 2,446,519 | +374,683 | -100,461 | -24,425 | -89,901 | 63.5 | +9,191 | +59,208 | +122,744 | +91,270 | -34,783 | -32,843 | 442 |
| NQ | 325,784 | +30,633 | +33,718 | +12,823 | +44,134 | 76.9 | -48,858 | -7,840 | -36,511 | +15,140 | -4,983 | -7,623 | 293 |
| 6E | 920,035 | -22,429 | -26,993 | +15,623 | +32,095 | 15.4 | +210 | -6,520 | -23,845 | +26,783 | -9,103 | -8,250 | 318 |
| 6J | 542,802 | +43,167 | +120,359 | +109,563 | +173,252 | 100.0 | -124,674 | -110,633 | -185,748 | +4,315 | +1,070 | +12,496 | 154 |
| BTC | 20,773 | -310 | +2,468 | +944 | -268 | 76.9 | -2,657 | -596 | -209 | +189 | -348 | +477 | 111 |

52w %ile is **net spec only**. Δ 1w / Δ 4w on net columns are contract changes in that net (not percent).

### Category longs / shorts (this Tuesday)

| Ticker | NC long | NC short | NC spread | Comm long | Comm short | N.rpt long | N.rpt short |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| CL | 371,202 | 235,297 | 605,061 | 895,203 | 1,060,061 | 84,298 | 55,345 |
| NG | 307,535 | 529,122 | 860,743 | 595,192 | 388,440 | 56,533 | 41,698 |
| GC | 258,059 | 27,721 | 47,963 | 56,417 | 318,138 | 47,460 | 16,077 |
| SI | 35,395 | 10,069 | 11,437 | 31,827 | 74,527 | 25,086 | 7,712 |
| ZC | 673,517 | 131,133 | 345,358 | 697,538 | 1,174,383 | 127,411 | 192,950 |
| ZS | 356,583 | 95,400 | 213,575 | 484,749 | 723,324 | 49,973 | 72,581 |
| ZW | 126,842 | 125,614 | 154,655 | 166,996 | 171,795 | 36,645 | 33,074 |
| ES | 240,290 | 340,751 | 96,393 | 1,825,396 | 1,816,205 | 284,440 | 193,170 |
| NQ | 85,062 | 51,344 | 15,435 | 175,896 | 224,754 | 49,391 | 34,251 |
| 6E | 209,000 | 235,993 | 37,369 | 485,267 | 485,057 | 188,399 | 161,616 |
| 6J | 237,951 | 117,592 | 3,385 | 149,757 | 274,431 | 151,709 | 147,394 |
| BTC | 16,744 | 14,276 | 2,901 | 107 | 2,764 | 1,021 | 832 |

### Percent of open interest (this Tuesday)

| Ticker | NC L % | NC S % | Comm L % | Comm S % | N.rpt L % | N.rpt S % |
| --- | ---: | ---: | ---: | ---: | ---: | ---: |
| CL | 19.0 | 12.0 | 45.8 | 54.2 | 4.3 | 2.8 |
| NG | 16.9 | 29.1 | 32.7 | 21.3 | 3.1 | 2.3 |
| GC | 63.0 | 6.8 | 13.8 | 77.6 | 11.6 | 3.9 |
| SI | 34.1 | 9.7 | 30.7 | 71.8 | 24.2 | 7.4 |
| ZC | 36.5 | 7.1 | 37.8 | 63.7 | 6.9 | 10.5 |
| ZS | 32.3 | 8.6 | 43.9 | 65.5 | 4.5 | 6.6 |
| ZW | 26.1 | 25.9 | 34.4 | 35.4 | 7.6 | 6.8 |
| ES | 9.8 | 13.9 | 74.6 | 74.2 | 11.6 | 7.9 |
| NQ | 26.1 | 15.8 | 54.0 | 69.0 | 15.2 | 10.5 |
| 6E | 22.7 | 25.7 | 52.7 | 52.7 | 20.5 | 17.6 |
| 6J | 43.8 | 21.7 | 27.6 | 50.6 | 27.9 | 27.2 |
| BTC | 80.6 | 68.7 | 0.5 | 13.3 | 4.9 | 4.0 |

Spreading % of OI is omitted here; longs + shorts + spreading do not sum to 100 because spreading is counted on both sides of OI.

---

## Read-through (this Friday only; not advice)

- **6J (yen):** net spec **+120,359**, 52-week percentile **100.0**, +109,563 on the week / +173,252 four-week — largest absolute weekly net-spec move in the pack; commercials the other side (-124,674).
- **ES (E-mini S&P):** net spec **-100,461** (63.5th), -24,425 week / -89,901 four-week — specs sold further.
- **NG (nat gas):** net spec **-221,587** (1.9th percentile). Specs sold -1,820 on the week — still deepest short end of the 52-week window. Commercials net long +206,752.
- **ZC (corn):** net spec **+542,384**, 52-week percentile **98.1**, -615 week / +240,242 four-week — still near the top of the window after last week's surge.
- **ZS (soybeans):** net spec **+261,183** (98.1th), -12,241 week / +70,222 four-week — near highs but trimmed.
- **ZW (wheat-SRW):** net spec **+1,228** (96.2th) after -9,242 week — still net long, cut hard.
- **6E (euro):** specs still short (-26,993, 15.4th) but covering (+15,623 week).
- **NQ (Nasdaq mini):** specs adding to net long (+33,718, +12,823 week; 76.9th).
- **GC (gold):** net spec **+230,338** (80.8th), -1,622 week. Commercials remain heavily net short (-261,721).
- **CL / SI / BTC:** CL spec long modest (+135,905, 67.3th). SI mid-pack (55.8th). BTC small net long (+2,468); thin vs the rest of the pack (OI 20,773; 111 traders).

Not investment advice. Public positioning snapshot only.

---

## Sample 3-of-12 (**public CFTC / free Sample**)

Three strongest headline names this week (full pack is **12** rows in the paid CSV/one-pager): **6J**, **ES**, **NG**.

| Ticker | Why Sample | Net spec | Δ 1w | Δ 4w | 52w %ile | OI |
| --- | --- | ---: | ---: | ---: | ---: | ---: |
| 6J | Largest |Δ1w| and 100th %ile net-spec surge | +120,359 | +109,563 | +173,252 | 100.0 | 542,802 |
| ES | Second-largest |Δ1w|; specs sold further | -100,461 | -24,425 | -89,901 | 63.5 | 2,446,519 |
| NG | Still at 52-week short extreme (1.9th %ile) | -221,587 | -1,820 | -18,084 | 1.9 | 1,820,003 |

CSV-equivalent rows for the Sample (same columns as the full Friday CSV; labeled **public CFTC / free Sample**):

```csv
as_of,release,ticker,cftc_name,cftc_code,oi,d_oi_1w,nc_long,nc_short,nc_spread,comm_long,comm_short,nr_long,nr_short,net_spec,net_comm,net_nr,d_net_spec_1w,d_net_comm_1w,d_net_nr_1w,d_net_spec_4w,d_net_comm_4w,d_net_nr_4w,net_spec_52w_percentile,traders,source
2026-09-15,2026-09-18,6J,JAPANESE YEN - CHICAGO MERCANTILE EXCHANGE,097741,542802,43167,237951,117592,3385,149757,274431,151709,147394,120359,-124674,4315,109563,-110633,1070,173252,-185748,12496,100.0,154,https://www.cftc.gov/dea/newcot/deafut.txt
2026-09-15,2026-09-18,ES,E-MINI S&P 500 - CHICAGO MERCANTILE EXCHANGE,13874A,2446519,374683,240290,340751,96393,1825396,1816205,284440,193170,-100461,9191,91270,-24425,59208,-34783,-89901,122744,-32843,63.5,442,https://www.cftc.gov/dea/newcot/deafut.txt
2026-09-15,2026-09-18,NG,NAT GAS NYME - NEW YORK MERCANTILE EXCHANGE,023651,1820003,-3240,307535,529122,860743,595192,388440,56533,41698,-221587,206752,14835,-1820,5626,-3806,-18084,18426,-342,1.9,326,https://www.cftc.gov/dea/newcot/deafut.txt
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
