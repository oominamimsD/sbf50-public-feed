# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T22:45:14Z**
- feed_generated_utc: 2026-10-20T22:45:16+00:00
- source_sha256: `e554089ab74b1d36f700ac4f12989ce77441ebe2ce92c41fbfd3d919e399905f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T22:45+00:00, close=82977.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T22:00+00:00, close=82932.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.057314|-11.31|254.29|-11.79|7146010|0.17|
|BAT_USDT|0.193880|-10.14|9.30|-10.62|10091356|0.52|
|TIA_USDT|0.619300|-0.54|7.27|-1.02|46460955|1.61|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.057314|0.056252|0.057314|0.78|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.193880|0.194560|0.193880|1.67|Y|Y/Y|N/N|N|N|
|TIA_USDT|0.619300|0.623700|0.619300|2.03|Y|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T22:45:01+00:00, last15m_closed_end=2026-10-20T22:45+00:00, prior8high=0.059875, depth_time=2026-10-20T22:45:05+00:00, book20_bid_proxy_usdt=8195, book20_ask_proxy_usdt=13457, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.31%, turnover=7146010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T22:45:01+00:00, last15m_closed_end=2026-10-20T22:45+00:00, prior8high=0.200820, depth_time=2026-10-20T22:45:09+00:00, book20_bid_proxy_usdt=15132, book20_ask_proxy_usdt=19516, funding_indicative=0.000001, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-10.14%, turnover=10091356. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-20T22:45:01+00:00, last15m_closed_end=2026-10-20T22:45+00:00, prior8high=0.637500, depth_time=2026-10-20T22:45:13+00:00, book20_bid_proxy_usdt=248527, book20_ask_proxy_usdt=217160, funding_indicative=-0.000112, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.54%, turnover=46460955. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
