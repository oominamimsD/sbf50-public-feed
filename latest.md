# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T19:45:08Z**
- feed_generated_utc: 2026-11-07T19:45:09+00:00
- source_sha256: `0419f0dc038463338bbf479adfe6a4d43d0a6f854351630b6b14d9b8b867b863`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T19:45+00:00, close=75720.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T19:00+00:00, close=75770.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T16:00+00:00, close=75725.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.122200|-1.76|-60.66|-1.76|13882907|8.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|UAI_USDT|0.122200|0.121600|0.122200|1.35|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- UAI_USDT: quote_utc=2026-11-07T19:45:02+00:00, last15m_closed_end=2026-11-07T19:45+00:00, prior8high=0.126600, depth_time=2026-11-07T19:45:08+00:00, book20_bid_proxy_usdt=218102, book20_ask_proxy_usdt=154819, funding_indicative=0.000050, next_funding_utc=2026-11-07T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.76%, turnover=13882907. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
