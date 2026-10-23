# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T08:30:29Z**
- feed_generated_utc: 2026-10-23T08:30:31+00:00
- source_sha256: `08fabfab16db71db45be17522e71639c07a37a1901dec953cad253f3505eda8e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T08:30+00:00, close=81787.7, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004248|-7.81|114.00|-7.97|8060228|9.41|
|LIT_USDT|3.434200|-4.98|11.08|-5.14|9728866|0.29|
|STRK_USDT|0.052800|-2.86|-45.20|-3.02|10744686|1.90|
|TIA_USDT|0.553300|-2.65|-8.16|-2.81|24657483|1.81|
|SILVER_USDT|53.970000|-2.33|-5.54|-2.49|343751902|1.85|
|QNT_USDT|187.830000|-1.51|-9.65|-1.67|48228883|1.60|
|PUMPFUN_USDT|0.004620|-1.26|2.07|-1.42|37513100|2.17|
|XPT_USDT|1568.070000|-1.18|-3.25|-1.34|5104666|0.77|
|XAU_USDT|4023.180000|-0.89|-3.19|-1.05|645470269|0.03|
|XAUT_USDT|4018.260000|-0.88|-3.05|-1.04|267916858|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004248|0.004176|0.004248|0.37|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.434200|3.399900|3.435800|1.86|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004620|0.004580|0.004620|2.27|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|187.830000|187.480000|187.860000|1.36|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.970000|53.870000|53.990000|1.16|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052800|0.052400|0.052800|1.49|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.553300|0.553400|0.553400|0.69|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4018.260000|4012.820000|4018.670000|0.72|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4023.180000|4018.880000|4024.200000|1.14|N|Y/Y|Y/Y|Y|N|
|XPT_USDT|1568.070000|1562.830000|1568.070000|6.24|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T08:30:01+00:00, last15m_closed_end=2026-10-23T08:30+00:00, prior8high=0.004316, depth_time=2026-10-23T08:30:05+00:00, book20_bid_proxy_usdt=54989, book20_ask_proxy_usdt=34574, funding_indicative=0.000101, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.81%, turnover=8060228. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T08:30:01+00:00, last15m_closed_end=2026-10-23T08:30+00:00, prior8high=3.450000, depth_time=2026-10-23T08:30:08+00:00, book20_bid_proxy_usdt=27181, book20_ask_proxy_usdt=22741, funding_indicative=0.000026, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.98%, turnover=9728866. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T08:30:01+00:00, last15m_closed_end=2026-10-23T08:30+00:00, prior8high=0.004684, depth_time=2026-10-23T08:30:21+00:00, book20_bid_proxy_usdt=1736261, book20_ask_proxy_usdt=1532315, funding_indicative=0.000016, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.26%, turnover=37513100. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T08:30:01+00:00, last15m_closed_end=2026-10-23T08:30+00:00, prior8high=190.170000, depth_time=2026-10-23T08:30:19+00:00, book20_bid_proxy_usdt=106622, book20_ask_proxy_usdt=121541, funding_indicative=-0.000143, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=48228883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T08:30:01+00:00, last15m_closed_end=2026-10-23T08:30+00:00, prior8high=54.490000, depth_time=2026-10-23T08:30:16+00:00, book20_bid_proxy_usdt=31058071, book20_ask_proxy_usdt=33806668, funding_indicative=0.000166, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=343751902. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T08:30:01+00:00, last15m_closed_end=2026-10-23T08:30+00:00, prior8high=0.053510, depth_time=2026-10-23T08:30:12+00:00, book20_bid_proxy_usdt=777652, book20_ask_proxy_usdt=533754, funding_indicative=-0.000029, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=10744686. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T08:30:01+00:00, last15m_closed_end=2026-10-23T08:30+00:00, prior8high=0.562000, depth_time=2026-10-23T08:30:13+00:00, book20_bid_proxy_usdt=319527, book20_ask_proxy_usdt=489388, funding_indicative=-0.000005, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.65%, turnover=24657483. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T08:30:01+00:00, last15m_closed_end=2026-10-23T08:30+00:00, prior8high=4026.740000, depth_time=2026-10-23T08:30:28+00:00, book20_bid_proxy_usdt=280450, book20_ask_proxy_usdt=97597, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=267916858. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T08:30:01+00:00, last15m_closed_end=2026-10-23T08:30+00:00, prior8high=4031.160000, depth_time=2026-10-23T08:30:25+00:00, book20_bid_proxy_usdt=1255943, book20_ask_proxy_usdt=711872, funding_indicative=0.000117, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.89%, turnover=645470269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPT_USDT: quote_utc=2026-10-23T08:29:59+00:00, last15m_closed_end=2026-10-23T08:30+00:00, prior8high=1580.570000, depth_time=2026-10-23T08:30:24+00:00, book20_bid_proxy_usdt=709660, book20_ask_proxy_usdt=384511, funding_indicative=0.000250, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.18%, turnover=5104666. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
