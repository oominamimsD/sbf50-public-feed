# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T12:15:27Z**
- feed_generated_utc: 2026-10-23T12:15:29+00:00
- source_sha256: `3022fb09d29e9302bcd1f60a348414a5e9997c9bef03a943884271c9368ed114`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T12:15+00:00, close=81471.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGMA_USDT|0.428360|-14.67|81.16|-14.46|6498153|0.93|
|LIT_USDT|3.344900|-7.45|8.20|-7.24|8452645|0.30|
|QNT_USDT|181.250000|-4.96|-12.82|-4.75|53234207|1.10|
|TIA_USDT|0.545100|-4.09|-9.52|-3.88|24942369|1.83|
|STRK_USDT|0.052800|-2.86|-45.20|-2.65|12096585|1.89|
|SILVER_USDT|53.980000|-2.31|-5.53|-2.10|319945303|1.85|
|ARB_USDT|0.179660|-2.16|-5.41|-1.95|24555818|0.56|
|OP_USDT|0.117590|-1.88|-15.32|-1.67|6061348|0.85|
|PUMPFUN_USDT|0.004595|-1.79|1.52|-1.58|39872817|2.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.179660|0.179250|0.179520|2.47|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.344900|3.349800|3.344900|1.76|Y|Y/Y|Y/Y|Y|Y|
|MAGMA_USDT|0.428360|0.431000|0.428360|1.54|Y|Y/Y|N/N|Y|N|
|OP_USDT|0.117590|0.116880|0.117540|2.33|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004595|0.004525|0.004595|1.47|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|181.250000|181.170000|181.250000|1.74|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.980000|53.890000|53.970000|0.64|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052800|0.051150|0.052800|0.62|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.545100|0.545000|0.545100|2.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T12:15:02+00:00, last15m_closed_end=2026-10-23T12:15+00:00, prior8high=0.181560, depth_time=2026-10-23T12:15:20+00:00, book20_bid_proxy_usdt=65492, book20_ask_proxy_usdt=78704, funding_indicative=-0.000018, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=24555818. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T12:15:02+00:00, last15m_closed_end=2026-10-23T12:15+00:00, prior8high=3.402200, depth_time=2026-10-23T12:15:09+00:00, book20_bid_proxy_usdt=24908, book20_ask_proxy_usdt=24074, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.45%, turnover=8452645. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGMA_USDT: quote_utc=2026-10-23T12:15:01+00:00, last15m_closed_end=2026-10-23T12:15+00:00, prior8high=0.510680, depth_time=2026-10-23T12:15:07+00:00, book20_bid_proxy_usdt=3547, book20_ask_proxy_usdt=7824, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.67%, turnover=6498153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T12:15:02+00:00, last15m_closed_end=2026-10-23T12:15+00:00, prior8high=0.118640, depth_time=2026-10-23T12:15:23+00:00, book20_bid_proxy_usdt=106639, book20_ask_proxy_usdt=166849, funding_indicative=0.000024, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=6061348. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T12:15:02+00:00, last15m_closed_end=2026-10-23T12:15+00:00, prior8high=0.004674, depth_time=2026-10-23T12:15:26+00:00, book20_bid_proxy_usdt=1570755, book20_ask_proxy_usdt=1252413, funding_indicative=0.000025, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.79%, turnover=39872817. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T12:15:01+00:00, last15m_closed_end=2026-10-23T12:15+00:00, prior8high=184.930000, depth_time=2026-10-23T12:15:11+00:00, book20_bid_proxy_usdt=46416, book20_ask_proxy_usdt=93412, funding_indicative=-0.000181, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.96%, turnover=53234207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T12:15:01+00:00, last15m_closed_end=2026-10-23T12:15+00:00, prior8high=54.210000, depth_time=2026-10-23T12:15:18+00:00, book20_bid_proxy_usdt=37192445, book20_ask_proxy_usdt=38033599, funding_indicative=0.000020, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=319945303. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T12:15:02+00:00, last15m_closed_end=2026-10-23T12:15+00:00, prior8high=0.052810, depth_time=2026-10-23T12:15:16+00:00, book20_bid_proxy_usdt=584698, book20_ask_proxy_usdt=506945, funding_indicative=0.000026, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=12096585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T12:15:02+00:00, last15m_closed_end=2026-10-23T12:15+00:00, prior8high=0.552300, depth_time=2026-10-23T12:15:13+00:00, book20_bid_proxy_usdt=375604, book20_ask_proxy_usdt=332897, funding_indicative=0.000015, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.09%, turnover=24942369. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
