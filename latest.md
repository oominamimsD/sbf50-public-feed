# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T13:15:26Z**
- feed_generated_utc: 2026-10-26T13:15:29+00:00
- source_sha256: `86c22cfc38fe76f8e8991748ca56a7ce4479c81c8587b16dd93a23c166a589c7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T13:15+00:00, close=80145.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T13:00+00:00, close=80301.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.028140|-26.79|130.65|-26.23|12020588|7.11|
|BTW_USDT|1.425300|-14.08|-38.17|-13.52|10892037|2.81|
|APR_USDT|0.035840|-13.24|31.57|-12.68|6273628|2.79|
|WLD_USDT|0.438000|-4.07|-8.04|-3.51|59521406|2.28|
|LIT_USDT|3.060400|-3.71|4.43|-3.15|5083435|0.33|
|STRK_USDT|0.044550|-2.60|-27.63|-2.04|9280250|2.25|
|XMR_USDT|592.510000|-2.42|1.71|-1.86|5525315|0.17|
|DOT_USDT|1.015700|-2.26|-5.02|-1.70|8728464|0.98|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.035840|0.033120|0.035840|1.39|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.425300|1.395000|1.425300|1.14|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.015700|1.015500|1.015700|1.50|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.028140|0.027970|0.028140|1.71|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.060400|3.071200|3.060400|5.39|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.044550|0.044360|0.044550|1.41|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.438000|0.435800|0.438000|1.12|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|592.510000|588.800000|592.510000|0.65|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T13:14:59+00:00, last15m_closed_end=2026-10-26T13:15+00:00, prior8high=0.036400, depth_time=2026-10-26T13:15:13+00:00, book20_bid_proxy_usdt=33012, book20_ask_proxy_usdt=45051, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.24%, turnover=6273628. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T13:15:00+00:00, last15m_closed_end=2026-10-26T13:15+00:00, prior8high=1.516100, depth_time=2026-10-26T13:15:10+00:00, book20_bid_proxy_usdt=13121, book20_ask_proxy_usdt=22273, funding_indicative=-0.015096, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.08%, turnover=10892037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T13:15:00+00:00, last15m_closed_end=2026-10-26T13:15+00:00, prior8high=1.028300, depth_time=2026-10-26T13:15:24+00:00, book20_bid_proxy_usdt=284721, book20_ask_proxy_usdt=349789, funding_indicative=-0.000074, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=8728464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T13:14:59+00:00, last15m_closed_end=2026-10-26T13:15+00:00, prior8high=0.029430, depth_time=2026-10-26T13:15:09+00:00, book20_bid_proxy_usdt=83156, book20_ask_proxy_usdt=68826, funding_indicative=-0.000729, next_funding_utc=2026-10-26T14:00:00+00:00, funding_cycle_h=1, 24h_change=-26.79%, turnover=12020588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T13:15:00+00:00, last15m_closed_end=2026-10-26T13:15+00:00, prior8high=3.115900, depth_time=2026-10-26T13:15:18+00:00, book20_bid_proxy_usdt=23742, book20_ask_proxy_usdt=23768, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.71%, turnover=5083435. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T13:15:00+00:00, last15m_closed_end=2026-10-26T13:15+00:00, prior8high=0.044890, depth_time=2026-10-26T13:15:20+00:00, book20_bid_proxy_usdt=1225731, book20_ask_proxy_usdt=722923, funding_indicative=-0.000006, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.60%, turnover=9280250. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T13:14:59+00:00, last15m_closed_end=2026-10-26T13:15+00:00, prior8high=0.444700, depth_time=2026-10-26T13:15:15+00:00, book20_bid_proxy_usdt=2415728, book20_ask_proxy_usdt=2683201, funding_indicative=-0.000168, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.07%, turnover=59521406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T13:15:00+00:00, last15m_closed_end=2026-10-26T13:15+00:00, prior8high=594.610000, depth_time=2026-10-26T13:15:22+00:00, book20_bid_proxy_usdt=22042, book20_ask_proxy_usdt=14823, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=5525315. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
