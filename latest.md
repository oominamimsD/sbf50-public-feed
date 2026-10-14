# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T16:30:09Z**
- feed_generated_utc: 2026-10-14T16:30:11+00:00
- source_sha256: `6d87354d16b2b3f4bac71cbf6c379520267681f4920911f0592b339f6ef519b7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T16:30+00:00, close=81704.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T16:00+00:00, close=81600.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T16:00+00:00, close=81600.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.053880|-1.66|35.24|-1.77|10414211|1.86|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|S_USDT|0.053880|0.054260|0.053870|1.19|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- S_USDT: quote_utc=2026-10-14T16:30:01+00:00, last15m_closed_end=2026-10-14T16:30+00:00, prior8high=0.055930, depth_time=2026-10-14T16:30:07+00:00, book20_bid_proxy_usdt=49424, book20_ask_proxy_usdt=90692, funding_indicative=-0.000074, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.66%, turnover=10414211. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
