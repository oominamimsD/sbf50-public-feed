# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T19:15:18Z**
- feed_generated_utc: 2026-10-24T19:15:21+00:00
- source_sha256: `a3abe9107fd2fd6f0f291ad9669be9eab0038ee3dfd8c018b4dd72587631c67a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T19:15+00:00, close=80479.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T19:00+00:00, close=80503.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.060110|-10.81|94.21|-11.70|12255502|3.31|
|IRYS_USDT|0.043220|-6.14|238.71|-7.03|60977619|2.32|
|BIRB_USDT|0.092110|-5.68|89.83|-6.57|11873328|4.34|
|BTW_USDT|1.717300|-1.37|-24.32|-2.26|14256318|6.99|
|AGT_USDT|0.066240|-1.03|-8.07|-1.92|10306429|4.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066240|0.064320|0.066240|1.15|N|Y/Y|Y/N|Y|N|
|BIRB_USDT|0.092110|0.088740|0.092110|0.63|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.717300|1.704100|1.716700|0.72|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.043220|0.042370|0.043190|0.77|N|Y/Y|Y/N|Y|N|
|ORDER_USDT|0.060110|0.057390|0.060100|0.49|N|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-24T19:14:59+00:00, last15m_closed_end=2026-10-24T19:15+00:00, prior8high=0.069650, depth_time=2026-10-24T19:15:18+00:00, book20_bid_proxy_usdt=9198, book20_ask_proxy_usdt=6041, funding_indicative=0.000069, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.03%, turnover=10306429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-24T19:14:59+00:00, last15m_closed_end=2026-10-24T19:15+00:00, prior8high=0.096610, depth_time=2026-10-24T19:15:13+00:00, book20_bid_proxy_usdt=19480, book20_ask_proxy_usdt=18539, funding_indicative=-0.007650, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.68%, turnover=11873328. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-24T19:14:59+00:00, last15m_closed_end=2026-10-24T19:15+00:00, prior8high=1.733500, depth_time=2026-10-24T19:15:14+00:00, book20_bid_proxy_usdt=14072, book20_ask_proxy_usdt=17700, funding_indicative=-0.006469, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.37%, turnover=14256318. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T19:14:59+00:00, last15m_closed_end=2026-10-24T19:15+00:00, prior8high=0.051840, depth_time=2026-10-24T19:15:11+00:00, book20_bid_proxy_usdt=55435, book20_ask_proxy_usdt=38257, funding_indicative=0.000012, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=1, 24h_change=-6.14%, turnover=60977619. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-24T19:14:59+00:00, last15m_closed_end=2026-10-24T19:15+00:00, prior8high=0.074180, depth_time=2026-10-24T19:15:07+00:00, book20_bid_proxy_usdt=37842, book20_ask_proxy_usdt=35011, funding_indicative=-0.003248, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=1, 24h_change=-10.81%, turnover=12255502. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
