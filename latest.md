# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T20:45:14Z**
- feed_generated_utc: 2026-10-24T20:45:17+00:00
- source_sha256: `6c0970732630aa36a1a29ddc0f6d4bb407fd97045066d5756a7abd3aec67808a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T20:45+00:00, close=80522.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.059510|-11.70|92.27|-12.65|12498176|5.04|
|BIRB_USDT|0.091600|-6.20|88.78|-7.15|11837580|4.36|
|IRYS_USDT|0.044010|-4.42|244.90|-5.37|44492354|4.54|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.091600|0.088740|0.091600|0.54|N|Y/Y|N/N|Y|N|
|IRYS_USDT|0.044010|0.042300|0.044010|0.38|N|Y/Y|Y/N|Y|N|
|ORDER_USDT|0.059510|0.057390|0.059610|0.73|N|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T20:45:01+00:00, last15m_closed_end=2026-10-24T20:45+00:00, prior8high=0.094600, depth_time=2026-10-24T20:45:11+00:00, book20_bid_proxy_usdt=26121, book20_ask_proxy_usdt=22052, funding_indicative=-0.007862, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.20%, turnover=11837580. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T20:45:01+00:00, last15m_closed_end=2026-10-24T20:45+00:00, prior8high=0.047980, depth_time=2026-10-24T20:45:13+00:00, book20_bid_proxy_usdt=63169, book20_ask_proxy_usdt=66063, funding_indicative=0.000012, next_funding_utc=2026-10-24T21:00:00+00:00, funding_cycle_h=1, 24h_change=-4.42%, turnover=44492354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-24T20:45:01+00:00, last15m_closed_end=2026-10-24T20:45+00:00, prior8high=0.068660, depth_time=2026-10-24T20:45:09+00:00, book20_bid_proxy_usdt=81714, book20_ask_proxy_usdt=62344, funding_indicative=-0.001645, next_funding_utc=2026-10-24T21:00:00+00:00, funding_cycle_h=1, 24h_change=-11.70%, turnover=12498176. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
