# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T23:15:40Z**
- feed_generated_utc: 2026-10-26T23:15:44+00:00
- source_sha256: `ebe8e192b7df50c3bb0311787550312fe90b715c59015c78a6c10f7d848f75a1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T23:15+00:00, close=79841.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T23:00+00:00, close=79977.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.617700|-5.23|-14.94|-4.55|5369733|0.62|
|QNT_USDT|201.110000|-4.36|2.76|-3.68|118370540|0.50|
|LIT_USDT|2.982800|-4.34|-1.61|-3.66|5074646|0.34|
|BR_USDT|0.482000|-3.50|-21.75|-2.82|10273806|4.15|
|NEAR_USDT|4.460000|-2.47|-9.05|-1.79|112961119|2.24|
|PEPE_USDT|0.000004|-2.19|3.82|-1.51|79456286|0.23|
|FILECOIN_USDT|0.900800|-2.16|-10.98|-1.48|6424025|1.11|
|ARB_USDT|0.166500|-2.05|-14.89|-1.37|20251587|0.60|
|LINK_USDT|11.301000|-1.96|-5.37|-1.28|99053226|0.89|
|DOT_USDT|1.003700|-1.84|-12.47|-1.16|10415524|1.00|
|FET_USDT|0.173400|-1.81|-8.25|-1.13|6485660|5.76|
|PENGU_USDT|0.007442|-1.74|-0.65|-1.06|5925421|1.34|
|TAO_USDT|249.100000|-1.73|-7.15|-1.05|47186736|0.80|
|BTW_USDT|1.175400|-1.69|-32.91|-1.01|21118803|0.85|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.166500|0.166370|0.166500|1.57|N|Y/Y|Y/Y|Y|N|
|BR_USDT|0.482000|0.473300|0.482000|0.65|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.175400|1.123800|1.175400|0.44|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.003700|0.999300|1.003700|0.49|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.173400|0.172200|0.173400|3.46|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.900800|0.895300|0.900800|2.22|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.301000|11.293000|11.301000|1.53|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.982800|2.972000|2.982800|0.25|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.460000|4.437000|4.460000|1.09|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007442|0.007419|0.007442|1.94|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|2.13|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|201.110000|200.670000|201.090000|1.40|N|Y/N|N/N|Y|N|
|TAO_USDT|249.100000|248.420000|249.100000|1.58|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.617700|1.609100|1.617700|0.22|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-26T23:15:01+00:00, last15m_closed_end=2026-10-26T23:15+00:00, prior8high=0.168330, depth_time=2026-10-26T23:15:23+00:00, book20_bid_proxy_usdt=56478, book20_ask_proxy_usdt=81239, funding_indicative=-0.000018, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=20251587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-26T23:15:01+00:00, last15m_closed_end=2026-10-26T23:15+00:00, prior8high=0.487600, depth_time=2026-10-26T23:15:15+00:00, book20_bid_proxy_usdt=41582, book20_ask_proxy_usdt=37912, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.50%, turnover=10273806. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T23:15:01+00:00, last15m_closed_end=2026-10-26T23:15+00:00, prior8high=1.218200, depth_time=2026-10-26T23:15:40+00:00, book20_bid_proxy_usdt=32466, book20_ask_proxy_usdt=41961, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.69%, turnover=21118803. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T23:15:01+00:00, last15m_closed_end=2026-10-26T23:15+00:00, prior8high=1.011200, depth_time=2026-10-26T23:15:29+00:00, book20_bid_proxy_usdt=258851, book20_ask_proxy_usdt=652239, funding_indicative=-0.000059, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=10415524. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-26T23:15:01+00:00, last15m_closed_end=2026-10-26T23:15+00:00, prior8high=0.174900, depth_time=2026-10-26T23:15:31+00:00, book20_bid_proxy_usdt=1941920, book20_ask_proxy_usdt=1010727, funding_indicative=0.000090, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=6485660. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T23:15:01+00:00, last15m_closed_end=2026-10-26T23:15+00:00, prior8high=0.909400, depth_time=2026-10-26T23:15:21+00:00, book20_bid_proxy_usdt=891424, book20_ask_proxy_usdt=1068709, funding_indicative=0.000071, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=6424025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-26T23:15:01+00:00, last15m_closed_end=2026-10-26T23:15+00:00, prior8high=11.397000, depth_time=2026-10-26T23:15:24+00:00, book20_bid_proxy_usdt=491241, book20_ask_proxy_usdt=504942, funding_indicative=0.000093, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=99053226. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T23:15:01+00:00, last15m_closed_end=2026-10-26T23:15+00:00, prior8high=3.019000, depth_time=2026-10-26T23:15:12+00:00, book20_bid_proxy_usdt=19212, book20_ask_proxy_usdt=22388, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.34%, turnover=5074646. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T23:15:01+00:00, last15m_closed_end=2026-10-26T23:15+00:00, prior8high=4.492000, depth_time=2026-10-26T23:15:15+00:00, book20_bid_proxy_usdt=5093582, book20_ask_proxy_usdt=4018187, funding_indicative=0.000055, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=112961119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-26T23:15:01+00:00, last15m_closed_end=2026-10-26T23:15+00:00, prior8high=0.007494, depth_time=2026-10-26T23:15:35+00:00, book20_bid_proxy_usdt=167887, book20_ask_proxy_usdt=313144, funding_indicative=0.000022, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=5925421. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T23:15:01+00:00, last15m_closed_end=2026-10-26T23:15+00:00, prior8high=0.000004, depth_time=2026-10-26T23:15:19+00:00, book20_bid_proxy_usdt=60233, book20_ask_proxy_usdt=48167, funding_indicative=0.000089, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=79456286. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-26T23:15:01+00:00, last15m_closed_end=2026-10-26T23:15+00:00, prior8high=204.690000, depth_time=2026-10-26T23:15:09+00:00, book20_bid_proxy_usdt=70989, book20_ask_proxy_usdt=65980, funding_indicative=-0.000013, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.36%, turnover=118370540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-26T23:15:01+00:00, last15m_closed_end=2026-10-26T23:15+00:00, prior8high=250.750000, depth_time=2026-10-26T23:15:37+00:00, book20_bid_proxy_usdt=86393, book20_ask_proxy_usdt=181096, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.73%, turnover=47186736. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-26T23:15:01+00:00, last15m_closed_end=2026-10-26T23:15+00:00, prior8high=1.643300, depth_time=2026-10-26T23:15:07+00:00, book20_bid_proxy_usdt=36212, book20_ask_proxy_usdt=49145, funding_indicative=-0.000006, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.23%, turnover=5369733. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
