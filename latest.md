# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T05:15:25Z**
- feed_generated_utc: 2026-11-09T05:15:26+00:00
- source_sha256: `501be689ad5a105e8f6c12d2ccea4cd5f3f6c393561ea29e094c51076de801b9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T05:15+00:00, close=74626.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T05:00+00:00, close=74800, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001626|-16.94|39.64|-15.10|10058417|0.61|
|AKE_USDT|0.004672|-12.78|-48.99|-10.94|11322063|4.28|
|ASTER_USDT|0.640500|-5.78|-8.42|-3.94|5150434|1.56|
|PUMPFUN_USDT|0.003554|-4.89|-15.74|-3.05|9318119|2.81|
|XRP_USDT|1.105300|-4.36|-11.56|-2.52|230155638|0.91|
|HYPE_USDT|74.445000|-3.85|-15.10|-2.01|39844525|0.13|
|LIT_USDT|3.094800|-3.08|-4.18|-1.24|13555708|0.32|
|DOT_USDT|0.864800|-2.92|-8.68|-1.08|7566602|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004672|0.004627|0.004674|1.24|N|Y/Y|Y/N|Y|N|
|ASTER_USDT|0.640500|0.637000|0.640600|0.60|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.864800|0.863900|0.864800|8.69|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|74.445000|74.350000|74.463000|1.08|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.094800|3.086100|3.094800|0.23|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001626|0.001636|0.001627|1.87|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.003554|0.003568|0.003556|0.64|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.105300|1.102400|1.105300|0.64|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T05:15:03+00:00, last15m_closed_end=2026-11-09T05:15+00:00, prior8high=0.005102, depth_time=2026-11-09T05:15:10+00:00, book20_bid_proxy_usdt=31737, book20_ask_proxy_usdt=50948, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.78%, turnover=11322063. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T05:15:03+00:00, last15m_closed_end=2026-11-09T05:15+00:00, prior8high=0.647300, depth_time=2026-11-09T05:15:09+00:00, book20_bid_proxy_usdt=712743, book20_ask_proxy_usdt=625639, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.78%, turnover=5150434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-09T05:15:03+00:00, last15m_closed_end=2026-11-09T05:15+00:00, prior8high=0.880100, depth_time=2026-11-09T05:15:23+00:00, book20_bid_proxy_usdt=554700, book20_ask_proxy_usdt=678987, funding_indicative=-0.000087, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.92%, turnover=7566602. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T05:15:03+00:00, last15m_closed_end=2026-11-09T05:15+00:00, prior8high=75.000000, depth_time=2026-11-09T05:15:18+00:00, book20_bid_proxy_usdt=106190, book20_ask_proxy_usdt=60276, funding_indicative=0.000034, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.85%, turnover=39844525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T05:15:03+00:00, last15m_closed_end=2026-11-09T05:15+00:00, prior8high=3.158400, depth_time=2026-11-09T05:15:21+00:00, book20_bid_proxy_usdt=22492, book20_ask_proxy_usdt=22571, funding_indicative=-0.000021, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=13555708. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T05:15:03+00:00, last15m_closed_end=2026-11-09T05:15+00:00, prior8high=0.001702, depth_time=2026-11-09T05:15:06+00:00, book20_bid_proxy_usdt=13056, book20_ask_proxy_usdt=17871, funding_indicative=-0.000239, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.94%, turnover=10058417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T05:15:03+00:00, last15m_closed_end=2026-11-09T05:15+00:00, prior8high=0.003661, depth_time=2026-11-09T05:15:13+00:00, book20_bid_proxy_usdt=2877207, book20_ask_proxy_usdt=2447622, funding_indicative=0.000024, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.89%, turnover=9318119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T05:15:03+00:00, last15m_closed_end=2026-11-09T05:15+00:00, prior8high=1.116100, depth_time=2026-11-09T05:15:16+00:00, book20_bid_proxy_usdt=3867079, book20_ask_proxy_usdt=4843152, funding_indicative=-0.000006, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.36%, turnover=230155638. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
