# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T09:30:33Z**
- feed_generated_utc: 2026-11-10T09:30:34+00:00
- source_sha256: `093d514357c5d58ab5cacab85346560addb460a3d8ccb2b59ade3d66ea89f575`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T09:30+00:00, close=74432.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T09:00+00:00, close=74699.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002487|-49.21|-54.79|-47.80|15326081|4.02|
|JCT_USDT|0.006108|-39.70|41.48|-38.29|25129894|1.64|
|ARB_USDT|0.169260|-8.03|6.23|-6.62|37118605|0.59|
|ZEC_USDT|1144.280000|-6.64|-8.75|-5.23|2315809999|0.09|
|AAVE_USDT|125.460000|-5.91|-3.90|-4.50|12432494|0.80|
|QNT_USDT|189.350000|-5.34|-6.47|-3.93|33202428|2.64|
|DOT_USDT|0.853500|-4.19|-8.62|-2.78|8218031|1.17|
|PUMPFUN_USDT|0.003536|-3.96|-13.84|-2.55|7346461|2.83|
|DASH_USDT|46.180000|-3.02|-2.16|-1.61|10573863|2.16|
|SOL_USDT|85.390000|-2.84|-8.68|-1.43|637212178|1.17|
|INJ_USDT|7.949000|-2.78|13.41|-1.37|16235237|1.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.460000|124.500000|125.460000|1.25|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002487|0.002412|0.002487|1.50|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.169260|0.166250|0.169260|0.54|N|Y/Y|Y/N|Y|N|
|DASH_USDT|46.180000|45.390000|46.180000|2.26|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.853500|0.846200|0.853500|3.83|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.949000|7.862000|7.949000|3.37|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006108|0.005560|0.006111|1.54|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003536|0.003516|0.003536|3.50|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.350000|187.970000|189.350000|2.08|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|85.390000|84.880000|85.390000|0.83|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1144.280000|1134.630000|1144.280000|0.75|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T09:29:59+00:00, last15m_closed_end=2026-11-10T09:30+00:00, prior8high=127.890000, depth_time=2026-11-10T09:30:15+00:00, book20_bid_proxy_usdt=304120, book20_ask_proxy_usdt=395506, funding_indicative=0.000056, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.91%, turnover=12432494. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T09:29:59+00:00, last15m_closed_end=2026-11-10T09:30+00:00, prior8high=0.002555, depth_time=2026-11-10T09:30:07+00:00, book20_bid_proxy_usdt=76028, book20_ask_proxy_usdt=67203, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-49.21%, turnover=15326081. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T09:29:59+00:00, last15m_closed_end=2026-11-10T09:30+00:00, prior8high=0.169040, depth_time=2026-11-10T09:30:12+00:00, book20_bid_proxy_usdt=468695, book20_ask_proxy_usdt=42453, funding_indicative=-0.000128, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.03%, turnover=37118605. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T09:30:00+00:00, last15m_closed_end=2026-11-10T09:30+00:00, prior8high=46.150000, depth_time=2026-11-10T09:30:27+00:00, book20_bid_proxy_usdt=607547, book20_ask_proxy_usdt=691970, funding_indicative=0.000039, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.02%, turnover=10573863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T09:29:59+00:00, last15m_closed_end=2026-11-10T09:30+00:00, prior8high=0.862700, depth_time=2026-11-10T09:30:20+00:00, book20_bid_proxy_usdt=755246, book20_ask_proxy_usdt=448733, funding_indicative=-0.000001, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.19%, turnover=8218031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-10T09:29:59+00:00, last15m_closed_end=2026-11-10T09:30+00:00, prior8high=8.177000, depth_time=2026-11-10T09:30:31+00:00, book20_bid_proxy_usdt=169779, book20_ask_proxy_usdt=150771, funding_indicative=-0.000041, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.78%, turnover=16235237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T09:29:59+00:00, last15m_closed_end=2026-11-10T09:30+00:00, prior8high=0.006657, depth_time=2026-11-10T09:30:10+00:00, book20_bid_proxy_usdt=42817, book20_ask_proxy_usdt=32245, funding_indicative=0.000169, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-39.70%, turnover=25129894. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T09:30:00+00:00, last15m_closed_end=2026-11-10T09:30+00:00, prior8high=0.003593, depth_time=2026-11-10T09:30:24+00:00, book20_bid_proxy_usdt=2855943, book20_ask_proxy_usdt=2957873, funding_indicative=0.000023, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.96%, turnover=7346461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T09:29:59+00:00, last15m_closed_end=2026-11-10T09:30+00:00, prior8high=192.140000, depth_time=2026-11-10T09:30:19+00:00, book20_bid_proxy_usdt=58530, book20_ask_proxy_usdt=88593, funding_indicative=-0.000169, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.34%, turnover=33202428. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T09:29:59+00:00, last15m_closed_end=2026-11-10T09:30+00:00, prior8high=86.490000, depth_time=2026-11-10T09:30:28+00:00, book20_bid_proxy_usdt=14338416, book20_ask_proxy_usdt=20036999, funding_indicative=0.000092, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.84%, turnover=637212178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T09:29:59+00:00, last15m_closed_end=2026-11-10T09:30+00:00, prior8high=1159.070000, depth_time=2026-11-10T09:30:15+00:00, book20_bid_proxy_usdt=409352, book20_ask_proxy_usdt=1021968, funding_indicative=0.000052, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.64%, turnover=2315809999. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
