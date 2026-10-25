# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T05:30:17Z**
- feed_generated_utc: 2026-10-25T05:30:19+00:00
- source_sha256: `e70efdb486f9342b7abee1b5445c1640a8809dbe21c3e0dae1dcc8dc38e41cf2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T05:30+00:00, close=80794, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T05:00+00:00, close=80894.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.083400|-14.60|71.88|-15.89|7698564|2.39|
|IRYS_USDT|0.040370|-12.33|216.37|-13.62|34043237|2.47|
|STRK_USDT|0.046770|0.08|-29.29|-1.21|8561138|4.27|
|DOT_USDT|1.040600|0.14|-6.87|-1.15|11556675|0.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.083400|0.078280|0.083400|0.60|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.040600|1.036400|1.040600|1.74|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.040370|0.038110|0.040180|0.83|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.046770|0.046520|0.046780|0.25|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T05:30:02+00:00, last15m_closed_end=2026-10-25T05:30+00:00, prior8high=0.091370, depth_time=2026-10-25T05:30:09+00:00, book20_bid_proxy_usdt=20568, book20_ask_proxy_usdt=12762, funding_indicative=-0.010645, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.60%, turnover=7698564. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T05:30:02+00:00, last15m_closed_end=2026-10-25T05:30+00:00, prior8high=1.044800, depth_time=2026-10-25T05:30:15+00:00, book20_bid_proxy_usdt=316063, book20_ask_proxy_usdt=244392, funding_indicative=-0.000096, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=0.14%, turnover=11556675. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T05:30:02+00:00, last15m_closed_end=2026-10-25T05:30+00:00, prior8high=0.049460, depth_time=2026-10-25T05:30:11+00:00, book20_bid_proxy_usdt=61782, book20_ask_proxy_usdt=57083, funding_indicative=-0.001121, next_funding_utc=2026-10-25T06:00:00+00:00, funding_cycle_h=1, 24h_change=-12.33%, turnover=34043237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T05:30:03+00:00, last15m_closed_end=2026-10-25T05:30+00:00, prior8high=0.047320, depth_time=2026-10-25T05:30:12+00:00, book20_bid_proxy_usdt=917137, book20_ask_proxy_usdt=657968, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=0.08%, turnover=8561138. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
