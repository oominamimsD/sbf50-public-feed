# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T15:30:34Z**
- feed_generated_utc: 2026-10-16T15:30:37+00:00
- source_sha256: `9bdecf099a7416fd50f98e36641a909db4776dbcd41b5d4c617e1d56d48826fc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T15:30+00:00, close=81555.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T15:00+00:00, close=81943.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.074370|-22.82|23.62|-21.83|38892243|2.69|
|PYTH_USDT|0.086270|-11.37|17.21|-10.38|8323164|1.16|
|AKE_USDT|0.029100|-7.92|0.26|-6.93|14252650|0.34|
|PUMPFUN_USDT|0.004301|-4.97|-21.22|-3.98|18337541|2.33|
|PEPE_USDT|0.000004|-4.19|6.43|-3.20|104580961|0.25|
|FET_USDT|0.200600|-4.01|-6.56|-3.02|11504085|4.98|
|UNI_USDT|7.244000|-3.98|-0.99|-2.99|15907330|1.38|
|HYPE_USDT|78.968000|-3.30|-5.26|-2.31|70864363|0.13|
|JUP_USDT|0.303200|-3.06|-12.74|-2.07|5763422|3.30|
|QNT_USDT|202.280000|-2.70|-11.69|-1.71|69814255|1.48|
|ADA_USDT|0.224600|-2.55|-2.93|-1.56|42843998|4.45|
|XPL_USDT|0.082800|-2.28|-0.48|-1.29|5621048|1.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.224600|0.224400|0.224600|1.30|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.029100|0.028349|0.029100|2.55|N|Y/Y|N/N|Y|N|
|FET_USDT|0.200600|0.200900|0.200900|4.12|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|78.968000|79.520000|78.968000|1.92|Y|Y/Y|N/Y|Y|N|
|JUP_USDT|0.303200|0.301800|0.303200|1.15|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|2.81|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004301|0.004326|0.004300|13.00|Y|Y/Y|Y/Y|Y|Y|
|PYTH_USDT|0.086270|0.086600|0.086270|1.23|N|Y/Y|N/N|Y|N|
|QNT_USDT|202.280000|202.460000|202.280000|1.93|Y|Y/Y|N/Y|Y|N|
|STRK_USDT|0.074370|0.074410|0.074360|0.84|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.244000|7.213000|7.244000|2.06|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.082800|0.082510|0.082800|1.61|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-16T15:30:00+00:00, last15m_closed_end=2026-10-16T15:30+00:00, prior8high=0.230800, depth_time=2026-10-16T15:30:32+00:00, book20_bid_proxy_usdt=6208553, book20_ask_proxy_usdt=6163327, funding_indicative=-0.000017, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.55%, turnover=42843998. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-16T15:30:00+00:00, last15m_closed_end=2026-10-16T15:30+00:00, prior8high=0.029607, depth_time=2026-10-16T15:30:12+00:00, book20_bid_proxy_usdt=16894, book20_ask_proxy_usdt=9867, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.92%, turnover=14252650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-16T15:30:00+00:00, last15m_closed_end=2026-10-16T15:30+00:00, prior8high=0.206900, depth_time=2026-10-16T15:30:20+00:00, book20_bid_proxy_usdt=1553297, book20_ask_proxy_usdt=1323700, funding_indicative=0.000100, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.01%, turnover=11504085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-16T15:30:00+00:00, last15m_closed_end=2026-10-16T15:30+00:00, prior8high=81.537000, depth_time=2026-10-16T15:30:24+00:00, book20_bid_proxy_usdt=73956, book20_ask_proxy_usdt=29959, funding_indicative=-0.000002, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.30%, turnover=70864363. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-16T15:30:01+00:00, last15m_closed_end=2026-10-16T15:30+00:00, prior8high=0.310600, depth_time=2026-10-16T15:30:25+00:00, book20_bid_proxy_usdt=453084, book20_ask_proxy_usdt=399497, funding_indicative=-0.000029, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.06%, turnover=5763422. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-16T15:30:00+00:00, last15m_closed_end=2026-10-16T15:30+00:00, prior8high=0.000004, depth_time=2026-10-16T15:30:17+00:00, book20_bid_proxy_usdt=49126, book20_ask_proxy_usdt=43052, funding_indicative=0.000038, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.19%, turnover=104580961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-16T15:30:00+00:00, last15m_closed_end=2026-10-16T15:30+00:00, prior8high=0.004461, depth_time=2026-10-16T15:30:14+00:00, book20_bid_proxy_usdt=1445058, book20_ask_proxy_usdt=1556144, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.97%, turnover=18337541. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T15:30:00+00:00, last15m_closed_end=2026-10-16T15:30+00:00, prior8high=0.089670, depth_time=2026-10-16T15:30:09+00:00, book20_bid_proxy_usdt=80065, book20_ask_proxy_usdt=76926, funding_indicative=0.000017, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.37%, turnover=8323164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-16T15:30:00+00:00, last15m_closed_end=2026-10-16T15:30+00:00, prior8high=208.330000, depth_time=2026-10-16T15:30:29+00:00, book20_bid_proxy_usdt=76110, book20_ask_proxy_usdt=62852, funding_indicative=0.000003, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=69814255. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T15:30:00+00:00, last15m_closed_end=2026-10-16T15:30+00:00, prior8high=0.077680, depth_time=2026-10-16T15:30:07+00:00, book20_bid_proxy_usdt=449847, book20_ask_proxy_usdt=327207, funding_indicative=-0.000017, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.82%, turnover=38892243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-16T15:30:00+00:00, last15m_closed_end=2026-10-16T15:30+00:00, prior8high=7.456000, depth_time=2026-10-16T15:30:22+00:00, book20_bid_proxy_usdt=1266994, book20_ask_proxy_usdt=1695359, funding_indicative=-0.000003, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.98%, turnover=15907330. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-16T15:30:00+00:00, last15m_closed_end=2026-10-16T15:30+00:00, prior8high=0.085030, depth_time=2026-10-16T15:30:34+00:00, book20_bid_proxy_usdt=184889, book20_ask_proxy_usdt=378687, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=5621048. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
