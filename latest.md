# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-12T16:45:25Z**
- feed_generated_utc: 2026-10-12T16:45:27+00:00
- source_sha256: `2afbf012ee84c6bb71525e216a335b33e87606571a4d67f0796d5570d33aee89`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-12T16:45+00:00, close=82766.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-12T16:00+00:00, close=82680.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-12T16:00+00:00, close=82680.3, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CKB_USDT|0.001612|-2.60|21.63|-2.70|5711299|3.10|
|US_USDT|0.011237|-2.32|9.29|-2.42|5018515|2.67|
|MAGIC_USDT|0.119620|-1.91|92.96|-2.01|12728528|0.84|
|INJ_USDT|7.740000|-1.55|3.28|-1.65|34018194|1.29|
|S_USDT|0.056510|-1.53|31.57|-1.63|31269175|1.77|
|CRV_USDT|0.356700|-1.51|-4.54|-1.61|5370071|2.80|
|NEAR_USDT|5.488000|-1.09|9.27|-1.19|275811386|1.82|
|JUP_USDT|0.339700|-0.93|0.53|-1.03|9141738|2.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CKB_USDT|0.001612|0.001600|0.001612|0.36|N|Y/Y|N/N|Y|N|
|CRV_USDT|0.356700|0.357600|0.356700|2.61|Y|Y/Y|Y/N|Y|N|
|INJ_USDT|7.740000|7.600000|7.740000|0.67|N|Y/Y|N/N|Y|N|
|JUP_USDT|0.339700|0.340400|0.339700|0.50|N|Y/Y|Y/Y|Y|N|
|MAGIC_USDT|0.119620|0.116500|0.119620|0.28|N|Y/Y|N/N|Y|N|
|NEAR_USDT|5.488000|5.512000|5.488000|1.77|Y|Y/Y|N/N|Y|N|
|S_USDT|0.056510|0.056310|0.056510|0.29|N|Y/N|N/N|Y|N|
|US_USDT|0.011237|0.010726|0.011237|0.91|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- CKB_USDT: quote_utc=2026-10-12T16:45:00+00:00, last15m_closed_end=2026-10-12T16:45+00:00, prior8high=0.001674, depth_time=2026-10-12T16:45:05+00:00, book20_bid_proxy_usdt=14172, book20_ask_proxy_usdt=23031, funding_indicative=-0.000773, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=5711299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-12T16:45:01+00:00, last15m_closed_end=2026-10-12T16:45+00:00, prior8high=0.365500, depth_time=2026-10-12T16:45:19+00:00, book20_bid_proxy_usdt=429753, book20_ask_proxy_usdt=517056, funding_indicative=0.000058, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=5370071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-12T16:45:00+00:00, last15m_closed_end=2026-10-12T16:45+00:00, prior8high=7.932000, depth_time=2026-10-12T16:45:14+00:00, book20_bid_proxy_usdt=351539, book20_ask_proxy_usdt=205803, funding_indicative=0.000225, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=34018194. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-12T16:45:00+00:00, last15m_closed_end=2026-10-12T16:45+00:00, prior8high=0.345800, depth_time=2026-10-12T16:45:24+00:00, book20_bid_proxy_usdt=586213, book20_ask_proxy_usdt=560127, funding_indicative=-0.000083, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.93%, turnover=9141738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGIC_USDT: quote_utc=2026-10-12T16:45:00+00:00, last15m_closed_end=2026-10-12T16:45+00:00, prior8high=0.123510, depth_time=2026-10-12T16:45:12+00:00, book20_bid_proxy_usdt=167260, book20_ask_proxy_usdt=177771, funding_indicative=-0.000206, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.91%, turnover=12728528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-12T16:45:00+00:00, last15m_closed_end=2026-10-12T16:45+00:00, prior8high=5.635000, depth_time=2026-10-12T16:45:21+00:00, book20_bid_proxy_usdt=2166093, book20_ask_proxy_usdt=1008813, funding_indicative=0.000012, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=275811386. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-12T16:45:00+00:00, last15m_closed_end=2026-10-12T16:45+00:00, prior8high=0.058770, depth_time=2026-10-12T16:45:16+00:00, book20_bid_proxy_usdt=126718, book20_ask_proxy_usdt=271252, funding_indicative=0.000046, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=31269175. target_RR/account_short_permission/settled_funding=UNKNOWN.
- US_USDT: quote_utc=2026-10-12T16:45:00+00:00, last15m_closed_end=2026-10-12T16:45+00:00, prior8high=0.011850, depth_time=2026-10-12T16:45:10+00:00, book20_bid_proxy_usdt=17840, book20_ask_proxy_usdt=13286, funding_indicative=0.000050, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.32%, turnover=5018515. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
