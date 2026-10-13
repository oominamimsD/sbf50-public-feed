# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T17:15:14Z**
- feed_generated_utc: 2026-10-13T17:15:16+00:00
- source_sha256: `0cad67f5d37ef4340f17e5d092cfb9b6c9d5c8e89b559bf8c65287d59a6ff3d8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T17:15+00:00, close=83156.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T17:00+00:00, close=83347, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|W_USDT|0.016364|-2.61|12.76|-2.33|11714191|9.78|
|STRK_USDT|0.085050|-2.16|62.96|-1.88|49821242|1.18|
|RLC_USDT|0.909900|-1.44|10.99|-1.16|5833931|1.10|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|RLC_USDT|0.909900|0.907600|0.909800|1.04|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085050|0.082420|0.085050|0.91|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016364|0.016711|0.016364|2.26|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- RLC_USDT: quote_utc=2026-10-13T17:15:03+00:00, last15m_closed_end=2026-10-13T17:15+00:00, prior8high=0.949500, depth_time=2026-10-13T17:15:12+00:00, book20_bid_proxy_usdt=70384, book20_ask_proxy_usdt=69678, funding_indicative=-0.000744, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.44%, turnover=5833931. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T17:15:03+00:00, last15m_closed_end=2026-10-13T17:15+00:00, prior8high=0.087530, depth_time=2026-10-13T17:15:11+00:00, book20_bid_proxy_usdt=188862, book20_ask_proxy_usdt=321129, funding_indicative=0.000004, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.16%, turnover=49821242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T17:15:03+00:00, last15m_closed_end=2026-10-13T17:15+00:00, prior8high=0.018109, depth_time=2026-10-13T17:15:08+00:00, book20_bid_proxy_usdt=53276, book20_ask_proxy_usdt=29525, funding_indicative=-0.000326, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=11714191. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
