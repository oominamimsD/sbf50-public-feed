# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T17:15:11Z**
- feed_generated_utc: 2026-11-03T17:15:12+00:00
- source_sha256: `715c7c1c1db00c82d03b22f58c6a623b7b816da0bafd812a976874e2aeb53b89`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T17:15+00:00, close=77723.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T17:00+00:00, close=77713.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BEAT_USDT|0.092080|-2.86|1.08|-2.93|8818809|1.09|
|AKE_USDT|0.004044|-2.69|-80.85|-2.76|12164677|4.95|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004044|0.003956|0.004044|1.02|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.092080|0.089460|0.092080|0.68|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T17:15:00+00:00, last15m_closed_end=2026-11-03T17:15+00:00, prior8high=0.004218, depth_time=2026-11-03T17:15:10+00:00, book20_bid_proxy_usdt=39796, book20_ask_proxy_usdt=31703, funding_indicative=-0.000447, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=12164677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-03T17:15:00+00:00, last15m_closed_end=2026-11-03T17:15+00:00, prior8high=0.099590, depth_time=2026-11-03T17:15:08+00:00, book20_bid_proxy_usdt=19283, book20_ask_proxy_usdt=18491, funding_indicative=0.000298, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=8818809. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
