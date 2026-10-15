# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T00:00:29Z**
- feed_generated_utc: 2026-10-15T00:00:32+00:00
- source_sha256: `7b8d9a064f8f6ab3454ee3e81406f521b75209c8c10368d2fa99a1b4b2f29323`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FET_USDT|0.196800|-5.43|-13.11|-5.08|10682772|5.08|
|S_USDT|0.054120|-2.55|35.84|-2.20|5170597|1.85|
|BAT_USDT|0.172160|-2.50|73.61|-2.15|24018876|1.74|
|NEAR_USDT|4.882000|-2.39|-3.01|-2.04|178483541|2.05|
|INJ_USDT|7.662000|-2.24|4.82|-1.89|32692727|1.30|
|LDO_USDT|0.401700|-2.02|-6.01|-1.67|5064425|2.49|
|ZRO_USDT|1.890000|-1.84|-10.40|-1.49|10036084|0.53|
|ZEC_USDT|1146.980000|-1.78|-13.54|-1.43|1574904340|2.96|
|PUMPFUN_USDT|0.004771|-1.58|-23.91|-1.23|21481001|2.10|
|AAVE_USDT|154.420000|-1.49|-10.09|-1.14|25762825|0.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.420000|152.860000|154.420000|0.52|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.172160|0.168080|0.172190|1.05|N|Y/Y|N/N|Y|N|
|FET_USDT|0.196800|0.196400|0.196800|0.05|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.662000|7.603000|7.662000|0.47|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.401700|0.398100|0.401700|1.32|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.882000|4.812000|4.882000|1.35|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004771|0.004724|0.004772|0.11|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.054120|0.052410|0.054120|0.41|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1146.980000|1125.330000|1147.170000|0.95|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.890000|1.894400|1.890000|2.08|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-15T00:00:01+00:00, last15m_closed_end=2026-10-15T00:00+00:00, prior8high=154.310000, depth_time=2026-10-15T00:00:28+00:00, book20_bid_proxy_usdt=269810, book20_ask_proxy_usdt=300620, funding_indicative=0.000069, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=25762825. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-15T00:00:01+00:00, last15m_closed_end=2026-10-15T00:00+00:00, prior8high=0.171730, depth_time=2026-10-15T00:00:11+00:00, book20_bid_proxy_usdt=27348, book20_ask_proxy_usdt=26950, funding_indicative=0.000038, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=24018876. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-15T00:00:01+00:00, last15m_closed_end=2026-10-15T00:00+00:00, prior8high=0.198600, depth_time=2026-10-15T00:00:07+00:00, book20_bid_proxy_usdt=870826, book20_ask_proxy_usdt=775434, funding_indicative=0.000070, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.43%, turnover=10682772. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-15T00:00:01+00:00, last15m_closed_end=2026-10-15T00:00+00:00, prior8high=7.699000, depth_time=2026-10-15T00:00:17+00:00, book20_bid_proxy_usdt=173687, book20_ask_proxy_usdt=472319, funding_indicative=0.000135, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=32692727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-15T00:00:01+00:00, last15m_closed_end=2026-10-15T00:00+00:00, prior8high=0.402400, depth_time=2026-10-15T00:00:19+00:00, book20_bid_proxy_usdt=464532, book20_ask_proxy_usdt=719265, funding_indicative=-0.000060, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.02%, turnover=5064425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-15T00:00:01+00:00, last15m_closed_end=2026-10-15T00:00+00:00, prior8high=4.912000, depth_time=2026-10-15T00:00:14+00:00, book20_bid_proxy_usdt=1303083, book20_ask_proxy_usdt=1846474, funding_indicative=0.000100, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=178483541. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-15T00:00:01+00:00, last15m_closed_end=2026-10-15T00:00+00:00, prior8high=0.004777, depth_time=2026-10-15T00:00:24+00:00, book20_bid_proxy_usdt=1261344, book20_ask_proxy_usdt=1483168, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.58%, turnover=21481001. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-15T00:00:01+00:00, last15m_closed_end=2026-10-15T00:00+00:00, prior8high=0.053880, depth_time=2026-10-15T00:00:09+00:00, book20_bid_proxy_usdt=212861, book20_ask_proxy_usdt=202996, funding_indicative=-0.000106, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.55%, turnover=5170597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-15T00:00:01+00:00, last15m_closed_end=2026-10-15T00:00+00:00, prior8high=1148.550000, depth_time=2026-10-15T00:00:24+00:00, book20_bid_proxy_usdt=310846, book20_ask_proxy_usdt=197345, funding_indicative=0.000065, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=1574904340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-15T00:00:01+00:00, last15m_closed_end=2026-10-15T00:00+00:00, prior8high=1.923100, depth_time=2026-10-15T00:00:21+00:00, book20_bid_proxy_usdt=53927, book20_ask_proxy_usdt=48161, funding_indicative=0.000016, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.84%, turnover=10036084. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
