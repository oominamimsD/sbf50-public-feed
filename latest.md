# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T09:00:42Z**
- feed_generated_utc: 2026-10-13T09:00:45+00:00
- source_sha256: `ef4e0a87adff1a19e8bd2f73ed0d9acbec8610cad893095c31415258e4e38594`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T09:00+00:00, close=83555.3, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T09:00+00:00, close=83555.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T08:00+00:00, close=83829.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.225200|-24.02|5.72|-25.07|9413319|4.44|
|W_USDT|0.019179|-20.28|35.60|-21.33|28200971|2.09|
|RSR_USDT|0.002026|-13.78|19.10|-14.83|14970386|9.87|
|ZRO_USDT|2.089200|-10.96|2.13|-12.01|22365709|1.44|
|RLC_USDT|0.944600|-7.98|72.37|-9.03|6716001|2.12|
|PUMPFUN_USDT|0.005051|-6.91|-20.26|-7.96|31844881|1.98|
|NEAR_USDT|5.168000|-6.86|2.90|-7.91|264604625|1.94|
|LIT_USDT|3.373000|-6.81|-11.28|-7.86|10048240|0.30|
|ONDO_USDT|0.475100|-4.61|-2.80|-5.66|63738499|2.10|
|STRK_USDT|0.086510|-4.58|66.01|-5.63|60575316|1.16|
|PONS_USDT|0.286500|-4.24|-25.29|-5.29|6214196|3.49|
|SEI_USDT|0.063930|-3.79|-11.09|-4.84|8553340|1.56|
|ICP_USDT|3.188000|-3.74|-8.02|-4.79|17106760|3.14|
|JUP_USDT|0.332100|-3.37|-1.71|-4.42|8544695|3.01|
|GRASS_USDT|0.745700|-3.18|5.74|-4.23|6256747|4.03|
|HBAR_USDT|0.087730|-3.06|-12.87|-4.11|22420999|2.28|
|USELESS_USDT|0.176670|-2.82|-22.08|-3.87|6135491|3.40|
|SAND_USDT|0.060550|-1.49|-10.29|-2.54|7776151|1.65|
|QNT_USDT|225.770000|-1.14|-12.07|-2.19|74063546|0.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.225200|0.223500|0.225200|2.30|N|Y/Y|Y/Y|N|N|
|GRASS_USDT|0.745700|0.745400|0.745700|1.00|N|Y/Y|N/N|N|N|
|ICP_USDT|3.188000|3.185000|3.188000|0.70|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.332100|0.333800|0.332100|0.48|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.373000|3.395000|3.373000|1.34|Y|Y/Y|Y/Y|N|Y|
|NEAR_USDT|5.168000|5.151000|5.166000|0.87|N|Y/Y|Y/Y|N|N|
|ONDO_USDT|0.475100|0.476500|0.475000|2.34|Y|Y/Y|Y/Y|N|Y|
|PONS_USDT|0.286500|0.285300|0.286500|2.18|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005051|0.005044|0.005051|0.78|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.944600|0.917000|0.944600|3.34|N|Y/Y|Y/Y|N|N|
|RSR_USDT|0.002026|0.001977|0.002027|0.43|N|Y/Y|N/N|N|N|
|SEI_USDT|0.063930|0.064140|0.063930|0.71|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.086510|0.083010|0.086560|0.97|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019179|0.019206|0.019175|1.17|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.089200|2.075100|2.089200|1.09|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T09:00:01+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=0.234500, depth_time=2026-10-13T09:00:08+00:00, book20_bid_proxy_usdt=71611, book20_ask_proxy_usdt=102112, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-24.02%, turnover=9413319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- GRASS_USDT: quote_utc=2026-10-13T09:00:02+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=0.794800, depth_time=2026-10-13T09:00:41+00:00, book20_bid_proxy_usdt=129344, book20_ask_proxy_usdt=242380, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.18%, turnover=6256747. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T09:00:02+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=3.275000, depth_time=2026-10-13T09:00:37+00:00, book20_bid_proxy_usdt=761779, book20_ask_proxy_usdt=806666, funding_indicative=-0.000039, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.74%, turnover=17106760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T09:00:02+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=0.339000, depth_time=2026-10-13T09:00:39+00:00, book20_bid_proxy_usdt=650699, book20_ask_proxy_usdt=354095, funding_indicative=-0.000034, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.37%, turnover=8544695. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T09:00:02+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=3.456200, depth_time=2026-10-13T09:00:25+00:00, book20_bid_proxy_usdt=25433, book20_ask_proxy_usdt=33797, funding_indicative=0.000038, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.81%, turnover=10048240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T09:00:01+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=5.301000, depth_time=2026-10-13T09:00:22+00:00, book20_bid_proxy_usdt=3964901, book20_ask_proxy_usdt=2684748, funding_indicative=0.000028, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.86%, turnover=264604625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-13T09:00:01+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=0.483600, depth_time=2026-10-13T09:00:27+00:00, book20_bid_proxy_usdt=1802085, book20_ask_proxy_usdt=2142870, funding_indicative=0.000000, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.61%, turnover=63738499. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T09:00:02+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=0.295200, depth_time=2026-10-13T09:00:32+00:00, book20_bid_proxy_usdt=234807, book20_ask_proxy_usdt=215709, funding_indicative=0.000051, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.24%, turnover=6214196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T09:00:02+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=0.005142, depth_time=2026-10-13T09:00:20+00:00, book20_bid_proxy_usdt=1689501, book20_ask_proxy_usdt=1326944, funding_indicative=-0.000004, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.91%, turnover=31844881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T09:00:02+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=0.955600, depth_time=2026-10-13T09:00:17+00:00, book20_bid_proxy_usdt=41655, book20_ask_proxy_usdt=55272, funding_indicative=-0.000901, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.98%, turnover=6716001. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RSR_USDT: quote_utc=2026-10-13T09:00:01+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=0.002122, depth_time=2026-10-13T09:00:13+00:00, book20_bid_proxy_usdt=111208, book20_ask_proxy_usdt=298828, funding_indicative=-0.006040, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-13.78%, turnover=14970386. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T09:00:02+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=0.064840, depth_time=2026-10-13T09:00:34+00:00, book20_bid_proxy_usdt=200022, book20_ask_proxy_usdt=211426, funding_indicative=0.000042, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.79%, turnover=8553340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T09:00:01+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=0.088100, depth_time=2026-10-13T09:00:29+00:00, book20_bid_proxy_usdt=187712, book20_ask_proxy_usdt=124346, funding_indicative=0.000018, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.58%, turnover=60575316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T09:00:01+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=0.019627, depth_time=2026-10-13T09:00:10+00:00, book20_bid_proxy_usdt=56266, book20_ask_proxy_usdt=23012, funding_indicative=-0.000477, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-20.28%, turnover=28200971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T09:00:02+00:00, last15m_closed_end=2026-10-13T09:00+00:00, prior8high=2.157300, depth_time=2026-10-13T09:00:15+00:00, book20_bid_proxy_usdt=29879, book20_ask_proxy_usdt=47123, funding_indicative=-0.000033, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.96%, turnover=22365709. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
