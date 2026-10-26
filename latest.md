# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T21:15:45Z**
- feed_generated_utc: 2026-10-26T21:15:49+00:00
- source_sha256: `496de6e31114387d8e7efc120fa9b5282badfc494f5409d21d6f37d373707772`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T21:15+00:00, close=79925.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T21:00+00:00, close=79843, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.026160|-5.14|113.02|-4.55|9362621|3.82|
|BR_USDT|0.476000|-4.70|-22.72|-4.11|12711561|2.10|
|BTW_USDT|1.142800|-4.42|-34.77|-3.83|20589021|0.88|
|LIT_USDT|2.983000|-4.33|-1.61|-3.74|5133145|0.34|
|QNT_USDT|201.180000|-4.32|2.80|-3.73|119863347|0.50|
|PUMPFUN_USDT|0.004185|-3.30|-6.08|-2.71|21901052|2.39|
|NEAR_USDT|4.445000|-2.79|-9.35|-2.20|117431441|2.25|
|FILECOIN_USDT|0.897000|-2.57|-11.36|-1.98|6397722|2.23|
|WLD_USDT|0.434400|-2.38|-14.20|-1.79|72166160|2.30|
|PEPE_USDT|0.000004|-2.37|3.63|-1.78|83732262|1.17|
|FET_USDT|0.172600|-2.26|-8.67|-1.67|6211681|5.79|
|DOT_USDT|1.000900|-2.12|-12.72|-1.53|10406995|2.00|
|ARB_USDT|0.166520|-2.04|-14.88|-1.45|20399500|0.60|
|PENGU_USDT|0.007426|-1.95|-0.86|-1.36|6132432|1.35|
|APT_USDT|0.688600|-1.90|-9.73|-1.31|5359565|1.45|
|LINK_USDT|11.315000|-1.84|-5.25|-1.25|97671634|0.88|
|AAVE_USDT|134.270000|-1.79|-8.79|-1.20|27370229|0.74|
|TAO_USDT|249.030000|-1.76|-7.18|-1.17|46282908|1.21|
|SUI_USDT|0.904900|-1.70|-8.69|-1.11|79002983|2.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.688600|0.689500|0.688600|0.80|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166520|0.166530|0.166560|1.12|N|Y/Y|Y/Y|Y|N|
|BR_USDT|0.476000|0.472600|0.475800|0.41|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.142800|1.103200|1.143500|0.26|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.000900|0.999500|1.000900|0.61|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.172600|0.173100|0.172600|5.52|Y|Y/Y|Y/Y|Y|Y|
|FILECOIN_USDT|0.897000|0.900500|0.897000|5.28|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.026160|0.025640|0.026140|0.67|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.983000|3.001700|2.983000|2.35|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.445000|4.442000|4.447000|1.34|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007426|0.007454|0.007426|1.32|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000004|0.000004|0.000004|1.25|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004185|0.004195|0.004185|2.06|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|201.180000|201.030000|201.180000|0.81|N|Y/N|N/N|Y|N|
|WLD_USDT|0.434400|0.435200|0.435000|1.28|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-26T21:15:00+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=0.696700, depth_time=2026-10-26T21:15:45+00:00, book20_bid_proxy_usdt=177474, book20_ask_proxy_usdt=156186, funding_indicative=-0.000011, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=5359565. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-26T21:15:04+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=0.168970, depth_time=2026-10-26T21:15:39+00:00, book20_bid_proxy_usdt=62838, book20_ask_proxy_usdt=75878, funding_indicative=-0.000040, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=20399500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-26T21:15:04+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=0.483600, depth_time=2026-10-26T21:15:11+00:00, book20_bid_proxy_usdt=40743, book20_ask_proxy_usdt=42225, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.70%, turnover=12711561. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T21:15:04+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=1.202500, depth_time=2026-10-26T21:15:14+00:00, book20_bid_proxy_usdt=10367, book20_ask_proxy_usdt=19290, funding_indicative=0.000041, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.42%, turnover=20589021. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T21:15:00+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=1.012800, depth_time=2026-10-26T21:15:37+00:00, book20_bid_proxy_usdt=403817, book20_ask_proxy_usdt=620043, funding_indicative=-0.000042, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=10406995. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-26T21:15:01+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=0.175200, depth_time=2026-10-26T21:15:33+00:00, book20_bid_proxy_usdt=1771629, book20_ask_proxy_usdt=1424065, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=6211681. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T21:15:01+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=0.914300, depth_time=2026-10-26T21:15:27+00:00, book20_bid_proxy_usdt=1157547, book20_ask_proxy_usdt=1242463, funding_indicative=0.000070, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.57%, turnover=6397722. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T21:15:04+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=0.026670, depth_time=2026-10-26T21:15:09+00:00, book20_bid_proxy_usdt=90238, book20_ask_proxy_usdt=96013, funding_indicative=-0.000590, next_funding_utc=2026-10-26T22:00:00+00:00, funding_cycle_h=1, 24h_change=-5.14%, turnover=9362621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T21:15:00+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=3.080700, depth_time=2026-10-26T21:15:15+00:00, book20_bid_proxy_usdt=32736, book20_ask_proxy_usdt=34332, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.33%, turnover=5133145. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T21:15:04+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=4.506000, depth_time=2026-10-26T21:15:24+00:00, book20_bid_proxy_usdt=3874281, book20_ask_proxy_usdt=4894250, funding_indicative=0.000071, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.79%, turnover=117431441. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-26T21:15:01+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=0.007533, depth_time=2026-10-26T21:15:42+00:00, book20_bid_proxy_usdt=169689, book20_ask_proxy_usdt=280398, funding_indicative=0.000031, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=6132432. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T21:15:04+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=0.000004, depth_time=2026-10-26T21:15:32+00:00, book20_bid_proxy_usdt=52281, book20_ask_proxy_usdt=200006, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.37%, turnover=83732262. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T21:15:00+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=0.004273, depth_time=2026-10-26T21:15:20+00:00, book20_bid_proxy_usdt=2193039, book20_ask_proxy_usdt=1333703, funding_indicative=0.000000, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.30%, turnover=21901052. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-26T21:15:04+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=205.320000, depth_time=2026-10-26T21:15:19+00:00, book20_bid_proxy_usdt=65578, book20_ask_proxy_usdt=61585, funding_indicative=0.000068, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.32%, turnover=119863347. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T21:15:04+00:00, last15m_closed_end=2026-10-26T21:15+00:00, prior8high=0.443100, depth_time=2026-10-26T21:15:29+00:00, book20_bid_proxy_usdt=3144333, book20_ask_proxy_usdt=2684398, funding_indicative=-0.000133, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=72166160. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
