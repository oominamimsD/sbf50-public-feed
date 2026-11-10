# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T02:15:33Z**
- feed_generated_utc: 2026-11-10T02:15:34+00:00
- source_sha256: `67986a716e0794f4958ccafb02c6167fd5c61b966165e8afe08af528b1cd2637`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T02:15+00:00, close=74950.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T02:00+00:00, close=75046.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002782|-43.18|-49.43|-42.46|13705527|3.60|
|ARB_USDT|0.173550|-5.69|8.92|-4.97|31110560|1.15|
|ZEC_USDT|1160.110000|-5.35|-7.49|-4.63|2351740474|0.09|
|DOT_USDT|0.854300|-4.10|-8.54|-3.38|10370728|1.17|
|PEPE_USDT|0.000005|-4.07|9.30|-3.35|78444073|0.20|
|WLD_USDT|0.315400|-3.22|-17.26|-2.50|26015039|3.17|
|QNT_USDT|193.750000|-3.14|-4.29|-2.42|38095304|0.52|
|PUMPFUN_USDT|0.003567|-3.12|-13.08|-2.40|8329762|2.80|
|DASH_USDT|46.380000|-2.60|-1.73|-1.88|15246879|2.16|
|INJ_USDT|7.966000|-2.58|13.65|-1.86|19351555|1.25|
|SOL_USDT|86.030000|-2.11|-7.99|-1.39|634016436|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002782|0.002154|0.002782|0.90|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.173550|0.173080|0.173580|1.40|N|Y/Y|N/N|Y|N|
|DASH_USDT|46.380000|46.550000|46.380000|1.55|Y|Y/Y|N/N|Y|N|
|DOT_USDT|0.854300|0.852500|0.854300|0.14|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.966000|7.996000|7.966000|1.09|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|2.08|N|Y/N|N/N|Y|N|
|PUMPFUN_USDT|0.003567|0.003574|0.003563|2.81|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|193.750000|193.200000|193.710000|0.56|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.030000|86.230000|86.030000|2.85|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.315400|0.314900|0.315400|1.85|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1160.110000|1160.240000|1160.120000|0.93|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T02:15:03+00:00, last15m_closed_end=2026-11-10T02:15+00:00, prior8high=0.002982, depth_time=2026-11-10T02:15:07+00:00, book20_bid_proxy_usdt=38684, book20_ask_proxy_usdt=22042, funding_indicative=-0.000175, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-43.18%, turnover=13705527. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T02:15:03+00:00, last15m_closed_end=2026-11-10T02:15+00:00, prior8high=0.176000, depth_time=2026-11-10T02:15:09+00:00, book20_bid_proxy_usdt=58499, book20_ask_proxy_usdt=39004, funding_indicative=-0.000025, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.69%, turnover=31110560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T02:15:03+00:00, last15m_closed_end=2026-11-10T02:15+00:00, prior8high=47.310000, depth_time=2026-11-10T02:15:23+00:00, book20_bid_proxy_usdt=685147, book20_ask_proxy_usdt=447653, funding_indicative=0.000012, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=15246879. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T02:15:03+00:00, last15m_closed_end=2026-11-10T02:15+00:00, prior8high=0.858500, depth_time=2026-11-10T02:15:15+00:00, book20_bid_proxy_usdt=735362, book20_ask_proxy_usdt=575034, funding_indicative=0.000014, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.10%, turnover=10370728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-10T02:15:03+00:00, last15m_closed_end=2026-11-10T02:15+00:00, prior8high=8.135000, depth_time=2026-11-10T02:15:30+00:00, book20_bid_proxy_usdt=293205, book20_ask_proxy_usdt=323039, funding_indicative=-0.000030, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.58%, turnover=19351555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-10T02:15:03+00:00, last15m_closed_end=2026-11-10T02:15+00:00, prior8high=0.000005, depth_time=2026-11-10T02:15:16+00:00, book20_bid_proxy_usdt=49784, book20_ask_proxy_usdt=23112, funding_indicative=0.000100, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.07%, turnover=78444073. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T02:15:03+00:00, last15m_closed_end=2026-11-10T02:15+00:00, prior8high=0.003624, depth_time=2026-11-10T02:15:24+00:00, book20_bid_proxy_usdt=2216993, book20_ask_proxy_usdt=2780554, funding_indicative=0.000024, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.12%, turnover=8329762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T02:15:03+00:00, last15m_closed_end=2026-11-10T02:15+00:00, prior8high=195.180000, depth_time=2026-11-10T02:15:22+00:00, book20_bid_proxy_usdt=77424, book20_ask_proxy_usdt=59912, funding_indicative=0.000100, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.14%, turnover=38095304. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T02:15:03+00:00, last15m_closed_end=2026-11-10T02:15+00:00, prior8high=86.790000, depth_time=2026-11-10T02:15:31+00:00, book20_bid_proxy_usdt=21775867, book20_ask_proxy_usdt=20422121, funding_indicative=0.000030, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=634016436. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T02:15:03+00:00, last15m_closed_end=2026-11-10T02:15+00:00, prior8high=0.319600, depth_time=2026-11-10T02:15:18+00:00, book20_bid_proxy_usdt=5033028, book20_ask_proxy_usdt=4683969, funding_indicative=0.000055, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.22%, turnover=26015039. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T02:15:03+00:00, last15m_closed_end=2026-11-10T02:15+00:00, prior8high=1178.530000, depth_time=2026-11-10T02:15:11+00:00, book20_bid_proxy_usdt=173482, book20_ask_proxy_usdt=322278, funding_indicative=0.000087, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.35%, turnover=2351740474. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
