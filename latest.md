# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T01:00:25Z**
- feed_generated_utc: 2026-10-27T01:00:30+00:00
- source_sha256: `772e64fc478cf67fa5eff043d2f58b4a233015996ec6f68210ed86a4413d2c4d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T01:00+00:00, close=80194.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T01:00+00:00, close=80194.2, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.616700|-5.29|-15.00|-5.07|5342814|3.09|
|DOT_USDT|1.005200|-2.52|-12.34|-2.30|10361319|0.99|
|NEAR_USDT|4.462000|-2.42|-9.01|-2.20|109328228|2.24|
|BTW_USDT|1.178500|-2.35|-32.73|-2.13|20932367|0.85|
|ARB_USDT|0.167860|-2.35|-14.19|-2.13|20049424|0.60|
|AAVE_USDT|135.020000|-2.07|-8.28|-1.85|24695419|0.74|
|LINK_USDT|11.366000|-1.72|-4.83|-1.50|101549836|0.88|
|SOL_USDT|100.810000|-1.25|-3.15|-1.03|701961944|0.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|135.020000|134.000000|135.030000|6.47|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167860|0.165690|0.167860|3.02|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.178500|1.171200|1.178500|0.62|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.005200|0.999000|1.005200|1.10|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.366000|11.242000|11.366000|0.69|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.462000|4.422000|4.463000|1.08|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|100.810000|99.870000|100.810000|1.35|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.616700|1.610100|1.617700|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T01:00:02+00:00, last15m_closed_end=2026-10-27T01:00+00:00, prior8high=136.180000, depth_time=2026-10-27T01:00:19+00:00, book20_bid_proxy_usdt=735847, book20_ask_proxy_usdt=334726, funding_indicative=0.000010, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=24695419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T01:00:02+00:00, last15m_closed_end=2026-10-27T01:00+00:00, prior8high=0.169780, depth_time=2026-10-27T01:00:16+00:00, book20_bid_proxy_usdt=88485, book20_ask_proxy_usdt=110904, funding_indicative=-0.000029, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.35%, turnover=20049424. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-27T01:00:02+00:00, last15m_closed_end=2026-10-27T01:00+00:00, prior8high=1.229000, depth_time=2026-10-27T01:00:16+00:00, book20_bid_proxy_usdt=23404, book20_ask_proxy_usdt=17198, funding_indicative=-0.000339, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=20932367. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T01:00:02+00:00, last15m_closed_end=2026-10-27T01:00+00:00, prior8high=1.013800, depth_time=2026-10-27T01:00:11+00:00, book20_bid_proxy_usdt=355070, book20_ask_proxy_usdt=283790, funding_indicative=-0.000068, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.52%, turnover=10361319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T01:00:02+00:00, last15m_closed_end=2026-10-27T01:00+00:00, prior8high=11.421000, depth_time=2026-10-27T01:00:21+00:00, book20_bid_proxy_usdt=640579, book20_ask_proxy_usdt=623826, funding_indicative=0.000075, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=101549836. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T01:00:02+00:00, last15m_closed_end=2026-10-27T01:00+00:00, prior8high=4.536000, depth_time=2026-10-27T01:00:13+00:00, book20_bid_proxy_usdt=4849252, book20_ask_proxy_usdt=3379314, funding_indicative=-0.000106, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=109328228. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T01:00:02+00:00, last15m_closed_end=2026-10-27T01:00+00:00, prior8high=101.110000, depth_time=2026-10-27T01:00:24+00:00, book20_bid_proxy_usdt=16838739, book20_ask_proxy_usdt=20296763, funding_indicative=0.000075, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=701961944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T01:00:02+00:00, last15m_closed_end=2026-10-27T01:00+00:00, prior8high=1.647700, depth_time=2026-10-27T01:00:09+00:00, book20_bid_proxy_usdt=48924, book20_ask_proxy_usdt=46708, funding_indicative=-0.000260, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.29%, turnover=5342814. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
