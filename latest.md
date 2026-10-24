# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T16:15:12Z**
- feed_generated_utc: 2026-10-24T16:15:15+00:00
- source_sha256: `a7ca4dbf1515e47508d8075a77e78c1e61d55ead583ce1a346f4b729d70d1706`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T16:15+00:00, close=79804.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.028677|-1.89|-0.98|-1.91|13022942|6.63|
|BIRB_USDT|0.095990|-1.71|97.83|-1.73|12409727|5.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028677|0.028706|0.028676|0.60|N|Y/Y|Y/Y|Y|N|
|BIRB_USDT|0.095990|0.094440|0.096090|1.02|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-24T16:15:03+00:00, last15m_closed_end=2026-10-24T16:15+00:00, prior8high=0.030504, depth_time=2026-10-24T16:15:09+00:00, book20_bid_proxy_usdt=16998, book20_ask_proxy_usdt=26065, funding_indicative=0.000050, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.89%, turnover=13022942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-24T16:15:03+00:00, last15m_closed_end=2026-10-24T16:15+00:00, prior8high=0.117460, depth_time=2026-10-24T16:15:11+00:00, book20_bid_proxy_usdt=19836, book20_ask_proxy_usdt=9449, funding_indicative=-0.009158, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=12409727. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
