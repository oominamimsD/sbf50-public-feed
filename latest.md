# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T04:45:35Z**
- feed_generated_utc: 2026-10-26T04:45:38+00:00
- source_sha256: `639e72e83e6fd7f027040642db0de5d1bf5ec683f3eb91fc57e55f3c5bac1af1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T04:45+00:00, close=79971.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005630|-19.24|205.48|-18.46|11936582|7.11|
|APR_USDT|0.035680|-13.62|30.98|-12.84|12138792|2.80|
|T_USDT|0.004900|-8.97|4.21|-8.19|6438404|2.04|
|IRYS_USDT|0.035450|-7.77|190.57|-6.99|15835346|2.82|
|LIT_USDT|3.045900|-4.16|3.94|-3.38|6172694|0.33|
|WLD_USDT|0.441500|-3.30|-7.30|-2.52|73211781|2.27|
|DASH_USDT|50.960000|-2.76|6.43|-1.98|13829152|3.93|
|PUMPFUN_USDT|0.004171|-2.66|-0.57|-1.88|17569935|2.40|
|DOT_USDT|1.012600|-2.55|-5.31|-1.77|11183432|0.99|
|XMR_USDT|592.010000|-2.51|1.63|-1.73|6831950|1.52|
|STRK_USDT|0.044760|-2.14|-27.29|-1.36|9356358|2.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.035680|0.032590|0.035680|0.62|N|Y/Y|N/N|Y|N|
|DASH_USDT|50.960000|50.050000|50.960000|1.89|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.012600|1.012000|1.012600|0.72|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.035450|0.035450|0.035440|0.85|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005630|0.003891|0.005631|1.11|N|Y/Y|Y/N|Y|N|
|LIT_USDT|3.045900|3.000300|3.045900|2.29|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004171|0.004111|0.004171|0.73|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044760|0.044630|0.044760|0.41|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004900|0.004895|0.004917|0.49|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.441500|0.434800|0.441600|0.63|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|592.010000|588.690000|592.010000|0.09|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T04:45:00+00:00, last15m_closed_end=2026-10-26T04:45+00:00, prior8high=0.036370, depth_time=2026-10-26T04:45:10+00:00, book20_bid_proxy_usdt=84572, book20_ask_proxy_usdt=78250, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.62%, turnover=12138792. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T04:45:01+00:00, last15m_closed_end=2026-10-26T04:45+00:00, prior8high=50.880000, depth_time=2026-10-26T04:45:23+00:00, book20_bid_proxy_usdt=741700, book20_ask_proxy_usdt=639168, funding_indicative=0.000045, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=13829152. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T04:45:00+00:00, last15m_closed_end=2026-10-26T04:45+00:00, prior8high=1.026700, depth_time=2026-10-26T04:45:28+00:00, book20_bid_proxy_usdt=182292, book20_ask_proxy_usdt=598840, funding_indicative=-0.000076, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.55%, turnover=11183432. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T04:45:00+00:00, last15m_closed_end=2026-10-26T04:45+00:00, prior8high=0.039970, depth_time=2026-10-26T04:45:15+00:00, book20_bid_proxy_usdt=59249, book20_ask_proxy_usdt=51870, funding_indicative=-0.000842, next_funding_utc=2026-10-26T05:00:00+00:00, funding_cycle_h=1, 24h_change=-7.77%, turnover=15835346. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T04:45:00+00:00, last15m_closed_end=2026-10-26T04:45+00:00, prior8high=0.005751, depth_time=2026-10-26T04:45:08+00:00, book20_bid_proxy_usdt=13379, book20_ask_proxy_usdt=16589, funding_indicative=0.000306, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.24%, turnover=11936582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T04:45:01+00:00, last15m_closed_end=2026-10-26T04:45+00:00, prior8high=3.136000, depth_time=2026-10-26T04:45:18+00:00, book20_bid_proxy_usdt=23819, book20_ask_proxy_usdt=22480, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.16%, turnover=6172694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T04:45:01+00:00, last15m_closed_end=2026-10-26T04:45+00:00, prior8high=0.004203, depth_time=2026-10-26T04:45:26+00:00, book20_bid_proxy_usdt=2772464, book20_ask_proxy_usdt=2340683, funding_indicative=0.000048, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=17569935. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T04:45:01+00:00, last15m_closed_end=2026-10-26T04:45+00:00, prior8high=0.045440, depth_time=2026-10-26T04:45:34+00:00, book20_bid_proxy_usdt=974625, book20_ask_proxy_usdt=1021319, funding_indicative=0.000044, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.14%, turnover=9356358. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T04:45:00+00:00, last15m_closed_end=2026-10-26T04:45+00:00, prior8high=0.004998, depth_time=2026-10-26T04:45:11+00:00, book20_bid_proxy_usdt=61950, book20_ask_proxy_usdt=66527, funding_indicative=-0.001507, next_funding_utc=2026-10-26T05:00:00+00:00, funding_cycle_h=1, 24h_change=-8.97%, turnover=6438404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T04:45:00+00:00, last15m_closed_end=2026-10-26T04:45+00:00, prior8high=0.447400, depth_time=2026-10-26T04:45:20+00:00, book20_bid_proxy_usdt=2299123, book20_ask_proxy_usdt=2337180, funding_indicative=0.000066, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.30%, turnover=73211781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T04:45:01+00:00, last15m_closed_end=2026-10-26T04:45+00:00, prior8high=598.030000, depth_time=2026-10-26T04:45:31+00:00, book20_bid_proxy_usdt=7828, book20_ask_proxy_usdt=16591, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=6831950. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
