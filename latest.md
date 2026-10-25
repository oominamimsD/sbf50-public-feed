# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T17:45:11Z**
- feed_generated_utc: 2026-10-25T17:45:13+00:00
- source_sha256: `a3823c4458a7a6258d815d2a48b1a8e9a05b0fc33369325e6f01d926deeee59f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T17:45+00:00, close=80792.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T17:00+00:00, close=80777.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T16:00+00:00, close=80602.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.037000|-3.74|203.27|-3.97|22309479|2.71|
|BTW_USDT|1.630300|-1.72|-29.28|-1.95|13063120|0.61|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.630300|1.557100|1.630300|0.41|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.037000|0.035970|0.037000|0.41|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-25T17:45:00+00:00, last15m_closed_end=2026-10-25T17:45+00:00, prior8high=1.687100, depth_time=2026-10-25T17:45:10+00:00, book20_bid_proxy_usdt=11898, book20_ask_proxy_usdt=18439, funding_indicative=-0.008196, next_funding_utc=2026-10-25T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=13063120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T17:45:00+00:00, last15m_closed_end=2026-10-25T17:45+00:00, prior8high=0.039980, depth_time=2026-10-25T17:45:07+00:00, book20_bid_proxy_usdt=59422, book20_ask_proxy_usdt=59941, funding_indicative=-0.000017, next_funding_utc=2026-10-25T18:00:00+00:00, funding_cycle_h=1, 24h_change=-3.74%, turnover=22309479. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
