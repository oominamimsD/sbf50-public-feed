# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T02:30:13Z**
- feed_generated_utc: 2026-10-14T02:30:14+00:00
- source_sha256: `ce4ac8f993dd7741dad3184e6db88098d124bbbb691a6c021bf60440b4e99e29`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T02:30+00:00, close=83263.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T02:00+00:00, close=83281.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|OGN_USDT|0.034060|-3.23|51.98|-3.08|5030401|2.94|
|MAGIC_USDT|0.116120|-2.13|70.46|-1.98|7368746|4.31|
|STRK_USDT|0.085080|-2.12|63.01|-1.97|31206370|1.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.116120|0.115510|0.116110|1.26|N|Y/Y|N/N|N|N|
|OGN_USDT|0.034060|0.034090|0.034060|0.37|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.085080|0.084230|0.085080|0.19|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T02:29:59+00:00, last15m_closed_end=2026-10-14T02:30+00:00, prior8high=0.123370, depth_time=2026-10-14T02:30:10+00:00, book20_bid_proxy_usdt=184939, book20_ask_proxy_usdt=181406, funding_indicative=-0.000077, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=7368746. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-14T02:29:59+00:00, last15m_closed_end=2026-10-14T02:30+00:00, prior8high=0.035070, depth_time=2026-10-14T02:30:07+00:00, book20_bid_proxy_usdt=173621, book20_ask_proxy_usdt=126789, funding_indicative=-0.000168, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=5030401. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T02:29:59+00:00, last15m_closed_end=2026-10-14T02:30+00:00, prior8high=0.086530, depth_time=2026-10-14T02:30:12+00:00, book20_bid_proxy_usdt=208502, book20_ask_proxy_usdt=268765, funding_indicative=0.000018, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=31206370. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
