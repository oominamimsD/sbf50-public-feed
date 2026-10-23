# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T17:30:17Z**
- feed_generated_utc: 2026-10-23T17:30:24+00:00
- source_sha256: `0caf9d353f8600ffca7be0a6ffe7d3eb6f0a66486aff8213aabaf6c8345a70bf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.11 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T17:30+00:00, close=81603, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T17:00+00:00, close=81682.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T16:00+00:00, close=81651.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BR_USDT|0.508300|-4.16|8.22|-4.10|8237368|3.94|
|ZRO_USDT|1.774600|-1.91|-15.54|-1.85|6669909|0.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BR_USDT|0.508300|0.497800|0.508300|0.63|N|N/N|N/Y|Y|N|
|ZRO_USDT|1.774600|1.789300|1.773000|1.22|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BR_USDT: quote_utc=2026-10-23T17:30:03+00:00, last15m_closed_end=2026-10-23T17:30+00:00, prior8high=0.557500, depth_time=2026-10-23T17:30:13+00:00, book20_bid_proxy_usdt=25144, book20_ask_proxy_usdt=22038, funding_indicative=0.000050, next_funding_utc=2026-10-23T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.16%, turnover=8237368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-23T17:30:03+00:00, last15m_closed_end=2026-10-23T17:30+00:00, prior8high=1.825900, depth_time=2026-10-23T17:30:16+00:00, book20_bid_proxy_usdt=66615, book20_ask_proxy_usdt=35107, funding_indicative=0.000037, next_funding_utc=2026-10-23T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.91%, turnover=6669909. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
