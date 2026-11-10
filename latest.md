# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T15:00:29Z**
- feed_generated_utc: 2026-11-10T15:00:31+00:00
- source_sha256: `66cbd65e201e2d71e520e6b12446be6fbc01aa5ab97a694e3b9f2f859c4684d8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T15:00+00:00, close=74373.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T15:00+00:00, close=74373.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002727|-44.31|-50.43|-42.81|13490263|3.65|
|ARB_USDT|0.165020|-10.33|3.57|-8.83|37654038|1.21|
|ANTHROPIC_USDT|1286.740000|-9.93|-23.35|-8.43|7533590|0.08|
|QNT_USDT|183.090000|-8.42|-9.56|-6.92|36337426|0.55|
|XMR_USDT|554.460000|-7.74|-8.39|-6.24|6246459|0.18|
|AAVE_USDT|124.990000|-5.68|-4.26|-4.18|10313397|3.20|
|AVAX_USDT|8.378000|-5.44|-1.44|-3.94|37569335|2.39|
|XRP_USDT|1.064900|-4.39|-14.69|-2.89|286944484|0.94|
|SOL_USDT|84.260000|-4.13|-9.89|-2.63|664671626|1.19|
|HYPE_USDT|73.604000|-3.55|-14.12|-2.05|40665129|0.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|124.990000|122.640000|124.990000|2.17|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002727|0.002383|0.002712|1.91|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1286.740000|1277.520000|1286.680000|0.26|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165020|0.161200|0.165060|1.54|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.378000|8.228000|8.378000|1.64|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|73.604000|72.149000|73.612000|2.32|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|183.090000|178.810000|183.090000|1.55|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|84.260000|82.420000|84.310000|1.44|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|554.460000|544.080000|554.460000|0.93|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.064900|1.048300|1.065200|1.43|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T15:00:02+00:00, last15m_closed_end=2026-11-10T15:00+00:00, prior8high=125.920000, depth_time=2026-11-10T15:00:17+00:00, book20_bid_proxy_usdt=229031, book20_ask_proxy_usdt=345722, funding_indicative=0.000037, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.68%, turnover=10313397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T15:00:02+00:00, last15m_closed_end=2026-11-10T15:00+00:00, prior8high=0.002815, depth_time=2026-11-10T15:00:07+00:00, book20_bid_proxy_usdt=45275, book20_ask_proxy_usdt=23904, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-44.31%, turnover=13490263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T15:00:02+00:00, last15m_closed_end=2026-11-10T15:00+00:00, prior8high=1309.180000, depth_time=2026-11-10T15:00:12+00:00, book20_bid_proxy_usdt=39887, book20_ask_proxy_usdt=25702, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.93%, turnover=7533590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T15:00:02+00:00, last15m_closed_end=2026-11-10T15:00+00:00, prior8high=0.166050, depth_time=2026-11-10T15:00:09+00:00, book20_bid_proxy_usdt=48955, book20_ask_proxy_usdt=75136, funding_indicative=-0.000126, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.33%, turnover=37654038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T15:00:02+00:00, last15m_closed_end=2026-11-10T15:00+00:00, prior8high=8.428000, depth_time=2026-11-10T15:00:21+00:00, book20_bid_proxy_usdt=741353, book20_ask_proxy_usdt=647248, funding_indicative=-0.000018, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.44%, turnover=37569335. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T15:00:02+00:00, last15m_closed_end=2026-11-10T15:00+00:00, prior8high=74.000000, depth_time=2026-11-10T15:00:28+00:00, book20_bid_proxy_usdt=53134, book20_ask_proxy_usdt=45929, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=40665129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T15:00:02+00:00, last15m_closed_end=2026-11-10T15:00+00:00, prior8high=188.280000, depth_time=2026-11-10T15:00:14+00:00, book20_bid_proxy_usdt=36158, book20_ask_proxy_usdt=72035, funding_indicative=-0.000089, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.42%, turnover=36337426. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T15:00:02+00:00, last15m_closed_end=2026-11-10T15:00+00:00, prior8high=85.210000, depth_time=2026-11-10T15:00:26+00:00, book20_bid_proxy_usdt=16046639, book20_ask_proxy_usdt=18881360, funding_indicative=0.000040, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.13%, turnover=664671626. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T15:00:02+00:00, last15m_closed_end=2026-11-10T15:00+00:00, prior8high=555.790000, depth_time=2026-11-10T15:00:17+00:00, book20_bid_proxy_usdt=15886, book20_ask_proxy_usdt=24474, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.74%, turnover=6246459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-10T15:00:02+00:00, last15m_closed_end=2026-11-10T15:00+00:00, prior8high=1.082900, depth_time=2026-11-10T15:00:24+00:00, book20_bid_proxy_usdt=3047448, book20_ask_proxy_usdt=3254205, funding_indicative=0.000072, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.39%, turnover=286944484. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
