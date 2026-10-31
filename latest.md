# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T14:15:32Z**
- feed_generated_utc: 2026-10-31T14:15:34+00:00
- source_sha256: `b535a0a6a3bf2ba2dd7b0f01be6b07c5f1d6837d27ff13786afeb7f535977e68`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T14:15+00:00, close=77451, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T14:00+00:00, close=77477.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011839|-37.42|-66.17|-37.26|11657291|1.69|
|Q_USDT|0.032350|-31.86|-72.66|-31.70|11739245|3.09|
|HYPE_USDT|86.613000|-6.20|10.47|-6.04|96023469|0.12|
|BEAT_USDT|0.098830|-6.01|36.14|-5.85|6837451|1.01|
|TRX_USDT|0.316970|-5.52|-3.75|-5.36|6564624|0.32|
|BTW_USDT|1.135400|-5.34|-33.30|-5.18|8069998|1.76|
|WLD_USDT|0.395700|-3.93|-25.67|-3.77|39839379|2.53|
|FET_USDT|0.161000|-3.36|-14.04|-3.20|5845801|6.21|
|DASH_USDT|47.980000|-2.16|-10.90|-2.00|7871461|2.08|
|DOT_USDT|0.952100|-1.76|-15.50|-1.60|8405564|1.05|
|PEPE_USDT|0.000005|-1.69|2.33|-1.53|101156145|0.40|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011839|0.011295|0.011848|0.48|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.098830|0.098720|0.098810|1.01|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.135400|1.081300|1.134500|2.09|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.980000|47.750000|47.990000|0.67|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.952100|0.951100|0.952100|2.96|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161000|0.160400|0.160900|0.36|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|86.613000|86.975000|86.597000|1.67|Y|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.61|N|Y/N|N/N|Y|N|
|Q_USDT|0.032350|0.031490|0.032300|0.70|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.316970|0.317290|0.317000|0.44|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.395700|0.395100|0.395700|1.42|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T14:15:04+00:00, last15m_closed_end=2026-10-31T14:15+00:00, prior8high=0.012080, depth_time=2026-10-31T14:15:07+00:00, book20_bid_proxy_usdt=33328, book20_ask_proxy_usdt=8504, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-37.42%, turnover=11657291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T14:15:04+00:00, last15m_closed_end=2026-10-31T14:15+00:00, prior8high=0.101380, depth_time=2026-10-31T14:15:15+00:00, book20_bid_proxy_usdt=13428, book20_ask_proxy_usdt=11826, funding_indicative=0.000139, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.01%, turnover=6837451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T14:15:04+00:00, last15m_closed_end=2026-10-31T14:15+00:00, prior8high=1.201700, depth_time=2026-10-31T14:15:19+00:00, book20_bid_proxy_usdt=10809, book20_ask_proxy_usdt=23132, funding_indicative=-0.000295, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.34%, turnover=8069998. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T14:15:04+00:00, last15m_closed_end=2026-10-31T14:15+00:00, prior8high=48.210000, depth_time=2026-10-31T14:15:23+00:00, book20_bid_proxy_usdt=749748, book20_ask_proxy_usdt=737913, funding_indicative=-0.000144, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=7871461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-31T14:15:04+00:00, last15m_closed_end=2026-10-31T14:15+00:00, prior8high=0.958600, depth_time=2026-10-31T14:15:28+00:00, book20_bid_proxy_usdt=456304, book20_ask_proxy_usdt=518363, funding_indicative=0.000016, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=8405564. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T14:15:04+00:00, last15m_closed_end=2026-10-31T14:15+00:00, prior8high=0.161800, depth_time=2026-10-31T14:15:24+00:00, book20_bid_proxy_usdt=1637669, book20_ask_proxy_usdt=940339, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.36%, turnover=5845801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T14:15:04+00:00, last15m_closed_end=2026-10-31T14:15+00:00, prior8high=88.704000, depth_time=2026-10-31T14:15:13+00:00, book20_bid_proxy_usdt=43169, book20_ask_proxy_usdt=85035, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.20%, turnover=96023469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T14:15:04+00:00, last15m_closed_end=2026-10-31T14:15+00:00, prior8high=0.000005, depth_time=2026-10-31T14:15:31+00:00, book20_bid_proxy_usdt=26188, book20_ask_proxy_usdt=72962, funding_indicative=-0.000799, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=101156145. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T14:15:04+00:00, last15m_closed_end=2026-10-31T14:15+00:00, prior8high=0.032780, depth_time=2026-10-31T14:15:09+00:00, book20_bid_proxy_usdt=42798, book20_ask_proxy_usdt=33771, funding_indicative=-0.000485, next_funding_utc=2026-10-31T15:00:00+00:00, funding_cycle_h=1, 24h_change=-31.86%, turnover=11739245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T14:15:04+00:00, last15m_closed_end=2026-10-31T14:15+00:00, prior8high=0.322470, depth_time=2026-10-31T14:15:14+00:00, book20_bid_proxy_usdt=118598, book20_ask_proxy_usdt=62904, funding_indicative=-0.000728, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.52%, turnover=6564624. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T14:15:04+00:00, last15m_closed_end=2026-10-31T14:15+00:00, prior8high=0.399000, depth_time=2026-10-31T14:15:19+00:00, book20_bid_proxy_usdt=3187055, book20_ask_proxy_usdt=3157437, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.93%, turnover=39839379. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
