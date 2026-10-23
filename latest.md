# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T06:00:24Z**
- feed_generated_utc: 2026-10-23T06:00:26+00:00
- source_sha256: `a4b06bd2d9cd84801050e2545c4add2f7c5d342b6ec01067c5d7ecd120ce0f15`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T06:00+00:00, close=81812.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T06:00+00:00, close=81812.9, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004260|-7.55|114.60|-7.75|8984327|7.04|
|LIT_USDT|3.423600|-5.27|10.74|-5.47|10565714|0.29|
|STRK_USDT|0.052960|-2.57|-45.03|-2.77|11572856|1.89|
|SILVER_USDT|54.380000|-1.59|-4.83|-1.79|365686387|1.84|
|TIA_USDT|0.559800|-1.51|-7.08|-1.71|24139989|1.79|
|ZEC_USDT|1222.320000|-0.96|3.61|-1.16|1904765593|0.08|
|QNT_USDT|189.060000|-0.86|-9.06|-1.06|51978910|1.06|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004260|0.004130|0.004260|1.71|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.423600|3.428400|3.423600|0.43|N|Y/Y|N/N|Y|N|
|QNT_USDT|189.060000|188.430000|189.060000|0.95|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.380000|53.720000|54.380000|0.86|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052960|0.052690|0.052960|0.61|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.559800|0.556900|0.559800|0.88|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1222.320000|1211.520000|1222.320000|0.86|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T05:59:59+00:00, last15m_closed_end=2026-10-23T06:00+00:00, prior8high=0.004429, depth_time=2026-10-23T06:00:08+00:00, book20_bid_proxy_usdt=23390, book20_ask_proxy_usdt=27766, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.55%, turnover=8984327. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T05:59:59+00:00, last15m_closed_end=2026-10-23T06:00+00:00, prior8high=3.509900, depth_time=2026-10-23T06:00:10+00:00, book20_bid_proxy_usdt=25733, book20_ask_proxy_usdt=37565, funding_indicative=0.000027, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.27%, turnover=10565714. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T05:59:59+00:00, last15m_closed_end=2026-10-23T06:00+00:00, prior8high=190.320000, depth_time=2026-10-23T06:00:23+00:00, book20_bid_proxy_usdt=111170, book20_ask_proxy_usdt=94649, funding_indicative=-0.000116, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.86%, turnover=51978910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T05:59:59+00:00, last15m_closed_end=2026-10-23T06:00+00:00, prior8high=54.680000, depth_time=2026-10-23T06:00:16+00:00, book20_bid_proxy_usdt=28430487, book20_ask_proxy_usdt=30449515, funding_indicative=0.000125, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.59%, turnover=365686387. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T05:59:59+00:00, last15m_closed_end=2026-10-23T06:00+00:00, prior8high=0.053360, depth_time=2026-10-23T06:00:12+00:00, book20_bid_proxy_usdt=558680, book20_ask_proxy_usdt=553427, funding_indicative=-0.000006, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=11572856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T05:59:59+00:00, last15m_closed_end=2026-10-23T06:00+00:00, prior8high=0.565400, depth_time=2026-10-23T06:00:18+00:00, book20_bid_proxy_usdt=374842, book20_ask_proxy_usdt=447681, funding_indicative=-0.000007, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=24139989. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-23T05:59:59+00:00, last15m_closed_end=2026-10-23T06:00+00:00, prior8high=1231.090000, depth_time=2026-10-23T06:00:20+00:00, book20_bid_proxy_usdt=1968266, book20_ask_proxy_usdt=1048500, funding_indicative=0.000006, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.96%, turnover=1904765593. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
