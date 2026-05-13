# Sources — Gooaye US Market Watch EP661 Baseline

Run: 2026-05-13 11:20 PDT  
Scope: US-tradable only  
Source collection timestamp: 2026-05-13 ~11:00-11:20 PDT

## Local Gooaye inputs

- EP661 structured notes: `/Users/weiting/.openclaw/workspace/gooaye-investment-notes/ep-661/structured-notes.md`
- EP661 tracking: `/Users/weiting/.openclaw/workspace/gooaye-investment-notes/ep-661/tracking.md`
- Previous state: `/Users/weiting/.openclaw/workspace/investment-research-reports/gooaye-market-watch/state/current-state.md`
- Plan: `/Users/weiting/.openclaw/workspace/investment-research-reports/gooaye-market-watch/PLAN.md`

## Market data snapshot

Fetched locally via Stooq CSV endpoint on 2026-05-13 ~11:12 PDT. Stooq quote timestamps are as returned by the endpoint.

Endpoint pattern: `https://stooq.com/q/l/?s=<symbol>&f=sd2t2ohlcv&h&e=csv`

| Symbol | Date | Time | Open | High | Low | Close | Volume |
|---|---:|---:|---:|---:|---:|---:|---:|
| TXN.US | 2026-05-13 | 19:46:42 | 302.74 | 309.32 | 301.92 | 308.725 | 2,628,438 |
| NXPI.US | 2026-05-13 | 19:46:17 | 300.02 | 302.41 | 293.24 | 299.415 | 910,037 |
| QCOM.US | 2026-05-13 | 19:46:41 | 216.625 | 219.49 | 207.15 | 216.83 | 10,964,100 |
| TSM.US | 2026-05-13 | 19:46:42 | 398.265 | 404.6799 | 391.47 | 404.0127 | 5,977,372 |
| MRAAY.US | 2026-05-12 | 21:59:00 | 19.21 | 19.28 | 18.95 | 19.25 | 39,966 |
| MRAAF.US | 2026-05-11 | 22:00:00 | 39.33 | 39.40 | 36.26 | 39.0719 | 3,200 |
| ROHCY.US | 2026-05-11 | 22:00:00 | 25.00 | 25.39 | 25.00 | 25.39 | 1,050 |

No usable current Stooq quote found for checked possible Nichicon / Nippon Chemi-Con OTC strings: `NCICY.US`, `NIPCF.US`, `NCCCF.US`, `NHCGY.US`.

## Company and primary-source links

### Texas Instruments / TXN

- TI Q1 2026 earnings release, 2026-04-21: https://investor.ti.com/news-releases/news-release-details/ti-reports-first-quarter-2026-financial-results-and-shareholder
  - Used for Q1 revenue +19% YoY, analog +22%, embedded +12%, management commentary on industrial/data-center-led growth, and inventory/capital-return context.
- TI investor relations home: https://investor.ti.com/

### NXP Semiconductors / NXPI

- NXP Q1 2026 earnings release, 2026-04-27: https://www.nxp.com/company/investor-relations/quarterly-results/nxp-semiconductors-reports-first-quarter-2026-results:NW-NXP-Q1-2026-RESULTS
  - Used for Q1 revenue +12% YoY, automotive/industrial/mobile/communication infrastructure segment growth, gross margin, channel inventory, and Q2 guide.
- NXP IR quarterly results page: https://www.nxp.com/company/investor-relations/quarterly-results:QUARTERLY-RESULTS

### VSMC / Vanguard International Semiconductor / NXP JV

- Vanguard / VIS release, 2024-06-05, announcing VIS-NXP Singapore 300mm JV: https://www.vis.com.tw/en/newsroom/news/vis-and-nxp-announce-plan-to-create-manufacturing-joint-venture-to-build-and-operate-300mm-semiconductor-wafer-fab-in-singapore/
  - Used for process range 130nm-40nm, mixed-signal/power management/analog focus, 2027 initial production, 2029 target 55,000 300mm wafers/month, and investment scale.
- NXP release, 2024-06-05, VIS and NXP announce VSMC JV: https://www.nxp.com/company/about-nxp/vis-and-nxp-announce-plan-to-create-manufacturing-joint-venture-to-build-and-operate-300-mm-semiconductor-wafer-fab-in-singapore:NW-NXP-VIS-300MM-SEMICONDUCTOR-FAB

### Taiwan Semiconductor Manufacturing Company / TSM

- TSMC April 2026 revenue report, 2026-05-08: https://investor.tsmc.com/english/monthly-revenue/2026
  - Used for April 2026 revenue NT$410.7B, +17.5% YoY; Jan-Apr revenue +29.9% YoY.
- TSMC Investor Relations: https://investor.tsmc.com/english

### Murata / MRAAY / MRAAF

- Murata IR news, FY2025 fourth-quarter consolidated results and FY2026 guidance, 2026-04-28: https://corporate.murata.com/en-us/ir/news
- Murata FY2025 fourth-quarter results PDF, official IR library link from Murata search result: `https://corporate.murata.com/-/media/corporate/ir/library/results/2025/2025_4q_e.ashx`
  - Used for FY2025 sales/profit baseline and FY2026 capacitor growth commentary.
- Murata IR / financial highlights: https://corporate.murata.com/en-us/ir/financial/highlight

### ROHM / ROHCY

- ROHM IR home / financial information: https://www.rohm.com/ir/financial-info
- ROHM results presentation page: https://www.rohm.com/ir/library/presentation
- Cross-check secondary report on FY2025 loss and impairment: https://www.tradingview.com/news/reuters.com,2026:newsml_L4N3S11PM:0-rohm-plans-to-halve-chip-investment-after-posting-largest-ever-net-loss/
  - Used only as a current-news cross-check for the cautionary Rohm stance; official ROHM results page should be rechecked directly in next run if access improves.

### Qualcomm / QCOM

- Qualcomm FY2026 Q2 results page/search result, release dated 2026-04-29: https://www.qualcomm.com/company/investor-relations/financial-results
- Qualcomm capital return increase, 2026-03-05: https://www.qualcomm.com/news/releases/2026/03/qualcomm-increases-quarterly-cash-dividend-by-8-percent-and-announ
  - Used for official framing of business lines and capital-return posture.

### Nichicon / Nippon Chemi-Con

- Nichicon IR Library: https://www.nichicon.co.jp/english/ir/library/
- Nippon Chemi-Con IR Library / schedule: https://www.chemi-con.co.jp/en/ir/library/
  - Used to note that FY2025 full-year results are scheduled for 2026-05-14 JST and should be checked after release.

## Secondary sources used only for discovery/cross-checking

- Reuters/TradingView ROHM article, used only to flag current impairment/EV-demand risk and not as the sole basis for any buy recommendation.
- Search-result snippets for current official source discovery where official pages were hard to fetch directly.

## Source-quality notes

- Gooaye/NotebookLM notes are treated as thesis-generation inputs, not verified facts.
- Primary-company sources were prioritized for financial and strategic claims.
- Market quotes came from Stooq because Yahoo Finance API returned HTTP 429 during this run.
- OTC liquidity conclusions are preliminary and should be verified in Weiting's actual broker quote screen before any order.
