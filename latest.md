# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T11:00:44Z**
- feed_generated_utc: 2026-11-03T11:00:46+00:00
- source_sha256: `a4d4af58c879b99a5b022e355788d6f2661c4f47ccd8dff6f9ac290b8500781d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T11:00+00:00, close=77103.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T11:00+00:00, close=77103.4, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-03T08:00+00:00, close=76799.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004506|-19.79|-85.36|-19.31|12759330|4.44|
|BTW_USDT|0.906400|-16.87|-24.19|-16.39|10029513|2.21|
|XPL_USDT|0.063460|-10.02|-14.57|-9.54|11248584|3.15|
|ZEC_USDT|1161.560000|-7.37|-6.90|-6.89|1753427691|0.09|
|NEAR_USDT|3.831000|-5.96|-16.22|-5.48|76438885|2.61|
|TIA_USDT|0.438100|-4.53|-18.21|-4.05|12471907|2.28|
|ENA_USDT|0.169970|-4.27|-19.20|-3.79|67250939|0.59|
|SILVER_USDT|49.070000|-4.10|-9.51|-3.62|429544281|2.04|
|DASH_USDT|45.800000|-3.96|-12.29|-3.48|8816831|2.18|
|XLM_USDT|0.162110|-3.50|-4.41|-3.02|33788093|0.62|
|OP_USDT|0.109520|-3.37|-1.95|-2.89|10227755|0.91|
|WLD_USDT|0.371400|-3.28|-16.53|-2.80|49133017|2.69|
|FARTCOIN_USDT|0.116400|-3.28|-9.29|-2.80|9684114|0.86|
|TRUMPOFFICIAL_USDT|1.593000|-2.56|-5.68|-2.08|9282657|6.28|
|TAO_USDT|223.600000|-2.51|-11.79|-2.03|39687440|1.34|
|ONDO_USDT|0.384100|-2.33|-8.28|-1.85|16493584|2.60|
|APT_USDT|0.615600|-2.20|-12.30|-1.72|5156397|1.62|
|SOL_USDT|92.390000|-2.03|-9.27|-1.55|658477477|1.08|
|LINK_USDT|11.112000|-1.98|-3.60|-1.50|168568521|2.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004506|0.004432|0.004506|1.02|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.906400|0.887500|0.906700|3.46|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|45.800000|45.440000|45.800000|2.52|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.169970|0.167890|0.169930|1.15|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.116400|0.114720|0.116400|1.57|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.831000|3.756000|3.831000|1.81|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.109520|0.107300|0.109520|0.68|N|N/Y|Y/Y|Y|N|
|SILVER_USDT|49.070000|48.730000|49.070000|0.37|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|223.600000|220.110000|223.600000|0.74|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.438100|0.436200|0.438100|0.65|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.593000|1.565000|1.593000|0.83|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.371400|0.364200|0.371400|0.47|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.162110|0.160890|0.162110|0.96|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.063460|0.063400|0.063460|0.35|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1161.560000|1125.680000|1161.710000|1.02|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=0.004638, depth_time=2026-11-03T11:00:08+00:00, book20_bid_proxy_usdt=44341, book20_ask_proxy_usdt=46391, funding_indicative=-0.001594, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.79%, turnover=12759330. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=0.930000, depth_time=2026-11-03T11:00:11+00:00, book20_bid_proxy_usdt=30233, book20_ask_proxy_usdt=33306, funding_indicative=-0.000331, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-16.87%, turnover=10029513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=45.880000, depth_time=2026-11-03T11:00:28+00:00, book20_bid_proxy_usdt=1025524, book20_ask_proxy_usdt=633558, funding_indicative=0.000083, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.96%, turnover=8816831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=0.170450, depth_time=2026-11-03T11:00:23+00:00, book20_bid_proxy_usdt=334619, book20_ask_proxy_usdt=292682, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.27%, turnover=67250939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=0.116560, depth_time=2026-11-03T11:00:38+00:00, book20_bid_proxy_usdt=89100, book20_ask_proxy_usdt=85668, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=9684114. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=3.849000, depth_time=2026-11-03T11:00:18+00:00, book20_bid_proxy_usdt=5942522, book20_ask_proxy_usdt=4018741, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.96%, turnover=76438885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=0.109470, depth_time=2026-11-03T11:00:33+00:00, book20_bid_proxy_usdt=194489, book20_ask_proxy_usdt=157357, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.37%, turnover=10227755. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=49.150000, depth_time=2026-11-03T11:00:23+00:00, book20_bid_proxy_usdt=59493245, book20_ask_proxy_usdt=51594575, funding_indicative=0.000042, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.10%, turnover=429544281. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=223.950000, depth_time=2026-11-03T11:00:42+00:00, book20_bid_proxy_usdt=258622, book20_ask_proxy_usdt=271476, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.51%, turnover=39687440. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=0.440000, depth_time=2026-11-03T11:00:21+00:00, book20_bid_proxy_usdt=390022, book20_ask_proxy_usdt=391900, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.53%, turnover=12471907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=1.601000, depth_time=2026-11-03T11:00:41+00:00, book20_bid_proxy_usdt=2278336, book20_ask_proxy_usdt=2184893, funding_indicative=-0.000064, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=9282657. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=0.372900, depth_time=2026-11-03T11:00:34+00:00, book20_bid_proxy_usdt=4943323, book20_ask_proxy_usdt=4378644, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.28%, turnover=49133017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=0.162210, depth_time=2026-11-03T11:00:28+00:00, book20_bid_proxy_usdt=148129, book20_ask_proxy_usdt=221861, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.50%, turnover=33788093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=0.064320, depth_time=2026-11-03T11:00:13+00:00, book20_bid_proxy_usdt=427656, book20_ask_proxy_usdt=438994, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.02%, turnover=11248584. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-03T11:00:01+00:00, last15m_closed_end=2026-11-03T11:00+00:00, prior8high=1162.790000, depth_time=2026-11-03T11:00:16+00:00, book20_bid_proxy_usdt=385097, book20_ask_proxy_usdt=154821, funding_indicative=0.000041, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.37%, turnover=1753427691. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
