# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T01:00:12Z**
- feed_generated_utc: 2026-10-25T01:00:15+00:00
- source_sha256: `b74d9862948ac6a92c95f8dfe1228f60b3d66453eb9e3754a536700c4473e6a4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T01:00+00:00, close=80842.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T01:00+00:00, close=80842.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.034490|-25.10|170.29|-26.45|33781038|8.71|
|ORDER_USDT|0.055850|-17.13|80.45|-18.48|13257685|7.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.034490|0.033800|0.034530|4.50|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.055850|0.056630|0.055850|1.16|N|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-25T01:00:02+00:00, last15m_closed_end=2026-10-25T01:00+00:00, prior8high=0.047160, depth_time=2026-10-25T01:00:09+00:00, book20_bid_proxy_usdt=60948, book20_ask_proxy_usdt=32664, funding_indicative=-0.000416, next_funding_utc=2026-10-25T02:00:00+00:00, funding_cycle_h=1, 24h_change=-25.10%, turnover=33781038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T01:00:02+00:00, last15m_closed_end=2026-10-25T01:00+00:00, prior8high=0.073400, depth_time=2026-10-25T01:00:11+00:00, book20_bid_proxy_usdt=47280, book20_ask_proxy_usdt=46215, funding_indicative=-0.002784, next_funding_utc=2026-10-25T02:00:00+00:00, funding_cycle_h=1, 24h_change=-17.13%, turnover=13257685. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
