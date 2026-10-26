# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T20:30:28Z**
- feed_generated_utc: 2026-10-26T20:30:31+00:00
- source_sha256: `aa1a02b52886d1ce808981065f694301b47e3e00962142611ec015a807740dfb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T20:30+00:00, close=79851.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.026080|-5.43|112.37|-4.75|9501283|3.83|
|BTW_USDT|1.145800|-4.17|-34.60|-3.49|20559687|0.88|
|QNT_USDT|202.000000|-3.93|3.21|-3.25|119698586|0.49|
|LIT_USDT|3.021200|-3.11|-0.35|-2.43|5097023|0.33|
|PUMPFUN_USDT|0.004231|-2.24|-5.04|-1.56|22144391|2.37|
|NEAR_USDT|4.476000|-2.12|-8.72|-1.44|118006497|2.24|
|WLD_USDT|0.436100|-2.00|-13.86|-1.32|72494634|2.29|
|DOT_USDT|1.004900|-1.73|-12.37|-1.05|10377330|0.99|
|FET_USDT|0.173600|-1.69|-8.14|-1.01|5905441|5.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.145800|1.103200|1.145100|0.43|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.004900|0.999500|1.005200|1.07|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.173600|0.173500|0.173600|1.98|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026080|0.025780|0.026080|0.41|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.021200|3.023400|3.021200|0.39|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.476000|4.442000|4.476000|0.27|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004231|0.004209|0.004231|0.07|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|202.000000|202.020000|201.960000|0.69|N|N/N|N/N|Y|N|
|WLD_USDT|0.436100|0.435200|0.436000|0.43|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T20:30:01+00:00, last15m_closed_end=2026-10-26T20:30+00:00, prior8high=1.291000, depth_time=2026-10-26T20:30:10+00:00, book20_bid_proxy_usdt=9084, book20_ask_proxy_usdt=12510, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.17%, turnover=20559687. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T20:30:01+00:00, last15m_closed_end=2026-10-26T20:30+00:00, prior8high=1.016400, depth_time=2026-10-26T20:30:24+00:00, book20_bid_proxy_usdt=347179, book20_ask_proxy_usdt=518954, funding_indicative=0.000020, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=10377330. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-26T20:30:01+00:00, last15m_closed_end=2026-10-26T20:30+00:00, prior8high=0.175700, depth_time=2026-10-26T20:30:27+00:00, book20_bid_proxy_usdt=1823068, book20_ask_proxy_usdt=1169414, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=5905441. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T20:30:01+00:00, last15m_closed_end=2026-10-26T20:30+00:00, prior8high=0.026670, depth_time=2026-10-26T20:30:08+00:00, book20_bid_proxy_usdt=88212, book20_ask_proxy_usdt=101035, funding_indicative=-0.000708, next_funding_utc=2026-10-26T21:00:00+00:00, funding_cycle_h=1, 24h_change=-5.43%, turnover=9501283. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T20:30:01+00:00, last15m_closed_end=2026-10-26T20:30+00:00, prior8high=3.094900, depth_time=2026-10-26T20:30:15+00:00, book20_bid_proxy_usdt=14562, book20_ask_proxy_usdt=56782, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=5097023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T20:30:01+00:00, last15m_closed_end=2026-10-26T20:30+00:00, prior8high=4.530000, depth_time=2026-10-26T20:30:19+00:00, book20_bid_proxy_usdt=5300669, book20_ask_proxy_usdt=3185907, funding_indicative=0.000078, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=118006497. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T20:30:01+00:00, last15m_closed_end=2026-10-26T20:30+00:00, prior8high=0.004280, depth_time=2026-10-26T20:30:17+00:00, book20_bid_proxy_usdt=3193436, book20_ask_proxy_usdt=1793787, funding_indicative=0.000041, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=22144391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-26T20:30:01+00:00, last15m_closed_end=2026-10-26T20:30+00:00, prior8high=206.650000, depth_time=2026-10-26T20:30:12+00:00, book20_bid_proxy_usdt=78424, book20_ask_proxy_usdt=64853, funding_indicative=0.000056, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.93%, turnover=119698586. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T20:30:01+00:00, last15m_closed_end=2026-10-26T20:30+00:00, prior8high=0.443100, depth_time=2026-10-26T20:30:21+00:00, book20_bid_proxy_usdt=2969599, book20_ask_proxy_usdt=2301267, funding_indicative=-0.000136, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=72494634. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
