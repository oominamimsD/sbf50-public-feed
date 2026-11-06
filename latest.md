# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T16:30:11Z**
- feed_generated_utc: 2026-11-06T16:30:12+00:00
- source_sha256: `72c09bc206fe9e387d259364bcda328a2983f2b8f7313c2e6a8e7d437650be94`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T16:30+00:00, close=75753.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T16:00+00:00, close=75832.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T16:00+00:00, close=75832.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003603|-4.30|-80.95|-4.21|54081640|8.33|
|ANTHROPIC_USDT|1402.580000|-2.00|-16.33|-1.91|5863494|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003603|0.002920|0.003600|5.51|N|Y/N|Y/N|Y|N|
|ANTHROPIC_USDT|1402.580000|1397.510000|1402.580000|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T16:30:01+00:00, last15m_closed_end=2026-11-06T16:30+00:00, prior8high=0.006292, depth_time=2026-11-06T16:30:08+00:00, book20_bid_proxy_usdt=20138, book20_ask_proxy_usdt=17462, funding_indicative=-0.000603, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.30%, turnover=54081640. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-06T16:30:01+00:00, last15m_closed_end=2026-11-06T16:30+00:00, prior8high=1472.780000, depth_time=2026-11-06T16:30:10+00:00, book20_bid_proxy_usdt=13998, book20_ask_proxy_usdt=20614, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=5863494. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
