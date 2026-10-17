# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T22:45:38Z**
- feed_generated_utc: 2026-10-17T22:45:40+00:00
- source_sha256: `fcc8602074138edfaf2ad36e518270ddc4a814c0ba2c94087eef2140f3a0cf81`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T22:45+00:00, close=81384.4, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T22:00+00:00, close=81099.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.167400|-9.61|68.92|-9.68|14685090|5.97|
|DNA_USDT|0.255300|-6.17|UNKNOWN|-6.24|6328708|7.84|
|EIGEN_USDT|0.249200|-2.77|5.77|-2.84|10572893|4.01|
|FILECOIN_USDT|1.059200|-2.59|-6.08|-2.66|21802276|0.94|
|STRK_USDT|0.064700|-2.19|-30.75|-2.26|16154640|1.54|
|TIA_USDT|0.644200|-2.09|25.57|-2.16|76174090|3.11|
|QNT_USDT|196.480000|-1.96|-19.84|-2.03|66631234|0.51|
|PUMPFUN_USDT|0.004345|-1.51|-24.10|-1.58|29908514|2.30|
|ARB_USDT|0.181340|-1.40|-2.85|-1.47|31062981|0.55|
|ZEC_USDT|1125.800000|-1.36|-8.60|-1.43|1169328079|0.09|
|WLD_USDT|0.488900|-1.35|-12.54|-1.42|68349815|2.04|
|PEPE_USDT|0.000004|-0.98|-4.55|-1.05|58966809|0.26|
|ZRO_USDT|1.866700|-0.98|-7.61|-1.05|8473933|1.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.181340|0.176600|0.181340|1.47|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.255300|0.245300|0.255300|0.31|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.249200|0.241300|0.249200|0.54|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.059200|1.038400|1.059200|0.19|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.167400|0.166700|0.167500|1.21|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.65|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004345|0.004262|0.004345|2.09|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|196.480000|190.470000|196.490000|2.04|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.064700|0.063090|0.064800|0.94|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.644200|0.634700|0.644200|0.96|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.488900|0.477800|0.489000|0.75|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1125.800000|1098.000000|1125.940000|0.71|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.866700|1.843200|1.866700|2.08|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T22:44:59+00:00, last15m_closed_end=2026-10-17T22:45+00:00, prior8high=0.184600, depth_time=2026-10-17T22:45:24+00:00, book20_bid_proxy_usdt=47618, book20_ask_proxy_usdt=97223, funding_indicative=0.000046, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=31062981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T22:44:59+00:00, last15m_closed_end=2026-10-17T22:45+00:00, prior8high=0.263400, depth_time=2026-10-17T22:45:10+00:00, book20_bid_proxy_usdt=70982, book20_ask_proxy_usdt=59896, funding_indicative=-0.001388, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.17%, turnover=6328708. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T22:44:59+00:00, last15m_closed_end=2026-10-17T22:45+00:00, prior8high=0.256100, depth_time=2026-10-17T22:45:12+00:00, book20_bid_proxy_usdt=620490, book20_ask_proxy_usdt=382345, funding_indicative=0.000021, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=10572893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T22:44:59+00:00, last15m_closed_end=2026-10-17T22:45+00:00, prior8high=1.098300, depth_time=2026-10-17T22:45:15+00:00, book20_bid_proxy_usdt=302950, book20_ask_proxy_usdt=205547, funding_indicative=-0.000071, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.59%, turnover=21802276. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-17T22:44:59+00:00, last15m_closed_end=2026-10-17T22:45+00:00, prior8high=0.193800, depth_time=2026-10-17T22:45:07+00:00, book20_bid_proxy_usdt=171466, book20_ask_proxy_usdt=137165, funding_indicative=-0.000318, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.61%, turnover=14685090. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-17T22:44:59+00:00, last15m_closed_end=2026-10-17T22:45+00:00, prior8high=0.000004, depth_time=2026-10-17T22:45:35+00:00, book20_bid_proxy_usdt=73194, book20_ask_proxy_usdt=81126, funding_indicative=-0.000302, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=58966809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-17T22:44:59+00:00, last15m_closed_end=2026-10-17T22:45+00:00, prior8high=0.004487, depth_time=2026-10-17T22:45:25+00:00, book20_bid_proxy_usdt=1433706, book20_ask_proxy_usdt=1473791, funding_indicative=0.000014, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=29908514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T22:44:59+00:00, last15m_closed_end=2026-10-17T22:45+00:00, prior8high=200.290000, depth_time=2026-10-17T22:45:22+00:00, book20_bid_proxy_usdt=56203, book20_ask_proxy_usdt=64895, funding_indicative=-0.000070, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=66631234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T22:44:59+00:00, last15m_closed_end=2026-10-17T22:45+00:00, prior8high=0.065560, depth_time=2026-10-17T22:45:17+00:00, book20_bid_proxy_usdt=263908, book20_ask_proxy_usdt=350554, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.19%, turnover=16154640. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-17T22:44:59+00:00, last15m_closed_end=2026-10-17T22:45+00:00, prior8high=0.670900, depth_time=2026-10-17T22:45:20+00:00, book20_bid_proxy_usdt=177390, book20_ask_proxy_usdt=186718, funding_indicative=-0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=76174090. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-17T22:44:59+00:00, last15m_closed_end=2026-10-17T22:45+00:00, prior8high=0.506800, depth_time=2026-10-17T22:45:32+00:00, book20_bid_proxy_usdt=1449690, book20_ask_proxy_usdt=1524346, funding_indicative=-0.000106, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=68349815. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T22:44:59+00:00, last15m_closed_end=2026-10-17T22:45+00:00, prior8high=1163.390000, depth_time=2026-10-17T22:45:29+00:00, book20_bid_proxy_usdt=311550, book20_ask_proxy_usdt=152877, funding_indicative=0.000032, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=1169328079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T22:44:59+00:00, last15m_closed_end=2026-10-17T22:45+00:00, prior8high=1.918400, depth_time=2026-10-17T22:45:37+00:00, book20_bid_proxy_usdt=69348, book20_ask_proxy_usdt=44976, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.98%, turnover=8473933. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
