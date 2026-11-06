# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T23:15:20Z**
- feed_generated_utc: 2026-11-06T23:15:21+00:00
- source_sha256: `558391b1cf3921b31cb5fe4df14a7d2c9e268603878ceb25ed66da9d87a7aed5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T23:15+00:00, close=75861.5, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T23:00+00:00, close=75873.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.140000|-26.31|-47.28|-26.34|33866857|7.14|
|ANTHROPIC_USDT|1329.030000|-7.14|-20.72|-7.17|7388028|1.50|
|PUMPFUN_USDT|0.003912|-3.28|-4.74|-3.31|12917010|2.56|
|LIT_USDT|3.301200|-2.68|16.88|-2.71|9620665|0.30|
|HBAR_USDT|0.067390|-1.47|-6.20|-1.50|5622574|1.48|
|XLM_USDT|0.153470|-1.03|-10.89|-1.06|24827944|1.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1329.030000|1309.270000|1329.030000|1.08|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.067390|0.067470|0.067380|0.30|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.301200|3.283100|3.301200|0.36|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003912|0.003935|0.003911|3.38|Y|Y/Y|Y/Y|Y|Y|
|UAI_USDT|0.140000|0.132600|0.140000|0.27|N|Y/Y|Y/N|Y|N|
|XLM_USDT|0.153470|0.153660|0.153470|1.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T23:15:01+00:00, last15m_closed_end=2026-11-06T23:15+00:00, prior8high=1364.960000, depth_time=2026-11-06T23:15:09+00:00, book20_bid_proxy_usdt=14191, book20_ask_proxy_usdt=16528, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.14%, turnover=7388028. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-06T23:15:01+00:00, last15m_closed_end=2026-11-06T23:15+00:00, prior8high=0.068220, depth_time=2026-11-06T23:15:16+00:00, book20_bid_proxy_usdt=848948, book20_ask_proxy_usdt=874577, funding_indicative=0.000028, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=5622574. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T23:15:01+00:00, last15m_closed_end=2026-11-06T23:15+00:00, prior8high=3.375500, depth_time=2026-11-06T23:15:13+00:00, book20_bid_proxy_usdt=30257, book20_ask_proxy_usdt=35953, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=9620665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-06T23:15:01+00:00, last15m_closed_end=2026-11-06T23:15+00:00, prior8high=0.004011, depth_time=2026-11-06T23:15:10+00:00, book20_bid_proxy_usdt=2124382, book20_ask_proxy_usdt=2311726, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=12917010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T23:15:01+00:00, last15m_closed_end=2026-11-06T23:15+00:00, prior8high=0.149300, depth_time=2026-11-06T23:15:06+00:00, book20_bid_proxy_usdt=139240, book20_ask_proxy_usdt=110503, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-26.31%, turnover=33866857. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-06T23:15:01+00:00, last15m_closed_end=2026-11-06T23:15+00:00, prior8high=0.155630, depth_time=2026-11-06T23:15:17+00:00, book20_bid_proxy_usdt=193318, book20_ask_proxy_usdt=157975, funding_indicative=0.000001, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.03%, turnover=24827944. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
