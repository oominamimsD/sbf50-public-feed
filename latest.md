# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T18:15:13Z**
- feed_generated_utc: 2026-10-14T18:15:14+00:00
- source_sha256: `d07d71cbff9626a35ea454423f78b935c39812d87d5775699d2cf63fd0389a61`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T18:15+00:00, close=81629.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T18:00+00:00, close=81556.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T16:00+00:00, close=81600.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.138300|-10.11|72.95|-10.14|58806861|2.81|
|S_USDT|0.052560|-4.07|31.92|-4.10|7593272|7.62|
|STRK_USDT|0.076020|-1.50|53.69|-1.53|24725981|1.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.138300|2.064400|2.138300|0.65|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.076020|0.075170|0.076020|1.06|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.052560|0.052320|0.052560|0.45|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-14T18:14:59+00:00, last15m_closed_end=2026-10-14T18:15+00:00, prior8high=2.425200, depth_time=2026-10-14T18:15:07+00:00, book20_bid_proxy_usdt=12170, book20_ask_proxy_usdt=8335, funding_indicative=-0.000007, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-10.11%, turnover=58806861. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T18:14:59+00:00, last15m_closed_end=2026-10-14T18:15+00:00, prior8high=0.078300, depth_time=2026-10-14T18:15:11+00:00, book20_bid_proxy_usdt=241073, book20_ask_proxy_usdt=284923, funding_indicative=0.000042, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=24725981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T18:14:59+00:00, last15m_closed_end=2026-10-14T18:15+00:00, prior8high=0.055040, depth_time=2026-10-14T18:15:10+00:00, book20_bid_proxy_usdt=134104, book20_ask_proxy_usdt=163733, funding_indicative=-0.000058, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.07%, turnover=7593272. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
