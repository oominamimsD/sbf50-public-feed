# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T12:45:24Z**
- feed_generated_utc: 2026-10-20T12:45:26+00:00
- source_sha256: `5119d7ea10c9bf2f93e886af84bfcdee1f6113056bae589aa8438422ce0b0003`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1201; contracts: 1193; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T12:45+00:00, close=81660.9, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.068013|-21.86|308.19|-21.56|8879726|2.06|
|NEAR_USDT|4.704000|-4.07|-15.22|-3.77|168931560|2.13|
|SAND_USDT|0.056930|-3.73|-8.31|-3.43|5426578|1.76|
|ARB_USDT|0.189330|-3.22|0.45|-2.92|98202678|0.53|
|BTW_USDT|1.719200|-1.87|-2.08|-1.57|36903164|3.50|
|UNI_USDT|7.177000|-1.52|-3.24|-1.22|9955358|1.39|
|LTC_USDT|58.880000|-1.42|-6.48|-1.12|13262398|3.40|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.068013|0.066520|0.068013|1.19|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.189330|0.187860|0.189330|1.10|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.719200|1.675000|1.719200|0.47|N|Y/Y|Y/Y|Y|N|
|LTC_USDT|58.880000|58.250000|58.870000|2.87|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.704000|4.630000|4.703000|0.55|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.056930|0.056510|0.056930|0.73|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.177000|7.106000|7.175000|2.20|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T12:45:01+00:00, last15m_closed_end=2026-10-20T12:45+00:00, prior8high=0.070454, depth_time=2026-10-20T12:45:08+00:00, book20_bid_proxy_usdt=7158, book20_ask_proxy_usdt=25010, funding_indicative=0.000063, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.86%, turnover=8879726. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T12:45:01+00:00, last15m_closed_end=2026-10-20T12:45+00:00, prior8high=0.190320, depth_time=2026-10-20T12:45:16+00:00, book20_bid_proxy_usdt=104050, book20_ask_proxy_usdt=104632, funding_indicative=0.000092, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.22%, turnover=98202678. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T12:45:01+00:00, last15m_closed_end=2026-10-20T12:45+00:00, prior8high=1.878700, depth_time=2026-10-20T12:45:18+00:00, book20_bid_proxy_usdt=13052, book20_ask_proxy_usdt=13586, funding_indicative=-0.003460, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.87%, turnover=36903164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-20T12:45:01+00:00, last15m_closed_end=2026-10-20T12:45+00:00, prior8high=59.050000, depth_time=2026-10-20T12:45:23+00:00, book20_bid_proxy_usdt=1692624, book20_ask_proxy_usdt=1596009, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=13262398. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T12:45:01+00:00, last15m_closed_end=2026-10-20T12:45+00:00, prior8high=4.728000, depth_time=2026-10-20T12:45:11+00:00, book20_bid_proxy_usdt=335020, book20_ask_proxy_usdt=3261760, funding_indicative=0.000023, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.07%, turnover=168931560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T12:45:01+00:00, last15m_closed_end=2026-10-20T12:45+00:00, prior8high=0.057080, depth_time=2026-10-20T12:45:12+00:00, book20_bid_proxy_usdt=937816, book20_ask_proxy_usdt=907441, funding_indicative=-0.001791, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.73%, turnover=5426578. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T12:45:01+00:00, last15m_closed_end=2026-10-20T12:45+00:00, prior8high=7.197000, depth_time=2026-10-20T12:45:20+00:00, book20_bid_proxy_usdt=1126447, book20_ask_proxy_usdt=2201008, funding_indicative=0.000029, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=9955358. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
