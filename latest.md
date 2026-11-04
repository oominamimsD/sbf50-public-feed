# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T09:30:14Z**
- feed_generated_utc: 2026-11-04T09:30:15+00:00
- source_sha256: `3c39a647982b7cf1919bb1d627c2aa06152c20f7279252e6ffe3d9a59a72c9cb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T09:30+00:00, close=78330.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T09:00+00:00, close=78473.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002937|-29.33|-86.09|-30.18|12321429|3.41|
|TRUMPOFFICIAL_USDT|1.471000|-8.51|-12.85|-9.36|10434605|6.80|
|Q_USDT|0.027910|-0.92|-56.10|-1.77|7320763|3.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002937|0.002914|0.002939|2.92|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.027910|0.027670|0.027910|1.82|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.471000|1.483000|1.471000|3.04|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T09:30:00+00:00, last15m_closed_end=2026-11-04T09:30+00:00, prior8high=0.003159, depth_time=2026-11-04T09:30:07+00:00, book20_bid_proxy_usdt=49011, book20_ask_proxy_usdt=52470, funding_indicative=0.000050, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-29.33%, turnover=12321429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T09:30:00+00:00, last15m_closed_end=2026-11-04T09:30+00:00, prior8high=0.028570, depth_time=2026-11-04T09:30:13+00:00, book20_bid_proxy_usdt=56068, book20_ask_proxy_usdt=41163, funding_indicative=-0.000477, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.92%, turnover=7320763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T09:30:00+00:00, last15m_closed_end=2026-11-04T09:30+00:00, prior8high=1.526000, depth_time=2026-11-04T09:30:10+00:00, book20_bid_proxy_usdt=2377678, book20_ask_proxy_usdt=2670101, funding_indicative=-0.000063, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.51%, turnover=10434605. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
