# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T12:30:31Z**
- feed_generated_utc: 2026-11-09T12:30:33+00:00
- source_sha256: `794c61d422ed35b262f71a6ff85ae6189c2847ecf052d03b10938ba363263857`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T12:30+00:00, close=74743.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001502|-23.28|28.98|-21.58|6232513|0.67|
|JCT_USDT|0.008770|-10.81|76.13|-9.11|65808481|1.14|
|ASTER_USDT|0.639400|-5.94|-8.57|-4.24|5636508|1.56|
|XRP_USDT|1.094000|-5.34|-12.47|-3.64|280693860|0.91|
|ETH_USDT|2123.140000|-5.26|-6.29|-3.56|1569972756|0.05|
|HYPE_USDT|73.589000|-4.96|-16.07|-3.26|49026188|0.14|
|NEAR_USDT|3.543000|-4.26|-18.19|-2.56|46226641|5.64|
|TRUMPOFFICIAL_USDT|1.139000|-4.20|-33.62|-2.50|6409761|8.78|
|ZEC_USDT|1218.800000|-4.08|-1.54|-2.38|2308551064|0.08|
|HOT_USDT|0.000412|-3.98|14.71|-2.28|7720837|2.42|
|SOL_USDT|86.690000|-3.33|-8.51|-1.63|734820179|1.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ASTER_USDT|0.639400|0.623900|0.639400|1.66|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2123.140000|2099.860000|2123.130000|0.68|N|Y/Y|Y/Y|Y|N|
|HOT_USDT|0.000412|0.000412|0.000412|0.37|N|Y/N|N/N|Y|N|
|HYPE_USDT|73.589000|72.747000|73.589000|0.49|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008770|0.008306|0.008770|0.65|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.543000|3.480000|3.543000|0.47|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001502|0.001487|0.001502|1.03|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.690000|85.770000|86.690000|0.77|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.139000|1.124000|1.139000|1.98|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.094000|1.076200|1.094000|1.41|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1218.800000|1192.400000|1218.800000|0.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ASTER_USDT: quote_utc=2026-11-09T12:29:59+00:00, last15m_closed_end=2026-11-09T12:30+00:00, prior8high=0.635800, depth_time=2026-11-09T12:30:08+00:00, book20_bid_proxy_usdt=820555, book20_ask_proxy_usdt=936043, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.94%, turnover=5636508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T12:29:59+00:00, last15m_closed_end=2026-11-09T12:30+00:00, prior8high=2132.860000, depth_time=2026-11-09T12:30:16+00:00, book20_bid_proxy_usdt=9209675, book20_ask_proxy_usdt=2029804, funding_indicative=-0.000016, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.26%, turnover=1569972756. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-09T12:29:59+00:00, last15m_closed_end=2026-11-09T12:30+00:00, prior8high=0.000437, depth_time=2026-11-09T12:30:27+00:00, book20_bid_proxy_usdt=99392, book20_ask_proxy_usdt=118253, funding_indicative=-0.001350, next_funding_utc=2026-11-09T13:00:00+00:00, funding_cycle_h=1, 24h_change=-3.98%, turnover=7720837. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T12:29:59+00:00, last15m_closed_end=2026-11-09T12:30+00:00, prior8high=74.029000, depth_time=2026-11-09T12:30:19+00:00, book20_bid_proxy_usdt=154718, book20_ask_proxy_usdt=97789, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.96%, turnover=49026188. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T12:29:59+00:00, last15m_closed_end=2026-11-09T12:30+00:00, prior8high=0.009430, depth_time=2026-11-09T12:30:09+00:00, book20_bid_proxy_usdt=38292, book20_ask_proxy_usdt=61987, funding_indicative=0.001285, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.81%, turnover=65808481. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T12:29:59+00:00, last15m_closed_end=2026-11-09T12:30+00:00, prior8high=3.570000, depth_time=2026-11-09T12:30:20+00:00, book20_bid_proxy_usdt=1997590, book20_ask_proxy_usdt=2322470, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.26%, turnover=46226641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T12:29:59+00:00, last15m_closed_end=2026-11-09T12:30+00:00, prior8high=0.001563, depth_time=2026-11-09T12:30:07+00:00, book20_bid_proxy_usdt=28708, book20_ask_proxy_usdt=13560, funding_indicative=0.000037, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.28%, turnover=6232513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T12:29:59+00:00, last15m_closed_end=2026-11-09T12:30+00:00, prior8high=87.140000, depth_time=2026-11-09T12:30:31+00:00, book20_bid_proxy_usdt=13819766, book20_ask_proxy_usdt=14834540, funding_indicative=0.000023, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.33%, turnover=734820179. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T12:29:59+00:00, last15m_closed_end=2026-11-09T12:30+00:00, prior8high=1.144000, depth_time=2026-11-09T12:30:20+00:00, book20_bid_proxy_usdt=2153165, book20_ask_proxy_usdt=2464071, funding_indicative=0.000011, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.20%, turnover=6409761. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T12:29:59+00:00, last15m_closed_end=2026-11-09T12:30+00:00, prior8high=1.093100, depth_time=2026-11-09T12:30:13+00:00, book20_bid_proxy_usdt=3584361, book20_ask_proxy_usdt=4847985, funding_indicative=0.000097, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.34%, turnover=280693860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T12:29:59+00:00, last15m_closed_end=2026-11-09T12:30+00:00, prior8high=1225.880000, depth_time=2026-11-09T12:30:26+00:00, book20_bid_proxy_usdt=290946, book20_ask_proxy_usdt=339063, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.08%, turnover=2308551064. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
