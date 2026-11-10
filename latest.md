# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T02:30:31Z**
- feed_generated_utc: 2026-11-10T02:30:33+00:00
- source_sha256: `d992b2af0325a2db0becdc0244dfb16eaeadc5e6942aac2bb98110f3ab753121`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T02:30+00:00, close=74862, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T02:00+00:00, close=75046.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1150.630000|-6.12|-8.25|-5.27|2378987106|0.09|
|ARB_USDT|0.173200|-5.89|8.70|-5.04|31319930|0.58|
|DOT_USDT|0.853800|-4.16|-8.59|-3.31|10571320|1.17|
|QNT_USDT|193.480000|-3.27|-4.43|-2.42|38301707|0.52|
|DASH_USDT|46.110000|-3.17|-2.30|-2.32|15617914|2.17|
|WLD_USDT|0.315600|-3.16|-17.20|-2.31|26322498|3.17|
|PUMPFUN_USDT|0.003566|-3.15|-13.10|-2.30|8334158|2.81|
|HBAR_USDT|0.066600|-2.73|-5.49|-1.88|8271419|3.00|
|INJ_USDT|7.975000|-2.47|13.78|-1.62|19468603|1.25|
|SOL_USDT|86.050000|-2.09|-7.97|-1.24|639196989|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.173200|0.172850|0.173200|0.96|N|Y/Y|N/N|Y|N|
|DASH_USDT|46.110000|46.360000|46.120000|4.47|Y|Y/Y|N/N|Y|N|
|DOT_USDT|0.853800|0.852500|0.853800|4.25|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.066600|0.066320|0.066600|0.34|N|Y/Y|Y/N|Y|N|
|INJ_USDT|7.975000|7.965000|7.972000|1.04|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003566|0.003563|0.003566|0.17|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|193.480000|193.200000|193.480000|0.55|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.050000|85.920000|86.050000|1.69|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.315600|0.314400|0.315600|2.06|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1150.630000|1158.600000|1151.310000|1.20|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-10T02:30:01+00:00, last15m_closed_end=2026-11-10T02:30+00:00, prior8high=0.176000, depth_time=2026-11-10T02:30:09+00:00, book20_bid_proxy_usdt=49921, book20_ask_proxy_usdt=50265, funding_indicative=-0.000025, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.89%, turnover=31319930. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T02:30:02+00:00, last15m_closed_end=2026-11-10T02:30+00:00, prior8high=47.310000, depth_time=2026-11-10T02:30:13+00:00, book20_bid_proxy_usdt=629726, book20_ask_proxy_usdt=554576, funding_indicative=0.000011, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=15617914. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T02:30:01+00:00, last15m_closed_end=2026-11-10T02:30+00:00, prior8high=0.858400, depth_time=2026-11-10T02:30:12+00:00, book20_bid_proxy_usdt=480788, book20_ask_proxy_usdt=569724, funding_indicative=0.000009, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.16%, turnover=10571320. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-10T02:30:01+00:00, last15m_closed_end=2026-11-10T02:30+00:00, prior8high=0.067110, depth_time=2026-11-10T02:30:25+00:00, book20_bid_proxy_usdt=872502, book20_ask_proxy_usdt=714934, funding_indicative=0.000090, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=8271419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-10T02:30:01+00:00, last15m_closed_end=2026-11-10T02:30+00:00, prior8high=8.108000, depth_time=2026-11-10T02:30:27+00:00, book20_bid_proxy_usdt=317422, book20_ask_proxy_usdt=286541, funding_indicative=-0.000051, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=19468603. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T02:30:01+00:00, last15m_closed_end=2026-11-10T02:30+00:00, prior8high=0.003620, depth_time=2026-11-10T02:30:20+00:00, book20_bid_proxy_usdt=2542298, book20_ask_proxy_usdt=2583759, funding_indicative=0.000028, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.15%, turnover=8334158. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T02:30:01+00:00, last15m_closed_end=2026-11-10T02:30+00:00, prior8high=195.180000, depth_time=2026-11-10T02:30:15+00:00, book20_bid_proxy_usdt=81481, book20_ask_proxy_usdt=29929, funding_indicative=0.000100, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.27%, turnover=38301707. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T02:30:01+00:00, last15m_closed_end=2026-11-10T02:30+00:00, prior8high=86.740000, depth_time=2026-11-10T02:30:30+00:00, book20_bid_proxy_usdt=17480460, book20_ask_proxy_usdt=17941752, funding_indicative=0.000019, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=639196989. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T02:30:01+00:00, last15m_closed_end=2026-11-10T02:30+00:00, prior8high=0.319200, depth_time=2026-11-10T02:30:19+00:00, book20_bid_proxy_usdt=4248579, book20_ask_proxy_usdt=4847581, funding_indicative=0.000019, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=26322498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T02:30:01+00:00, last15m_closed_end=2026-11-10T02:30+00:00, prior8high=1178.530000, depth_time=2026-11-10T02:30:06+00:00, book20_bid_proxy_usdt=196975, book20_ask_proxy_usdt=193161, funding_indicative=0.000079, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.12%, turnover=2378987106. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
