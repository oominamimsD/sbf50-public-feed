# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T00:15:32Z**
- feed_generated_utc: 2026-10-18T00:15:34+00:00
- source_sha256: `4b2ade53669d0b08e7e9e8c6e4c586accdc23a1f240c77104a77e4b058bbbfa4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T00:15+00:00, close=81440.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.170600|-7.88|72.14|-8.03|14722588|5.86|
|DNA_USDT|0.257000|-5.54|UNKNOWN|-5.69|5497821|3.89|
|STRK_USDT|0.064180|-2.97|-31.30|-3.12|16156526|1.56|
|EIGEN_USDT|0.249600|-2.61|5.94|-2.76|10788439|4.00|
|QNT_USDT|195.250000|-2.57|-20.34|-2.72|66338985|0.51|
|FILECOIN_USDT|1.061900|-2.34|-5.84|-2.49|20797319|0.94|
|TIA_USDT|0.646200|-1.79|25.96|-1.94|73859316|1.55|
|PUMPFUN_USDT|0.004335|-1.74|-24.27|-1.89|24667501|2.31|
|XPL_USDT|0.078750|-1.72|-9.23|-1.87|5018385|1.27|
|ARB_USDT|0.181260|-1.44|-2.89|-1.59|30586442|0.55|
|ZEC_USDT|1126.620000|-1.28|-8.53|-1.43|1149179264|0.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.181260|0.178870|0.181260|0.33|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.257000|0.251600|0.257000|0.31|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.249600|0.246900|0.249600|0.08|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|1.061900|1.050300|1.061900|1.47|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.170600|0.163200|0.170200|0.75|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004335|0.004297|0.004335|1.09|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.250000|193.740000|195.180000|0.49|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.064180|0.064020|0.064190|0.93|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.646200|0.639600|0.646100|0.34|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.078750|0.078140|0.078750|0.20|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1126.620000|1113.720000|1126.000000|0.59|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-18T00:15:02+00:00, last15m_closed_end=2026-10-18T00:15+00:00, prior8high=0.181720, depth_time=2026-10-18T00:15:28+00:00, book20_bid_proxy_usdt=65319, book20_ask_proxy_usdt=67005, funding_indicative=0.000039, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=30586442. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-18T00:15:02+00:00, last15m_closed_end=2026-10-18T00:15+00:00, prior8high=0.260000, depth_time=2026-10-18T00:15:09+00:00, book20_bid_proxy_usdt=86368, book20_ask_proxy_usdt=78934, funding_indicative=-0.001720, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.54%, turnover=5497821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T00:15:02+00:00, last15m_closed_end=2026-10-18T00:15+00:00, prior8high=0.252000, depth_time=2026-10-18T00:15:13+00:00, book20_bid_proxy_usdt=448496, book20_ask_proxy_usdt=365042, funding_indicative=0.000008, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=10788439. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T00:15:02+00:00, last15m_closed_end=2026-10-18T00:15+00:00, prior8high=1.066900, depth_time=2026-10-18T00:15:17+00:00, book20_bid_proxy_usdt=275864, book20_ask_proxy_usdt=465374, funding_indicative=-0.000040, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=20797319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T00:15:02+00:00, last15m_closed_end=2026-10-18T00:15+00:00, prior8high=0.174600, depth_time=2026-10-18T00:15:07+00:00, book20_bid_proxy_usdt=318796, book20_ask_proxy_usdt=143999, funding_indicative=-0.000097, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.88%, turnover=14722588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T00:15:02+00:00, last15m_closed_end=2026-10-18T00:15+00:00, prior8high=0.004372, depth_time=2026-10-18T00:15:24+00:00, book20_bid_proxy_usdt=1805199, book20_ask_proxy_usdt=1817986, funding_indicative=0.000031, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=24667501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T00:15:02+00:00, last15m_closed_end=2026-10-18T00:15+00:00, prior8high=196.940000, depth_time=2026-10-18T00:15:17+00:00, book20_bid_proxy_usdt=64230, book20_ask_proxy_usdt=101730, funding_indicative=-0.000046, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.57%, turnover=66338985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T00:15:02+00:00, last15m_closed_end=2026-10-18T00:15+00:00, prior8high=0.065060, depth_time=2026-10-18T00:15:12+00:00, book20_bid_proxy_usdt=304788, book20_ask_proxy_usdt=301020, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.97%, turnover=16156526. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T00:15:02+00:00, last15m_closed_end=2026-10-18T00:15+00:00, prior8high=0.649400, depth_time=2026-10-18T00:15:20+00:00, book20_bid_proxy_usdt=171519, book20_ask_proxy_usdt=205632, funding_indicative=0.000000, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.79%, turnover=73859316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T00:15:03+00:00, last15m_closed_end=2026-10-18T00:15+00:00, prior8high=0.078920, depth_time=2026-10-18T00:15:26+00:00, book20_bid_proxy_usdt=365073, book20_ask_proxy_usdt=483214, funding_indicative=0.000037, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=5018385. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T00:15:02+00:00, last15m_closed_end=2026-10-18T00:15+00:00, prior8high=1131.290000, depth_time=2026-10-18T00:15:31+00:00, book20_bid_proxy_usdt=189034, book20_ask_proxy_usdt=281885, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=1149179264. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
