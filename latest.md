# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T04:30:34Z**
- feed_generated_utc: 2026-10-26T04:30:37+00:00
- source_sha256: `7a74533aec2fd7e21ecb54075f7e0f0805352e116a7cce391b97c266ea7292d9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T04:30+00:00, close=79905.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|APR_USDT|0.035260|-14.64|29.44|-13.78|12120311|5.67|
|T_USDT|0.004912|-8.74|4.46|-7.88|6435144|2.04|
|IRYS_USDT|0.035850|-6.73|193.85|-5.87|15749112|2.79|
|LIT_USDT|3.010300|-5.28|2.72|-4.42|6089924|0.33|
|WLD_USDT|0.440300|-3.56|-7.55|-2.70|72927947|2.27|
|DASH_USDT|50.650000|-3.35|5.78|-2.49|13674980|1.97|
|PUMPFUN_USDT|0.004156|-3.01|-0.92|-2.15|17492466|2.41|
|XMR_USDT|592.450000|-2.43|1.70|-1.57|6827801|0.17|
|STRK_USDT|0.044690|-2.29|-27.40|-1.43|9343495|2.24|
|HYPE_USDT|75.429000|-2.03|-2.72|-1.17|29780404|0.53|
|DOT_USDT|1.018200|-2.02|-4.78|-1.16|11131590|0.98|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.035260|0.032120|0.035260|1.41|N|Y/Y|N/N|Y|N|
|DASH_USDT|50.650000|50.050000|50.650000|0.20|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.018200|1.012000|1.018200|0.37|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|75.429000|74.954000|75.429000|0.74|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.035850|0.035450|0.035870|0.50|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.010300|3.000800|3.010300|4.68|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004156|0.004111|0.004156|1.23|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044690|0.044650|0.044690|1.60|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004912|0.004895|0.004912|0.86|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.440300|0.434800|0.440400|0.99|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|592.450000|588.690000|592.450000|1.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T04:30:03+00:00, last15m_closed_end=2026-10-26T04:30+00:00, prior8high=0.036370, depth_time=2026-10-26T04:30:08+00:00, book20_bid_proxy_usdt=61029, book20_ask_proxy_usdt=91670, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.64%, turnover=12120311. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T04:30:00+00:00, last15m_closed_end=2026-10-26T04:30+00:00, prior8high=50.890000, depth_time=2026-10-26T04:30:19+00:00, book20_bid_proxy_usdt=490479, book20_ask_proxy_usdt=680582, funding_indicative=0.000037, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.35%, turnover=13674980. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T04:30:00+00:00, last15m_closed_end=2026-10-26T04:30+00:00, prior8high=1.026700, depth_time=2026-10-26T04:30:32+00:00, book20_bid_proxy_usdt=345469, book20_ask_proxy_usdt=485364, funding_indicative=-0.000083, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.02%, turnover=11131590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-26T04:30:00+00:00, last15m_closed_end=2026-10-26T04:30+00:00, prior8high=76.230000, depth_time=2026-10-26T04:30:30+00:00, book20_bid_proxy_usdt=129348, book20_ask_proxy_usdt=80270, funding_indicative=0.000019, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.03%, turnover=29780404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T04:30:03+00:00, last15m_closed_end=2026-10-26T04:30+00:00, prior8high=0.039970, depth_time=2026-10-26T04:30:11+00:00, book20_bid_proxy_usdt=56064, book20_ask_proxy_usdt=40537, funding_indicative=-0.000738, next_funding_utc=2026-10-26T05:00:00+00:00, funding_cycle_h=1, 24h_change=-6.73%, turnover=15749112. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T04:30:00+00:00, last15m_closed_end=2026-10-26T04:30+00:00, prior8high=3.151600, depth_time=2026-10-26T04:30:15+00:00, book20_bid_proxy_usdt=26418, book20_ask_proxy_usdt=33617, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.28%, turnover=6089924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T04:30:00+00:00, last15m_closed_end=2026-10-26T04:30+00:00, prior8high=0.004203, depth_time=2026-10-26T04:30:22+00:00, book20_bid_proxy_usdt=2490957, book20_ask_proxy_usdt=2844199, funding_indicative=0.000049, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=17492466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T04:30:00+00:00, last15m_closed_end=2026-10-26T04:30+00:00, prior8high=0.045490, depth_time=2026-10-26T04:30:27+00:00, book20_bid_proxy_usdt=1106036, book20_ask_proxy_usdt=856029, funding_indicative=0.000047, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.29%, turnover=9343495. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T04:30:00+00:00, last15m_closed_end=2026-10-26T04:30+00:00, prior8high=0.004998, depth_time=2026-10-26T04:30:10+00:00, book20_bid_proxy_usdt=60281, book20_ask_proxy_usdt=57732, funding_indicative=-0.001563, next_funding_utc=2026-10-26T05:00:00+00:00, funding_cycle_h=1, 24h_change=-8.74%, turnover=6435144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T04:30:03+00:00, last15m_closed_end=2026-10-26T04:30+00:00, prior8high=0.447400, depth_time=2026-10-26T04:30:17+00:00, book20_bid_proxy_usdt=2636499, book20_ask_proxy_usdt=2353596, funding_indicative=0.000079, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.56%, turnover=72927947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T04:30:00+00:00, last15m_closed_end=2026-10-26T04:30+00:00, prior8high=598.030000, depth_time=2026-10-26T04:30:24+00:00, book20_bid_proxy_usdt=30128, book20_ask_proxy_usdt=9833, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=6827801. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
