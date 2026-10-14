# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T06:45:19Z**
- feed_generated_utc: 2026-10-14T06:45:21+00:00
- source_sha256: `680cb5f6d331fd2a51e015dea9cdcb807a035cf4df27bb10613f765455554c1c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T06:45+00:00, close=83457.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T06:00+00:00, close=83434.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGIC_USDT|0.112140|-5.48|64.62|-5.55|5491932|1.78|
|STRK_USDT|0.082230|-5.40|57.55|-5.47|31128251|1.22|
|W_USDT|0.016185|-3.67|11.52|-3.74|7113273|0.62|
|TIA_USDT|0.556900|-3.53|16.92|-3.60|44994204|1.80|
|UNI_USDT|7.380000|-2.53|-14.82|-2.60|19880692|2.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.112140|0.111620|0.112140|0.67|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.082230|0.080270|0.082230|3.42|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.556900|0.547400|0.556900|1.00|N|Y/Y|N/N|N|N|
|UNI_USDT|7.380000|7.259000|7.380000|0.15|N|Y/Y|Y/N|N|N|
|W_USDT|0.016185|0.015869|0.016185|1.14|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T06:45:00+00:00, last15m_closed_end=2026-10-14T06:45+00:00, prior8high=0.115610, depth_time=2026-10-14T06:45:08+00:00, book20_bid_proxy_usdt=183367, book20_ask_proxy_usdt=184354, funding_indicative=-0.000040, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.48%, turnover=5491932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T06:45:00+00:00, last15m_closed_end=2026-10-14T06:45+00:00, prior8high=0.085530, depth_time=2026-10-14T06:45:11+00:00, book20_bid_proxy_usdt=207081, book20_ask_proxy_usdt=177777, funding_indicative=0.000050, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.40%, turnover=31128251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T06:45:00+00:00, last15m_closed_end=2026-10-14T06:45+00:00, prior8high=0.581500, depth_time=2026-10-14T06:45:14+00:00, book20_bid_proxy_usdt=147283, book20_ask_proxy_usdt=211491, funding_indicative=0.000000, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.53%, turnover=44994204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T06:45:00+00:00, last15m_closed_end=2026-10-14T06:45+00:00, prior8high=7.510000, depth_time=2026-10-14T06:45:18+00:00, book20_bid_proxy_usdt=1421779, book20_ask_proxy_usdt=1678074, funding_indicative=0.000100, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=19880692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T06:45:00+00:00, last15m_closed_end=2026-10-14T06:45+00:00, prior8high=0.016644, depth_time=2026-10-14T06:45:13+00:00, book20_bid_proxy_usdt=40952, book20_ask_proxy_usdt=39962, funding_indicative=-0.000163, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.67%, turnover=7113273. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
