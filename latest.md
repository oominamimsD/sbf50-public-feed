# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T21:30:46Z**
- feed_generated_utc: 2026-10-26T21:30:50+00:00
- source_sha256: `2e23bdcfc216f9b62901029a248b7358e960aa832d92913aaa36455cd57e92da`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T21:30+00:00, close=80041, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T21:00+00:00, close=79843, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.026230|-4.89|113.59|-4.45|9384458|3.81|
|ZRO_USDT|1.623600|-4.89|-14.63|-4.45|5062194|0.62|
|BTW_USDT|1.141800|-4.50|-34.82|-4.06|20647493|3.50|
|LIT_USDT|2.991000|-4.08|-1.34|-3.64|5192124|0.33|
|BR_USDT|0.480000|-3.90|-22.07|-3.46|12738384|6.25|
|QNT_USDT|202.220000|-3.83|3.33|-3.39|120463880|0.99|
|PUMPFUN_USDT|0.004215|-2.61|-5.40|-2.17|21931639|2.37|
|NEAR_USDT|4.465000|-2.36|-8.95|-1.92|117928949|2.24|
|WLD_USDT|0.435200|-2.20|-14.04|-1.76|73200388|2.30|
|FILECOIN_USDT|0.902000|-2.03|-10.86|-1.59|6567972|1.11|
|PEPE_USDT|0.000004|-1.93|4.10|-1.49|84170829|0.23|
|DOT_USDT|1.004000|-1.81|-12.45|-1.37|10591811|1.00|
|FET_USDT|0.173400|-1.81|-8.25|-1.37|6520077|5.76|
|ARB_USDT|0.167220|-1.62|-14.52|-1.18|20575903|0.60|
|PENGU_USDT|0.007452|-1.61|-0.52|-1.17|6161929|1.34|
|LINK_USDT|11.344000|-1.59|-5.01|-1.15|98482421|0.88|
|APT_USDT|0.690900|-1.58|-9.43|-1.14|5386371|2.90|
|TAO_USDT|249.540000|-1.56|-6.99|-1.12|46744428|1.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.167220|0.166430|0.167150|1.57|N|Y/Y|Y/Y|Y|N|
|BR_USDT|0.480000|0.472600|0.480200|0.49|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.141800|1.103200|1.141800|0.25|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.004000|1.000200|1.003700|1.60|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.173400|0.172600|0.173500|6.14|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.902000|0.895900|0.902000|3.09|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026230|0.025640|0.026230|0.70|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.991000|2.979500|2.991000|1.12|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.465000|4.439000|4.465000|0.47|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007452|0.007426|0.007451|0.94|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.81|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004215|0.004181|0.004217|0.13|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|202.220000|200.670000|202.220000|0.60|N|Y/N|N/N|Y|N|
|WLD_USDT|0.435200|0.434500|0.435400|1.44|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.623600|1.608700|1.623600|1.35|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-26T21:30:03+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=0.168970, depth_time=2026-10-26T21:30:43+00:00, book20_bid_proxy_usdt=114045, book20_ask_proxy_usdt=41938, funding_indicative=-0.000035, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=20575903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-26T21:30:03+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=0.482800, depth_time=2026-10-26T21:30:21+00:00, book20_bid_proxy_usdt=43813, book20_ask_proxy_usdt=41486, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.90%, turnover=12738384. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T21:30:03+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=1.194600, depth_time=2026-10-26T21:30:15+00:00, book20_bid_proxy_usdt=16150, book20_ask_proxy_usdt=12509, funding_indicative=0.000041, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.50%, turnover=20647493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T21:30:03+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=1.012800, depth_time=2026-10-26T21:30:37+00:00, book20_bid_proxy_usdt=289353, book20_ask_proxy_usdt=254751, funding_indicative=-0.000073, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=10591811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-26T21:30:03+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=0.175200, depth_time=2026-10-26T21:30:40+00:00, book20_bid_proxy_usdt=1370874, book20_ask_proxy_usdt=1166974, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=6520077. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T21:30:03+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=0.914300, depth_time=2026-10-26T21:30:32+00:00, book20_bid_proxy_usdt=908219, book20_ask_proxy_usdt=1360449, funding_indicative=0.000076, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=6567972. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T21:30:02+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=0.026610, depth_time=2026-10-26T21:30:10+00:00, book20_bid_proxy_usdt=84734, book20_ask_proxy_usdt=99531, funding_indicative=-0.000658, next_funding_utc=2026-10-26T22:00:00+00:00, funding_cycle_h=1, 24h_change=-4.89%, turnover=9384458. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T21:30:03+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=3.080700, depth_time=2026-10-26T21:30:18+00:00, book20_bid_proxy_usdt=31392, book20_ask_proxy_usdt=41439, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.08%, turnover=5192124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T21:30:02+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=4.506000, depth_time=2026-10-26T21:30:26+00:00, book20_bid_proxy_usdt=4730117, book20_ask_proxy_usdt=3099157, funding_indicative=0.000068, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.36%, turnover=117928949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-26T21:30:03+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=0.007533, depth_time=2026-10-26T21:30:43+00:00, book20_bid_proxy_usdt=221275, book20_ask_proxy_usdt=199684, funding_indicative=0.000038, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.61%, turnover=6161929. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T21:30:03+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=0.000004, depth_time=2026-10-26T21:30:36+00:00, book20_bid_proxy_usdt=72473, book20_ask_proxy_usdt=98854, funding_indicative=0.000089, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=84170829. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T21:30:03+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=0.004273, depth_time=2026-10-26T21:30:26+00:00, book20_bid_proxy_usdt=2087046, book20_ask_proxy_usdt=1424759, funding_indicative=-0.000006, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=21931639. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-26T21:30:02+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=205.320000, depth_time=2026-10-26T21:30:23+00:00, book20_bid_proxy_usdt=71849, book20_ask_proxy_usdt=71702, funding_indicative=0.000064, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.83%, turnover=120463880. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T21:30:03+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=0.443100, depth_time=2026-10-26T21:30:29+00:00, book20_bid_proxy_usdt=2608851, book20_ask_proxy_usdt=3242044, funding_indicative=-0.000129, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=73200388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-26T21:30:03+00:00, last15m_closed_end=2026-10-26T21:30+00:00, prior8high=1.635400, depth_time=2026-10-26T21:30:12+00:00, book20_bid_proxy_usdt=33439, book20_ask_proxy_usdt=40207, funding_indicative=-0.000081, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.89%, turnover=5062194. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
