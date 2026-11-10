# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T01:30:17Z**
- feed_generated_utc: 2026-11-10T01:30:18+00:00
- source_sha256: `8b70d8d3ab5e6fce93ef83e5e353b673f11ca7ac16025484cefad5ce08271a7f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T01:30+00:00, close=75123.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T01:00+00:00, close=75052, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002782|-43.18|-49.43|-42.68|12970165|3.60|
|ARB_USDT|0.173900|-5.50|9.14|-5.00|31272921|0.57|
|ZEC_USDT|1174.000000|-4.21|-6.38|-3.71|2398945431|0.09|
|DOT_USDT|0.856900|-3.81|-8.26|-3.31|10622643|1.17|
|QNT_USDT|194.560000|-2.73|-3.89|-2.23|40051947|2.57|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002782|0.002154|0.002769|7.21|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.173900|0.173630|0.173900|0.75|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.856900|0.852500|0.856800|0.60|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.560000|193.200000|194.560000|0.76|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1174.000000|1152.430000|1174.560000|0.98|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T01:30:03+00:00, last15m_closed_end=2026-11-10T01:30+00:00, prior8high=0.005106, depth_time=2026-11-10T01:30:07+00:00, book20_bid_proxy_usdt=38032, book20_ask_proxy_usdt=28377, funding_indicative=-0.000454, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-43.18%, turnover=12970165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T01:30:03+00:00, last15m_closed_end=2026-11-10T01:30+00:00, prior8high=0.176000, depth_time=2026-11-10T01:30:09+00:00, book20_bid_proxy_usdt=24824, book20_ask_proxy_usdt=42908, funding_indicative=-0.000033, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.50%, turnover=31272921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T01:29:59+00:00, last15m_closed_end=2026-11-10T01:30+00:00, prior8high=0.858500, depth_time=2026-11-10T01:30:14+00:00, book20_bid_proxy_usdt=730554, book20_ask_proxy_usdt=604855, funding_indicative=0.000004, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.81%, turnover=10622643. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T01:29:59+00:00, last15m_closed_end=2026-11-10T01:30+00:00, prior8high=195.180000, depth_time=2026-11-10T01:30:16+00:00, book20_bid_proxy_usdt=70568, book20_ask_proxy_usdt=89773, funding_indicative=0.000100, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=40051947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T01:30:03+00:00, last15m_closed_end=2026-11-10T01:30+00:00, prior8high=1178.530000, depth_time=2026-11-10T01:30:12+00:00, book20_bid_proxy_usdt=89393, book20_ask_proxy_usdt=291596, funding_indicative=0.000098, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.21%, turnover=2398945431. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
