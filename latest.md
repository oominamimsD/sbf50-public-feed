# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T08:15:35Z**
- feed_generated_utc: 2026-10-26T08:15:39+00:00
- source_sha256: `edaae4e2d5052598aa413be6c21f296fb9ae800b901dd97cb7d4ed8b38cae5d3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T08:15+00:00, close=79706.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.029440|-23.41|141.31|-22.32|13119840|3.40|
|CAP_USDT|0.087140|-18.92|31.03|-17.83|6643518|5.74|
|APR_USDT|0.037170|-10.02|36.45|-8.93|8958643|5.37|
|BTW_USDT|1.542500|-7.01|-33.09|-5.92|10735706|1.30|
|WLD_USDT|0.436200|-4.46|-8.41|-3.37|68491318|2.29|
|XMR_USDT|583.640000|-3.88|0.19|-2.79|6199926|4.46|
|LIT_USDT|3.056400|-3.83|4.29|-2.74|5842196|0.33|
|DOT_USDT|1.004100|-3.37|-6.10|-2.28|10597509|1.00|
|PUMPFUN_USDT|0.004146|-3.24|-1.16|-2.15|16667804|2.41|
|DASH_USDT|50.880000|-2.91|6.26|-1.82|11794465|1.97|
|STRK_USDT|0.044500|-2.71|-27.71|-1.62|9804920|2.25|
|FET_USDT|0.171800|-2.38|-8.32|-1.29|5275040|5.82|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.037170|0.032200|0.037010|1.58|N|N/Y|N/N|Y|N|
|BTW_USDT|1.542500|1.578900|1.542500|2.95|Y|Y/Y|Y/Y|Y|Y|
|CAP_USDT|0.087140|0.087390|0.087140|1.60|Y|Y/Y|N/N|Y|N|
|DASH_USDT|50.880000|50.730000|50.870000|0.90|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.004100|1.002800|1.004100|1.67|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.171800|0.172600|0.171900|3.17|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.029440|0.029600|0.029410|2.86|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|3.056400|3.061100|3.056400|0.25|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004146|0.004140|0.004145|1.25|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044500|0.044160|0.044500|0.97|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.436200|0.434900|0.436200|1.45|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|583.640000|584.290000|583.640000|0.63|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T08:15:01+00:00, last15m_closed_end=2026-10-26T08:15+00:00, prior8high=0.039060, depth_time=2026-10-26T08:15:12+00:00, book20_bid_proxy_usdt=25408, book20_ask_proxy_usdt=55982, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.02%, turnover=8958643. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T08:15:01+00:00, last15m_closed_end=2026-10-26T08:15+00:00, prior8high=1.648900, depth_time=2026-10-26T08:15:15+00:00, book20_bid_proxy_usdt=12634, book20_ask_proxy_usdt=16352, funding_indicative=-0.004256, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.01%, turnover=10735706. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T08:15:01+00:00, last15m_closed_end=2026-10-26T08:15+00:00, prior8high=0.111390, depth_time=2026-10-26T08:15:10+00:00, book20_bid_proxy_usdt=55206, book20_ask_proxy_usdt=61545, funding_indicative=0.000438, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.92%, turnover=6643518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T08:15:02+00:00, last15m_closed_end=2026-10-26T08:15+00:00, prior8high=51.350000, depth_time=2026-10-26T08:15:29+00:00, book20_bid_proxy_usdt=524852, book20_ask_proxy_usdt=626550, funding_indicative=0.000030, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=11794465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T08:15:02+00:00, last15m_closed_end=2026-10-26T08:15+00:00, prior8high=1.016100, depth_time=2026-10-26T08:15:22+00:00, book20_bid_proxy_usdt=406838, book20_ask_proxy_usdt=301168, funding_indicative=-0.000103, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.37%, turnover=10597509. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-26T08:15:02+00:00, last15m_closed_end=2026-10-26T08:15+00:00, prior8high=0.175500, depth_time=2026-10-26T08:15:34+00:00, book20_bid_proxy_usdt=1523310, book20_ask_proxy_usdt=1040034, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=5275040. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T08:15:01+00:00, last15m_closed_end=2026-10-26T08:15+00:00, prior8high=0.033830, depth_time=2026-10-26T08:15:08+00:00, book20_bid_proxy_usdt=45605, book20_ask_proxy_usdt=78624, funding_indicative=-0.000120, next_funding_utc=2026-10-26T09:00:00+00:00, funding_cycle_h=1, 24h_change=-23.41%, turnover=13119840. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T08:15:02+00:00, last15m_closed_end=2026-10-26T08:15+00:00, prior8high=3.131600, depth_time=2026-10-26T08:15:21+00:00, book20_bid_proxy_usdt=19002, book20_ask_proxy_usdt=17949, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.83%, turnover=5842196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T08:15:02+00:00, last15m_closed_end=2026-10-26T08:15+00:00, prior8high=0.004233, depth_time=2026-10-26T08:15:26+00:00, book20_bid_proxy_usdt=1775294, book20_ask_proxy_usdt=2928852, funding_indicative=-0.000017, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.24%, turnover=16667804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T08:15:02+00:00, last15m_closed_end=2026-10-26T08:15+00:00, prior8high=0.045270, depth_time=2026-10-26T08:15:31+00:00, book20_bid_proxy_usdt=1067541, book20_ask_proxy_usdt=799667, funding_indicative=0.000021, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=9804920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T08:15:01+00:00, last15m_closed_end=2026-10-26T08:15+00:00, prior8high=0.442700, depth_time=2026-10-26T08:15:17+00:00, book20_bid_proxy_usdt=2730187, book20_ask_proxy_usdt=2649139, funding_indicative=-0.000070, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.46%, turnover=68491318. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T08:15:02+00:00, last15m_closed_end=2026-10-26T08:15+00:00, prior8high=590.640000, depth_time=2026-10-26T08:15:20+00:00, book20_bid_proxy_usdt=7475, book20_ask_proxy_usdt=12707, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.88%, turnover=6199926. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
