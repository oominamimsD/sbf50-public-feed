# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T02:45:15Z**
- feed_generated_utc: 2026-11-11T02:45:16+00:00
- source_sha256: `eede8cec9eb6a877c59cb1fbfae392446cf35ec3ae72ca30dba4ecc4367d3de0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T02:45+00:00, close=73713.5, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T02:00+00:00, close=73573.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.724600|-14.88|46.72|-15.60|5126436|1.74|
|ZEC_USDT|1030.610000|-5.73|-14.38|-6.45|2232746601|0.39|
|DASH_USDT|43.530000|-3.56|-5.65|-4.28|14254625|2.30|
|UNI_USDT|6.758000|-1.05|-8.09|-1.77|36173608|2.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|43.530000|42.750000|43.530000|0.74|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.724600|1.682600|1.725500|2.30|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.758000|6.626000|6.758000|1.04|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1030.610000|1007.730000|1030.120000|1.42|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-11T02:45:00+00:00, last15m_closed_end=2026-11-11T02:45+00:00, prior8high=44.600000, depth_time=2026-11-11T02:45:10+00:00, book20_bid_proxy_usdt=819813, book20_ask_proxy_usdt=589961, funding_indicative=-0.000162, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.56%, turnover=14254625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-11T02:45:00+00:00, last15m_closed_end=2026-11-11T02:45+00:00, prior8high=1.870000, depth_time=2026-11-11T02:45:06+00:00, book20_bid_proxy_usdt=15900, book20_ask_proxy_usdt=15140, funding_indicative=0.000102, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.88%, turnover=5126436. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T02:45:00+00:00, last15m_closed_end=2026-11-11T02:45+00:00, prior8high=6.820000, depth_time=2026-11-11T02:45:14+00:00, book20_bid_proxy_usdt=1871371, book20_ask_proxy_usdt=1900732, funding_indicative=0.000002, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=36173608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T02:45:00+00:00, last15m_closed_end=2026-11-11T02:45+00:00, prior8high=1047.780000, depth_time=2026-11-11T02:45:09+00:00, book20_bid_proxy_usdt=361923, book20_ask_proxy_usdt=291438, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.73%, turnover=2232746601. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
