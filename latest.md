# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T03:45:19Z**
- feed_generated_utc: 2026-11-09T03:45:21+00:00
- source_sha256: `8401ab4056096a43b710d30531aae3f973bb80a3364761759c072d7cd7663785`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T03:45+00:00, close=75072, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T03:00+00:00, close=75248.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001672|-14.58|43.62|-13.30|10901670|0.60|
|JCT_USDT|0.008547|-13.08|71.66|-11.80|65964270|5.85|
|AKE_USDT|0.004897|-8.58|-46.53|-7.30|12258709|4.08|
|XRP_USDT|1.115000|-3.53|-10.79|-2.25|231124061|0.90|
|HYPE_USDT|74.811000|-3.38|-14.68|-2.10|40751555|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004897|0.004888|0.004897|1.37|N|Y/Y|N/N|Y|N|
|HYPE_USDT|74.811000|74.059000|74.812000|0.79|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008547|0.008360|0.008581|1.06|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001672|0.001672|0.001672|0.14|N|Y/Y|Y/N|Y|N|
|XRP_USDT|1.115000|1.103000|1.115600|0.69|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T03:45:03+00:00, last15m_closed_end=2026-11-09T03:45+00:00, prior8high=0.005151, depth_time=2026-11-09T03:45:13+00:00, book20_bid_proxy_usdt=33084, book20_ask_proxy_usdt=41626, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.58%, turnover=12258709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T03:45:03+00:00, last15m_closed_end=2026-11-09T03:45+00:00, prior8high=75.262000, depth_time=2026-11-09T03:45:16+00:00, book20_bid_proxy_usdt=28847, book20_ask_proxy_usdt=204866, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.38%, turnover=40751555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T03:45:03+00:00, last15m_closed_end=2026-11-09T03:45+00:00, prior8high=0.012446, depth_time=2026-11-09T03:45:10+00:00, book20_bid_proxy_usdt=22891, book20_ask_proxy_usdt=30290, funding_indicative=0.001245, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.08%, turnover=65964270. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T03:45:03+00:00, last15m_closed_end=2026-11-09T03:45+00:00, prior8high=0.001731, depth_time=2026-11-09T03:45:08+00:00, book20_bid_proxy_usdt=16307, book20_ask_proxy_usdt=4956, funding_indicative=-0.000563, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.58%, turnover=10901670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T03:45:03+00:00, last15m_closed_end=2026-11-09T03:45+00:00, prior8high=1.123100, depth_time=2026-11-09T03:45:16+00:00, book20_bid_proxy_usdt=4549635, book20_ask_proxy_usdt=4364770, funding_indicative=-0.000007, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.53%, turnover=231124061. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
