# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T12:15:27Z**
- feed_generated_utc: 2026-10-26T12:15:30+00:00
- source_sha256: `f9a999f89c00fe9b002930613114477b7759b09fc3a0f5e19fdaceec43b6e3f0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T12:15+00:00, close=80360, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CAP_USDT|0.075300|-29.94|13.23|-29.64|7127735|4.00|
|IRYS_USDT|0.028280|-26.43|131.80|-26.13|12109713|3.54|
|APR_USDT|0.033690|-18.44|23.67|-18.14|7177232|5.93|
|BTW_USDT|1.415500|-14.67|-38.60|-14.37|11679391|0.71|
|WLD_USDT|0.441400|-3.32|-7.32|-3.02|60426242|2.27|
|LIT_USDT|3.094900|-2.62|5.61|-2.32|5366348|0.32|
|XMR_USDT|591.400000|-2.61|1.52|-2.31|5715827|0.68|
|STRK_USDT|0.044670|-2.33|-27.43|-2.03|9205462|2.24|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.033690|0.033120|0.033690|0.80|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.415500|1.453200|1.415500|9.79|Y|Y/Y|Y/Y|Y|Y|
|CAP_USDT|0.075300|0.070960|0.075300|0.87|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.028280|0.027970|0.028270|0.96|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.094900|3.066900|3.094900|0.80|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044670|0.044360|0.044670|1.67|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.441400|0.435800|0.441400|0.48|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|591.400000|588.790000|591.400000|1.21|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T12:14:59+00:00, last15m_closed_end=2026-10-26T12:15+00:00, prior8high=0.035450, depth_time=2026-10-26T12:15:12+00:00, book20_bid_proxy_usdt=59838, book20_ask_proxy_usdt=72702, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-18.44%, turnover=7177232. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T12:14:59+00:00, last15m_closed_end=2026-10-26T12:15+00:00, prior8high=1.524700, depth_time=2026-10-26T12:15:15+00:00, book20_bid_proxy_usdt=24832, book20_ask_proxy_usdt=24306, funding_indicative=-0.012811, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.67%, turnover=11679391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T12:14:59+00:00, last15m_closed_end=2026-10-26T12:15+00:00, prior8high=0.085200, depth_time=2026-10-26T12:15:08+00:00, book20_bid_proxy_usdt=51194, book20_ask_proxy_usdt=62075, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-29.94%, turnover=7127735. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T12:14:59+00:00, last15m_closed_end=2026-10-26T12:15+00:00, prior8high=0.029760, depth_time=2026-10-26T12:15:10+00:00, book20_bid_proxy_usdt=92438, book20_ask_proxy_usdt=76338, funding_indicative=-0.000395, next_funding_utc=2026-10-26T13:00:00+00:00, funding_cycle_h=1, 24h_change=-26.43%, turnover=12109713. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T12:14:59+00:00, last15m_closed_end=2026-10-26T12:15+00:00, prior8high=3.116600, depth_time=2026-10-26T12:15:21+00:00, book20_bid_proxy_usdt=27677, book20_ask_proxy_usdt=19093, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.62%, turnover=5366348. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T12:15:00+00:00, last15m_closed_end=2026-10-26T12:15+00:00, prior8high=0.045620, depth_time=2026-10-26T12:15:24+00:00, book20_bid_proxy_usdt=970654, book20_ask_proxy_usdt=796371, funding_indicative=-0.000042, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=9205462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T12:14:59+00:00, last15m_closed_end=2026-10-26T12:15+00:00, prior8high=0.441800, depth_time=2026-10-26T12:15:17+00:00, book20_bid_proxy_usdt=2771604, book20_ask_proxy_usdt=2603944, funding_indicative=-0.000150, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.32%, turnover=60426242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T12:14:59+00:00, last15m_closed_end=2026-10-26T12:15+00:00, prior8high=592.020000, depth_time=2026-10-26T12:15:22+00:00, book20_bid_proxy_usdt=13191, book20_ask_proxy_usdt=18601, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=5715827. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
