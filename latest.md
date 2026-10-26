# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T16:45:23Z**
- feed_generated_utc: 2026-10-26T16:45:26+00:00
- source_sha256: `1618ea901547752ae35e317d04f94c5ff56551db38d0f5c2e87a3ac1216888d1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T16:45+00:00, close=79862.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T16:00+00:00, close=80399.8, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T16:00+00:00, close=80399.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|0.911700|-23.75|-47.96|-23.09|17630374|2.19|
|IRYS_USDT|0.026520|-3.84|115.96|-3.18|10644996|3.77|
|PUMPFUN_USDT|0.004225|-2.37|-5.18|-1.71|23079428|2.37|
|NEAR_USDT|4.486000|-1.90|-8.52|-1.24|133305709|2.23|
|WLD_USDT|0.436700|-1.86|-13.74|-1.20|72752974|2.29|
|FILECOIN_USDT|0.905200|-1.68|-10.55|-1.02|5943528|1.10|
|DOT_USDT|1.005600|-1.66|-12.31|-1.00|9412564|1.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|0.911700|0.933200|0.918500|2.50|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|1.005600|1.008900|1.005600|2.60|Y|Y/N|Y/Y|Y|N|
|FILECOIN_USDT|0.905200|0.909900|0.905200|1.09|N|N/N|Y/Y|Y|N|
|IRYS_USDT|0.026520|0.026690|0.026520|1.01|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.486000|4.514000|4.486000|1.92|Y|N/N|Y/Y|Y|N|
|PUMPFUN_USDT|0.004225|0.004260|0.004225|2.19|Y|N/N|N/Y|Y|N|
|WLD_USDT|0.436700|0.437800|0.436700|3.45|Y|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T16:45:01+00:00, last15m_closed_end=2026-10-26T16:45+00:00, prior8high=1.634800, depth_time=2026-10-26T16:45:09+00:00, book20_bid_proxy_usdt=10826, book20_ask_proxy_usdt=10666, funding_indicative=-0.011201, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-23.75%, turnover=17630374. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T16:45:01+00:00, last15m_closed_end=2026-10-26T16:45+00:00, prior8high=1.034900, depth_time=2026-10-26T16:45:23+00:00, book20_bid_proxy_usdt=209814, book20_ask_proxy_usdt=401341, funding_indicative=-0.000082, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.66%, turnover=9412564. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T16:45:02+00:00, last15m_closed_end=2026-10-26T16:45+00:00, prior8high=0.931600, depth_time=2026-10-26T16:45:19+00:00, book20_bid_proxy_usdt=1000496, book20_ask_proxy_usdt=1347376, funding_indicative=0.000080, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=5943528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T16:45:01+00:00, last15m_closed_end=2026-10-26T16:45+00:00, prior8high=0.028090, depth_time=2026-10-26T16:45:11+00:00, book20_bid_proxy_usdt=89431, book20_ask_proxy_usdt=145124, funding_indicative=-0.000779, next_funding_utc=2026-10-26T17:00:00+00:00, funding_cycle_h=1, 24h_change=-3.84%, turnover=10644996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T16:45:01+00:00, last15m_closed_end=2026-10-26T16:45+00:00, prior8high=4.663000, depth_time=2026-10-26T16:45:16+00:00, book20_bid_proxy_usdt=2142863, book20_ask_proxy_usdt=5521722, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=133305709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T16:45:01+00:00, last15m_closed_end=2026-10-26T16:45+00:00, prior8high=0.004414, depth_time=2026-10-26T16:45:13+00:00, book20_bid_proxy_usdt=1414936, book20_ask_proxy_usdt=1458774, funding_indicative=0.000047, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.37%, turnover=23079428. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T16:45:01+00:00, last15m_closed_end=2026-10-26T16:45+00:00, prior8high=0.452700, depth_time=2026-10-26T16:45:17+00:00, book20_bid_proxy_usdt=2305652, book20_ask_proxy_usdt=3173689, funding_indicative=-0.000130, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.86%, turnover=72752974. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
