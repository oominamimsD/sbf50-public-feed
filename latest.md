# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T02:30:34Z**
- feed_generated_utc: 2026-11-01T02:30:36+00:00
- source_sha256: `61d4d18576f42c962534b5688d8ae9005b3f2ab77afc12ece6fda7a2832e118b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T02:30+00:00, close=77674.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T02:00+00:00, close=77680, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.232940|-21.34|38.72|-21.48|29598038|2.15|
|AKE_USDT|0.009537|-14.37|-67.37|-14.51|11344234|3.15|
|BLESS_USDT|0.009296|-12.00|14.58|-12.14|7493939|2.15|
|ENA_USDT|0.187220|-3.49|0.23|-3.63|45286032|0.53|
|INJ_USDT|7.242000|-3.25|-3.61|-3.39|20195240|1.38|
|ZEC_USDT|1249.260000|-2.74|9.08|-2.88|988070316|0.08|
|WLD_USDT|0.397600|-1.68|-13.93|-1.82|32606830|2.52|
|FARTCOIN_USDT|0.119930|-1.68|-1.68|-1.82|6238654|0.83|
|XLM_USDT|0.168860|-1.67|0.26|-1.81|20290706|0.59|
|FET_USDT|0.160700|-1.59|-6.73|-1.73|5339273|6.22|
|TRX_USDT|0.309120|-1.02|-6.02|-1.16|11174706|2.59|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009537|0.010128|0.009620|10.51|Y|Y/Y|Y/Y|Y|Y|
|BLESS_USDT|0.009296|0.009262|0.009296|0.69|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187220|0.187870|0.187340|4.07|Y|Y/Y|Y/Y|Y|Y|
|FARTCOIN_USDT|0.119930|0.119960|0.119930|1.24|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160700|0.159300|0.160700|0.40|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.242000|7.218000|7.242000|0.95|N|N/N|Y/Y|Y|N|
|LSK_USDT|0.232940|0.231920|0.233110|0.56|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.309120|0.303180|0.309120|0.70|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.397600|0.397700|0.397700|1.64|N|Y/N|Y/Y|Y|N|
|XLM_USDT|0.168860|0.168450|0.168860|0.95|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1249.260000|1249.930000|1249.270000|0.90|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T02:30:03+00:00, last15m_closed_end=2026-11-01T02:30+00:00, prior8high=0.011523, depth_time=2026-11-01T02:30:11+00:00, book20_bid_proxy_usdt=6971, book20_ask_proxy_usdt=17468, funding_indicative=-0.000400, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.37%, turnover=11344234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T02:30:03+00:00, last15m_closed_end=2026-11-01T02:30+00:00, prior8high=0.009626, depth_time=2026-11-01T02:30:13+00:00, book20_bid_proxy_usdt=14838, book20_ask_proxy_usdt=8645, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.00%, turnover=7493939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T02:30:03+00:00, last15m_closed_end=2026-11-01T02:30+00:00, prior8high=0.190060, depth_time=2026-11-01T02:30:16+00:00, book20_bid_proxy_usdt=162144, book20_ask_proxy_usdt=196997, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.49%, turnover=45286032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-01T02:30:03+00:00, last15m_closed_end=2026-11-01T02:30+00:00, prior8high=0.120890, depth_time=2026-11-01T02:30:26+00:00, book20_bid_proxy_usdt=108805, book20_ask_proxy_usdt=75696, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=6238654. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-01T02:30:03+00:00, last15m_closed_end=2026-11-01T02:30+00:00, prior8high=0.161600, depth_time=2026-11-01T02:30:28+00:00, book20_bid_proxy_usdt=1339580, book20_ask_proxy_usdt=862910, funding_indicative=-0.000278, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=5339273. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-01T02:30:03+00:00, last15m_closed_end=2026-11-01T02:30+00:00, prior8high=7.348000, depth_time=2026-11-01T02:30:16+00:00, book20_bid_proxy_usdt=330535, book20_ask_proxy_usdt=366943, funding_indicative=0.000037, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=20195240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T02:30:03+00:00, last15m_closed_end=2026-11-01T02:30+00:00, prior8high=0.253830, depth_time=2026-11-01T02:30:08+00:00, book20_bid_proxy_usdt=6075, book20_ask_proxy_usdt=6014, funding_indicative=-0.001290, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-21.34%, turnover=29598038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T02:30:03+00:00, last15m_closed_end=2026-11-01T02:30+00:00, prior8high=0.309890, depth_time=2026-11-01T02:30:32+00:00, book20_bid_proxy_usdt=97258, book20_ask_proxy_usdt=79329, funding_indicative=-0.001632, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=11174706. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-01T02:30:03+00:00, last15m_closed_end=2026-11-01T02:30+00:00, prior8high=0.400800, depth_time=2026-11-01T02:30:24+00:00, book20_bid_proxy_usdt=3439442, book20_ask_proxy_usdt=2685393, funding_indicative=0.000039, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=32606830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T02:30:03+00:00, last15m_closed_end=2026-11-01T02:30+00:00, prior8high=0.169810, depth_time=2026-11-01T02:30:28+00:00, book20_bid_proxy_usdt=224179, book20_ask_proxy_usdt=198189, funding_indicative=-0.000027, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=20290706. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T02:30:03+00:00, last15m_closed_end=2026-11-01T02:30+00:00, prior8high=1263.460000, depth_time=2026-11-01T02:30:21+00:00, book20_bid_proxy_usdt=973705, book20_ask_proxy_usdt=511623, funding_indicative=-0.000114, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=988070316. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
