# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T01:45:24Z**
- feed_generated_utc: 2026-10-27T01:45:27+00:00
- source_sha256: `aa6f8e22940577b29e3104ec6e61ed5f887267d90dc2108517a0afade70afaca`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T01:45+00:00, close=80266.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T01:00+00:00, close=80194.2, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.627300|-4.67|-14.44|-4.51|5401095|3.07|
|BTW_USDT|1.160700|-2.92|-33.75|-2.76|21105025|3.45|
|DOT_USDT|1.001300|-2.08|-12.68|-1.92|11114998|1.00|
|NEAR_USDT|4.502000|-1.55|-8.19|-1.39|111566251|2.22|
|LINK_USDT|11.371000|-1.36|-4.78|-1.20|104804513|0.88|
|FILECOIN_USDT|0.908600|-1.31|-10.21|-1.15|6590721|1.10|
|TAO_USDT|250.530000|-1.17|-6.62|-1.01|47110590|1.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.160700|1.154700|1.160700|0.90|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.001300|0.996300|1.001300|3.89|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.908600|0.903600|0.908600|0.23|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.371000|11.321000|11.371000|1.18|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.502000|4.446000|4.502000|0.60|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|250.530000|249.270000|250.530000|0.79|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.627300|1.608300|1.627300|0.17|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-27T01:45:01+00:00, last15m_closed_end=2026-10-27T01:45+00:00, prior8high=1.229000, depth_time=2026-10-27T01:45:10+00:00, book20_bid_proxy_usdt=9914, book20_ask_proxy_usdt=14372, funding_indicative=-0.000217, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.92%, turnover=21105025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T01:45:01+00:00, last15m_closed_end=2026-10-27T01:45+00:00, prior8high=1.013800, depth_time=2026-10-27T01:45:13+00:00, book20_bid_proxy_usdt=413592, book20_ask_proxy_usdt=390893, funding_indicative=-0.000106, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=11114998. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T01:45:01+00:00, last15m_closed_end=2026-10-27T01:45+00:00, prior8high=0.916600, depth_time=2026-10-27T01:45:19+00:00, book20_bid_proxy_usdt=1115350, book20_ask_proxy_usdt=1181820, funding_indicative=0.000079, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=6590721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T01:45:01+00:00, last15m_closed_end=2026-10-27T01:45+00:00, prior8high=11.421000, depth_time=2026-10-27T01:45:18+00:00, book20_bid_proxy_usdt=525440, book20_ask_proxy_usdt=528148, funding_indicative=0.000075, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=104804513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T01:45:01+00:00, last15m_closed_end=2026-10-27T01:45+00:00, prior8high=4.536000, depth_time=2026-10-27T01:45:15+00:00, book20_bid_proxy_usdt=2846330, book20_ask_proxy_usdt=452012, funding_indicative=-0.000085, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=111566251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T01:45:01+00:00, last15m_closed_end=2026-10-27T01:45+00:00, prior8high=252.300000, depth_time=2026-10-27T01:45:23+00:00, book20_bid_proxy_usdt=75778, book20_ask_proxy_usdt=104250, funding_indicative=0.000036, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=47110590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T01:45:01+00:00, last15m_closed_end=2026-10-27T01:45+00:00, prior8high=1.647700, depth_time=2026-10-27T01:45:08+00:00, book20_bid_proxy_usdt=34647, book20_ask_proxy_usdt=64392, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.67%, turnover=5401095. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
