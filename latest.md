# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T07:45:45Z**
- feed_generated_utc: 2026-10-26T07:45:48+00:00
- source_sha256: `a04550fa23120ea61990b280bbf0a191a35e8c9153bd0bc151d1841c608bd1cd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T07:45+00:00, close=80085, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T07:00+00:00, close=80093.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CAP_USDT|0.089530|-16.70|34.63|-16.06|6587907|5.57|
|APR_USDT|0.035800|-13.33|31.42|-12.69|9344908|2.80|
|T_USDT|0.004788|-11.05|1.82|-10.41|5529981|2.09|
|WLD_USDT|0.437000|-4.29|-8.25|-3.65|69312340|2.29|
|XMR_USDT|586.290000|-3.45|0.65|-2.81|6360427|0.17|
|BTW_USDT|1.607600|-3.09|-30.26|-2.45|11096870|1.25|
|DOT_USDT|1.008300|-2.97|-5.71|-2.33|10724121|0.99|
|PUMPFUN_USDT|0.004158|-2.96|-0.88|-2.32|16777489|2.40|
|LIT_USDT|3.088700|-2.82|5.40|-2.18|6018714|0.32|
|DASH_USDT|51.010000|-2.67|6.53|-2.03|11915577|1.96|
|STRK_USDT|0.044520|-2.66|-27.68|-2.02|10101477|2.25|
|NEAR_USDT|4.458000|-1.89|-5.90|-1.25|132160869|2.24|
|TIA_USDT|0.527200|-1.84|-14.67|-1.20|18083539|3.79|
|INJ_USDT|7.569000|-1.75|-6.79|-1.11|25899515|1.32|
|FET_USDT|0.173000|-1.70|-7.68|-1.06|5279729|5.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.035800|0.032200|0.035800|1.18|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.607600|1.578900|1.607600|0.82|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.089530|0.091760|0.089530|2.48|Y|Y/N|N/N|Y|N|
|DASH_USDT|51.010000|50.790000|51.010000|0.07|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.008300|1.002800|1.008300|1.95|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.173000|0.173500|0.173000|5.76|Y|Y/Y|Y/Y|Y|Y|
|INJ_USDT|7.569000|7.528000|7.569000|0.94|N|Y/Y|Y/N|Y|N|
|LIT_USDT|3.088700|3.061300|3.088700|1.33|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.458000|4.442000|4.458000|1.52|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004158|0.004163|0.004158|2.62|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.044520|0.044490|0.044520|7.03|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.527200|0.519000|0.527200|3.28|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004788|0.004788|0.004788|1.04|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.437000|0.436400|0.437000|1.37|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|586.290000|584.290000|586.290000|2.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T07:44:59+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=0.037240, depth_time=2026-10-26T07:45:11+00:00, book20_bid_proxy_usdt=28824, book20_ask_proxy_usdt=43134, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.33%, turnover=9344908. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T07:45:00+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=1.667700, depth_time=2026-10-26T07:45:21+00:00, book20_bid_proxy_usdt=9805, book20_ask_proxy_usdt=11747, funding_indicative=-0.003989, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.09%, turnover=11096870. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T07:44:59+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=0.114130, depth_time=2026-10-26T07:45:09+00:00, book20_bid_proxy_usdt=58870, book20_ask_proxy_usdt=60567, funding_indicative=0.000542, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.70%, turnover=6587907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T07:45:00+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=51.350000, depth_time=2026-10-26T07:45:28+00:00, book20_bid_proxy_usdt=779311, book20_ask_proxy_usdt=558983, funding_indicative=0.000025, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.67%, turnover=11915577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T07:45:00+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=1.019800, depth_time=2026-10-26T07:45:24+00:00, book20_bid_proxy_usdt=254525, book20_ask_proxy_usdt=197358, funding_indicative=-0.000121, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=10724121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-26T07:45:00+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=0.175500, depth_time=2026-10-26T07:45:44+00:00, book20_bid_proxy_usdt=1655210, book20_ask_proxy_usdt=918195, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=5279729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-26T07:45:00+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=7.711000, depth_time=2026-10-26T07:45:41+00:00, book20_bid_proxy_usdt=219146, book20_ask_proxy_usdt=241651, funding_indicative=0.000102, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=25899515. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T07:45:00+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=3.131600, depth_time=2026-10-26T07:45:27+00:00, book20_bid_proxy_usdt=20537, book20_ask_proxy_usdt=15413, funding_indicative=0.000040, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.82%, turnover=6018714. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T07:45:00+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=4.537000, depth_time=2026-10-26T07:45:36+00:00, book20_bid_proxy_usdt=2787441, book20_ask_proxy_usdt=5330161, funding_indicative=0.000038, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=132160869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T07:45:00+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=0.004233, depth_time=2026-10-26T07:45:26+00:00, book20_bid_proxy_usdt=2262965, book20_ask_proxy_usdt=1967626, funding_indicative=-0.000024, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.96%, turnover=16777489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T07:45:00+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=0.045270, depth_time=2026-10-26T07:45:33+00:00, book20_bid_proxy_usdt=902979, book20_ask_proxy_usdt=620197, funding_indicative=0.000013, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=10101477. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-26T07:45:00+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=0.533000, depth_time=2026-10-26T07:45:39+00:00, book20_bid_proxy_usdt=199400, book20_ask_proxy_usdt=285046, funding_indicative=-0.000016, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.84%, turnover=18083539. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T07:45:00+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=0.004881, depth_time=2026-10-26T07:45:13+00:00, book20_bid_proxy_usdt=68466, book20_ask_proxy_usdt=73212, funding_indicative=-0.000595, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=1, 24h_change=-11.05%, turnover=5529981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T07:45:00+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=0.445600, depth_time=2026-10-26T07:45:16+00:00, book20_bid_proxy_usdt=2054052, book20_ask_proxy_usdt=2409712, funding_indicative=-0.000078, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.29%, turnover=69312340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T07:45:00+00:00, last15m_closed_end=2026-10-26T07:45+00:00, prior8high=591.270000, depth_time=2026-10-26T07:45:18+00:00, book20_bid_proxy_usdt=5138, book20_ask_proxy_usdt=18556, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=6360427. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
