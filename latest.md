# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T17:30:10Z**
- feed_generated_utc: 2026-10-15T17:30:11+00:00
- source_sha256: `def0a0efa4ce02ade51b7d65df5108279a10f13824cd16386e5cf36f597a0819`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T17:30+00:00, close=82349.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T17:00+00:00, close=82081.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T16:00+00:00, close=82375.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.051100|-4.12|53.49|-4.09|12394158|3.92|
|BTW_USDT|1.860500|-2.45|34.01|-2.42|29668265|0.54|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.860500|1.873000|1.860800|1.39|Y|Y/Y|Y/Y|Y|Y|
|WAL_USDT|0.051100|0.050240|0.051100|0.39|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-15T17:30:00+00:00, last15m_closed_end=2026-10-15T17:30+00:00, prior8high=1.943600, depth_time=2026-10-15T17:30:09+00:00, book20_bid_proxy_usdt=11145, book20_ask_proxy_usdt=9857, funding_indicative=0.000050, next_funding_utc=2026-10-15T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.45%, turnover=29668265. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T17:30:00+00:00, last15m_closed_end=2026-10-15T17:30+00:00, prior8high=0.055770, depth_time=2026-10-15T17:30:07+00:00, book20_bid_proxy_usdt=168137, book20_ask_proxy_usdt=150192, funding_indicative=-0.000557, next_funding_utc=2026-10-15T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.12%, turnover=12394158. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
