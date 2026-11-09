# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T09:00:33Z**
- feed_generated_utc: 2026-11-09T09:00:34+00:00
- source_sha256: `babad49998cad4f6441a317fa354f4787979ea0f2e575b19c278ae2cce3964df`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T09:00+00:00, close=74524.7, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T09:00+00:00, close=74524.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T08:00+00:00, close=73840.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001578|-19.41|35.50|-17.42|9279046|0.63|
|JCT_USDT|0.008600|-12.54|72.72|-10.55|72757388|6.97|
|AKE_USDT|0.004693|-12.39|-48.76|-10.40|11059668|2.13|
|ASTER_USDT|0.636500|-6.36|-8.99|-4.37|5419093|1.57|
|ETH_USDT|2122.210000|-5.30|-6.33|-3.31|1478147097|0.05|
|XRP_USDT|1.097600|-5.03|-12.18|-3.04|263945574|0.91|
|HYPE_USDT|74.007000|-4.42|-15.60|-2.43|46105984|0.14|
|PUMPFUN_USDT|0.003575|-4.33|-15.24|-2.34|10203244|2.80|
|NEAR_USDT|3.557000|-3.89|-17.87|-1.90|42800724|2.81|
|UNI_USDT|6.760000|-3.46|-6.83|-1.47|29389309|1.48|
|XLM_USDT|0.146360|-3.20|-13.06|-1.21|27912546|0.68|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004693|0.004511|0.004693|1.74|N|Y/Y|Y/Y|Y|N|
|ASTER_USDT|0.636500|0.624700|0.636500|0.25|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2122.210000|2081.410000|2122.220000|1.26|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|74.007000|72.442000|74.001000|1.58|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008600|0.007376|0.008599|0.63|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.557000|3.460000|3.557000|2.17|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001578|0.001562|0.001578|2.07|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003575|0.003485|0.003575|0.48|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.760000|6.646000|6.760000|2.95|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.146360|0.143780|0.146360|0.92|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.097600|1.081600|1.097600|0.44|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T08:59:59+00:00, last15m_closed_end=2026-11-09T09:00+00:00, prior8high=0.004675, depth_time=2026-11-09T09:00:11+00:00, book20_bid_proxy_usdt=59928, book20_ask_proxy_usdt=43578, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.39%, turnover=11059668. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T08:59:59+00:00, last15m_closed_end=2026-11-09T09:00+00:00, prior8high=0.635700, depth_time=2026-11-09T09:00:14+00:00, book20_bid_proxy_usdt=616068, book20_ask_proxy_usdt=537654, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.36%, turnover=5419093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T08:59:59+00:00, last15m_closed_end=2026-11-09T09:00+00:00, prior8high=2116.200000, depth_time=2026-11-09T09:00:16+00:00, book20_bid_proxy_usdt=5287587, book20_ask_proxy_usdt=2635774, funding_indicative=-0.000030, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.30%, turnover=1478147097. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T08:59:59+00:00, last15m_closed_end=2026-11-09T09:00+00:00, prior8high=74.267000, depth_time=2026-11-09T09:00:21+00:00, book20_bid_proxy_usdt=76092, book20_ask_proxy_usdt=125319, funding_indicative=0.000044, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.42%, turnover=46105984. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T08:59:59+00:00, last15m_closed_end=2026-11-09T09:00+00:00, prior8high=0.010326, depth_time=2026-11-09T09:00:09+00:00, book20_bid_proxy_usdt=21391, book20_ask_proxy_usdt=28688, funding_indicative=0.001249, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.54%, turnover=72757388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T08:59:59+00:00, last15m_closed_end=2026-11-09T09:00+00:00, prior8high=3.563000, depth_time=2026-11-09T09:00:26+00:00, book20_bid_proxy_usdt=2465256, book20_ask_proxy_usdt=2505984, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.89%, turnover=42800724. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T08:59:59+00:00, last15m_closed_end=2026-11-09T09:00+00:00, prior8high=0.001636, depth_time=2026-11-09T09:00:06+00:00, book20_bid_proxy_usdt=14592, book20_ask_proxy_usdt=8081, funding_indicative=-0.000069, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.41%, turnover=9279046. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T08:59:59+00:00, last15m_closed_end=2026-11-09T09:00+00:00, prior8high=0.003566, depth_time=2026-11-09T09:00:22+00:00, book20_bid_proxy_usdt=2856308, book20_ask_proxy_usdt=2648150, funding_indicative=0.000039, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.33%, turnover=10203244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-09T08:59:59+00:00, last15m_closed_end=2026-11-09T09:00+00:00, prior8high=6.793000, depth_time=2026-11-09T09:00:26+00:00, book20_bid_proxy_usdt=2292408, book20_ask_proxy_usdt=2561065, funding_indicative=0.000049, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.46%, turnover=29389309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-09T08:59:59+00:00, last15m_closed_end=2026-11-09T09:00+00:00, prior8high=0.145970, depth_time=2026-11-09T09:00:30+00:00, book20_bid_proxy_usdt=99017, book20_ask_proxy_usdt=185592, funding_indicative=0.000040, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.20%, turnover=27912546. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T08:59:59+00:00, last15m_closed_end=2026-11-09T09:00+00:00, prior8high=1.098500, depth_time=2026-11-09T09:00:18+00:00, book20_bid_proxy_usdt=3122604, book20_ask_proxy_usdt=3907355, funding_indicative=0.000068, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.03%, turnover=263945574. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
