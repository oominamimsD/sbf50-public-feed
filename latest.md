# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T21:00:18Z**
- feed_generated_utc: 2026-10-30T21:00:20+00:00
- source_sha256: `5cf8a90306dc37bdcf9b9d3393502ad9794d6780c3d849fb29f9cbb14a218d12`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T21:00+00:00, close=76891.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T21:00+00:00, close=76891.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.116600|-12.90|112.72|-12.02|6778720|3.58|
|LIT_USDT|2.714300|-3.89|-18.34|-3.01|12158884|0.37|
|Q_USDT|0.045870|-3.39|-61.23|-2.51|23879309|2.18|
|BLESS_USDT|0.009520|-3.36|16.65|-2.48|14559223|3.15|
|HYPE_USDT|89.897000|-2.64|14.65|-1.76|203164905|0.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009520|0.008786|0.009520|0.85|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.116600|1.072200|1.116600|0.69|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|89.897000|89.105000|89.897000|0.24|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.714300|2.683300|2.714300|0.14|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.045870|0.044090|0.045870|1.08|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T20:59:59+00:00, last15m_closed_end=2026-10-30T21:00+00:00, prior8high=0.009387, depth_time=2026-10-30T21:00:15+00:00, book20_bid_proxy_usdt=21113, book20_ask_proxy_usdt=17011, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.36%, turnover=14559223. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T20:59:59+00:00, last15m_closed_end=2026-10-30T21:00+00:00, prior8high=1.163600, depth_time=2026-10-30T21:00:07+00:00, book20_bid_proxy_usdt=9924, book20_ask_proxy_usdt=7826, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.90%, turnover=6778720. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T20:59:59+00:00, last15m_closed_end=2026-10-30T21:00+00:00, prior8high=90.924000, depth_time=2026-10-30T21:00:17+00:00, book20_bid_proxy_usdt=245077, book20_ask_proxy_usdt=71777, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.64%, turnover=203164905. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T20:59:59+00:00, last15m_closed_end=2026-10-30T21:00+00:00, prior8high=2.780500, depth_time=2026-10-30T21:00:08+00:00, book20_bid_proxy_usdt=28343, book20_ask_proxy_usdt=19969, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.89%, turnover=12158884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T20:59:59+00:00, last15m_closed_end=2026-10-30T21:00+00:00, prior8high=0.045830, depth_time=2026-10-30T21:00:12+00:00, book20_bid_proxy_usdt=30739, book20_ask_proxy_usdt=29890, funding_indicative=0.000052, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.39%, turnover=23879309. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
