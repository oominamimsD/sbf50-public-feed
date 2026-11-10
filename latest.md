# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T04:30:27Z**
- feed_generated_utc: 2026-11-10T04:30:28+00:00
- source_sha256: `7ec572f4d9dd5957560d6296abd442371030e05136f108f934dca9a7c21f356c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T04:30+00:00, close=74799.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002756|-43.72|-49.90|-42.80|15367672|7.24|
|JCT_USDT|0.008010|-20.93|85.54|-20.01|27289730|3.75|
|ARB_USDT|0.171630|-6.74|7.71|-5.82|32220919|1.75|
|ZEC_USDT|1156.780000|-5.62|-7.76|-4.70|2414261950|0.09|
|QNT_USDT|191.430000|-4.30|-5.44|-3.38|36761413|0.52|
|DOT_USDT|0.853700|-4.17|-8.60|-3.25|10936185|1.17|
|AAVE_USDT|127.840000|-4.13|-2.08|-3.21|13604316|0.78|
|DASH_USDT|46.320000|-2.72|-1.86|-1.80|14277139|2.16|
|SOL_USDT|86.170000|-1.95|-7.84|-1.03|640935602|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.840000|127.510000|127.840000|1.86|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002756|0.002302|0.002753|0.40|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.171630|0.170950|0.171630|0.67|N|Y/Y|N/N|Y|N|
|DASH_USDT|46.320000|45.750000|46.320000|0.82|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.853700|0.846300|0.853700|1.23|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008010|0.007903|0.008040|1.67|N|Y/Y|N/N|Y|N|
|QNT_USDT|191.430000|190.530000|191.430000|1.06|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.170000|85.470000|86.170000|3.44|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1156.780000|1141.980000|1156.780000|0.96|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T04:30:01+00:00, last15m_closed_end=2026-11-10T04:30+00:00, prior8high=131.680000, depth_time=2026-11-10T04:30:21+00:00, book20_bid_proxy_usdt=448632, book20_ask_proxy_usdt=396200, funding_indicative=0.000013, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.13%, turnover=13604316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T04:30:00+00:00, last15m_closed_end=2026-11-10T04:30+00:00, prior8high=0.002802, depth_time=2026-11-10T04:30:07+00:00, book20_bid_proxy_usdt=30728, book20_ask_proxy_usdt=40243, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-43.72%, turnover=15367672. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T04:30:00+00:00, last15m_closed_end=2026-11-10T04:30+00:00, prior8high=0.173580, depth_time=2026-11-10T04:30:12+00:00, book20_bid_proxy_usdt=67246, book20_ask_proxy_usdt=64496, funding_indicative=-0.000002, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.74%, turnover=32220919. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T04:30:01+00:00, last15m_closed_end=2026-11-10T04:30+00:00, prior8high=46.380000, depth_time=2026-11-10T04:30:23+00:00, book20_bid_proxy_usdt=537233, book20_ask_proxy_usdt=570218, funding_indicative=-0.000007, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.72%, turnover=14277139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T04:30:01+00:00, last15m_closed_end=2026-11-10T04:30+00:00, prior8high=0.854600, depth_time=2026-11-10T04:30:19+00:00, book20_bid_proxy_usdt=519697, book20_ask_proxy_usdt=627753, funding_indicative=0.000064, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.17%, turnover=10936185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T04:30:00+00:00, last15m_closed_end=2026-11-10T04:30+00:00, prior8high=0.009348, depth_time=2026-11-10T04:30:10+00:00, book20_bid_proxy_usdt=12213, book20_ask_proxy_usdt=13594, funding_indicative=0.000302, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-20.93%, turnover=27289730. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T04:30:01+00:00, last15m_closed_end=2026-11-10T04:30+00:00, prior8high=194.060000, depth_time=2026-11-10T04:30:17+00:00, book20_bid_proxy_usdt=80891, book20_ask_proxy_usdt=105686, funding_indicative=-0.000039, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.30%, turnover=36761413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T04:30:00+00:00, last15m_closed_end=2026-11-10T04:30+00:00, prior8high=86.240000, depth_time=2026-11-10T04:30:26+00:00, book20_bid_proxy_usdt=18257690, book20_ask_proxy_usdt=18016072, funding_indicative=-0.000004, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=640935602. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T04:30:00+00:00, last15m_closed_end=2026-11-10T04:30+00:00, prior8high=1164.970000, depth_time=2026-11-10T04:30:15+00:00, book20_bid_proxy_usdt=342630, book20_ask_proxy_usdt=284980, funding_indicative=0.000066, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.62%, turnover=2414261950. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
