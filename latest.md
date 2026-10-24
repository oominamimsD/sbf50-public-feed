# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T21:00:23Z**
- feed_generated_utc: 2026-10-24T21:00:27+00:00
- source_sha256: `7c7bdb936494a826766095b96e31284931f6de0ced5ac694f00de2a1d0410d19`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T21:00+00:00, close=80489.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T21:00+00:00, close=80489.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.044910|-21.09|251.95|-22.00|37869265|6.68|
|BIRB_USDT|0.092120|-16.61|89.85|-17.52|11742339|6.50|
|ORDER_USDT|0.059520|-11.69|92.31|-12.60|12514446|5.04|
|AGT_USDT|0.068940|-3.07|-4.32|-3.98|8820637|2.90|
|DOT_USDT|1.037100|-1.14|-7.18|-2.05|12047923|3.85|
|TIA_USDT|0.531100|-0.54|-19.28|-1.45|28487853|1.88|
|STRK_USDT|0.046650|-0.17|-29.47|-1.08|8825912|2.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.068940|0.065820|0.068940|0.53|N|Y/Y|Y/Y|Y|N|
|BIRB_USDT|0.092120|0.089620|0.092120|0.52|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.037100|1.037400|1.037100|0.47|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.044910|0.042300|0.044910|0.61|N|Y/Y|Y/N|Y|N|
|ORDER_USDT|0.059520|0.057390|0.059480|0.33|N|N/N|N/N|Y|N|
|STRK_USDT|0.046650|0.046860|0.046640|0.79|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.531100|0.528400|0.531100|0.27|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-24T21:00:01+00:00, last15m_closed_end=2026-10-24T21:00+00:00, prior8high=0.070920, depth_time=2026-10-24T21:00:13+00:00, book20_bid_proxy_usdt=16441, book20_ask_proxy_usdt=22903, funding_indicative=0.000157, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=8820637. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-24T21:00:01+00:00, last15m_closed_end=2026-10-24T21:00+00:00, prior8high=0.094490, depth_time=2026-10-24T21:00:11+00:00, book20_bid_proxy_usdt=23872, book20_ask_proxy_usdt=18098, funding_indicative=-0.007951, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-16.61%, turnover=11742339. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-24T21:00:01+00:00, last15m_closed_end=2026-10-24T21:00+00:00, prior8high=1.047500, depth_time=2026-10-24T21:00:18+00:00, book20_bid_proxy_usdt=509145, book20_ask_proxy_usdt=248172, funding_indicative=-0.000073, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.14%, turnover=12047923. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T21:00:01+00:00, last15m_closed_end=2026-10-24T21:00+00:00, prior8high=0.045710, depth_time=2026-10-24T21:00:07+00:00, book20_bid_proxy_usdt=56088, book20_ask_proxy_usdt=59868, funding_indicative=0.000012, next_funding_utc=2026-10-24T22:00:00+00:00, funding_cycle_h=1, 24h_change=-21.09%, turnover=37869265. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-24T21:00:01+00:00, last15m_closed_end=2026-10-24T21:00+00:00, prior8high=0.064800, depth_time=2026-10-24T21:00:13+00:00, book20_bid_proxy_usdt=59910, book20_ask_proxy_usdt=49348, funding_indicative=-0.001464, next_funding_utc=2026-10-24T22:00:00+00:00, funding_cycle_h=1, 24h_change=-11.69%, turnover=12514446. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-24T21:00:01+00:00, last15m_closed_end=2026-10-24T21:00+00:00, prior8high=0.047680, depth_time=2026-10-24T21:00:22+00:00, book20_bid_proxy_usdt=1047591, book20_ask_proxy_usdt=897872, funding_indicative=0.000036, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.17%, turnover=8825912. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-24T21:00:01+00:00, last15m_closed_end=2026-10-24T21:00+00:00, prior8high=0.534900, depth_time=2026-10-24T21:00:20+00:00, book20_bid_proxy_usdt=290591, book20_ask_proxy_usdt=249067, funding_indicative=-0.000071, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.54%, turnover=28487853. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
