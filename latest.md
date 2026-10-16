# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T17:45:22Z**
- feed_generated_utc: 2026-10-16T17:45:24+00:00
- source_sha256: `a7754bd06a1d652228a5fb458429b38e79c0f8bb6bab3a48ad15c1463d05ab28`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T17:45+00:00, close=81499.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T17:00+00:00, close=81405.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T16:00+00:00, close=81322.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.197680|-3.58|62.48|-3.79|21712396|8.60|
|ZRO_USDT|2.044000|-2.72|0.35|-2.93|16146808|0.49|
|ZEC_USDT|1161.500000|-2.23|-4.66|-2.44|1585556328|0.09|
|HBAR_USDT|0.083090|-1.21|-8.55|-1.42|22604253|1.20|
|STRK_USDT|0.073130|-1.10|-2.89|-1.31|28751463|2.73|
|PYTH_USDT|0.085520|-0.88|0.15|-1.09|6073131|1.17|
|AAVE_USDT|156.030000|-0.79|-8.13|-1.00|32840918|0.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|156.030000|153.780000|156.030000|2.02|N|Y/Y|Y/N|Y|N|
|BAT_USDT|0.197680|0.191460|0.197700|1.53|N|N/N|N/N|Y|N|
|HBAR_USDT|0.083090|0.082130|0.083090|0.87|N|Y/Y|Y/N|Y|N|
|PYTH_USDT|0.085520|0.083450|0.085520|3.27|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.073130|0.072400|0.073130|1.13|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1161.500000|1133.160000|1161.660000|1.85|N|Y/Y|Y/N|Y|N|
|ZRO_USDT|2.044000|1.975000|2.044000|2.50|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T17:45:00+00:00, last15m_closed_end=2026-10-16T17:45+00:00, prior8high=158.710000, depth_time=2026-10-16T17:45:21+00:00, book20_bid_proxy_usdt=429429, book20_ask_proxy_usdt=459381, funding_indicative=0.000089, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.79%, turnover=32840918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T17:45:00+00:00, last15m_closed_end=2026-10-16T17:45+00:00, prior8high=0.209940, depth_time=2026-10-16T17:45:06+00:00, book20_bid_proxy_usdt=18422, book20_ask_proxy_usdt=22804, funding_indicative=-0.000273, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.58%, turnover=21712396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T17:45:00+00:00, last15m_closed_end=2026-10-16T17:45+00:00, prior8high=0.084760, depth_time=2026-10-16T17:45:14+00:00, book20_bid_proxy_usdt=1285664, book20_ask_proxy_usdt=639474, funding_indicative=0.000063, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.21%, turnover=22604253. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T17:45:00+00:00, last15m_closed_end=2026-10-16T17:45+00:00, prior8high=0.087360, depth_time=2026-10-16T17:45:18+00:00, book20_bid_proxy_usdt=148103, book20_ask_proxy_usdt=66114, funding_indicative=-0.000036, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=6073131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T17:45:00+00:00, last15m_closed_end=2026-10-16T17:45+00:00, prior8high=0.074900, depth_time=2026-10-16T17:45:16+00:00, book20_bid_proxy_usdt=464817, book20_ask_proxy_usdt=201181, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=28751463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T17:45:00+00:00, last15m_closed_end=2026-10-16T17:45+00:00, prior8high=1205.970000, depth_time=2026-10-16T17:45:12+00:00, book20_bid_proxy_usdt=389860, book20_ask_proxy_usdt=82658, funding_indicative=0.000040, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=1585556328. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T17:45:00+00:00, last15m_closed_end=2026-10-16T17:45+00:00, prior8high=2.138100, depth_time=2026-10-16T17:45:09+00:00, book20_bid_proxy_usdt=42947, book20_ask_proxy_usdt=25044, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.72%, turnover=16146808. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
