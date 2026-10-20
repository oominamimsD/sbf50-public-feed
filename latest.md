# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T08:15:27Z**
- feed_generated_utc: 2026-10-20T08:15:30+00:00
- source_sha256: `2fab6082e80ae7480a1df4e3d553e20b7ce4c48b74d641ee6fe3f9ad603aa248`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T08:15+00:00, close=81385.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.574600|-10.12|-10.32|-9.48|31187256|5.07|
|Q_USDT|0.119524|-5.12|288.17|-4.48|6663342|3.35|
|SAND_USDT|0.056630|-4.24|-8.79|-3.60|7295318|1.77|
|NEAR_USDT|4.748000|-3.18|-14.43|-2.54|163839019|2.11|
|ARB_USDT|0.190800|-2.46|1.23|-1.82|95639062|0.52|
|ATOM_USDT|1.734000|-2.36|-5.14|-1.72|5107566|5.77|
|QNT_USDT|191.400000|-2.19|-16.19|-1.55|80654399|0.52|
|TAO_USDT|263.360000|-1.84|-8.00|-1.20|56293872|1.14|
|UNI_USDT|7.161000|-1.74|-3.46|-1.10|9918394|1.40|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.190800|0.192210|0.190750|3.57|Y|Y/Y|N/N|Y|N|
|ATOM_USDT|1.734000|1.737000|1.734000|3.99|Y|Y/N|N/N|Y|N|
|BTW_USDT|1.574600|1.647500|1.575600|4.21|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.748000|4.749000|4.748000|2.43|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|191.400000|191.100000|191.400000|1.69|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.119524|0.112553|0.119472|0.56|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.056630|0.056480|0.056610|7.76|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|263.360000|263.320000|263.360000|3.32|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.161000|7.119000|7.161000|3.82|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-20T08:15:01+00:00, last15m_closed_end=2026-10-20T08:15+00:00, prior8high=0.199790, depth_time=2026-10-20T08:15:17+00:00, book20_bid_proxy_usdt=58634, book20_ask_proxy_usdt=627944, funding_indicative=-0.000039, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.46%, turnover=95639062. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T08:15:01+00:00, last15m_closed_end=2026-10-20T08:15+00:00, prior8high=1.757000, depth_time=2026-10-20T08:15:16+00:00, book20_bid_proxy_usdt=934435, book20_ask_proxy_usdt=1144948, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.36%, turnover=5107566. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T08:15:01+00:00, last15m_closed_end=2026-10-20T08:15+00:00, prior8high=1.778500, depth_time=2026-10-20T08:15:08+00:00, book20_bid_proxy_usdt=6166, book20_ask_proxy_usdt=12827, funding_indicative=-0.004819, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.12%, turnover=31187256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T08:15:01+00:00, last15m_closed_end=2026-10-20T08:15+00:00, prior8high=4.806000, depth_time=2026-10-20T08:15:14+00:00, book20_bid_proxy_usdt=2810161, book20_ask_proxy_usdt=3112902, funding_indicative=-0.000016, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.18%, turnover=163839019. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T08:15:01+00:00, last15m_closed_end=2026-10-20T08:15+00:00, prior8high=194.060000, depth_time=2026-10-20T08:15:21+00:00, book20_bid_proxy_usdt=96822, book20_ask_proxy_usdt=71406, funding_indicative=0.000036, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=80654399. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T08:15:01+00:00, last15m_closed_end=2026-10-20T08:15+00:00, prior8high=0.124246, depth_time=2026-10-20T08:15:07+00:00, book20_bid_proxy_usdt=14395, book20_ask_proxy_usdt=15790, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.12%, turnover=6663342. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T08:15:02+00:00, last15m_closed_end=2026-10-20T08:15+00:00, prior8high=0.057290, depth_time=2026-10-20T08:15:12+00:00, book20_bid_proxy_usdt=835382, book20_ask_proxy_usdt=967587, funding_indicative=-0.001365, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.24%, turnover=7295318. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T08:15:01+00:00, last15m_closed_end=2026-10-20T08:15+00:00, prior8high=266.450000, depth_time=2026-10-20T08:15:24+00:00, book20_bid_proxy_usdt=87168, book20_ask_proxy_usdt=103415, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.84%, turnover=56293872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T08:15:01+00:00, last15m_closed_end=2026-10-20T08:15+00:00, prior8high=7.224000, depth_time=2026-10-20T08:15:26+00:00, book20_bid_proxy_usdt=1365475, book20_ask_proxy_usdt=1853250, funding_indicative=0.000046, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=9918394. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
