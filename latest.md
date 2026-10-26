# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T04:15:30Z**
- feed_generated_utc: 2026-10-26T04:15:33+00:00
- source_sha256: `56c39597914ae047da9c618d6e068664ff4d9e50cc96a928ac0b0a75779f8183`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T04:15+00:00, close=79907, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004811|-30.99|161.04|-30.14|11624692|4.15|
|APR_USDT|0.035120|-14.98|28.92|-14.13|12079001|2.84|
|T_USDT|0.004949|-8.06|5.25|-7.21|6429141|4.04|
|IRYS_USDT|0.036210|-5.80|196.80|-4.95|15697656|2.77|
|LIT_USDT|3.041800|-4.29|3.80|-3.44|5922200|0.33|
|DASH_USDT|50.650000|-3.35|5.78|-2.50|13657161|1.98|
|WLD_USDT|0.442100|-3.17|-7.18|-2.32|72479719|2.26|
|XMR_USDT|592.540000|-2.42|1.72|-1.57|6780360|0.17|
|PUMPFUN_USDT|0.004183|-2.38|-0.28|-1.53|17369641|2.39|
|STRK_USDT|0.044880|-1.88|-27.09|-1.03|9292855|2.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.035120|0.032120|0.035110|0.34|N|Y/Y|N/N|Y|N|
|DASH_USDT|50.650000|50.050000|50.650000|1.39|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.036210|0.035450|0.036210|0.45|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004811|0.003891|0.004800|1.34|N|Y/Y|Y/N|Y|N|
|LIT_USDT|3.041800|3.000800|3.044500|3.12|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004183|0.004111|0.004183|1.42|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044880|0.044650|0.044880|0.50|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004949|0.004895|0.004950|0.39|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.442100|0.434800|0.442100|1.02|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|592.540000|588.690000|592.540000|1.24|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T04:15:01+00:00, last15m_closed_end=2026-10-26T04:15+00:00, prior8high=0.036370, depth_time=2026-10-26T04:15:10+00:00, book20_bid_proxy_usdt=66188, book20_ask_proxy_usdt=60558, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.98%, turnover=12079001. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T04:15:02+00:00, last15m_closed_end=2026-10-26T04:15+00:00, prior8high=51.070000, depth_time=2026-10-26T04:15:19+00:00, book20_bid_proxy_usdt=528639, book20_ask_proxy_usdt=693050, funding_indicative=0.000041, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.35%, turnover=13657161. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T04:15:01+00:00, last15m_closed_end=2026-10-26T04:15+00:00, prior8high=0.039970, depth_time=2026-10-26T04:15:14+00:00, book20_bid_proxy_usdt=44906, book20_ask_proxy_usdt=56521, funding_indicative=-0.000618, next_funding_utc=2026-10-26T05:00:00+00:00, funding_cycle_h=1, 24h_change=-5.80%, turnover=15697656. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T04:15:01+00:00, last15m_closed_end=2026-10-26T04:15+00:00, prior8high=0.005751, depth_time=2026-10-26T04:15:07+00:00, book20_bid_proxy_usdt=13205, book20_ask_proxy_usdt=10602, funding_indicative=0.000195, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-30.99%, turnover=11624692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T04:15:02+00:00, last15m_closed_end=2026-10-26T04:15+00:00, prior8high=3.152900, depth_time=2026-10-26T04:15:17+00:00, book20_bid_proxy_usdt=22072, book20_ask_proxy_usdt=43294, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.29%, turnover=5922200. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T04:15:02+00:00, last15m_closed_end=2026-10-26T04:15+00:00, prior8high=0.004222, depth_time=2026-10-26T04:15:24+00:00, book20_bid_proxy_usdt=1298020, book20_ask_proxy_usdt=1900144, funding_indicative=0.000049, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.38%, turnover=17369641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T04:15:02+00:00, last15m_closed_end=2026-10-26T04:15+00:00, prior8high=0.045660, depth_time=2026-10-26T04:15:29+00:00, book20_bid_proxy_usdt=886390, book20_ask_proxy_usdt=670481, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.88%, turnover=9292855. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T04:15:02+00:00, last15m_closed_end=2026-10-26T04:15+00:00, prior8high=0.004998, depth_time=2026-10-26T04:15:12+00:00, book20_bid_proxy_usdt=59437, book20_ask_proxy_usdt=66788, funding_indicative=-0.001584, next_funding_utc=2026-10-26T05:00:00+00:00, funding_cycle_h=1, 24h_change=-8.06%, turnover=6429141. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T04:15:02+00:00, last15m_closed_end=2026-10-26T04:15+00:00, prior8high=0.447900, depth_time=2026-10-26T04:15:22+00:00, book20_bid_proxy_usdt=1977016, book20_ask_proxy_usdt=2313068, funding_indicative=0.000093, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=72479719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T04:15:02+00:00, last15m_closed_end=2026-10-26T04:15+00:00, prior8high=598.030000, depth_time=2026-10-26T04:15:23+00:00, book20_bid_proxy_usdt=20857, book20_ask_proxy_usdt=25955, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=6780360. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
