# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T13:30:47Z**
- feed_generated_utc: 2026-10-27T13:30:51+00:00
- source_sha256: `f2d9cd1a716a6ea482799d2fe5d713d6ac16c148c5a05eb36eeab832314194d8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1191; contracts: 1183; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T13:30+00:00, close=80128.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T13:00+00:00, close=80337, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.024860|-9.86|102.44|-9.53|7015496|4.02|
|QNT_USDT|198.750000|-5.48|1.55|-5.15|105713371|0.50|
|AAVE_USDT|131.480000|-3.83|-10.69|-3.50|28438838|0.76|
|DOT_USDT|0.985700|-3.60|-14.04|-3.27|11010991|1.01|
|FILECOIN_USDT|0.888500|-3.49|-12.20|-3.16|6702858|1.13|
|WLD_USDT|0.430700|-3.21|-14.93|-2.88|68816292|2.32|
|PUMPFUN_USDT|0.004191|-3.16|-5.94|-2.83|19805386|2.39|
|TIA_USDT|0.521200|-2.70|-14.34|-2.37|17620016|3.84|
|AVAX_USDT|8.762000|-2.61|-8.36|-2.28|22608155|1.14|
|ICP_USDT|2.576000|-2.05|-9.70|-1.72|5281359|3.88|
|ONDO_USDT|0.411000|-1.86|-4.99|-1.53|22409473|2.43|
|TAO_USDT|248.880000|-1.82|-7.23|-1.49|52093845|0.40|
|HBAR_USDT|0.075950|-1.82|-7.23|-1.49|10420014|1.32|
|LINK_USDT|11.320000|-1.80|-5.21|-1.47|133718478|0.88|
|ARB_USDT|0.167000|-1.75|-14.63|-1.42|17725591|0.60|
|SOL_USDT|100.380000|-1.43|-3.56|-1.10|717165110|1.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.480000|130.520000|131.480000|0.39|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167000|0.166210|0.167070|0.55|N|N/Y|Y/Y|Y|N|
|AVAX_USDT|8.762000|8.732000|8.762000|11.47|N|N/Y|Y/Y|Y|N|
|DOT_USDT|0.985700|0.982200|0.985700|0.52|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.888500|0.887200|0.888500|0.87|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.075950|0.075590|0.075950|1.58|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.576000|2.565000|2.576000|1.88|N|N/Y|Y/Y|Y|N|
|IRYS_USDT|0.024860|0.024590|0.024860|0.75|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.320000|11.290000|11.318000|0.88|N|N/Y|Y/Y|Y|N|
|ONDO_USDT|0.411000|0.406400|0.411000|1.14|N|N/N|Y/Y|Y|N|
|PUMPFUN_USDT|0.004191|0.004133|0.004191|0.82|N|N/Y|Y/Y|Y|N|
|QNT_USDT|198.750000|198.190000|198.750000|1.16|N|Y/Y|N/N|Y|N|
|TAO_USDT|248.880000|247.220000|248.880000|0.86|N|N/Y|Y/Y|Y|N|
|TIA_USDT|0.521200|0.521200|0.521400|2.73|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.430700|0.428900|0.430700|2.20|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=133.100000, depth_time=2026-10-27T13:30:14+00:00, book20_bid_proxy_usdt=337035, book20_ask_proxy_usdt=355914, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.83%, turnover=28438838. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=0.169600, depth_time=2026-10-27T13:30:46+00:00, book20_bid_proxy_usdt=101052, book20_ask_proxy_usdt=79372, funding_indicative=0.000027, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=17725591. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=8.864000, depth_time=2026-10-27T13:30:30+00:00, book20_bid_proxy_usdt=1062122, book20_ask_proxy_usdt=823840, funding_indicative=0.000054, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=22608155. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=0.996900, depth_time=2026-10-27T13:30:17+00:00, book20_bid_proxy_usdt=262664, book20_ask_proxy_usdt=268046, funding_indicative=-0.000183, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.60%, turnover=11010991. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=0.902000, depth_time=2026-10-27T13:30:16+00:00, book20_bid_proxy_usdt=1012437, book20_ask_proxy_usdt=1379711, funding_indicative=0.000064, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.49%, turnover=6702858. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=0.076600, depth_time=2026-10-27T13:30:41+00:00, book20_bid_proxy_usdt=971013, book20_ask_proxy_usdt=953230, funding_indicative=0.000083, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=10420014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=2.608000, depth_time=2026-10-27T13:30:33+00:00, book20_bid_proxy_usdt=1031840, book20_ask_proxy_usdt=963549, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=5281359. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=0.025210, depth_time=2026-10-27T13:30:09+00:00, book20_bid_proxy_usdt=121728, book20_ask_proxy_usdt=130868, funding_indicative=-0.000239, next_funding_utc=2026-10-27T14:00:00+00:00, funding_cycle_h=1, 24h_change=-9.86%, turnover=7015496. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=11.453000, depth_time=2026-10-27T13:30:43+00:00, book20_bid_proxy_usdt=446126, book20_ask_proxy_usdt=543722, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=133718478. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=0.415900, depth_time=2026-10-27T13:30:35+00:00, book20_bid_proxy_usdt=2677888, book20_ask_proxy_usdt=2530752, funding_indicative=-0.000003, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=22409473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=0.004256, depth_time=2026-10-27T13:30:25+00:00, book20_bid_proxy_usdt=2745877, book20_ask_proxy_usdt=1910968, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.16%, turnover=19805386. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=204.380000, depth_time=2026-10-27T13:30:09+00:00, book20_bid_proxy_usdt=45715, book20_ask_proxy_usdt=39746, funding_indicative=-0.000236, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.48%, turnover=105713371. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=251.610000, depth_time=2026-10-27T13:30:38+00:00, book20_bid_proxy_usdt=90570, book20_ask_proxy_usdt=115168, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=52093845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=0.531400, depth_time=2026-10-27T13:30:28+00:00, book20_bid_proxy_usdt=337869, book20_ask_proxy_usdt=383530, funding_indicative=0.000023, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.70%, turnover=17620016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T13:30:01+00:00, last15m_closed_end=2026-10-27T13:30+00:00, prior8high=0.438400, depth_time=2026-10-27T13:30:23+00:00, book20_bid_proxy_usdt=3562377, book20_ask_proxy_usdt=3379156, funding_indicative=-0.000049, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=68816292. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
