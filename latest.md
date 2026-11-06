# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T10:30:16Z**
- feed_generated_utc: 2026-11-06T10:30:17+00:00
- source_sha256: `62454c330c23b4430f1b6081c4acd823c4f5fde8f0e8b86ce7a66fe508d08394`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T10:30+00:00, close=76139.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T10:00+00:00, close=76151.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|268.580000|-3.77|-6.83|-3.93|7500614|4.47|
|XRP_USDT|1.198000|-3.74|-8.51|-3.90|476859566|0.83|
|XPL_USDT|0.057770|-1.38|-26.80|-1.54|12280831|1.73|
|QNT_USDT|189.300000|-1.31|-4.74|-1.47|36146925|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|268.580000|264.550000|268.580000|3.21|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.300000|188.370000|189.300000|0.78|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057770|0.057370|0.057770|4.99|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.198000|1.187400|1.198000|0.48|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T10:30:00+00:00, last15m_closed_end=2026-11-06T10:30+00:00, prior8high=269.310000, depth_time=2026-11-06T10:30:07+00:00, book20_bid_proxy_usdt=47218, book20_ask_proxy_usdt=104218, funding_indicative=-0.000045, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.77%, turnover=7500614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T10:30:00+00:00, last15m_closed_end=2026-11-06T10:30+00:00, prior8high=190.420000, depth_time=2026-11-06T10:30:15+00:00, book20_bid_proxy_usdt=99423, book20_ask_proxy_usdt=99722, funding_indicative=0.000018, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=36146925. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T10:30:00+00:00, last15m_closed_end=2026-11-06T10:30+00:00, prior8high=0.057950, depth_time=2026-11-06T10:30:13+00:00, book20_bid_proxy_usdt=496260, book20_ask_proxy_usdt=351034, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.38%, turnover=12280831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T10:30:00+00:00, last15m_closed_end=2026-11-06T10:30+00:00, prior8high=1.201800, depth_time=2026-11-06T10:30:10+00:00, book20_bid_proxy_usdt=4827016, book20_ask_proxy_usdt=3587684, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.74%, turnover=476859566. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
