# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T18:30:11Z**
- feed_generated_utc: 2026-10-24T18:30:14+00:00
- source_sha256: `d959ee59c561f074d259a15bf24cd36396f497900cd9918129a69e8b575da153`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T18:30+00:00, close=80368.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T18:00+00:00, close=80238.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.094400|-3.33|94.55|-4.08|11876657|2.12|
|BR_USDT|0.464600|-0.44|23.69|-1.19|5253504|4.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.094400|0.091630|0.094400|0.50|N|Y/Y|N/N|Y|N|
|BR_USDT|0.464600|0.458600|0.464600|1.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T18:29:59+00:00, last15m_closed_end=2026-10-24T18:30+00:00, prior8high=0.097360, depth_time=2026-10-24T18:30:08+00:00, book20_bid_proxy_usdt=16242, book20_ask_proxy_usdt=22490, funding_indicative=-0.007684, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.33%, turnover=11876657. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-24T18:30:00+00:00, last15m_closed_end=2026-10-24T18:30+00:00, prior8high=0.479200, depth_time=2026-10-24T18:30:10+00:00, book20_bid_proxy_usdt=28463, book20_ask_proxy_usdt=32750, funding_indicative=0.000050, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.44%, turnover=5253504. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
