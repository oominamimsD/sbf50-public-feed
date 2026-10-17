# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T23:00:37Z**
- feed_generated_utc: 2026-10-17T23:00:39+00:00
- source_sha256: `c16f1a650200eb431a917bdfeda5caf095c30afc4357f7f855b5b0cc012e8a15`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T23:00+00:00, close=81327, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T23:00+00:00, close=81327, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.169200|-8.63|70.73|-8.64|14745087|5.91|
|DNA_USDT|0.256800|-5.62|UNKNOWN|-5.63|6337942|7.79|
|EIGEN_USDT|0.249300|-2.73|5.81|-2.74|10584970|4.01|
|QNT_USDT|195.220000|-2.58|-20.36|-2.59|67436067|0.51|
|FILECOIN_USDT|1.060400|-2.48|-5.97|-2.49|21819977|0.94|
|TIA_USDT|0.643600|-2.18|25.45|-2.19|76366012|1.55|
|STRK_USDT|0.064870|-1.93|-30.56|-1.94|16229831|1.54|
|ZEC_USDT|1124.140000|-1.50|-8.73|-1.51|1181111522|0.09|
|PUMPFUN_USDT|0.004347|-1.47|-24.06|-1.48|30013081|2.30|
|WLD_USDT|0.488600|-1.41|-12.59|-1.42|68583896|2.05|
|ARB_USDT|0.181460|-1.33|-2.79|-1.34|31204517|0.55|
|ZRO_USDT|1.864200|-1.11|-7.74|-1.12|8552580|0.54|
|PEPE_USDT|0.000004|-1.09|-4.65|-1.10|59226035|0.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.181460|0.176600|0.181460|0.88|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.256800|0.245300|0.256800|0.55|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.249300|0.241300|0.249300|0.18|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.060400|1.038400|1.060400|0.17|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.169200|0.163200|0.169200|0.57|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.42|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004347|0.004262|0.004347|0.94|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.220000|190.470000|195.220000|1.25|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.064870|0.063090|0.064870|0.54|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.643600|0.634700|0.643600|0.39|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.488600|0.477800|0.488600|0.69|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1124.140000|1098.000000|1124.140000|0.74|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.864200|1.841200|1.864500|1.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T22:59:58+00:00, last15m_closed_end=2026-10-17T23:00+00:00, prior8high=0.184600, depth_time=2026-10-17T23:00:30+00:00, book20_bid_proxy_usdt=58827, book20_ask_proxy_usdt=53903, funding_indicative=0.000048, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=31204517. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T22:59:58+00:00, last15m_closed_end=2026-10-17T23:00+00:00, prior8high=0.263400, depth_time=2026-10-17T23:00:10+00:00, book20_bid_proxy_usdt=70327, book20_ask_proxy_usdt=56608, funding_indicative=-0.001419, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.62%, turnover=6337942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T22:59:59+00:00, last15m_closed_end=2026-10-17T23:00+00:00, prior8high=0.255200, depth_time=2026-10-17T23:00:12+00:00, book20_bid_proxy_usdt=632766, book20_ask_proxy_usdt=318510, funding_indicative=0.000022, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.73%, turnover=10584970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T22:59:58+00:00, last15m_closed_end=2026-10-17T23:00+00:00, prior8high=1.098300, depth_time=2026-10-17T23:00:16+00:00, book20_bid_proxy_usdt=530008, book20_ask_proxy_usdt=535478, funding_indicative=-0.000059, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=21819977. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-17T22:59:58+00:00, last15m_closed_end=2026-10-17T23:00+00:00, prior8high=0.193800, depth_time=2026-10-17T23:00:08+00:00, book20_bid_proxy_usdt=208311, book20_ask_proxy_usdt=147642, funding_indicative=-0.000264, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.63%, turnover=14745087. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-17T22:59:58+00:00, last15m_closed_end=2026-10-17T23:00+00:00, prior8high=0.000004, depth_time=2026-10-17T23:00:36+00:00, book20_bid_proxy_usdt=44908, book20_ask_proxy_usdt=202470, funding_indicative=-0.000294, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=59226035. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-17T22:59:58+00:00, last15m_closed_end=2026-10-17T23:00+00:00, prior8high=0.004473, depth_time=2026-10-17T23:00:26+00:00, book20_bid_proxy_usdt=2099862, book20_ask_proxy_usdt=875824, funding_indicative=0.000020, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.47%, turnover=30013081. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T22:59:58+00:00, last15m_closed_end=2026-10-17T23:00+00:00, prior8high=200.290000, depth_time=2026-10-17T23:00:15+00:00, book20_bid_proxy_usdt=60106, book20_ask_proxy_usdt=92819, funding_indicative=-0.000067, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.58%, turnover=67436067. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T22:59:59+00:00, last15m_closed_end=2026-10-17T23:00+00:00, prior8high=0.065560, depth_time=2026-10-17T23:00:22+00:00, book20_bid_proxy_usdt=545392, book20_ask_proxy_usdt=347393, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=16229831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-17T22:59:58+00:00, last15m_closed_end=2026-10-17T23:00+00:00, prior8high=0.670900, depth_time=2026-10-17T23:00:20+00:00, book20_bid_proxy_usdt=208598, book20_ask_proxy_usdt=183770, funding_indicative=-0.000037, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.18%, turnover=76366012. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-17T22:59:58+00:00, last15m_closed_end=2026-10-17T23:00+00:00, prior8high=0.506800, depth_time=2026-10-17T23:00:29+00:00, book20_bid_proxy_usdt=1966240, book20_ask_proxy_usdt=1546843, funding_indicative=-0.000103, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=68583896. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T22:59:58+00:00, last15m_closed_end=2026-10-17T23:00+00:00, prior8high=1163.390000, depth_time=2026-10-17T23:00:24+00:00, book20_bid_proxy_usdt=381661, book20_ask_proxy_usdt=177596, funding_indicative=0.000031, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=1181111522. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T22:59:58+00:00, last15m_closed_end=2026-10-17T23:00+00:00, prior8high=1.915800, depth_time=2026-10-17T23:00:34+00:00, book20_bid_proxy_usdt=40497, book20_ask_proxy_usdt=54939, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.11%, turnover=8552580. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
