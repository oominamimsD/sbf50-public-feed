# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T03:00:19Z**
- feed_generated_utc: 2026-11-09T03:00:21+00:00
- source_sha256: `a4d7402d4cbea1552fc3cc9d6d1495d0f0ae35569a3dc335c65d09bdead8f8e4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T03:00+00:00, close=75248.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T03:00+00:00, close=75248.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001691|-10.62|45.18|-9.59|10852371|0.59|
|HOT_USDT|0.000398|-7.33|10.70|-6.30|6245677|2.51|
|AKE_USDT|0.005081|-5.15|-44.53|-4.12|12051798|1.97|
|XRP_USDT|1.114500|-3.90|-10.83|-2.87|224493100|0.90|
|HYPE_USDT|74.833000|-3.41|-14.65|-2.38|40102381|0.13|
|LIT_USDT|3.129200|-3.09|-3.12|-2.06|12713452|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005081|0.004921|0.005080|0.82|N|Y/Y|N/N|Y|N|
|HOT_USDT|0.000398|0.000394|0.000398|0.28|N|Y/Y|N/N|Y|N|
|HYPE_USDT|74.833000|74.059000|74.833000|0.44|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.129200|3.075700|3.129200|0.77|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001691|0.001686|0.001691|0.89|N|Y/Y|Y/N|Y|N|
|XRP_USDT|1.114500|1.106800|1.114500|0.46|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T03:00:01+00:00, last15m_closed_end=2026-11-09T03:00+00:00, prior8high=0.005297, depth_time=2026-11-09T03:00:12+00:00, book20_bid_proxy_usdt=46414, book20_ask_proxy_usdt=59622, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.15%, turnover=12051798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-09T03:00:01+00:00, last15m_closed_end=2026-11-09T03:00+00:00, prior8high=0.000404, depth_time=2026-11-09T03:00:09+00:00, book20_bid_proxy_usdt=103304, book20_ask_proxy_usdt=125479, funding_indicative=-0.000131, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=1, 24h_change=-7.33%, turnover=6245677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T03:00:01+00:00, last15m_closed_end=2026-11-09T03:00+00:00, prior8high=75.332000, depth_time=2026-11-09T03:00:16+00:00, book20_bid_proxy_usdt=354521, book20_ask_proxy_usdt=88685, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.41%, turnover=40102381. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T03:00:01+00:00, last15m_closed_end=2026-11-09T03:00+00:00, prior8high=3.157600, depth_time=2026-11-09T03:00:19+00:00, book20_bid_proxy_usdt=19099, book20_ask_proxy_usdt=20372, funding_indicative=-0.000012, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.09%, turnover=12713452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T03:00:01+00:00, last15m_closed_end=2026-11-09T03:00+00:00, prior8high=0.001746, depth_time=2026-11-09T03:00:07+00:00, book20_bid_proxy_usdt=11088, book20_ask_proxy_usdt=11395, funding_indicative=-0.000724, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.62%, turnover=10852371. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T03:00:01+00:00, last15m_closed_end=2026-11-09T03:00+00:00, prior8high=1.125700, depth_time=2026-11-09T03:00:14+00:00, book20_bid_proxy_usdt=3030725, book20_ask_proxy_usdt=3844692, funding_indicative=0.000006, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.90%, turnover=224493100. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
