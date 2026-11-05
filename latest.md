# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T17:30:20Z**
- feed_generated_utc: 2026-11-05T17:30:21+00:00
- source_sha256: `825987ae31080506923a4739ec967fa87fa3977ba4b9b86cf9ff306d6fe0a91e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T17:30+00:00, close=75897.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T17:00+00:00, close=76361, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T16:00+00:00, close=76013.2, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FLUID_USDT|2.406000|-4.97|16.56|-4.80|8854852|8.33|
|TRUMPOFFICIAL_USDT|1.116000|-4.37|-35.41|-4.20|33289224|8.96|
|PENGU_USDT|0.006374|-2.05|-21.60|-1.88|5846949|1.57|
|BCH_USDT|274.390000|-1.69|-4.81|-1.52|9732195|4.01|
|LIT_USDT|3.276600|-1.52|0.60|-1.35|10630875|0.31|
|QNT_USDT|189.240000|-1.34|-4.78|-1.17|47726427|1.06|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|274.390000|274.540000|274.390000|2.07|Y|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.406000|2.364000|2.406000|0.22|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.276600|3.224400|3.276600|0.95|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.006374|0.006389|0.006376|3.60|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|189.240000|189.510000|189.240000|0.62|N|Y/Y|Y/N|Y|N|
|TRUMPOFFICIAL_USDT|1.116000|1.116000|1.118000|0.92|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-05T17:30:01+00:00, last15m_closed_end=2026-11-05T17:30+00:00, prior8high=284.530000, depth_time=2026-11-05T17:30:14+00:00, book20_bid_proxy_usdt=51320, book20_ask_proxy_usdt=211989, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=9732195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T17:30:00+00:00, last15m_closed_end=2026-11-05T17:30+00:00, prior8high=2.611000, depth_time=2026-11-05T17:30:04+00:00, book20_bid_proxy_usdt=201171, book20_ask_proxy_usdt=243406, funding_indicative=0.000263, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.97%, turnover=8854852. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-05T17:30:01+00:00, last15m_closed_end=2026-11-05T17:30+00:00, prior8high=3.478900, depth_time=2026-11-05T17:30:16+00:00, book20_bid_proxy_usdt=22297, book20_ask_proxy_usdt=33936, funding_indicative=-0.000025, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.52%, turnover=10630875. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-11-05T17:30:01+00:00, last15m_closed_end=2026-11-05T17:30+00:00, prior8high=0.006821, depth_time=2026-11-05T17:30:11+00:00, book20_bid_proxy_usdt=128478, book20_ask_proxy_usdt=168287, funding_indicative=-0.000022, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.05%, turnover=5846949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-05T17:30:01+00:00, last15m_closed_end=2026-11-05T17:30+00:00, prior8high=196.370000, depth_time=2026-11-05T17:30:19+00:00, book20_bid_proxy_usdt=91625, book20_ask_proxy_usdt=69249, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=47726427. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T17:30:01+00:00, last15m_closed_end=2026-11-05T17:30+00:00, prior8high=1.204000, depth_time=2026-11-05T17:30:09+00:00, book20_bid_proxy_usdt=2095582, book20_ask_proxy_usdt=1912674, funding_indicative=-0.000070, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.37%, turnover=33289224. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
