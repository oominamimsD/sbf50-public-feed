# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T21:15:13Z**
- feed_generated_utc: 2026-11-09T21:15:14+00:00
- source_sha256: `d2103ae0936e33d3f714b1e363054a019be17ad98374ed34ebb6fd3c42a14258`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T21:15+00:00, close=74845.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T21:00+00:00, close=74845.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1164.400000|-5.00|-7.15|-4.16|2529327145|0.09|
|QNT_USDT|195.400000|-2.31|-3.48|-1.47|44229131|0.51|
|XRP_USDT|1.091000|-2.05|-12.60|-1.21|323857474|0.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|QNT_USDT|195.400000|194.710000|195.400000|1.50|N|Y/Y|Y/N|Y|N|
|XRP_USDT|1.091000|1.087800|1.090300|1.21|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1164.400000|1162.990000|1164.060000|0.91|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- QNT_USDT: quote_utc=2026-11-09T21:15:01+00:00, last15m_closed_end=2026-11-09T21:15+00:00, prior8high=197.510000, depth_time=2026-11-09T21:15:02+00:00, book20_bid_proxy_usdt=66458, book20_ask_proxy_usdt=79745, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.31%, turnover=44229131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T21:15:01+00:00, last15m_closed_end=2026-11-09T21:15+00:00, prior8high=1.103100, depth_time=2026-11-09T21:15:12+00:00, book20_bid_proxy_usdt=2806978, book20_ask_proxy_usdt=2756983, funding_indicative=0.000080, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=323857474. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T21:15:01+00:00, last15m_closed_end=2026-11-09T21:15+00:00, prior8high=1189.910000, depth_time=2026-11-09T21:15:06+00:00, book20_bid_proxy_usdt=59283, book20_ask_proxy_usdt=296337, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.00%, turnover=2529327145. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
