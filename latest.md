# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T09:30:43Z**
- feed_generated_utc: 2026-11-07T09:30:45+00:00
- source_sha256: `8b7fdb5409f16bbcdf5d28c866a9a01b6ecc32a313ffdc8bfb378828a7715547`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T09:30+00:00, close=76037.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T09:00+00:00, close=76158.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-07T08:00+00:00, close=76053.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.124800|-34.31|-53.01|-34.57|31197657|8.02|
|ANTHROPIC_USDT|1349.820000|-5.68|-19.48|-5.94|7991917|2.15|
|TRUMPOFFICIAL_USDT|1.178000|-5.15|-25.06|-5.41|9446551|8.49|
|OP_USDT|0.103130|-3.90|-4.69|-4.16|5665277|1.94|
|DOT_USDT|0.905300|-3.39|-6.59|-3.65|6450107|1.10|
|PUMPFUN_USDT|0.003912|-3.28|-4.74|-3.54|12067670|2.56|
|ENA_USDT|0.162900|-2.75|-14.20|-3.01|27839856|0.61|
|PEPE_USDT|0.000005|-2.51|-2.12|-2.77|85933609|0.60|
|ADA_USDT|0.183600|-2.39|-4.67|-2.65|27021972|5.45|
|ONDO_USDT|0.368200|-2.20|-7.81|-2.46|9977915|2.72|
|BEAT_USDT|0.106920|-2.17|1.68|-2.43|7810236|1.87|
|WLD_USDT|0.337600|-2.08|-18.03|-2.34|27885003|2.96|
|FARTCOIN_USDT|0.117920|-1.75|-1.97|-2.01|9463202|2.54|
|ARB_USDT|0.165520|-1.60|2.09|-1.86|22614735|0.60|
|DOGE_USDT|0.071990|-1.50|-5.05|-1.76|76168089|1.39|
|AVAX_USDT|8.309000|-1.17|-0.46|-1.43|12012333|1.20|
|XLM_USDT|0.153280|-1.15|-11.00|-1.41|22599991|3.26|
|NEAR_USDT|3.721000|-0.98|-13.90|-1.24|34777605|2.69|
|SUI_USDT|0.865600|-0.85|-2.64|-1.11|31258559|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.183600|0.183600|0.183600|1.54|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1349.820000|1343.740000|1349.820000|0.41|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165520|0.165350|0.165520|0.43|N|Y/N|N/N|Y|N|
|BEAT_USDT|0.106920|0.105900|0.106920|0.45|N|Y/Y|N/N|Y|N|
|DOGE_USDT|0.071990|0.071890|0.071930|3.85|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.905300|0.904100|0.905300|1.40|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.162900|0.163010|0.162900|4.19|Y|Y/Y|Y/Y|Y|Y|
|FARTCOIN_USDT|0.117920|0.117760|0.117920|1.36|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.368200|0.368300|0.368200|2.01|Y|Y/Y|Y/Y|Y|Y|
|OP_USDT|0.103130|0.103060|0.103130|4.90|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.12|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003912|0.003917|0.003912|1.44|Y|N/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.178000|1.180000|1.178000|1.18|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.124800|0.121500|0.124800|0.77|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.337600|0.337600|0.337600|0.52|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=0.185200, depth_time=2026-11-07T09:30:27+00:00, book20_bid_proxy_usdt=10594359, book20_ask_proxy_usdt=7890020, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=27021972. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=1361.580000, depth_time=2026-11-07T09:30:09+00:00, book20_bid_proxy_usdt=26634, book20_ask_proxy_usdt=30392, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.68%, turnover=7991917. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=0.167180, depth_time=2026-11-07T09:30:39+00:00, book20_bid_proxy_usdt=74064, book20_ask_proxy_usdt=77863, funding_indicative=-0.000034, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=22614735. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=0.108330, depth_time=2026-11-07T09:30:29+00:00, book20_bid_proxy_usdt=7523, book20_ask_proxy_usdt=6727, funding_indicative=0.000144, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=7810236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=0.072150, depth_time=2026-11-07T09:30:40+00:00, book20_bid_proxy_usdt=5001832, book20_ask_proxy_usdt=5476753, funding_indicative=0.000032, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=76168089. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=0.911600, depth_time=2026-11-07T09:30:12+00:00, book20_bid_proxy_usdt=463752, book20_ask_proxy_usdt=549080, funding_indicative=0.000044, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.39%, turnover=6450107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=0.165160, depth_time=2026-11-07T09:30:21+00:00, book20_bid_proxy_usdt=142804, book20_ask_proxy_usdt=136323, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=27839856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=0.118640, depth_time=2026-11-07T09:30:36+00:00, book20_bid_proxy_usdt=55795, book20_ask_proxy_usdt=50236, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.75%, turnover=9463202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=0.371200, depth_time=2026-11-07T09:30:29+00:00, book20_bid_proxy_usdt=1902011, book20_ask_proxy_usdt=2075793, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.20%, turnover=9977915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=0.104580, depth_time=2026-11-07T09:30:13+00:00, book20_bid_proxy_usdt=138149, book20_ask_proxy_usdt=138950, funding_indicative=0.000035, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.90%, turnover=5665277. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=0.000005, depth_time=2026-11-07T09:30:23+00:00, book20_bid_proxy_usdt=36978, book20_ask_proxy_usdt=46778, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=85933609. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=0.003958, depth_time=2026-11-07T09:30:16+00:00, book20_bid_proxy_usdt=2876022, book20_ask_proxy_usdt=1902979, funding_indicative=0.000012, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=12067670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=1.191000, depth_time=2026-11-07T09:30:09+00:00, book20_bid_proxy_usdt=1593655, book20_ask_proxy_usdt=1595131, funding_indicative=-0.000018, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.15%, turnover=9446551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=0.136000, depth_time=2026-11-07T09:30:06+00:00, book20_bid_proxy_usdt=148228, book20_ask_proxy_usdt=87419, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-34.31%, turnover=31197657. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T09:29:59+00:00, last15m_closed_end=2026-11-07T09:30+00:00, prior8high=0.342400, depth_time=2026-11-07T09:30:34+00:00, book20_bid_proxy_usdt=2863265, book20_ask_proxy_usdt=3052826, funding_indicative=-0.000031, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=27885003. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
