# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T23:30:11Z**
- feed_generated_utc: 2026-11-07T23:30:12+00:00
- source_sha256: `74931ef9606b86225278e78ea1eea61d457f9e9728102b59bb1057760f3e3c2e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T23:30+00:00, close=75753.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T23:00+00:00, close=75749.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T20:00+00:00, close=75772.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001985|-2.53|69.06|-2.56|30201535|0.50|
|QNT_USDT|195.430000|-1.71|-2.79|-1.74|42740327|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ONE_USDT|0.001985|0.001934|0.001986|0.45|N|N/N|N/N|Y|N|
|QNT_USDT|195.430000|195.250000|195.430000|1.78|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ONE_USDT: quote_utc=2026-11-07T23:30:01+00:00, last15m_closed_end=2026-11-07T23:30+00:00, prior8high=0.002383, depth_time=2026-11-07T23:30:07+00:00, book20_bid_proxy_usdt=16470, book20_ask_proxy_usdt=15560, funding_indicative=-0.000046, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=30201535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-07T23:30:01+00:00, last15m_closed_end=2026-11-07T23:30+00:00, prior8high=197.260000, depth_time=2026-11-07T23:30:09+00:00, book20_bid_proxy_usdt=70940, book20_ask_proxy_usdt=99595, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=42740327. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
