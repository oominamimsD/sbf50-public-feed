# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T13:30:33Z**
- feed_generated_utc: 2026-10-23T13:30:36+00:00
- source_sha256: `ae767546be78800cad1ab710853ae49195f66b29c52afea103fdec3cf4f6261d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T13:30+00:00, close=81670.4, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T13:00+00:00, close=81711.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.322100|-8.08|7.46|-8.10|8614195|0.30|
|QNT_USDT|181.340000|-4.91|-12.77|-4.93|56526488|2.76|
|TIA_USDT|0.545500|-4.02|-9.46|-4.04|24618620|1.83|
|STRK_USDT|0.052590|-3.25|-45.42|-3.27|12024922|1.90|
|ARB_USDT|0.178920|-2.57|-5.80|-2.59|24581528|2.79|
|SILVER_USDT|53.970000|-2.33|-5.54|-2.35|326219341|1.85|
|PUMPFUN_USDT|0.004580|-2.11|1.19|-2.13|39558187|2.18|
|OP_USDT|0.117550|-1.91|-15.35|-1.93|6134306|0.85|
|APT_USDT|0.761000|-1.45|-7.94|-1.47|7528947|1.31|
|SEI_USDT|0.057470|-1.03|-6.49|-1.05|7621607|3.48|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.761000|0.762000|0.761000|1.34|Y|Y/Y|Y/Y|Y|Y|
|ARB_USDT|0.178920|0.179320|0.178940|3.07|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|3.322100|3.341700|3.322100|1.67|Y|Y/Y|Y/Y|Y|Y|
|OP_USDT|0.117550|0.117420|0.117550|1.20|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004580|0.004556|0.004582|1.27|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|181.340000|180.980000|181.320000|1.88|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.057470|0.057490|0.057470|0.86|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.970000|53.830000|53.940000|3.49|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052590|0.051310|0.052590|0.83|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.545500|0.544800|0.545500|1.11|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-23T13:30:01+00:00, last15m_closed_end=2026-10-23T13:30+00:00, prior8high=0.770000, depth_time=2026-10-23T13:30:29+00:00, book20_bid_proxy_usdt=69664, book20_ask_proxy_usdt=79311, funding_indicative=0.000051, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=7528947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-23T13:30:01+00:00, last15m_closed_end=2026-10-23T13:30+00:00, prior8high=0.181300, depth_time=2026-10-23T13:30:18+00:00, book20_bid_proxy_usdt=54716, book20_ask_proxy_usdt=59722, funding_indicative=-0.000008, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.57%, turnover=24581528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T13:30:02+00:00, last15m_closed_end=2026-10-23T13:30+00:00, prior8high=3.406000, depth_time=2026-10-23T13:30:07+00:00, book20_bid_proxy_usdt=24127, book20_ask_proxy_usdt=24005, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.08%, turnover=8614195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T13:30:02+00:00, last15m_closed_end=2026-10-23T13:30+00:00, prior8high=0.118580, depth_time=2026-10-23T13:30:26+00:00, book20_bid_proxy_usdt=38686, book20_ask_proxy_usdt=45747, funding_indicative=0.000004, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=6134306. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T13:30:01+00:00, last15m_closed_end=2026-10-23T13:30+00:00, prior8high=0.004674, depth_time=2026-10-23T13:30:23+00:00, book20_bid_proxy_usdt=1292928, book20_ask_proxy_usdt=1913045, funding_indicative=0.000018, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=39558187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T13:30:01+00:00, last15m_closed_end=2026-10-23T13:30+00:00, prior8high=183.550000, depth_time=2026-10-23T13:30:10+00:00, book20_bid_proxy_usdt=26014, book20_ask_proxy_usdt=55060, funding_indicative=-0.000188, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.91%, turnover=56526488. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-23T13:30:02+00:00, last15m_closed_end=2026-10-23T13:30+00:00, prior8high=0.058040, depth_time=2026-10-23T13:30:32+00:00, book20_bid_proxy_usdt=68212, book20_ask_proxy_usdt=276348, funding_indicative=0.000045, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.03%, turnover=7621607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T13:30:01+00:00, last15m_closed_end=2026-10-23T13:30+00:00, prior8high=54.210000, depth_time=2026-10-23T13:30:21+00:00, book20_bid_proxy_usdt=30777666, book20_ask_proxy_usdt=30354157, funding_indicative=0.000068, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=326219341. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T13:30:01+00:00, last15m_closed_end=2026-10-23T13:30+00:00, prior8high=0.053770, depth_time=2026-10-23T13:30:15+00:00, book20_bid_proxy_usdt=766070, book20_ask_proxy_usdt=547570, funding_indicative=-0.000019, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.25%, turnover=12024922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T13:30:01+00:00, last15m_closed_end=2026-10-23T13:30+00:00, prior8high=0.552300, depth_time=2026-10-23T13:30:13+00:00, book20_bid_proxy_usdt=293575, book20_ask_proxy_usdt=337679, funding_indicative=0.000001, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.02%, turnover=24618620. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
