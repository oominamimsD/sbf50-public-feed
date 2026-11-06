# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T13:00:31Z**
- feed_generated_utc: 2026-11-06T13:00:32+00:00
- source_sha256: `742060e0addd974d01c488e289647babd354c9450e34f72a332d8a29db5908c6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T13:00+00:00, close=76005.5, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T13:00+00:00, close=76005.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T12:00+00:00, close=76114.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|XPL_USDT|0.057750|-8.28|-26.83|-8.28|11553696|1.73|
|XRP_USDT|1.188700|-7.18|-9.22|-7.18|470955849|0.84|
|BCH_USDT|268.840000|-5.60|-6.74|-5.60|6912831|3.35|
|ATOM_USDT|1.410000|-4.47|-13.54|-4.47|6385066|7.09|
|NEAR_USDT|3.711000|-4.05|-20.17|-4.05|70521793|2.69|
|XLM_USDT|0.153990|-3.88|-10.85|-3.88|36431338|0.65|
|ONDO_USDT|0.374800|-3.65|-12.79|-3.65|25727404|2.67|
|FET_USDT|0.148100|-3.26|-19.85|-3.26|6151421|6.75|
|DOGE_USDT|0.072340|-2.57|-10.28|-2.57|145214470|1.38|
|HBAR_USDT|0.068210|-2.01|-9.37|-2.01|9774936|1.47|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ATOM_USDT|1.410000|1.403000|1.410000|1.60|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|268.840000|266.560000|268.840000|0.42|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.072340|0.072210|0.072340|3.17|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.148100|0.148600|0.148100|5.19|Y|Y/Y|Y/Y|Y|Y|
|HBAR_USDT|0.068210|0.068420|0.068210|2.60|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|3.711000|3.728000|3.711000|2.10|Y|Y/Y|Y/Y|Y|Y|
|ONDO_USDT|0.374800|0.376000|0.374800|0.99|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.153990|0.154130|0.153980|1.83|Y|Y/Y|Y/Y|Y|Y|
|XPL_USDT|0.057750|0.057550|0.057750|1.69|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.188700|1.189600|1.188700|0.71|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ATOM_USDT: quote_utc=2026-11-06T13:00:02+00:00, last15m_closed_end=2026-11-06T13:00+00:00, prior8high=1.423000, depth_time=2026-11-06T13:00:12+00:00, book20_bid_proxy_usdt=1610722, book20_ask_proxy_usdt=2586941, funding_indicative=0.000089, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.47%, turnover=6385066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-06T13:00:02+00:00, last15m_closed_end=2026-11-06T13:00+00:00, prior8high=271.890000, depth_time=2026-11-06T13:00:12+00:00, book20_bid_proxy_usdt=53169, book20_ask_proxy_usdt=83170, funding_indicative=-0.000039, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.60%, turnover=6912831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-06T13:00:01+00:00, last15m_closed_end=2026-11-06T13:00+00:00, prior8high=0.072960, depth_time=2026-11-06T13:00:27+00:00, book20_bid_proxy_usdt=5685510, book20_ask_proxy_usdt=5578102, funding_indicative=0.000054, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.57%, turnover=145214470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-06T13:00:01+00:00, last15m_closed_end=2026-11-06T13:00+00:00, prior8high=0.150200, depth_time=2026-11-06T13:00:24+00:00, book20_bid_proxy_usdt=2362557, book20_ask_proxy_usdt=958397, funding_indicative=0.000059, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.26%, turnover=6151421. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-06T13:00:01+00:00, last15m_closed_end=2026-11-06T13:00+00:00, prior8high=0.069070, depth_time=2026-11-06T13:00:28+00:00, book20_bid_proxy_usdt=623707, book20_ask_proxy_usdt=702550, funding_indicative=0.000077, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.01%, turnover=9774936. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-06T13:00:01+00:00, last15m_closed_end=2026-11-06T13:00+00:00, prior8high=3.795000, depth_time=2026-11-06T13:00:16+00:00, book20_bid_proxy_usdt=3471274, book20_ask_proxy_usdt=3670314, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.05%, turnover=70521793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-06T13:00:01+00:00, last15m_closed_end=2026-11-06T13:00+00:00, prior8high=0.379400, depth_time=2026-11-06T13:00:22+00:00, book20_bid_proxy_usdt=1797010, book20_ask_proxy_usdt=1529539, funding_indicative=0.000050, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.65%, turnover=25727404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-06T13:00:01+00:00, last15m_closed_end=2026-11-06T13:00+00:00, prior8high=0.155540, depth_time=2026-11-06T13:00:19+00:00, book20_bid_proxy_usdt=134368, book20_ask_proxy_usdt=230174, funding_indicative=-0.000117, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.88%, turnover=36431338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T13:00:02+00:00, last15m_closed_end=2026-11-06T13:00+00:00, prior8high=0.058510, depth_time=2026-11-06T13:00:07+00:00, book20_bid_proxy_usdt=576407, book20_ask_proxy_usdt=361320, funding_indicative=0.000050, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.28%, turnover=11553696. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T13:00:01+00:00, last15m_closed_end=2026-11-06T13:00+00:00, prior8high=1.202300, depth_time=2026-11-06T13:00:10+00:00, book20_bid_proxy_usdt=4067126, book20_ask_proxy_usdt=3687346, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.18%, turnover=470955849. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
