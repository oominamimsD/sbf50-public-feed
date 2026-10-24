# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T19:00:20Z**
- feed_generated_utc: 2026-10-24T19:00:23+00:00
- source_sha256: `f1b718d496e6f40ad4464be0d7e5aebcf481d5d8a12c37175727f13e3af41e08`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T19:00+00:00, close=80503.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T19:00+00:00, close=80503.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.060400|-10.38|95.15|-11.30|12191736|6.61|
|BIRB_USDT|0.090450|-7.38|86.41|-8.30|11855838|1.10|
|IRYS_USDT|0.042940|-6.75|236.52|-7.67|60777220|4.65|
|AGT_USDT|0.066380|-6.67|-7.87|-7.59|10241816|7.54|
|BTW_USDT|1.707500|-1.79|-24.75|-2.71|14202542|0.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066380|0.064320|0.066380|0.95|N|Y/Y|Y/N|Y|N|
|BIRB_USDT|0.090450|0.088740|0.090730|0.94|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.707500|1.709100|1.707700|0.71|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.042940|0.043670|0.042800|1.11|N|Y/Y|Y/N|Y|N|
|ORDER_USDT|0.060400|0.057390|0.061030|0.65|N|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-24T19:00:03+00:00, last15m_closed_end=2026-10-24T19:00+00:00, prior8high=0.069650, depth_time=2026-10-24T19:00:15+00:00, book20_bid_proxy_usdt=9331, book20_ask_proxy_usdt=7829, funding_indicative=0.000077, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.67%, turnover=10241816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-24T19:00:03+00:00, last15m_closed_end=2026-10-24T19:00+00:00, prior8high=0.096610, depth_time=2026-10-24T19:00:10+00:00, book20_bid_proxy_usdt=16294, book20_ask_proxy_usdt=20441, funding_indicative=-0.007706, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.38%, turnover=11855838. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-24T19:00:03+00:00, last15m_closed_end=2026-10-24T19:00+00:00, prior8high=1.739200, depth_time=2026-10-24T19:00:19+00:00, book20_bid_proxy_usdt=8356, book20_ask_proxy_usdt=8881, funding_indicative=-0.006258, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.79%, turnover=14202542. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T19:00:03+00:00, last15m_closed_end=2026-10-24T19:00+00:00, prior8high=0.051840, depth_time=2026-10-24T19:00:14+00:00, book20_bid_proxy_usdt=38612, book20_ask_proxy_usdt=80238, funding_indicative=0.000012, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=1, 24h_change=-6.75%, turnover=60777220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-24T19:00:03+00:00, last15m_closed_end=2026-10-24T19:00+00:00, prior8high=0.074180, depth_time=2026-10-24T19:00:09+00:00, book20_bid_proxy_usdt=39728, book20_ask_proxy_usdt=33835, funding_indicative=-0.003276, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=1, 24h_change=-10.38%, turnover=12191736. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
