# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T12:45:32Z**
- feed_generated_utc: 2026-10-23T12:45:35+00:00
- source_sha256: `130f22daeb063cd70bce1b180f79c250244448752235e922a6bc0c40b4b336e6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T12:45+00:00, close=81744.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGMA_USDT|0.434380|-13.47|83.70|-13.58|6605824|2.99|
|JCT_USDT|0.004172|-9.46|110.17|-9.57|6432764|9.59|
|LIT_USDT|3.384800|-6.34|9.49|-6.45|8782379|0.29|
|QNT_USDT|181.690000|-4.72|-12.61|-4.83|55334242|0.55|
|TIA_USDT|0.546700|-3.81|-9.26|-3.92|25405943|1.83|
|STRK_USDT|0.052790|-2.88|-45.21|-2.99|12324797|1.89|
|SILVER_USDT|53.960000|-2.35|-5.56|-2.46|328267122|1.85|
|ARB_USDT|0.180250|-1.84|-5.10|-1.95|25059798|0.56|
|OP_USDT|0.117800|-1.71|-15.17|-1.82|6237718|0.85|
|PUMPFUN_USDT|0.004608|-1.51|1.81|-1.62|40431334|2.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180250|0.179250|0.180250|0.65|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004172|0.004042|0.004172|0.37|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.384800|3.341700|3.384800|0.96|N|Y/Y|Y/Y|Y|N|
|MAGMA_USDT|0.434380|0.426720|0.434320|0.85|N|Y/Y|N/N|Y|N|
|OP_USDT|0.117800|0.116880|0.117800|0.64|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004608|0.004525|0.004608|1.13|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|181.690000|180.980000|181.690000|1.49|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.960000|53.860000|53.960000|0.66|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052790|0.051150|0.052790|0.80|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.546700|0.544800|0.546700|1.06|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T12:45:00+00:00, last15m_closed_end=2026-10-23T12:45+00:00, prior8high=0.180950, depth_time=2026-10-23T12:45:26+00:00, book20_bid_proxy_usdt=78811, book20_ask_proxy_usdt=105617, funding_indicative=-0.000005, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=25059798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T12:45:00+00:00, last15m_closed_end=2026-10-23T12:45+00:00, prior8high=0.004254, depth_time=2026-10-23T12:45:11+00:00, book20_bid_proxy_usdt=45739, book20_ask_proxy_usdt=37414, funding_indicative=0.000078, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.46%, turnover=6432764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T12:45:00+00:00, last15m_closed_end=2026-10-23T12:45+00:00, prior8high=3.406000, depth_time=2026-10-23T12:45:13+00:00, book20_bid_proxy_usdt=26724, book20_ask_proxy_usdt=22810, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.34%, turnover=8782379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGMA_USDT: quote_utc=2026-10-23T12:44:59+00:00, last15m_closed_end=2026-10-23T12:45+00:00, prior8high=0.504110, depth_time=2026-10-23T12:45:07+00:00, book20_bid_proxy_usdt=6106, book20_ask_proxy_usdt=3311, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.47%, turnover=6605824. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T12:45:00+00:00, last15m_closed_end=2026-10-23T12:45+00:00, prior8high=0.118430, depth_time=2026-10-23T12:45:27+00:00, book20_bid_proxy_usdt=174245, book20_ask_proxy_usdt=149570, funding_indicative=0.000026, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=6237718. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T12:45:00+00:00, last15m_closed_end=2026-10-23T12:45+00:00, prior8high=0.004674, depth_time=2026-10-23T12:45:31+00:00, book20_bid_proxy_usdt=1848497, book20_ask_proxy_usdt=2002346, funding_indicative=0.000017, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=40431334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T12:45:00+00:00, last15m_closed_end=2026-10-23T12:45+00:00, prior8high=183.550000, depth_time=2026-10-23T12:45:16+00:00, book20_bid_proxy_usdt=140999, book20_ask_proxy_usdt=88778, funding_indicative=-0.000184, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.72%, turnover=55334242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T12:45:00+00:00, last15m_closed_end=2026-10-23T12:45+00:00, prior8high=54.210000, depth_time=2026-10-23T12:45:24+00:00, book20_bid_proxy_usdt=34915544, book20_ask_proxy_usdt=28192152, funding_indicative=0.000032, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=328267122. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T12:45:00+00:00, last15m_closed_end=2026-10-23T12:45+00:00, prior8high=0.053400, depth_time=2026-10-23T12:45:21+00:00, book20_bid_proxy_usdt=716044, book20_ask_proxy_usdt=626114, funding_indicative=0.000011, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.88%, turnover=12324797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T12:45:00+00:00, last15m_closed_end=2026-10-23T12:45+00:00, prior8high=0.550500, depth_time=2026-10-23T12:45:18+00:00, book20_bid_proxy_usdt=536218, book20_ask_proxy_usdt=371928, funding_indicative=0.000027, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.81%, turnover=25405943. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
