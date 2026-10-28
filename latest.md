# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T08:45:13Z**
- feed_generated_utc: 2026-10-28T08:45:16+00:00
- source_sha256: `721983eb83c44c0e481714e2e06e05717316a5d5cacfa32cb38fd3f9c7ac3451`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T08:45+00:00, close=81643, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.020192|-4.41|-35.05|-5.79|5892199|1.49|
|DASH_USDT|54.160000|-0.01|8.45|-1.39|16879113|1.85|
|QNT_USDT|198.360000|0.23|1.63|-1.15|73487314|1.01|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020192|0.020327|0.020192|1.08|N|Y/Y|Y/Y|N|N|
|DASH_USDT|54.160000|53.960000|54.160000|2.96|N|Y/Y|N/N|N|N|
|QNT_USDT|198.360000|198.060000|198.330000|1.02|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T08:44:59+00:00, last15m_closed_end=2026-10-28T08:45+00:00, prior8high=0.021607, depth_time=2026-10-28T08:45:07+00:00, book20_bid_proxy_usdt=5744, book20_ask_proxy_usdt=4378, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.41%, turnover=5892199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T08:45:00+00:00, last15m_closed_end=2026-10-28T08:45+00:00, prior8high=54.730000, depth_time=2026-10-28T08:45:08+00:00, book20_bid_proxy_usdt=952228, book20_ask_proxy_usdt=549351, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.01%, turnover=16879113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-28T08:44:59+00:00, last15m_closed_end=2026-10-28T08:45+00:00, prior8high=201.750000, depth_time=2026-10-28T08:45:12+00:00, book20_bid_proxy_usdt=70836, book20_ask_proxy_usdt=67208, funding_indicative=-0.000355, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.23%, turnover=73487314. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
