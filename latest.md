# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T20:15:34Z**
- feed_generated_utc: 2026-11-04T20:15:36+00:00
- source_sha256: `2a116d060f7ec12adb86a00680381bb16d747ec5530b12affe053d81b9647018`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T20:15+00:00, close=80075.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.288000|-9.55|-24.63|-9.30|24844341|7.75|
|AGT_USDT|0.032600|-9.19|-27.70|-8.94|5090343|3.07|
|IDOL_USDT|0.021439|-8.64|147.64|-8.39|6397862|1.87|
|AKE_USDT|0.002574|-8.39|-87.19|-8.14|17016395|3.89|
|PUMPFUN_USDT|0.004189|-5.86|-0.42|-5.61|19207221|2.39|
|ZRO_USDT|1.773000|-4.91|3.56|-4.66|11305752|0.56|
|WLD_USDT|0.373700|-4.69|-13.65|-4.44|75919816|2.68|
|OP_USDT|0.109110|-4.45|-1.77|-4.20|11689616|0.92|
|PEPE_USDT|0.000005|-4.32|2.03|-4.07|145596689|0.20|
|HYPE_USDT|83.486000|-2.81|4.54|-2.56|89544860|0.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.032600|0.031770|0.032590|0.29|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002574|0.002455|0.002566|0.29|N|Y/Y|Y/Y|N|N|
|HYPE_USDT|83.486000|83.281000|83.486000|1.70|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.021439|0.021833|0.021443|1.23|N|N/N|N/N|N|N|
|OP_USDT|0.109110|0.109230|0.109120|1.57|Y|Y/Y|Y/N|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.32|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004189|0.004138|0.004189|0.87|N|Y/Y|Y/N|N|N|
|TRUMPOFFICIAL_USDT|1.288000|1.237000|1.288000|0.47|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.373700|0.373000|0.373800|2.17|N|Y/Y|Y/N|N|N|
|ZRO_USDT|1.773000|1.765400|1.773000|1.50|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T20:15:03+00:00, last15m_closed_end=2026-11-04T20:15+00:00, prior8high=0.033760, depth_time=2026-11-04T20:15:11+00:00, book20_bid_proxy_usdt=32653, book20_ask_proxy_usdt=34144, funding_indicative=0.000053, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.19%, turnover=5090343. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T20:15:03+00:00, last15m_closed_end=2026-11-04T20:15+00:00, prior8high=0.002774, depth_time=2026-11-04T20:15:18+00:00, book20_bid_proxy_usdt=65296, book20_ask_proxy_usdt=97206, funding_indicative=-0.000535, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.39%, turnover=17016395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T20:15:02+00:00, last15m_closed_end=2026-11-04T20:15+00:00, prior8high=85.210000, depth_time=2026-11-04T20:15:32+00:00, book20_bid_proxy_usdt=66325, book20_ask_proxy_usdt=145630, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.81%, turnover=89544860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-04T20:15:02+00:00, last15m_closed_end=2026-11-04T20:15+00:00, prior8high=0.024026, depth_time=2026-11-04T20:15:14+00:00, book20_bid_proxy_usdt=6720, book20_ask_proxy_usdt=5672, funding_indicative=0.000289, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.64%, turnover=6397862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-04T20:15:03+00:00, last15m_closed_end=2026-11-04T20:15+00:00, prior8high=0.112460, depth_time=2026-11-04T20:15:27+00:00, book20_bid_proxy_usdt=100513, book20_ask_proxy_usdt=113653, funding_indicative=0.000059, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.45%, turnover=11689616. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-04T20:15:03+00:00, last15m_closed_end=2026-11-04T20:15+00:00, prior8high=0.000005, depth_time=2026-11-04T20:15:31+00:00, book20_bid_proxy_usdt=41931, book20_ask_proxy_usdt=42594, funding_indicative=0.000100, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.32%, turnover=145596689. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T20:15:03+00:00, last15m_closed_end=2026-11-04T20:15+00:00, prior8high=0.004277, depth_time=2026-11-04T20:15:20+00:00, book20_bid_proxy_usdt=1211591, book20_ask_proxy_usdt=2298399, funding_indicative=0.000049, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.86%, turnover=19207221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T20:15:03+00:00, last15m_closed_end=2026-11-04T20:15+00:00, prior8high=1.327000, depth_time=2026-11-04T20:15:09+00:00, book20_bid_proxy_usdt=1053754, book20_ask_proxy_usdt=1128654, funding_indicative=-0.000314, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.55%, turnover=24844341. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-04T20:15:03+00:00, last15m_closed_end=2026-11-04T20:15+00:00, prior8high=0.383900, depth_time=2026-11-04T20:15:26+00:00, book20_bid_proxy_usdt=1125424, book20_ask_proxy_usdt=2136346, funding_indicative=-0.000457, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.69%, turnover=75919816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T20:15:03+00:00, last15m_closed_end=2026-11-04T20:15+00:00, prior8high=1.845000, depth_time=2026-11-04T20:15:23+00:00, book20_bid_proxy_usdt=42744, book20_ask_proxy_usdt=57904, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.91%, turnover=11305752. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
