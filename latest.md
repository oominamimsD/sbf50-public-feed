# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T19:30:20Z**
- feed_generated_utc: 2026-10-24T19:30:23+00:00
- source_sha256: `0dbf2c56273f5c4a02a5dfca4bdfa97e09756a9025eb7829b353a00d716b2a78`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T19:30+00:00, close=80501.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T19:00+00:00, close=80503.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.059380|-11.89|91.85|-12.81|12316612|5.05|
|BIRB_USDT|0.093960|-3.78|93.65|-4.70|11888348|1.06|
|IRYS_USDT|0.044440|-3.49|248.27|-4.41|61262148|2.25|
|BTW_USDT|1.711100|-1.73|-24.60|-2.65|14348877|2.34|
|AGT_USDT|0.066150|-1.16|-8.19|-2.08|10336463|3.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066150|0.065300|0.066180|0.53|N|Y/Y|Y/N|Y|N|
|BIRB_USDT|0.093960|0.088740|0.094090|0.56|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.711100|1.704100|1.711100|1.21|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.044440|0.042370|0.044490|1.14|N|Y/Y|Y/N|Y|N|
|ORDER_USDT|0.059380|0.057390|0.059230|0.56|N|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-24T19:30:03+00:00, last15m_closed_end=2026-10-24T19:30+00:00, prior8high=0.069650, depth_time=2026-10-24T19:30:18+00:00, book20_bid_proxy_usdt=10282, book20_ask_proxy_usdt=10730, funding_indicative=0.000094, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.16%, turnover=10336463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-24T19:30:03+00:00, last15m_closed_end=2026-10-24T19:30+00:00, prior8high=0.096610, depth_time=2026-10-24T19:30:10+00:00, book20_bid_proxy_usdt=25736, book20_ask_proxy_usdt=19220, funding_indicative=-0.007653, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.78%, turnover=11888348. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-24T19:30:03+00:00, last15m_closed_end=2026-10-24T19:30+00:00, prior8high=1.733500, depth_time=2026-10-24T19:30:16+00:00, book20_bid_proxy_usdt=15739, book20_ask_proxy_usdt=12162, funding_indicative=-0.006482, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.73%, turnover=14348877. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T19:30:03+00:00, last15m_closed_end=2026-10-24T19:30+00:00, prior8high=0.051840, depth_time=2026-10-24T19:30:14+00:00, book20_bid_proxy_usdt=51791, book20_ask_proxy_usdt=67088, funding_indicative=0.000012, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=1, 24h_change=-3.49%, turnover=61262148. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-24T19:30:03+00:00, last15m_closed_end=2026-10-24T19:30+00:00, prior8high=0.072450, depth_time=2026-10-24T19:30:09+00:00, book20_bid_proxy_usdt=58628, book20_ask_proxy_usdt=52251, funding_indicative=-0.003057, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=1, 24h_change=-11.89%, turnover=12316612. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
