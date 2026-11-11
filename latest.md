# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T00:00:36Z**
- feed_generated_utc: 2026-11-11T00:00:38+00:00
- source_sha256: `1a9d9a1caf34db83a4a0efe7a8a92ed0ccb90b263d9a738d71ba83e8d2c7d09c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005213|-13.53|24.77|-12.71|18763843|5.75|
|ZEC_USDT|1044.470000|-11.91|-13.23|-11.09|2154309820|0.10|
|PIEVERSE_USDT|1.837000|-10.55|56.28|-9.73|5292954|0.54|
|DASH_USDT|42.950000|-7.73|-6.91|-6.91|14045043|2.33|
|UNI_USDT|6.667000|-5.63|-9.32|-4.81|31589080|1.50|
|ENA_USDT|0.150090|-4.26|-12.82|-3.44|34114711|0.67|
|ARB_USDT|0.160550|-2.73|0.41|-1.91|33534117|0.62|
|VVV_USDT|19.299000|-2.61|-13.69|-1.79|5311648|0.52|
|DOT_USDT|0.842700|-2.29|-10.59|-1.47|8337094|1.19|
|LINK_USDT|10.289000|-2.10|-7.75|-1.28|88768143|0.97|
|HBAR_USDT|0.065540|-2.06|-6.41|-1.24|8655973|3.05|
|DOGE_USDT|0.068030|-1.95|-9.87|-1.13|95875526|1.47|
|ADA_USDT|0.173900|-1.91|-8.90|-1.09|22640640|5.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.173900|0.172600|0.173900|0.47|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.160550|0.158610|0.160550|0.29|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|42.950000|42.400000|42.950000|0.91|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.068030|0.067530|0.068030|1.02|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.842700|0.837800|0.842700|0.68|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.150090|0.149960|0.150090|0.28|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065540|0.065190|0.065540|0.42|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005213|0.005119|0.005213|0.45|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.289000|10.223000|10.289000|0.63|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.837000|1.832000|1.837000|0.24|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.667000|6.611000|6.667000|1.05|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.299000|19.229000|19.299000|1.55|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1044.470000|1030.550000|1044.650000|0.87|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-11T00:00:00+00:00, last15m_closed_end=2026-11-11T00:00+00:00, prior8high=0.174700, depth_time=2026-11-11T00:00:36+00:00, book20_bid_proxy_usdt=9077237, book20_ask_proxy_usdt=10663245, funding_indicative=-0.000052, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=22640640. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T00:00:00+00:00, last15m_closed_end=2026-11-11T00:00+00:00, prior8high=0.161710, depth_time=2026-11-11T00:00:19+00:00, book20_bid_proxy_usdt=108019, book20_ask_proxy_usdt=70047, funding_indicative=-0.000176, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=33534117. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T00:00:00+00:00, last15m_closed_end=2026-11-11T00:00+00:00, prior8high=43.460000, depth_time=2026-11-11T00:00:13+00:00, book20_bid_proxy_usdt=667220, book20_ask_proxy_usdt=675506, funding_indicative=-0.000148, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.73%, turnover=14045043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-11T00:00:00+00:00, last15m_closed_end=2026-11-11T00:00+00:00, prior8high=0.068210, depth_time=2026-11-11T00:00:29+00:00, book20_bid_proxy_usdt=4770587, book20_ask_proxy_usdt=4582683, funding_indicative=-0.000033, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=95875526. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T00:00:00+00:00, last15m_closed_end=2026-11-11T00:00+00:00, prior8high=0.846200, depth_time=2026-11-11T00:00:22+00:00, book20_bid_proxy_usdt=649454, book20_ask_proxy_usdt=784029, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.29%, turnover=8337094. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-11T00:00:00+00:00, last15m_closed_end=2026-11-11T00:00+00:00, prior8high=0.151800, depth_time=2026-11-11T00:00:17+00:00, book20_bid_proxy_usdt=229861, book20_ask_proxy_usdt=254961, funding_indicative=0.000035, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.26%, turnover=34114711. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T00:00:00+00:00, last15m_closed_end=2026-11-11T00:00+00:00, prior8high=0.066260, depth_time=2026-11-11T00:00:31+00:00, book20_bid_proxy_usdt=657879, book20_ask_proxy_usdt=694006, funding_indicative=0.000057, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.06%, turnover=8655973. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-11T00:00:00+00:00, last15m_closed_end=2026-11-11T00:00+00:00, prior8high=0.005343, depth_time=2026-11-11T00:00:07+00:00, book20_bid_proxy_usdt=54466, book20_ask_proxy_usdt=42561, funding_indicative=0.000435, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.53%, turnover=18763843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-11T00:00:00+00:00, last15m_closed_end=2026-11-11T00:00+00:00, prior8high=10.378000, depth_time=2026-11-11T00:00:29+00:00, book20_bid_proxy_usdt=332250, book20_ask_proxy_usdt=343985, funding_indicative=0.000023, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=88768143. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-11T00:00:00+00:00, last15m_closed_end=2026-11-11T00:00+00:00, prior8high=1.858500, depth_time=2026-11-11T00:00:11+00:00, book20_bid_proxy_usdt=37478, book20_ask_proxy_usdt=25588, funding_indicative=0.000050, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.55%, turnover=5292954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T00:00:00+00:00, last15m_closed_end=2026-11-11T00:00+00:00, prior8high=6.769000, depth_time=2026-11-11T00:00:14+00:00, book20_bid_proxy_usdt=2779800, book20_ask_proxy_usdt=2913208, funding_indicative=-0.000005, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.63%, turnover=31589080. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T00:00:00+00:00, last15m_closed_end=2026-11-11T00:00+00:00, prior8high=19.529000, depth_time=2026-11-11T00:00:22+00:00, book20_bid_proxy_usdt=22743, book20_ask_proxy_usdt=29558, funding_indicative=0.000011, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=5311648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T00:00:00+00:00, last15m_closed_end=2026-11-11T00:00+00:00, prior8high=1069.190000, depth_time=2026-11-11T00:00:09+00:00, book20_bid_proxy_usdt=91546, book20_ask_proxy_usdt=435015, funding_indicative=0.000031, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.91%, turnover=2154309820. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
