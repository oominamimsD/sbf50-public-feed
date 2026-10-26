# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T13:45:26Z**
- feed_generated_utc: 2026-10-26T13:45:30+00:00
- source_sha256: `0c48b564b950202d7b44813995b2a8cd156507e96fcc74be672fad9bca8709e6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T13:45+00:00, close=79747.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T13:00+00:00, close=80301.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.027690|-27.96|126.96|-26.91|12435550|7.23|
|APR_USDT|0.032690|-20.86|20.00|-19.81|6470838|6.11|
|BTW_USDT|1.411300|-14.92|-38.78|-13.87|11238575|3.54|
|WLD_USDT|0.439600|-3.72|-7.70|-2.67|61842313|2.27|
|LIT_USDT|3.065000|-3.56|4.59|-2.51|5222243|0.33|
|STRK_USDT|0.044600|-2.49|-27.55|-1.44|9568313|2.24|
|XMR_USDT|592.110000|-2.49|1.64|-1.44|5616677|1.01|
|DOT_USDT|1.015700|-2.26|-5.02|-1.21|8973926|0.98|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.032690|0.031070|0.032690|0.99|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.411300|1.395000|1.411300|2.15|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.015700|1.013300|1.015700|2.95|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.027690|0.027500|0.027690|1.56|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.065000|3.047200|3.065000|3.78|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044600|0.044200|0.044590|1.34|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.439600|0.435800|0.439600|2.36|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|592.110000|588.980000|592.110000|1.73|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T13:45:02+00:00, last15m_closed_end=2026-10-26T13:45+00:00, prior8high=0.037130, depth_time=2026-10-26T13:45:10+00:00, book20_bid_proxy_usdt=31219, book20_ask_proxy_usdt=36234, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.86%, turnover=6470838. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T13:45:03+00:00, last15m_closed_end=2026-10-26T13:45+00:00, prior8high=1.496900, depth_time=2026-10-26T13:45:13+00:00, book20_bid_proxy_usdt=20557, book20_ask_proxy_usdt=18887, funding_indicative=-0.015868, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.92%, turnover=11238575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T13:45:03+00:00, last15m_closed_end=2026-10-26T13:45+00:00, prior8high=1.028300, depth_time=2026-10-26T13:45:26+00:00, book20_bid_proxy_usdt=222413, book20_ask_proxy_usdt=136462, funding_indicative=-0.000035, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=8973926. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T13:45:02+00:00, last15m_closed_end=2026-10-26T13:45+00:00, prior8high=0.029430, depth_time=2026-10-26T13:45:08+00:00, book20_bid_proxy_usdt=92777, book20_ask_proxy_usdt=78690, funding_indicative=-0.000716, next_funding_utc=2026-10-26T14:00:00+00:00, funding_cycle_h=1, 24h_change=-27.96%, turnover=12435550. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T13:45:03+00:00, last15m_closed_end=2026-10-26T13:45+00:00, prior8high=3.115900, depth_time=2026-10-26T13:45:18+00:00, book20_bid_proxy_usdt=23154, book20_ask_proxy_usdt=33020, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.56%, turnover=5222243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T13:45:03+00:00, last15m_closed_end=2026-10-26T13:45+00:00, prior8high=0.044830, depth_time=2026-10-26T13:45:20+00:00, book20_bid_proxy_usdt=749176, book20_ask_proxy_usdt=666773, funding_indicative=0.000007, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.49%, turnover=9568313. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T13:45:02+00:00, last15m_closed_end=2026-10-26T13:45+00:00, prior8high=0.444700, depth_time=2026-10-26T13:45:16+00:00, book20_bid_proxy_usdt=2424859, book20_ask_proxy_usdt=2035503, funding_indicative=-0.000156, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=61842313. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T13:45:03+00:00, last15m_closed_end=2026-10-26T13:45+00:00, prior8high=594.610000, depth_time=2026-10-26T13:45:23+00:00, book20_bid_proxy_usdt=16019, book20_ask_proxy_usdt=20999, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.49%, turnover=5616677. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
