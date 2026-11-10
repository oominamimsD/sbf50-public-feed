# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T01:45:22Z**
- feed_generated_utc: 2026-11-10T01:45:24+00:00
- source_sha256: `7dcdb451f0ffd9c658019d776b85c9d2adb53d7bb6ffae73dcd8bedd80a05022`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T01:45+00:00, close=74998.9, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T01:00+00:00, close=75052, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002776|-43.31|-49.54|-42.66|13446324|3.61|
|ARB_USDT|0.173820|-5.55|9.09|-4.90|31578323|0.57|
|ZEC_USDT|1164.420000|-5.00|-7.15|-4.35|2426034743|0.09|
|DOT_USDT|0.856900|-3.81|-8.26|-3.16|10626468|1.17|
|WLD_USDT|0.316000|-3.03|-17.10|-2.38|27959313|3.17|
|QNT_USDT|194.510000|-2.76|-3.92|-2.11|40443258|0.51|
|SOL_USDT|86.380000|-1.71|-7.62|-1.06|671501066|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002776|0.002154|0.002772|7.63|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.173820|0.173600|0.173820|1.48|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.856900|0.852500|0.857000|0.06|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.510000|193.200000|194.510000|1.04|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.380000|86.300000|86.380000|2.80|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.316000|0.316800|0.316000|2.83|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1164.420000|1152.430000|1164.230000|1.15|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T01:45:02+00:00, last15m_closed_end=2026-11-10T01:45+00:00, prior8high=0.003900, depth_time=2026-11-10T01:45:07+00:00, book20_bid_proxy_usdt=56371, book20_ask_proxy_usdt=20099, funding_indicative=-0.000353, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-43.31%, turnover=13446324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T01:45:02+00:00, last15m_closed_end=2026-11-10T01:45+00:00, prior8high=0.176000, depth_time=2026-11-10T01:45:08+00:00, book20_bid_proxy_usdt=59623, book20_ask_proxy_usdt=37932, funding_indicative=-0.000030, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.55%, turnover=31578323. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T01:45:03+00:00, last15m_closed_end=2026-11-10T01:45+00:00, prior8high=0.858500, depth_time=2026-11-10T01:45:13+00:00, book20_bid_proxy_usdt=843825, book20_ask_proxy_usdt=543037, funding_indicative=0.000010, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.81%, turnover=10626468. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T01:45:02+00:00, last15m_closed_end=2026-11-10T01:45+00:00, prior8high=195.180000, depth_time=2026-11-10T01:45:19+00:00, book20_bid_proxy_usdt=64149, book20_ask_proxy_usdt=66817, funding_indicative=0.000100, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=40443258. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T01:45:02+00:00, last15m_closed_end=2026-11-10T01:45+00:00, prior8high=86.790000, depth_time=2026-11-10T01:45:21+00:00, book20_bid_proxy_usdt=16916912, book20_ask_proxy_usdt=15317205, funding_indicative=0.000036, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=671501066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T01:45:02+00:00, last15m_closed_end=2026-11-10T01:45+00:00, prior8high=0.319600, depth_time=2026-11-10T01:45:17+00:00, book20_bid_proxy_usdt=4863329, book20_ask_proxy_usdt=4724201, funding_indicative=0.000055, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.03%, turnover=27959313. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T01:45:02+00:00, last15m_closed_end=2026-11-10T01:45+00:00, prior8high=1178.530000, depth_time=2026-11-10T01:45:12+00:00, book20_bid_proxy_usdt=114925, book20_ask_proxy_usdt=173948, funding_indicative=0.000093, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.00%, turnover=2426034743. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
