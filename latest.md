# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T16:30:12Z**
- feed_generated_utc: 2026-11-03T16:30:13+00:00
- source_sha256: `98056a63c04158a4a836eeeafae72110bc4b82b3e4bdc74dd294d6a1e996e574`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T16:30+00:00, close=77532.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BEAT_USDT|0.091490|-3.49|0.43|-3.33|8372758|2.19|
|AKE_USDT|0.004050|-2.55|-80.82|-2.39|12808506|2.47|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004050|0.003956|0.004050|0.98|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.091490|0.092610|0.091490|1.75|Y|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T16:30:00+00:00, last15m_closed_end=2026-11-03T16:30+00:00, prior8high=0.004218, depth_time=2026-11-03T16:30:10+00:00, book20_bid_proxy_usdt=28829, book20_ask_proxy_usdt=74188, funding_indicative=-0.000186, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.55%, turnover=12808506. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-03T16:30:00+00:00, last15m_closed_end=2026-11-03T16:30+00:00, prior8high=0.101890, depth_time=2026-11-03T16:30:08+00:00, book20_bid_proxy_usdt=11098, book20_ask_proxy_usdt=23368, funding_indicative=0.000347, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.49%, turnover=8372758. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
