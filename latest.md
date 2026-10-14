# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T05:30:15Z**
- feed_generated_utc: 2026-10-14T05:30:17+00:00
- source_sha256: `3550289b950ad9ab0ea62a1b4ae61766b042e5dac5c431a69d330488c6f5daa2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T05:30+00:00, close=83567.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T05:00+00:00, close=83704.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.082600|-4.98|58.26|-5.18|29663735|2.42|
|W_USDT|0.016294|-3.02|12.27|-3.22|7013202|1.84|
|MAGIC_USDT|0.115270|-2.84|69.21|-3.04|5509917|0.87|
|TIA_USDT|0.571500|-1.00|19.98|-1.20|45768795|1.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.115270|0.113190|0.115290|0.30|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.082600|0.081770|0.082680|4.73|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.571500|0.571300|0.571500|3.64|N|N/Y|N/N|N|N|
|W_USDT|0.016294|0.016080|0.016294|2.01|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T05:29:59+00:00, last15m_closed_end=2026-10-14T05:30+00:00, prior8high=0.116740, depth_time=2026-10-14T05:30:12+00:00, book20_bid_proxy_usdt=169684, book20_ask_proxy_usdt=186457, funding_indicative=-0.000122, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=5509917. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T05:29:59+00:00, last15m_closed_end=2026-10-14T05:30+00:00, prior8high=0.085530, depth_time=2026-10-14T05:30:07+00:00, book20_bid_proxy_usdt=167873, book20_ask_proxy_usdt=164371, funding_indicative=0.000050, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.98%, turnover=29663735. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T05:29:59+00:00, last15m_closed_end=2026-10-14T05:30+00:00, prior8high=0.581500, depth_time=2026-10-14T05:30:15+00:00, book20_bid_proxy_usdt=135172, book20_ask_proxy_usdt=151367, funding_indicative=-0.000026, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.00%, turnover=45768795. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T05:29:59+00:00, last15m_closed_end=2026-10-14T05:30+00:00, prior8high=0.016644, depth_time=2026-10-14T05:30:10+00:00, book20_bid_proxy_usdt=27202, book20_ask_proxy_usdt=18920, funding_indicative=-0.000129, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=7013202. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
