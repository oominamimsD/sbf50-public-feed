# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T08:15:43Z**
- feed_generated_utc: 2026-11-07T08:15:45+00:00
- source_sha256: `eb483efbe057a79fb6884ef4cee50dd5d7faddd640f6d90b97a54f61cbb024ff`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T08:15+00:00, close=76076.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T08:00+00:00, close=76053.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-07T08:00+00:00, close=76053.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.125900|-33.73|-52.59|-34.05|31325153|7.94|
|ANTHROPIC_USDT|1349.730000|-5.69|-19.48|-6.01|7545584|0.81|
|TRUMPOFFICIAL_USDT|1.187000|-4.42|-24.49|-4.74|9614107|8.43|
|OP_USDT|0.104000|-3.09|-3.89|-3.41|5550911|0.96|
|PEPE_USDT|0.000005|-3.06|-2.68|-3.38|88337399|0.20|
|DOT_USDT|0.909200|-2.97|-6.19|-3.29|6414897|1.10|
|BEAT_USDT|0.106330|-2.71|1.12|-3.03|8266976|1.88|
|PUMPFUN_USDT|0.003942|-2.54|-4.01|-2.86|12137937|2.54|
|ADA_USDT|0.184400|-1.96|-4.25|-2.28|27179965|5.42|
|ONDO_USDT|0.369600|-1.83|-7.46|-2.15|10420512|2.71|
|ENA_USDT|0.164450|-1.82|-13.39|-2.14|27941597|0.61|
|FARTCOIN_USDT|0.118070|-1.63|-1.85|-1.95|9782252|0.85|
|DOGE_USDT|0.072040|-1.43|-4.98|-1.75|76595007|1.39|
|WLD_USDT|0.340100|-1.36|-17.43|-1.68|27727954|2.94|
|ARB_USDT|0.165930|-1.36|2.35|-1.68|21945670|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.184400|0.184300|0.184400|0.91|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1349.730000|1342.910000|1349.720000|1.29|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165930|0.165260|0.165930|2.64|N|N/N|N/N|Y|N|
|BEAT_USDT|0.106330|0.105300|0.106330|1.36|N|Y/Y|N/N|Y|N|
|DOGE_USDT|0.072040|0.071870|0.072040|1.31|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.909200|0.905400|0.909200|1.18|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.164450|0.163460|0.164450|2.83|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118070|0.117990|0.118070|0.91|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.369600|0.368900|0.369600|0.93|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.104000|0.104210|0.104000|4.91|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000005|0.000005|0.000005|1.15|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003942|0.003893|0.003942|1.22|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.187000|1.179000|1.187000|0.49|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.125900|0.120200|0.125800|1.14|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.340100|0.339100|0.340100|1.31|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=0.185200, depth_time=2026-11-07T08:15:27+00:00, book20_bid_proxy_usdt=10693001, book20_ask_proxy_usdt=8732944, funding_indicative=0.000097, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=27179965. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=1358.000000, depth_time=2026-11-07T08:15:10+00:00, book20_bid_proxy_usdt=28188, book20_ask_proxy_usdt=19336, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.69%, turnover=7545584. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=0.167190, depth_time=2026-11-07T08:15:42+00:00, book20_bid_proxy_usdt=80547, book20_ask_proxy_usdt=82776, funding_indicative=-0.000013, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=21945670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=0.107900, depth_time=2026-11-07T08:15:22+00:00, book20_bid_proxy_usdt=7379, book20_ask_proxy_usdt=10124, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=8266976. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=0.072110, depth_time=2026-11-07T08:15:36+00:00, book20_bid_proxy_usdt=4899883, book20_ask_proxy_usdt=4668146, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=76595007. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=0.911600, depth_time=2026-11-07T08:15:19+00:00, book20_bid_proxy_usdt=716545, book20_ask_proxy_usdt=416250, funding_indicative=0.000085, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=6414897. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=0.165160, depth_time=2026-11-07T08:15:31+00:00, book20_bid_proxy_usdt=181663, book20_ask_proxy_usdt=197102, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=27941597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=0.118640, depth_time=2026-11-07T08:15:34+00:00, book20_bid_proxy_usdt=57906, book20_ask_proxy_usdt=45957, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=9782252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=0.371200, depth_time=2026-11-07T08:15:28+00:00, book20_bid_proxy_usdt=1710734, book20_ask_proxy_usdt=1620876, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.83%, turnover=10420512. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=0.104900, depth_time=2026-11-07T08:15:14+00:00, book20_bid_proxy_usdt=87863, book20_ask_proxy_usdt=102276, funding_indicative=0.000012, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.09%, turnover=5550911. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=0.000005, depth_time=2026-11-07T08:15:17+00:00, book20_bid_proxy_usdt=31831, book20_ask_proxy_usdt=71046, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=88337399. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=0.003942, depth_time=2026-11-07T08:15:23+00:00, book20_bid_proxy_usdt=2682963, book20_ask_proxy_usdt=2637832, funding_indicative=-0.000013, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.54%, turnover=12137937. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=1.188000, depth_time=2026-11-07T08:15:09+00:00, book20_bid_proxy_usdt=1441867, book20_ask_proxy_usdt=1874295, funding_indicative=0.000019, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.42%, turnover=9614107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=0.127300, depth_time=2026-11-07T08:15:07+00:00, book20_bid_proxy_usdt=85976, book20_ask_proxy_usdt=76177, funding_indicative=0.000020, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-33.73%, turnover=31325153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T08:14:59+00:00, last15m_closed_end=2026-11-07T08:15+00:00, prior8high=0.342400, depth_time=2026-11-07T08:15:37+00:00, book20_bid_proxy_usdt=3470397, book20_ask_proxy_usdt=3342016, funding_indicative=-0.000056, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=27727954. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
