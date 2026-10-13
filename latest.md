# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T16:15:12Z**
- feed_generated_utc: 2026-10-13T16:15:14+00:00
- source_sha256: `1036ad3ccb8e59ac8a121906f8fd3f213f9639def732d1c547c6bbf2bfcbffbc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T16:15+00:00, close=83416.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|RLC_USDT|0.910200|-1.40|11.02|-1.44|6188973|3.30|
|STRK_USDT|0.085810|-1.28|64.41|-1.32|51170125|2.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|RLC_USDT|0.910200|0.900600|0.911000|0.98|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085810|0.085110|0.085850|1.21|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- RLC_USDT: quote_utc=2026-10-13T16:15:04+00:00, last15m_closed_end=2026-10-13T16:15+00:00, prior8high=0.949500, depth_time=2026-10-13T16:15:07+00:00, book20_bid_proxy_usdt=61046, book20_ask_proxy_usdt=76752, funding_indicative=-0.000751, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.40%, turnover=6188973. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T16:15:04+00:00, last15m_closed_end=2026-10-13T16:15+00:00, prior8high=0.089320, depth_time=2026-10-13T16:15:11+00:00, book20_bid_proxy_usdt=162184, book20_ask_proxy_usdt=255296, funding_indicative=0.000000, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=51170125. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
