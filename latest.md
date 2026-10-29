# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T14:30:36Z**
- feed_generated_utc: 2026-10-29T14:30:37+00:00
- source_sha256: `d90badc6ef5778b352153dc6a9ad0932a480c70ef3510cc43ce2b5df37fe34fb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T14:30+00:00, close=80393.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T14:00+00:00, close=80275.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-29T12:00+00:00, close=80133.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.040730|-34.59|-64.93|-34.44|34033832|2.46|
|EVAA_USDT|1.162200|-21.73|106.21|-21.58|18860396|7.75|
|BLESS_USDT|0.009589|-12.48|19.14|-12.33|9343805|5.21|
|JASMY_USDT|0.003873|-8.59|-20.57|-8.44|7779172|2.58|
|DASH_USDT|50.350000|-5.07|-5.48|-4.92|14932878|1.99|
|NEAR_USDT|4.442000|-4.03|-17.51|-3.88|104179451|4.50|
|HBAR_USDT|0.073940|-2.59|-13.96|-2.44|14748878|1.35|
|WLD_USDT|0.422100|-2.47|-26.41|-2.32|79263267|2.37|
|SILVER_USDT|52.650000|-1.90|-8.68|-1.75|549979311|1.90|
|BTW_USDT|1.710300|-1.59|16.36|-1.44|9724787|1.76|
|XRP_USDT|1.290900|-1.54|-6.47|-1.39|292880993|0.78|
|LTC_USDT|57.670000|-1.16|-7.05|-1.01|12080514|1.73|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009589|0.009476|0.009589|0.75|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.710300|1.606100|1.710300|2.48|N|N/N|N/N|Y|N|
|DASH_USDT|50.350000|49.890000|50.360000|1.13|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.162200|1.168600|1.162500|0.87|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.073940|0.073330|0.073940|1.23|N|N/Y|Y/Y|Y|N|
|JASMY_USDT|0.003873|0.003843|0.003870|0.96|N|Y/Y|Y/Y|Y|N|
|LTC_USDT|57.670000|57.640000|57.670000|1.61|N|N/N|N/Y|Y|N|
|NEAR_USDT|4.442000|4.389000|4.442000|0.38|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.040730|0.039680|0.040730|1.54|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.650000|52.110000|52.640000|1.26|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.422100|0.416800|0.422200|2.28|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.290900|1.285100|1.290900|2.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-29T14:30:01+00:00, last15m_closed_end=2026-10-29T14:30+00:00, prior8high=0.009702, depth_time=2026-10-29T14:30:12+00:00, book20_bid_proxy_usdt=10204, book20_ask_proxy_usdt=13449, funding_indicative=0.000227, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.48%, turnover=9343805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T14:30:01+00:00, last15m_closed_end=2026-10-29T14:30+00:00, prior8high=1.794200, depth_time=2026-10-29T14:30:29+00:00, book20_bid_proxy_usdt=19048, book20_ask_proxy_usdt=10045, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.59%, turnover=9724787. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-29T14:30:01+00:00, last15m_closed_end=2026-10-29T14:30+00:00, prior8high=50.560000, depth_time=2026-10-29T14:30:16+00:00, book20_bid_proxy_usdt=388242, book20_ask_proxy_usdt=611469, funding_indicative=0.000006, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.07%, turnover=14932878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T14:30:01+00:00, last15m_closed_end=2026-10-29T14:30+00:00, prior8high=1.285900, depth_time=2026-10-29T14:30:09+00:00, book20_bid_proxy_usdt=16278, book20_ask_proxy_usdt=19324, funding_indicative=0.000153, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.73%, turnover=18860396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T14:30:01+00:00, last15m_closed_end=2026-10-29T14:30+00:00, prior8high=0.074600, depth_time=2026-10-29T14:30:22+00:00, book20_bid_proxy_usdt=713592, book20_ask_proxy_usdt=455051, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.59%, turnover=14748878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JASMY_USDT: quote_utc=2026-10-29T14:30:01+00:00, last15m_closed_end=2026-10-29T14:30+00:00, prior8high=0.003998, depth_time=2026-10-29T14:30:14+00:00, book20_bid_proxy_usdt=166268, book20_ask_proxy_usdt=104384, funding_indicative=-0.000340, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.59%, turnover=7779172. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-29T14:30:01+00:00, last15m_closed_end=2026-10-29T14:30+00:00, prior8high=58.340000, depth_time=2026-10-29T14:30:34+00:00, book20_bid_proxy_usdt=1700837, book20_ask_proxy_usdt=1519454, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=12080514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T14:30:01+00:00, last15m_closed_end=2026-10-29T14:30+00:00, prior8high=4.511000, depth_time=2026-10-29T14:30:19+00:00, book20_bid_proxy_usdt=552194, book20_ask_proxy_usdt=4979373, funding_indicative=0.000072, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.03%, turnover=104179451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T14:30:01+00:00, last15m_closed_end=2026-10-29T14:30+00:00, prior8high=0.042860, depth_time=2026-10-29T14:30:07+00:00, book20_bid_proxy_usdt=75223, book20_ask_proxy_usdt=60293, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-34.59%, turnover=34033832. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-29T14:30:01+00:00, last15m_closed_end=2026-10-29T14:30+00:00, prior8high=52.850000, depth_time=2026-10-29T14:30:27+00:00, book20_bid_proxy_usdt=48749538, book20_ask_proxy_usdt=45211094, funding_indicative=0.000077, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=549979311. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T14:30:01+00:00, last15m_closed_end=2026-10-29T14:30+00:00, prior8high=0.424500, depth_time=2026-10-29T14:30:24+00:00, book20_bid_proxy_usdt=2522119, book20_ask_proxy_usdt=3618862, funding_indicative=0.000042, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=79263267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-10-29T14:30:01+00:00, last15m_closed_end=2026-10-29T14:30+00:00, prior8high=1.294800, depth_time=2026-10-29T14:30:32+00:00, book20_bid_proxy_usdt=2745584, book20_ask_proxy_usdt=3898757, funding_indicative=0.000095, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=292880993. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
