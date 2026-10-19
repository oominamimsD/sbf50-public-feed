# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T22:25:30Z**
- feed_generated_utc: 2026-10-19T22:25:36+00:00
- source_sha256: `35d2b03f028d0e9f5f6400dd2c988c148230bc222f96e78fb0a43e7995b96486`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.1 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T22:15+00:00, close=82107.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T22:00+00:00, close=82012.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-19T20:00+00:00, close=81847.2, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CT_USDT|0.327530|-0.78|-4.26|-1.00|5152744|2.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.327530|0.324490|0.326170|0.63|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-19T22:25:17+00:00, last15m_closed_end=2026-10-19T22:15+00:00, prior8high=0.329680, depth_time=2026-10-19T22:25:26+00:00, book20_bid_proxy_usdt=11811, book20_ask_proxy_usdt=9383, funding_indicative=-0.000635, next_funding_utc=2026-10-20T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.78%, turnover=5152744. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
