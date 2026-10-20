# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T21:45:14Z**
- feed_generated_utc: 2026-10-20T21:45:16+00:00
- source_sha256: `2091f561e25f13a4ff2703e9f51c44fed601d944ab17c40efccadc9c1d651d91`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T21:45+00:00, close=82824.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T21:00+00:00, close=82810, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.058152|-10.02|259.47|-10.31|7169064|1.55|
|BAT_USDT|0.195220|-9.52|10.05|-9.81|10698526|1.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.058152|0.057751|0.058152|0.47|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.195220|0.198100|0.195230|1.58|Y|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T21:45:00+00:00, last15m_closed_end=2026-10-20T21:45+00:00, prior8high=0.062837, depth_time=2026-10-20T21:45:09+00:00, book20_bid_proxy_usdt=3246, book20_ask_proxy_usdt=4996, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.02%, turnover=7169064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T21:45:00+00:00, last15m_closed_end=2026-10-20T21:45+00:00, prior8high=0.204480, depth_time=2026-10-20T21:45:13+00:00, book20_bid_proxy_usdt=16840, book20_ask_proxy_usdt=17982, funding_indicative=0.000020, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-9.52%, turnover=10698526. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
