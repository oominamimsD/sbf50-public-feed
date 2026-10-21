# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T06:15:21Z**
- feed_generated_utc: 2026-10-21T06:15:24+00:00
- source_sha256: `6625c7645a0c1683c3b0bea09ce0c84808a967e99f545bd7ca01011893e7259e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T06:15+00:00, close=82629.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T06:00+00:00, close=82635.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.183470|-14.96|3.43|-15.02|10823014|2.73|
|AGT_USDT|0.055793|-13.67|244.89|-13.73|6331358|5.58|
|BR_USDT|0.584350|-10.19|34.95|-10.25|33325716|0.17|
|XMR_USDT|577.080000|-6.95|9.31|-7.01|21160962|0.52|
|PHA_USDT|0.056810|-1.74|3.23|-1.80|6780193|3.52|
|FILECOIN_USDT|1.025000|-1.44|-9.54|-1.50|9766327|0.97|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.055793|0.060567|0.055793|2.14|Y|Y/Y|Y/Y|N|Y|
|BAT_USDT|0.183470|0.182340|0.183470|0.86|N|Y/Y|Y/N|N|N|
|BR_USDT|0.584350|0.580080|0.584350|1.45|N|Y/Y|N/N|N|N|
|FILECOIN_USDT|1.025000|1.022600|1.025000|1.03|N|Y/Y|Y/Y|N|N|
|PHA_USDT|0.056810|0.055950|0.056810|0.24|N|Y/Y|N/N|N|N|
|XMR_USDT|577.080000|575.320000|577.080000|0.72|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T06:15:00+00:00, last15m_closed_end=2026-10-21T06:15+00:00, prior8high=0.063305, depth_time=2026-10-21T06:15:11+00:00, book20_bid_proxy_usdt=7696, book20_ask_proxy_usdt=4475, funding_indicative=0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.67%, turnover=6331358. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T06:15:00+00:00, last15m_closed_end=2026-10-21T06:15+00:00, prior8high=0.187530, depth_time=2026-10-21T06:15:08+00:00, book20_bid_proxy_usdt=31594, book20_ask_proxy_usdt=31791, funding_indicative=-0.000097, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-14.96%, turnover=10823014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T06:15:00+00:00, last15m_closed_end=2026-10-21T06:15+00:00, prior8high=0.621040, depth_time=2026-10-21T06:15:13+00:00, book20_bid_proxy_usdt=4912, book20_ask_proxy_usdt=2570, funding_indicative=0.000048, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.19%, turnover=33325716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-21T06:15:01+00:00, last15m_closed_end=2026-10-21T06:15+00:00, prior8high=1.039400, depth_time=2026-10-21T06:15:19+00:00, book20_bid_proxy_usdt=618179, book20_ask_proxy_usdt=1084897, funding_indicative=-0.000011, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=9766327. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T06:15:00+00:00, last15m_closed_end=2026-10-21T06:15+00:00, prior8high=0.057330, depth_time=2026-10-21T06:15:15+00:00, book20_bid_proxy_usdt=88728, book20_ask_proxy_usdt=79344, funding_indicative=-0.000026, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=6780193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T06:15:00+00:00, last15m_closed_end=2026-10-21T06:15+00:00, prior8high=581.680000, depth_time=2026-10-21T06:15:15+00:00, book20_bid_proxy_usdt=21229, book20_ask_proxy_usdt=6964, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.95%, turnover=21160962. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
