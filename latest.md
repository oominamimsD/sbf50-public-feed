# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T06:00:25Z**
- feed_generated_utc: 2026-11-10T06:00:26+00:00
- source_sha256: `9d6dcb7517d0f345ccf9772a0d0b7d33644fdd5212556b17df499e5867550b0e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T06:00+00:00, close=74787.9, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T06:00+00:00, close=74787.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002496|-47.46|-54.63|-46.52|15251673|4.01|
|JCT_USDT|0.007030|-30.60|62.84|-29.66|25603383|2.85|
|ZEC_USDT|1155.310000|-5.74|-7.87|-4.80|2375370023|0.09|
|AAVE_USDT|127.040000|-4.73|-2.69|-3.79|12897827|0.79|
|ARB_USDT|0.172450|-4.35|8.23|-3.41|33818859|0.58|
|QNT_USDT|191.450000|-4.29|-5.43|-3.35|34902944|0.52|
|DASH_USDT|45.900000|-3.61|-2.75|-2.67|13676121|2.18|
|DOT_USDT|0.857200|-3.22|-8.23|-2.28|10399918|1.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.040000|126.070000|127.020000|0.44|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002496|0.002443|0.002496|0.14|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.172450|0.170290|0.172450|1.51|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.900000|45.750000|45.900000|0.63|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.857200|0.846900|0.857200|0.90|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.007030|0.006725|0.007038|0.57|N|Y/Y|N/N|Y|N|
|QNT_USDT|191.450000|190.450000|191.480000|0.66|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1155.310000|1145.810000|1155.050000|0.91|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T06:00:03+00:00, last15m_closed_end=2026-11-10T06:00+00:00, prior8high=128.770000, depth_time=2026-11-10T06:00:15+00:00, book20_bid_proxy_usdt=481954, book20_ask_proxy_usdt=409838, funding_indicative=0.000024, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.73%, turnover=12897827. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T06:00:02+00:00, last15m_closed_end=2026-11-10T06:00+00:00, prior8high=0.002790, depth_time=2026-11-10T06:00:08+00:00, book20_bid_proxy_usdt=39145, book20_ask_proxy_usdt=46536, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-47.46%, turnover=15251673. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T06:00:02+00:00, last15m_closed_end=2026-11-10T06:00+00:00, prior8high=0.172570, depth_time=2026-11-10T06:00:16+00:00, book20_bid_proxy_usdt=296537, book20_ask_proxy_usdt=56144, funding_indicative=-0.000016, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.35%, turnover=33818859. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T06:00:03+00:00, last15m_closed_end=2026-11-10T06:00+00:00, prior8high=46.350000, depth_time=2026-11-10T06:00:19+00:00, book20_bid_proxy_usdt=838766, book20_ask_proxy_usdt=580323, funding_indicative=0.000028, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.61%, turnover=13676121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T06:00:03+00:00, last15m_closed_end=2026-11-10T06:00+00:00, prior8high=0.856900, depth_time=2026-11-10T06:00:23+00:00, book20_bid_proxy_usdt=514428, book20_ask_proxy_usdt=473464, funding_indicative=0.000036, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.22%, turnover=10399918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T06:00:02+00:00, last15m_closed_end=2026-11-10T06:00+00:00, prior8high=0.008970, depth_time=2026-11-10T06:00:10+00:00, book20_bid_proxy_usdt=43044, book20_ask_proxy_usdt=26275, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-30.60%, turnover=25603383. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T06:00:03+00:00, last15m_closed_end=2026-11-10T06:00+00:00, prior8high=192.760000, depth_time=2026-11-10T06:00:19+00:00, book20_bid_proxy_usdt=45821, book20_ask_proxy_usdt=128014, funding_indicative=-0.000124, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.29%, turnover=34902944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T06:00:02+00:00, last15m_closed_end=2026-11-10T06:00+00:00, prior8high=1162.230000, depth_time=2026-11-10T06:00:12+00:00, book20_bid_proxy_usdt=194999, book20_ask_proxy_usdt=196829, funding_indicative=0.000081, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.74%, turnover=2375370023. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
