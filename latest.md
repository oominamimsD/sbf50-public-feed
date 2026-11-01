# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T00:00:43Z**
- feed_generated_utc: 2026-11-01T00:00:45+00:00
- source_sha256: `ee5271a0843597a6375d69cea54c50345048fe08cc7f0f636c688a47df0660f3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.244030|-17.60|45.32|-17.56|28884068|2.05|
|BLESS_USDT|0.009440|-10.63|16.35|-10.59|7913709|5.30|
|BTW_USDT|1.081200|-3.62|-37.90|-3.58|5569955|2.77|
|INJ_USDT|7.225000|-3.48|-3.84|-3.44|20912318|1.39|
|TRX_USDT|0.303420|-2.85|-7.75|-2.81|10486415|2.97|
|Q_USDT|0.031200|-2.74|-60.47|-2.70|10640240|3.20|
|ENA_USDT|0.188720|-2.72|1.03|-2.68|46559278|0.53|
|ZEC_USDT|1250.950000|-2.61|9.23|-2.57|1083417119|0.08|
|FET_USDT|0.159700|-2.20|-7.31|-2.16|5918227|6.26|
|AKE_USDT|0.010912|-2.02|-62.66|-1.98|11928741|1.83|
|FARTCOIN_USDT|0.120070|-1.57|-1.56|-1.53|6660037|0.83|
|WLD_USDT|0.398300|-1.50|-13.78|-1.46|34863723|2.51|
|XLM_USDT|0.169500|-1.30|0.64|-1.26|22047468|0.59|
|APT_USDT|0.632600|-1.27|-9.87|-1.23|5042503|1.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010912|0.010836|0.010912|0.28|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.632600|0.631000|0.632600|0.04|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009440|0.009300|0.009440|0.23|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.081200|1.086300|1.081200|2.16|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.188720|0.187820|0.188720|1.26|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120070|0.119850|0.120070|0.40|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.159700|0.159300|0.159700|0.34|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.225000|7.188000|7.225000|0.60|N|N/Y|Y/Y|Y|N|
|LSK_USDT|0.244030|0.237060|0.244220|0.67|N|Y/Y|N/N|Y|N|
|Q_USDT|0.031200|0.031180|0.031200|0.59|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.303420|0.300760|0.303440|0.75|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.398300|0.396700|0.398300|0.50|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.169500|0.169610|0.169500|0.48|N|N/N|N/N|Y|N|
|ZEC_USDT|1250.950000|1243.100000|1250.970000|1.28|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T23:59:59+00:00, last15m_closed_end=2026-11-01T00:00+00:00, prior8high=0.011387, depth_time=2026-11-01T00:00:31+00:00, book20_bid_proxy_usdt=17017, book20_ask_proxy_usdt=8956, funding_indicative=-0.000342, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.02%, turnover=11928741. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-31T23:59:59+00:00, last15m_closed_end=2026-11-01T00:00+00:00, prior8high=0.638000, depth_time=2026-11-01T00:00:41+00:00, book20_bid_proxy_usdt=174152, book20_ask_proxy_usdt=121088, funding_indicative=0.000064, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=5042503. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T23:59:59+00:00, last15m_closed_end=2026-11-01T00:00+00:00, prior8high=0.009573, depth_time=2026-11-01T00:00:11+00:00, book20_bid_proxy_usdt=23154, book20_ask_proxy_usdt=10373, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.63%, turnover=7913709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T23:59:59+00:00, last15m_closed_end=2026-11-01T00:00+00:00, prior8high=1.115500, depth_time=2026-11-01T00:00:14+00:00, book20_bid_proxy_usdt=14465, book20_ask_proxy_usdt=31910, funding_indicative=-0.000129, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.62%, turnover=5569955. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-31T23:59:59+00:00, last15m_closed_end=2026-11-01T00:00+00:00, prior8high=0.191470, depth_time=2026-11-01T00:00:24+00:00, book20_bid_proxy_usdt=137199, book20_ask_proxy_usdt=119516, funding_indicative=0.000000, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.72%, turnover=46559278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-31T23:59:59+00:00, last15m_closed_end=2026-11-01T00:00+00:00, prior8high=0.121480, depth_time=2026-11-01T00:00:34+00:00, book20_bid_proxy_usdt=123308, book20_ask_proxy_usdt=87307, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.57%, turnover=6660037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T23:59:59+00:00, last15m_closed_end=2026-11-01T00:00+00:00, prior8high=0.161300, depth_time=2026-11-01T00:00:28+00:00, book20_bid_proxy_usdt=1084267, book20_ask_proxy_usdt=977198, funding_indicative=-0.000175, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=5918227. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-31T23:59:59+00:00, last15m_closed_end=2026-11-01T00:00+00:00, prior8high=7.312000, depth_time=2026-11-01T00:00:14+00:00, book20_bid_proxy_usdt=399163, book20_ask_proxy_usdt=348466, funding_indicative=0.000081, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=20912318. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T23:59:59+00:00, last15m_closed_end=2026-11-01T00:00+00:00, prior8high=0.252180, depth_time=2026-11-01T00:00:09+00:00, book20_bid_proxy_usdt=8341, book20_ask_proxy_usdt=7604, funding_indicative=-0.001206, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-17.60%, turnover=28884068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T23:59:59+00:00, last15m_closed_end=2026-11-01T00:00+00:00, prior8high=0.032570, depth_time=2026-11-01T00:00:20+00:00, book20_bid_proxy_usdt=55069, book20_ask_proxy_usdt=81271, funding_indicative=-0.000966, next_funding_utc=2026-11-01T01:00:00+00:00, funding_cycle_h=1, 24h_change=-2.74%, turnover=10640240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T23:59:59+00:00, last15m_closed_end=2026-11-01T00:00+00:00, prior8high=0.304080, depth_time=2026-11-01T00:00:17+00:00, book20_bid_proxy_usdt=88930, book20_ask_proxy_usdt=153472, funding_indicative=-0.001228, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=10486415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T23:59:59+00:00, last15m_closed_end=2026-11-01T00:00+00:00, prior8high=0.400500, depth_time=2026-11-01T00:00:36+00:00, book20_bid_proxy_usdt=3001000, book20_ask_proxy_usdt=3089455, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=34863723. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-31T23:59:59+00:00, last15m_closed_end=2026-11-01T00:00+00:00, prior8high=0.170750, depth_time=2026-11-01T00:00:39+00:00, book20_bid_proxy_usdt=185198, book20_ask_proxy_usdt=177632, funding_indicative=-0.000073, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=22047468. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-31T23:59:59+00:00, last15m_closed_end=2026-11-01T00:00+00:00, prior8high=1284.960000, depth_time=2026-11-01T00:00:26+00:00, book20_bid_proxy_usdt=1070861, book20_ask_proxy_usdt=260695, funding_indicative=-0.000044, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=1083417119. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
