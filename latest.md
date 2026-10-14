# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T23:00:30Z**
- feed_generated_utc: 2026-10-14T23:00:32+00:00
- source_sha256: `f8699220d77c58e0bd131baf5ecd6a1706cfadf3c1c24a3e0dfe2f0a9cd4640d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T23:00+00:00, close=81624.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T23:00+00:00, close=81624.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.053180|-4.24|33.48|-4.26|5260865|1.88|
|FET_USDT|0.197200|-3.28|-12.93|-3.30|10656458|5.07|
|INJ_USDT|7.655000|-2.33|4.73|-2.35|33218610|1.31|
|BAT_USDT|0.170440|-2.28|71.88|-2.30|24909318|2.35|
|LDO_USDT|0.401100|-2.17|-6.15|-2.19|5078213|2.49|
|AAVE_USDT|153.750000|-1.92|-10.48|-1.94|26042623|0.65|
|STRK_USDT|0.076460|-1.82|54.58|-1.84|23361618|1.31|
|PUMPFUN_USDT|0.004765|-1.71|-24.01|-1.73|21554305|2.10|
|SILVER_USDT|55.750000|-1.11|-7.02|-1.13|420917354|1.79|
|COPPER_USDT|6.622000|-1.01|-0.94|-1.03|6048106|4.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|153.750000|152.860000|153.750000|0.83|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.170440|0.167700|0.170260|0.25|N|Y/Y|Y/N|Y|N|
|COPPER_USDT|6.622000|6.623000|6.620000|3.05|Y|Y/Y|Y/Y|Y|Y|
|FET_USDT|0.197200|0.194800|0.197400|0.19|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.655000|7.530000|7.656000|0.36|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.401100|0.394500|0.401100|1.55|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004765|0.004715|0.004765|0.32|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|55.750000|55.620000|55.750000|0.81|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.076460|0.075900|0.076460|0.30|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053180|0.052410|0.053180|0.22|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T23:00:02+00:00, last15m_closed_end=2026-10-14T23:00+00:00, prior8high=154.450000, depth_time=2026-10-14T23:00:20+00:00, book20_bid_proxy_usdt=381213, book20_ask_proxy_usdt=410700, funding_indicative=0.000082, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=26042623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T23:00:02+00:00, last15m_closed_end=2026-10-14T23:00+00:00, prior8high=0.171100, depth_time=2026-10-14T23:00:15+00:00, book20_bid_proxy_usdt=28591, book20_ask_proxy_usdt=21850, funding_indicative=0.000045, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=24909318. target_RR/account_short_permission/settled_funding=UNKNOWN.
- COPPER_USDT: quote_utc=2026-10-14T23:00:03+00:00, last15m_closed_end=2026-10-14T23:00+00:00, prior8high=6.654000, depth_time=2026-10-14T23:00:28+00:00, book20_bid_proxy_usdt=1679756, book20_ask_proxy_usdt=1238169, funding_indicative=0.000000, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.01%, turnover=6048106. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T23:00:02+00:00, last15m_closed_end=2026-10-14T23:00+00:00, prior8high=0.198600, depth_time=2026-10-14T23:00:10+00:00, book20_bid_proxy_usdt=962549, book20_ask_proxy_usdt=1294003, funding_indicative=0.000013, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.28%, turnover=10656458. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-14T23:00:02+00:00, last15m_closed_end=2026-10-14T23:00+00:00, prior8high=7.669000, depth_time=2026-10-14T23:00:12+00:00, book20_bid_proxy_usdt=447118, book20_ask_proxy_usdt=249464, funding_indicative=0.000153, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.33%, turnover=33218610. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-14T23:00:03+00:00, last15m_closed_end=2026-10-14T23:00+00:00, prior8high=0.402500, depth_time=2026-10-14T23:00:16+00:00, book20_bid_proxy_usdt=567239, book20_ask_proxy_usdt=647334, funding_indicative=-0.000053, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=5078213. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-14T23:00:02+00:00, last15m_closed_end=2026-10-14T23:00+00:00, prior8high=0.004786, depth_time=2026-10-14T23:00:23+00:00, book20_bid_proxy_usdt=1386343, book20_ask_proxy_usdt=1401343, funding_indicative=0.000050, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=21554305. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T23:00:02+00:00, last15m_closed_end=2026-10-14T23:00+00:00, prior8high=55.860000, depth_time=2026-10-14T23:00:25+00:00, book20_bid_proxy_usdt=41271631, book20_ask_proxy_usdt=52896658, funding_indicative=0.000080, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.11%, turnover=420917354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T23:00:02+00:00, last15m_closed_end=2026-10-14T23:00+00:00, prior8high=0.077510, depth_time=2026-10-14T23:00:21+00:00, book20_bid_proxy_usdt=285051, book20_ask_proxy_usdt=244340, funding_indicative=0.000036, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=23361618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T23:00:02+00:00, last15m_closed_end=2026-10-14T23:00+00:00, prior8high=0.053570, depth_time=2026-10-14T23:00:07+00:00, book20_bid_proxy_usdt=154996, book20_ask_proxy_usdt=194745, funding_indicative=-0.000071, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.24%, turnover=5260865. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
