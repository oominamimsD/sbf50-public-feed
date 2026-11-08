# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T16:45:13Z**
- feed_generated_utc: 2026-11-08T16:45:14+00:00
- source_sha256: `16b40d6f348441068033f9b0eeca55b6820e9c71cb50344e534b1e3fca3de47c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T16:45+00:00, close=75965.6, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001769|-9.65|51.91|-9.56|21434327|0.56|
|IDOL_USDT|0.030146|-2.31|53.22|-2.22|14302066|3.98|
|AKE_USDT|0.005278|-1.47|-42.37|-1.38|23359595|5.68|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005278|0.005235|0.005274|0.18|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.030146|0.029439|0.030146|1.12|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001769|0.001818|0.001763|3.14|Y|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T16:45:02+00:00, last15m_closed_end=2026-11-08T16:45+00:00, prior8high=0.005501, depth_time=2026-11-08T16:45:12+00:00, book20_bid_proxy_usdt=57294, book20_ask_proxy_usdt=53791, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.47%, turnover=23359595. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T16:45:02+00:00, last15m_closed_end=2026-11-08T16:45+00:00, prior8high=0.031336, depth_time=2026-11-08T16:45:10+00:00, book20_bid_proxy_usdt=5489, book20_ask_proxy_usdt=7419, funding_indicative=0.000931, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=14302066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T16:45:02+00:00, last15m_closed_end=2026-11-08T16:45+00:00, prior8high=0.001987, depth_time=2026-11-08T16:45:07+00:00, book20_bid_proxy_usdt=15508, book20_ask_proxy_usdt=6204, funding_indicative=-0.001453, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.65%, turnover=21434327. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
