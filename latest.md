# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T04:45:25Z**
- feed_generated_utc: 2026-11-09T04:45:26+00:00
- source_sha256: `67cb84fd15bb4f01a526220ba00024401bdfb3c43a6a01e2628704c420ffa714`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T04:45+00:00, close=74901.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001649|-15.78|41.60|-14.30|10416331|0.61|
|AKE_USDT|0.004684|-12.56|-48.86|-11.08|11621080|6.41|
|JCT_USDT|0.008691|-11.62|74.55|-10.14|67016317|3.45|
|XRP_USDT|1.105600|-4.34|-11.54|-2.86|233444231|0.90|
|PUMPFUN_USDT|0.003591|-3.90|-14.86|-2.42|9315593|2.78|
|HYPE_USDT|74.553000|-3.71|-14.97|-2.23|40210746|0.13|
|LIT_USDT|3.107800|-2.68|-3.78|-1.20|13556333|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004684|0.004627|0.004688|1.27|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|74.553000|74.350000|74.556000|0.57|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008691|0.007861|0.008668|0.65|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.107800|3.086100|3.107800|0.86|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001649|0.001639|0.001646|0.50|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003591|0.003574|0.003590|0.18|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.105600|1.103000|1.105600|1.15|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T04:45:03+00:00, last15m_closed_end=2026-11-09T04:45+00:00, prior8high=0.005144, depth_time=2026-11-09T04:45:11+00:00, book20_bid_proxy_usdt=44868, book20_ask_proxy_usdt=42836, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.56%, turnover=11621080. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T04:45:03+00:00, last15m_closed_end=2026-11-09T04:45+00:00, prior8high=75.262000, depth_time=2026-11-09T04:45:20+00:00, book20_bid_proxy_usdt=107048, book20_ask_proxy_usdt=72546, funding_indicative=0.000038, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.71%, turnover=40210746. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T04:45:03+00:00, last15m_closed_end=2026-11-09T04:45+00:00, prior8high=0.009716, depth_time=2026-11-09T04:45:14+00:00, book20_bid_proxy_usdt=27276, book20_ask_proxy_usdt=18963, funding_indicative=0.001459, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.62%, turnover=67016317. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T04:45:03+00:00, last15m_closed_end=2026-11-09T04:45+00:00, prior8high=3.158500, depth_time=2026-11-09T04:45:23+00:00, book20_bid_proxy_usdt=19905, book20_ask_proxy_usdt=20155, funding_indicative=-0.000038, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=13556333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T04:45:03+00:00, last15m_closed_end=2026-11-09T04:45+00:00, prior8high=0.001709, depth_time=2026-11-09T04:45:08+00:00, book20_bid_proxy_usdt=10852, book20_ask_proxy_usdt=28470, funding_indicative=-0.000326, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.78%, turnover=10416331. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T04:45:03+00:00, last15m_closed_end=2026-11-09T04:45+00:00, prior8high=0.003675, depth_time=2026-11-09T04:45:18+00:00, book20_bid_proxy_usdt=2146023, book20_ask_proxy_usdt=2913379, funding_indicative=0.000004, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.90%, turnover=9315593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T04:45:03+00:00, last15m_closed_end=2026-11-09T04:45+00:00, prior8high=1.122600, depth_time=2026-11-09T04:45:16+00:00, book20_bid_proxy_usdt=4761106, book20_ask_proxy_usdt=3420126, funding_indicative=-0.000005, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.34%, turnover=233444231. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
