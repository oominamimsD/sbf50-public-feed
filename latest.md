# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T01:45:20Z**
- feed_generated_utc: 2026-11-09T01:45:21+00:00
- source_sha256: `1651e3dad831139422be052d4aa5467be3350f7b375271fc0e6b89f641e2f479`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T01:45+00:00, close=75152.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T01:00+00:00, close=75213.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001705|-12.94|46.37|-11.79|11582737|0.59|
|HOT_USDT|0.000398|-7.37|10.65|-6.22|6247537|2.51|
|AKE_USDT|0.005038|-5.95|-45.00|-4.80|13734107|3.97|
|XRP_USDT|1.116800|-3.37|-10.64|-2.22|232613075|0.90|
|HYPE_USDT|74.908000|-3.25|-14.57|-2.10|39853810|0.13|
|LIT_USDT|3.107000|-2.70|-3.81|-1.55|12167604|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005038|0.005107|0.005038|0.94|N|Y/Y|N/N|Y|N|
|HOT_USDT|0.000398|0.000397|0.000398|1.35|N|Y/N|N/N|Y|N|
|HYPE_USDT|74.908000|74.174000|74.869000|0.78|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.107000|3.031200|3.107000|0.29|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001705|0.001698|0.001705|0.71|N|Y/Y|Y/N|Y|N|
|XRP_USDT|1.116800|1.105100|1.116300|1.01|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T01:45:01+00:00, last15m_closed_end=2026-11-09T01:45+00:00, prior8high=0.005316, depth_time=2026-11-09T01:45:12+00:00, book20_bid_proxy_usdt=30064, book20_ask_proxy_usdt=36919, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.95%, turnover=13734107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-09T01:45:02+00:00, last15m_closed_end=2026-11-09T01:45+00:00, prior8high=0.000411, depth_time=2026-11-09T01:45:08+00:00, book20_bid_proxy_usdt=114458, book20_ask_proxy_usdt=64932, funding_indicative=-0.000312, next_funding_utc=2026-11-09T02:00:00+00:00, funding_cycle_h=1, 24h_change=-7.37%, turnover=6247537. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T01:45:02+00:00, last15m_closed_end=2026-11-09T01:45+00:00, prior8high=75.474000, depth_time=2026-11-09T01:45:16+00:00, book20_bid_proxy_usdt=83147, book20_ask_proxy_usdt=104944, funding_indicative=0.000027, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.25%, turnover=39853810. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T01:45:01+00:00, last15m_closed_end=2026-11-09T01:45+00:00, prior8high=3.121700, depth_time=2026-11-09T01:45:19+00:00, book20_bid_proxy_usdt=23175, book20_ask_proxy_usdt=22198, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.70%, turnover=12167604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T01:45:01+00:00, last15m_closed_end=2026-11-09T01:45+00:00, prior8high=0.001763, depth_time=2026-11-09T01:45:07+00:00, book20_bid_proxy_usdt=10205, book20_ask_proxy_usdt=15833, funding_indicative=-0.001018, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.94%, turnover=11582737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T01:45:02+00:00, last15m_closed_end=2026-11-09T01:45+00:00, prior8high=1.125800, depth_time=2026-11-09T01:45:13+00:00, book20_bid_proxy_usdt=2068435, book20_ask_proxy_usdt=3701117, funding_indicative=0.000025, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.37%, turnover=232613075. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
