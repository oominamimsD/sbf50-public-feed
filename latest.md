# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T21:30:13Z**
- feed_generated_utc: 2026-10-27T21:30:16+00:00
- source_sha256: `c349a419dc0623da46f08deface3c68396761f0a99f640448e692d3c1c592565`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T21:30+00:00, close=80703.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T21:00+00:00, close=80753.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T20:00+00:00, close=80778.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.054280|-14.63|-55.78|-14.84|51276500|3.14|
|UNI_USDT|7.048000|-1.55|-3.06|-1.76|13136156|1.42|
|ARB_USDT|0.166000|-1.48|-12.14|-1.69|15019215|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.166000|0.166630|0.165990|2.68|Y|Y/Y|Y/Y|N|Y|
|Q_USDT|0.054280|0.051125|0.054415|0.60|N|Y/Y|Y/Y|N|N|
|UNI_USDT|7.048000|7.051000|7.048000|3.91|Y|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-27T21:30:02+00:00, last15m_closed_end=2026-10-27T21:30+00:00, prior8high=0.168670, depth_time=2026-10-27T21:30:12+00:00, book20_bid_proxy_usdt=55900, book20_ask_proxy_usdt=115635, funding_indicative=0.000011, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=15019215. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-27T21:30:02+00:00, last15m_closed_end=2026-10-27T21:30+00:00, prior8high=0.055664, depth_time=2026-10-27T21:30:08+00:00, book20_bid_proxy_usdt=4779, book20_ask_proxy_usdt=4905, funding_indicative=0.000027, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-14.63%, turnover=51276500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-27T21:30:02+00:00, last15m_closed_end=2026-10-27T21:30+00:00, prior8high=7.107000, depth_time=2026-10-27T21:30:09+00:00, book20_bid_proxy_usdt=2233334, book20_ask_proxy_usdt=2177877, funding_indicative=0.000051, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=13136156. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
