# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T20:30:13Z**
- feed_generated_utc: 2026-10-25T20:30:15+00:00
- source_sha256: `7af6b7fd106fc398457609d3d69a859a7ee622fde03d39a62d3218f88bb36d32`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T20:30+00:00, close=80512.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.035950|-6.47|194.67|-6.36|20590669|2.78|
|USELESS_USDT|0.170040|-1.46|20.22|-1.35|5235912|0.59|
|T_USDT|0.005317|-1.22|13.07|-1.11|8501898|1.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.035950|0.035650|0.035970|0.56|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.005317|0.005298|0.005317|1.57|N|Y/Y|N/N|Y|N|
|USELESS_USDT|0.170040|0.166550|0.170000|1.03|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-25T20:30:02+00:00, last15m_closed_end=2026-10-25T20:30+00:00, prior8high=0.036760, depth_time=2026-10-25T20:30:07+00:00, book20_bid_proxy_usdt=59559, book20_ask_proxy_usdt=61959, funding_indicative=-0.000048, next_funding_utc=2026-10-25T21:00:00+00:00, funding_cycle_h=1, 24h_change=-6.47%, turnover=20590669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-25T20:30:02+00:00, last15m_closed_end=2026-10-25T20:30+00:00, prior8high=0.005495, depth_time=2026-10-25T20:30:11+00:00, book20_bid_proxy_usdt=61520, book20_ask_proxy_usdt=65312, funding_indicative=-0.002845, next_funding_utc=2026-10-25T21:00:00+00:00, funding_cycle_h=1, 24h_change=-1.22%, turnover=8501898. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T20:30:03+00:00, last15m_closed_end=2026-10-25T20:30+00:00, prior8high=0.170380, depth_time=2026-10-25T20:30:07+00:00, book20_bid_proxy_usdt=23384, book20_ask_proxy_usdt=32159, funding_indicative=0.000114, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.46%, turnover=5235912. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
