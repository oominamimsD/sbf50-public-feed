# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T03:15:21Z**
- feed_generated_utc: 2026-10-19T03:15:23+00:00
- source_sha256: `c979e0d71dc052de6e1b81aade2eaaa4f263d2d56e5e5b32a9505ea8222564c2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T03:15+00:00, close=82594.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T03:00+00:00, close=82682.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.171000|-4.68|61.32|-6.47|7674354|5.85|
|BTW_USDT|2.246200|-2.56|33.52|-4.35|21634784|6.68|
|BAT_USDT|0.171420|-2.25|2.86|-4.04|6268334|1.17|
|HBAR_USDT|0.084390|-1.62|-10.01|-3.41|51378075|1.19|
|STRK_USDT|0.060800|-1.23|-49.02|-3.02|17159880|1.65|
|AGT_USDT|0.066793|-1.08|277.68|-2.87|7739348|2.10|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066793|0.061750|0.066793|3.80|N|Y/Y|N/N|N|N|
|BAT_USDT|0.171420|0.170000|0.171420|0.28|N|Y/Y|Y/Y|N|N|
|BTW_USDT|2.246200|2.237300|2.245600|0.66|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084390|0.083740|0.084390|0.69|N|Y/Y|N/Y|N|N|
|ICNT_USDT|0.171000|0.163100|0.171000|1.68|N|Y/Y|N/N|N|N|
|STRK_USDT|0.060800|0.060390|0.060800|0.31|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T03:14:59+00:00, last15m_closed_end=2026-10-19T03:15+00:00, prior8high=0.067918, depth_time=2026-10-19T03:15:19+00:00, book20_bid_proxy_usdt=2376, book20_ask_proxy_usdt=2112, funding_indicative=0.000167, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.08%, turnover=7739348. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-19T03:14:59+00:00, last15m_closed_end=2026-10-19T03:15+00:00, prior8high=0.176060, depth_time=2026-10-19T03:15:12+00:00, book20_bid_proxy_usdt=26309, book20_ask_proxy_usdt=25674, funding_indicative=0.000100, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=6268334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T03:14:59+00:00, last15m_closed_end=2026-10-19T03:15+00:00, prior8high=2.347600, depth_time=2026-10-19T03:15:10+00:00, book20_bid_proxy_usdt=7876, book20_ask_proxy_usdt=10811, funding_indicative=-0.000302, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=21634784. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T03:14:59+00:00, last15m_closed_end=2026-10-19T03:15+00:00, prior8high=0.084670, depth_time=2026-10-19T03:15:15+00:00, book20_bid_proxy_usdt=967006, book20_ask_proxy_usdt=826507, funding_indicative=-0.000025, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=51378075. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T03:14:59+00:00, last15m_closed_end=2026-10-19T03:15+00:00, prior8high=0.183100, depth_time=2026-10-19T03:15:08+00:00, book20_bid_proxy_usdt=143266, book20_ask_proxy_usdt=127439, funding_indicative=-0.000061, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.68%, turnover=7674354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T03:14:59+00:00, last15m_closed_end=2026-10-19T03:15+00:00, prior8high=0.061960, depth_time=2026-10-19T03:15:18+00:00, book20_bid_proxy_usdt=535682, book20_ask_proxy_usdt=228729, funding_indicative=0.000001, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.23%, turnover=17159880. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
