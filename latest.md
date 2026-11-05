# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T00:00:29Z**
- feed_generated_utc: 2026-11-05T00:00:31+00:00
- source_sha256: `7491f83b2750e1b9ea98b38ee02fd74376515a0579ccf5f832d2e1ec0be37f47`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002456|-22.98|-87.77|-23.20|16370665|4.07|
|TRUMPOFFICIAL_USDT|1.267000|-11.15|-25.86|-11.37|27036641|7.89|
|BTW_USDT|1.028800|-7.03|-40.80|-7.25|6014402|1.94|
|EVAA_USDT|1.543000|-5.78|3.90|-6.00|5025131|3.24|
|WLD_USDT|0.374600|-4.46|-13.44|-4.68|71710603|2.67|
|PUMPFUN_USDT|0.004245|-4.11|0.90|-4.33|17529677|2.36|
|IDOL_USDT|0.021410|-3.31|147.31|-3.53|6163550|6.54|
|HYPE_USDT|83.803000|-2.44|4.94|-2.66|94140607|0.12|
|ZRO_USDT|1.823400|-2.21|6.50|-2.43|11064492|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002456|0.002379|0.002456|0.59|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.028800|1.026000|1.028800|1.21|N|Y/Y|Y/N|N|N|
|EVAA_USDT|1.543000|1.512800|1.542500|0.61|N|Y/Y|N/N|N|N|
|HYPE_USDT|83.803000|83.100000|83.808000|0.37|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.021410|0.021124|0.021410|0.33|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004245|0.004219|0.004245|1.26|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.267000|1.259000|1.267000|0.66|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.374600|0.374500|0.374800|0.71|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.823400|1.812600|1.823600|0.05|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T00:00:02+00:00, last15m_closed_end=2026-11-05T00:00+00:00, prior8high=0.002595, depth_time=2026-11-05T00:00:08+00:00, book20_bid_proxy_usdt=126913, book20_ask_proxy_usdt=73310, funding_indicative=-0.000970, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-22.98%, turnover=16370665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T00:00:03+00:00, last15m_closed_end=2026-11-05T00:00+00:00, prior8high=1.044500, depth_time=2026-11-05T00:00:13+00:00, book20_bid_proxy_usdt=24828, book20_ask_proxy_usdt=17985, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.03%, turnover=6014402. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-11-05T00:00:03+00:00, last15m_closed_end=2026-11-05T00:00+00:00, prior8high=1.595600, depth_time=2026-11-05T00:00:15+00:00, book20_bid_proxy_usdt=11793, book20_ask_proxy_usdt=3320, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.78%, turnover=5025131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T00:00:02+00:00, last15m_closed_end=2026-11-05T00:00+00:00, prior8high=84.362000, depth_time=2026-11-05T00:00:25+00:00, book20_bid_proxy_usdt=79238, book20_ask_proxy_usdt=407161, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.44%, turnover=94140607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T00:00:02+00:00, last15m_closed_end=2026-11-05T00:00+00:00, prior8high=0.021651, depth_time=2026-11-05T00:00:21+00:00, book20_bid_proxy_usdt=8162, book20_ask_proxy_usdt=4848, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.31%, turnover=6163550. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-05T00:00:03+00:00, last15m_closed_end=2026-11-05T00:00+00:00, prior8high=0.004318, depth_time=2026-11-05T00:00:20+00:00, book20_bid_proxy_usdt=2426675, book20_ask_proxy_usdt=2364698, funding_indicative=0.000010, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.11%, turnover=17529677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T00:00:03+00:00, last15m_closed_end=2026-11-05T00:00+00:00, prior8high=1.286000, depth_time=2026-11-05T00:00:10+00:00, book20_bid_proxy_usdt=941347, book20_ask_proxy_usdt=816006, funding_indicative=-0.000347, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.15%, turnover=27036641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T00:00:02+00:00, last15m_closed_end=2026-11-05T00:00+00:00, prior8high=0.384000, depth_time=2026-11-05T00:00:18+00:00, book20_bid_proxy_usdt=2877695, book20_ask_proxy_usdt=2229032, funding_indicative=-0.000437, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.46%, turnover=71710603. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T00:00:03+00:00, last15m_closed_end=2026-11-05T00:00+00:00, prior8high=1.856300, depth_time=2026-11-05T00:00:29+00:00, book20_bid_proxy_usdt=99655, book20_ask_proxy_usdt=70647, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.21%, turnover=11064492. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
