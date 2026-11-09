# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T04:00:24Z**
- feed_generated_utc: 2026-11-09T04:00:26+00:00
- source_sha256: `daebbc2d89cc017ae80e16def07b38d57d6d0a9beb14178bdf333f56c368b46b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CLAUDIA_USDT|0.006910|-17.14|278.42|-15.56|9593174|2.89|
|JCT_USDT|0.008277|-15.83|66.23|-14.25|66225962|4.83|
|AKE_USDT|0.004734|-11.62|-48.31|-10.04|11323868|6.34|
|ONE_USDT|0.001682|-11.08|44.43|-9.50|10361952|0.59|
|XRP_USDT|1.110500|-4.25|-11.15|-2.67|225414987|0.90|
|HYPE_USDT|74.512000|-3.82|-15.02|-2.24|39943916|0.54|
|LIT_USDT|3.125800|-3.20|-3.22|-1.62|13067579|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004734|0.004847|0.004735|2.45|Y|Y/Y|Y/N|Y|N|
|CLAUDIA_USDT|0.006910|0.006377|0.006906|0.43|N|Y/Y|N/N|Y|N|
|HYPE_USDT|74.512000|74.391000|74.512000|0.23|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008277|0.008360|0.008288|0.83|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.125800|3.101300|3.125800|1.32|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001682|0.001669|0.001682|0.33|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.110500|1.103000|1.110500|0.43|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T04:00:03+00:00, last15m_closed_end=2026-11-09T04:00+00:00, prior8high=0.005144, depth_time=2026-11-09T04:00:13+00:00, book20_bid_proxy_usdt=35324, book20_ask_proxy_usdt=53834, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.62%, turnover=11323868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLAUDIA_USDT: quote_utc=2026-11-09T04:00:03+00:00, last15m_closed_end=2026-11-09T04:00+00:00, prior8high=0.007150, depth_time=2026-11-09T04:00:08+00:00, book20_bid_proxy_usdt=190, book20_ask_proxy_usdt=81, funding_indicative=0.000134, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-17.14%, turnover=9593174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T04:00:03+00:00, last15m_closed_end=2026-11-09T04:00+00:00, prior8high=75.262000, depth_time=2026-11-09T04:00:21+00:00, book20_bid_proxy_usdt=147890, book20_ask_proxy_usdt=78930, funding_indicative=0.000048, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.82%, turnover=39943916. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T04:00:03+00:00, last15m_closed_end=2026-11-09T04:00+00:00, prior8high=0.010607, depth_time=2026-11-09T04:00:11+00:00, book20_bid_proxy_usdt=18475, book20_ask_proxy_usdt=38333, funding_indicative=0.001233, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.83%, turnover=66225962. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T04:00:03+00:00, last15m_closed_end=2026-11-09T04:00+00:00, prior8high=3.158500, depth_time=2026-11-09T04:00:23+00:00, book20_bid_proxy_usdt=24295, book20_ask_proxy_usdt=31306, funding_indicative=-0.000039, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.20%, turnover=13067579. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T04:00:03+00:00, last15m_closed_end=2026-11-09T04:00+00:00, prior8high=0.001728, depth_time=2026-11-09T04:00:16+00:00, book20_bid_proxy_usdt=8669, book20_ask_proxy_usdt=10283, funding_indicative=-0.000494, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.08%, turnover=10361952. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T04:00:03+00:00, last15m_closed_end=2026-11-09T04:00+00:00, prior8high=1.123100, depth_time=2026-11-09T04:00:18+00:00, book20_bid_proxy_usdt=4017281, book20_ask_proxy_usdt=3495574, funding_indicative=-0.000008, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.25%, turnover=225414987. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
