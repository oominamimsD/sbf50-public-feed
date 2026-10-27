# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T22:30:12Z**
- feed_generated_utc: 2026-10-27T22:30:15+00:00
- source_sha256: `534e85e2bf10751de06759d273a61f1407ed94976440f0346a99d5417da2ea5c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T22:30+00:00, close=80885.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T22:00+00:00, close=80874.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T20:00+00:00, close=80778.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.054076|-14.95|-55.94|-15.39|49425337|2.40|
|SYN_USDT|0.179200|-1.21|-2.39|-1.65|5886349|5.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|Q_USDT|0.054076|0.052810|0.054100|1.14|N|Y/Y|Y/Y|N|N|
|SYN_USDT|0.179200|0.178600|0.179200|0.41|N|N/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- Q_USDT: quote_utc=2026-10-27T22:30:00+00:00, last15m_closed_end=2026-10-27T22:30+00:00, prior8high=0.055980, depth_time=2026-10-27T22:30:09+00:00, book20_bid_proxy_usdt=3626, book20_ask_proxy_usdt=2171, funding_indicative=-0.000026, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-14.95%, turnover=49425337. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SYN_USDT: quote_utc=2026-10-27T22:30:00+00:00, last15m_closed_end=2026-10-27T22:30+00:00, prior8high=0.183400, depth_time=2026-10-27T22:30:11+00:00, book20_bid_proxy_usdt=95697, book20_ask_proxy_usdt=93328, funding_indicative=0.000050, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.21%, turnover=5886349. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
