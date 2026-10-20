# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T09:15:36Z**
- feed_generated_utc: 2026-10-20T09:15:39+00:00
- source_sha256: `0434459ed2238da7fbe7e9870a0a350dbb9964889a3d56f34c9c7b438aae4974`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T09:15+00:00, close=81376.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T09:00+00:00, close=81498.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.070042|-19.52|320.36|-18.87|9548295|2.99|
|BTW_USDT|1.530300|-12.65|-12.84|-12.00|32831988|3.27|
|SAND_USDT|0.056400|-4.63|-9.16|-3.98|5788842|1.77|
|NEAR_USDT|4.712000|-3.91|-15.08|-3.26|162821017|2.12|
|ATOM_USDT|1.718000|-3.26|-6.01|-2.61|5106532|5.82|
|ARB_USDT|0.189270|-3.25|0.42|-2.60|95691572|0.53|
|UNI_USDT|7.124000|-2.25|-3.96|-1.60|10241972|2.81|
|TAO_USDT|262.360000|-2.21|-8.35|-1.56|58068463|1.14|
|QNT_USDT|191.510000|-2.14|-16.14|-1.49|80145754|0.52|
|SEI_USDT|0.059590|-1.78|-10.21|-1.13|6726574|1.68|
|STRK_USDT|0.055640|-1.66|-38.63|-1.01|19428723|1.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.070042|0.066550|0.069980|2.78|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189270|0.188850|0.189280|0.56|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.718000|1.719000|1.718000|1.49|Y|Y/Y|N/N|Y|N|
|BTW_USDT|1.530300|1.486000|1.532000|1.81|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.712000|4.712000|4.711000|0.81|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.510000|189.730000|191.590000|0.96|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.056400|0.056450|0.056400|1.45|Y|Y/Y|Y/Y|Y|Y|
|SEI_USDT|0.059590|0.059530|0.059600|0.86|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.055640|0.055510|0.055640|2.42|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|262.360000|261.940000|262.360000|0.85|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.124000|7.099000|7.124000|0.80|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T09:15:03+00:00, last15m_closed_end=2026-10-20T09:15+00:00, prior8high=0.079107, depth_time=2026-10-20T09:15:09+00:00, book20_bid_proxy_usdt=10080, book20_ask_proxy_usdt=6629, funding_indicative=0.000047, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.52%, turnover=9548295. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T09:15:03+00:00, last15m_closed_end=2026-10-20T09:15+00:00, prior8high=0.197440, depth_time=2026-10-20T09:15:22+00:00, book20_bid_proxy_usdt=69876, book20_ask_proxy_usdt=79129, funding_indicative=0.000037, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=95691572. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T09:15:03+00:00, last15m_closed_end=2026-10-20T09:15+00:00, prior8high=1.753000, depth_time=2026-10-20T09:15:17+00:00, book20_bid_proxy_usdt=1443947, book20_ask_proxy_usdt=1342928, funding_indicative=0.000098, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.26%, turnover=5106532. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T09:15:03+00:00, last15m_closed_end=2026-10-20T09:15+00:00, prior8high=1.720000, depth_time=2026-10-20T09:15:11+00:00, book20_bid_proxy_usdt=11932, book20_ask_proxy_usdt=6280, funding_indicative=-0.004491, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.65%, turnover=32831988. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T09:15:03+00:00, last15m_closed_end=2026-10-20T09:15+00:00, prior8high=4.806000, depth_time=2026-10-20T09:15:16+00:00, book20_bid_proxy_usdt=6721369, book20_ask_proxy_usdt=2851211, funding_indicative=0.000029, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.91%, turnover=162821017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T09:15:03+00:00, last15m_closed_end=2026-10-20T09:15+00:00, prior8high=194.060000, depth_time=2026-10-20T09:15:30+00:00, book20_bid_proxy_usdt=137240, book20_ask_proxy_usdt=82587, funding_indicative=0.000025, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=80145754. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T09:15:03+00:00, last15m_closed_end=2026-10-20T09:15+00:00, prior8high=0.057280, depth_time=2026-10-20T09:15:13+00:00, book20_bid_proxy_usdt=931833, book20_ask_proxy_usdt=1192372, funding_indicative=-0.001468, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.63%, turnover=5788842. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T09:15:03+00:00, last15m_closed_end=2026-10-20T09:15+00:00, prior8high=0.060420, depth_time=2026-10-20T09:15:32+00:00, book20_bid_proxy_usdt=207438, book20_ask_proxy_usdt=382676, funding_indicative=0.000016, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=6726574. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T09:15:03+00:00, last15m_closed_end=2026-10-20T09:15+00:00, prior8high=0.056720, depth_time=2026-10-20T09:15:35+00:00, book20_bid_proxy_usdt=550656, book20_ask_proxy_usdt=765690, funding_indicative=0.000047, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.66%, turnover=19428723. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T09:15:03+00:00, last15m_closed_end=2026-10-20T09:15+00:00, prior8high=265.980000, depth_time=2026-10-20T09:15:27+00:00, book20_bid_proxy_usdt=121426, book20_ask_proxy_usdt=106344, funding_indicative=0.000045, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.21%, turnover=58068463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T09:15:03+00:00, last15m_closed_end=2026-10-20T09:15+00:00, prior8high=7.207000, depth_time=2026-10-20T09:15:24+00:00, book20_bid_proxy_usdt=1691504, book20_ask_proxy_usdt=2282902, funding_indicative=0.000069, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=10241972. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
