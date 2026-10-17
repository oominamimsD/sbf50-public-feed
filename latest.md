# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T04:45:28Z**
- feed_generated_utc: 2026-10-17T04:45:30+00:00
- source_sha256: `651b0b683ed4778633f3a42ffd6281443a45c760cd2d66535c44d37038638614`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T04:45+00:00, close=81531.5, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.977400|-5.89|-2.91|-6.14|14640323|0.51|
|RIVER_USDT|1.084000|-3.73|-8.29|-3.98|5132759|9.21|
|BAT_USDT|0.197890|-3.48|62.65|-3.73|14541540|3.54|
|STRK_USDT|0.071620|-3.15|-4.89|-3.40|21841339|1.40|
|ZEC_USDT|1155.860000|-2.70|-5.13|-2.95|1387459502|0.09|
|ARB_USDT|0.190850|-2.09|5.55|-2.34|33085985|1.05|
|FET_USDT|0.195800|-1.90|-9.76|-2.15|11467215|5.11|
|TAO_USDT|276.500000|-1.46|0.66|-1.71|76865294|1.08|
|AVAX_USDT|10.002000|-0.80|-1.86|-1.05|121782141|1.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.190850|0.187590|0.190850|0.93|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|10.002000|9.933000|10.000000|0.79|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.197890|0.196790|0.197890|1.86|N|N/N|N/N|Y|N|
|FET_USDT|0.195800|0.194100|0.195800|0.74|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.084000|1.071000|1.084000|0.32|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.071620|0.069640|0.071620|0.37|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|276.500000|273.190000|276.500000|1.11|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1155.860000|1140.370000|1155.860000|0.96|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.977400|1.943800|1.977300|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T04:45:01+00:00, last15m_closed_end=2026-10-17T04:45+00:00, prior8high=0.190460, depth_time=2026-10-17T04:45:20+00:00, book20_bid_proxy_usdt=81286, book20_ask_proxy_usdt=75530, funding_indicative=-0.000024, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=33085985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T04:45:01+00:00, last15m_closed_end=2026-10-17T04:45+00:00, prior8high=10.018000, depth_time=2026-10-17T04:45:27+00:00, book20_bid_proxy_usdt=653458, book20_ask_proxy_usdt=617109, funding_indicative=0.000075, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.80%, turnover=121782141. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T04:45:01+00:00, last15m_closed_end=2026-10-17T04:45+00:00, prior8high=0.203660, depth_time=2026-10-17T04:45:12+00:00, book20_bid_proxy_usdt=29141, book20_ask_proxy_usdt=26548, funding_indicative=-0.000025, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=14541540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T04:45:01+00:00, last15m_closed_end=2026-10-17T04:45+00:00, prior8high=0.196500, depth_time=2026-10-17T04:45:23+00:00, book20_bid_proxy_usdt=1477427, book20_ask_proxy_usdt=1279201, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=11467215. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T04:45:01+00:00, last15m_closed_end=2026-10-17T04:45+00:00, prior8high=1.090000, depth_time=2026-10-17T04:45:09+00:00, book20_bid_proxy_usdt=514138, book20_ask_proxy_usdt=420259, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.73%, turnover=5132759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T04:45:01+00:00, last15m_closed_end=2026-10-17T04:45+00:00, prior8high=0.072390, depth_time=2026-10-17T04:45:16+00:00, book20_bid_proxy_usdt=391063, book20_ask_proxy_usdt=343896, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.15%, turnover=21841339. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T04:45:01+00:00, last15m_closed_end=2026-10-17T04:45+00:00, prior8high=277.190000, depth_time=2026-10-17T04:45:23+00:00, book20_bid_proxy_usdt=84187, book20_ask_proxy_usdt=70580, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.46%, turnover=76865294. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T04:45:01+00:00, last15m_closed_end=2026-10-17T04:45+00:00, prior8high=1160.600000, depth_time=2026-10-17T04:45:18+00:00, book20_bid_proxy_usdt=533935, book20_ask_proxy_usdt=1488817, funding_indicative=0.000033, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=1387459502. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T04:45:01+00:00, last15m_closed_end=2026-10-17T04:45+00:00, prior8high=1.986600, depth_time=2026-10-17T04:45:08+00:00, book20_bid_proxy_usdt=57484, book20_ask_proxy_usdt=41990, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.89%, turnover=14640323. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
