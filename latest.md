# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T17:30:12Z**
- feed_generated_utc: 2026-10-26T17:30:15+00:00
- source_sha256: `be336de3ea61fb33861dd6e231f958ef837012b6f0e7360d75d68306d40b864d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T17:30+00:00, close=80318, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T17:00+00:00, close=80200, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T16:00+00:00, close=80399.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.027030|-1.99|120.11|-1.85|10063872|3.70|
|NEAR_USDT|4.506000|-1.46|-8.11|-1.32|127758613|2.22|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.027030|0.026240|0.027040|0.29|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.506000|4.474000|4.506000|1.09|N|Y/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-26T17:30:03+00:00, last15m_closed_end=2026-10-26T17:30+00:00, prior8high=0.028060, depth_time=2026-10-26T17:30:09+00:00, book20_bid_proxy_usdt=70918, book20_ask_proxy_usdt=90642, funding_indicative=-0.000748, next_funding_utc=2026-10-26T18:00:00+00:00, funding_cycle_h=1, 24h_change=-1.99%, turnover=10063872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T17:30:03+00:00, last15m_closed_end=2026-10-26T17:30+00:00, prior8high=4.657000, depth_time=2026-10-26T17:30:12+00:00, book20_bid_proxy_usdt=5855811, book20_ask_proxy_usdt=2560847, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=127758613. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
