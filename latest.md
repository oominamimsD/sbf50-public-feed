# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T09:00:41Z**
- feed_generated_utc: 2026-11-11T09:00:42+00:00
- source_sha256: `0ebe133b27d514bf1fc7dd6d3843b076c01387bc4dbaf29927404d0fdcd1a488`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T09:00+00:00, close=73699.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T09:00+00:00, close=73699.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.216360|-13.78|60.88|-14.46|67228457|0.46|
|ZEC_USDT|969.900000|-11.29|-19.43|-11.97|2148923881|0.10|
|ONE_USDT|0.001598|-10.91|43.14|-11.59|11293264|0.62|
|PEPE_USDT|0.000005|-8.95|3.40|-9.63|76255775|0.20|
|DASH_USDT|43.240000|-7.11|-6.28|-7.79|16869070|2.31|
|UNI_USDT|6.389000|-6.45|-13.11|-7.13|40210265|1.56|
|AKE_USDT|0.002544|-6.19|-38.78|-6.87|8995994|3.93|
|VVV_USDT|18.847000|-4.89|-15.71|-5.57|5395089|1.59|
|ARB_USDT|0.159200|-3.55|-0.42|-4.23|28855130|0.63|
|QNT_USDT|177.360000|-3.12|-9.24|-3.80|45329538|0.56|
|HYPE_USDT|71.800000|-2.46|-17.80|-3.14|35800233|0.14|
|DOGE_USDT|0.067740|-2.37|-10.25|-3.05|114130191|1.48|
|AAVE_USDT|122.770000|-1.77|-4.42|-2.45|9788383|0.81|
|SOL_USDT|82.940000|-1.62|-11.50|-2.30|588583588|1.21|
|DOT_USDT|0.836600|-0.60|-11.24|-1.28|8576418|1.20|
|HBAR_USDT|0.065390|-0.59|-6.62|-1.27|6362981|1.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|122.770000|121.970000|122.800000|0.47|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002544|0.002501|0.002544|0.51|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159200|0.157280|0.159200|1.06|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.240000|43.250000|43.240000|0.81|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.067740|0.067390|0.067740|0.81|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.836600|0.824500|0.836500|0.80|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|71.800000|71.430000|71.800000|1.25|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.216360|0.183320|0.217850|1.11|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001598|0.001564|0.001599|0.80|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|4.83|Y|Y/Y|N/N|Y|N|
|QNT_USDT|177.360000|177.180000|177.360000|0.30|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|82.940000|82.230000|82.940000|0.54|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.389000|6.373000|6.389000|2.15|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|18.847000|18.851000|18.847000|1.18|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|969.900000|965.410000|970.880000|0.87|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-11T09:00:01+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=123.940000, depth_time=2026-11-11T09:00:34+00:00, book20_bid_proxy_usdt=353456, book20_ask_proxy_usdt=671052, funding_indicative=0.000042, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=9788383. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-11T09:00:01+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=0.002707, depth_time=2026-11-11T09:00:21+00:00, book20_bid_proxy_usdt=57735, book20_ask_proxy_usdt=65244, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.19%, turnover=8995994. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T09:00:01+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=0.160150, depth_time=2026-11-11T09:00:25+00:00, book20_bid_proxy_usdt=52254, book20_ask_proxy_usdt=62360, funding_indicative=-0.000013, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.55%, turnover=28855130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T09:00:01+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=44.240000, depth_time=2026-11-11T09:00:16+00:00, book20_bid_proxy_usdt=572178, book20_ask_proxy_usdt=725495, funding_indicative=-0.000121, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.11%, turnover=16869070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-11T09:00:01+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=0.068190, depth_time=2026-11-11T09:00:33+00:00, book20_bid_proxy_usdt=5660196, book20_ask_proxy_usdt=5597770, funding_indicative=0.000052, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.37%, turnover=114130191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T09:00:01+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=0.841800, depth_time=2026-11-11T09:00:39+00:00, book20_bid_proxy_usdt=378406, book20_ask_proxy_usdt=575637, funding_indicative=0.000100, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.60%, turnover=8576418. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-11T09:00:01+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=72.500000, depth_time=2026-11-11T09:00:30+00:00, book20_bid_proxy_usdt=67862, book20_ask_proxy_usdt=53074, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.46%, turnover=35800233. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T09:00:01+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=0.220410, depth_time=2026-11-11T09:00:07+00:00, book20_bid_proxy_usdt=4614, book20_ask_proxy_usdt=24888, funding_indicative=-0.010250, next_funding_utc=2026-11-11T10:00:00+00:00, funding_cycle_h=1, 24h_change=-13.78%, turnover=67228457. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T09:00:01+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=0.001719, depth_time=2026-11-11T09:00:11+00:00, book20_bid_proxy_usdt=20369, book20_ask_proxy_usdt=22257, funding_indicative=-0.001669, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.91%, turnover=11293264. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T09:00:01+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=0.000005, depth_time=2026-11-11T09:00:14+00:00, book20_bid_proxy_usdt=30310, book20_ask_proxy_usdt=45835, funding_indicative=-0.000093, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.95%, turnover=76255775. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T09:00:01+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=179.710000, depth_time=2026-11-11T09:00:23+00:00, book20_bid_proxy_usdt=53212, book20_ask_proxy_usdt=84529, funding_indicative=-0.000135, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=45329538. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-11T09:00:01+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=83.370000, depth_time=2026-11-11T09:00:35+00:00, book20_bid_proxy_usdt=12719084, book20_ask_proxy_usdt=12953958, funding_indicative=0.000088, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=588583588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T09:00:01+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=6.495000, depth_time=2026-11-11T09:00:18+00:00, book20_bid_proxy_usdt=2469232, book20_ask_proxy_usdt=3079592, funding_indicative=-0.000006, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.45%, turnover=40210265. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T09:00:01+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=19.191000, depth_time=2026-11-11T09:00:22+00:00, book20_bid_proxy_usdt=17612, book20_ask_proxy_usdt=29206, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.89%, turnover=5395089. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T09:00:00+00:00, last15m_closed_end=2026-11-11T09:00+00:00, prior8high=1003.100000, depth_time=2026-11-11T09:00:09+00:00, book20_bid_proxy_usdt=152677, book20_ask_proxy_usdt=131276, funding_indicative=0.000019, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.29%, turnover=2148923881. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
