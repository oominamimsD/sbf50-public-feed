# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T20:00:38Z**
- feed_generated_utc: 2026-10-14T20:00:40+00:00
- source_sha256: `b135b0cad7f3a419690f9444b6758c60e62b6c191c01af510b3efe6d5b77dd54`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.178900|-10.55|76.24|-10.78|60668479|3.67|
|FET_USDT|0.195500|-6.05|-13.68|-6.28|10618127|5.11|
|BAT_USDT|0.169110|-4.23|70.54|-4.46|32501851|0.59|
|S_USDT|0.053270|-4.08|33.70|-4.31|6392575|3.75|
|NEAR_USDT|4.804000|-3.95|-4.56|-4.18|175254126|2.08|
|STRK_USDT|0.076110|-2.27|53.88|-2.50|23846136|1.31|
|INJ_USDT|7.677000|-2.05|5.03|-2.28|36221973|1.30|
|PUMPFUN_USDT|0.004752|-1.98|-24.22|-2.21|21176790|2.10|
|AAVE_USDT|154.630000|-1.35|-9.97|-1.58|23843850|0.65|
|ZEC_USDT|1153.480000|-1.22|-13.05|-1.45|1536512207|0.09|
|COPPER_USDT|6.611000|-1.18|-1.10|-1.41|6408504|1.51|
|SILVER_USDT|55.720000|-1.17|-7.07|-1.40|405772146|1.79|
|FILECOIN_USDT|1.083500|-1.17|4.17|-1.40|21339459|2.77|
|ZRO_USDT|1.903200|-1.15|-9.77|-1.38|10469445|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.630000|153.970000|154.630000|0.76|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.169110|0.167120|0.169110|1.44|N|Y/Y|Y/N|Y|N|
|BTW_USDT|2.178900|2.064400|2.179000|0.59|N|Y/Y|N/N|Y|N|
|COPPER_USDT|6.611000|6.609000|6.611000|2.63|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.195500|0.194100|0.195500|2.40|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.083500|1.082300|1.083500|2.38|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.677000|7.638000|7.677000|0.58|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.804000|4.769000|4.804000|0.93|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004752|0.004673|0.004752|0.13|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|55.720000|55.500000|55.720000|1.05|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.076110|0.075110|0.076110|0.89|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053270|0.052350|0.053270|0.57|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1153.480000|1136.570000|1153.480000|0.68|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.903200|1.880500|1.903200|0.33|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T20:00:00+00:00, last15m_closed_end=2026-10-14T20:00+00:00, prior8high=156.220000, depth_time=2026-10-14T20:00:26+00:00, book20_bid_proxy_usdt=244831, book20_ask_proxy_usdt=310182, funding_indicative=0.000052, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=23843850. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T20:00:00+00:00, last15m_closed_end=2026-10-14T20:00+00:00, prior8high=0.173100, depth_time=2026-10-14T20:00:11+00:00, book20_bid_proxy_usdt=40453, book20_ask_proxy_usdt=26174, funding_indicative=0.000010, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.23%, turnover=32501851. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T20:00:00+00:00, last15m_closed_end=2026-10-14T20:00+00:00, prior8high=2.275500, depth_time=2026-10-14T20:00:08+00:00, book20_bid_proxy_usdt=8933, book20_ask_proxy_usdt=13305, funding_indicative=0.000004, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.55%, turnover=60668479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- COPPER_USDT: quote_utc=2026-10-14T20:00:01+00:00, last15m_closed_end=2026-10-14T20:00+00:00, prior8high=6.657000, depth_time=2026-10-14T20:00:30+00:00, book20_bid_proxy_usdt=1517544, book20_ask_proxy_usdt=1392661, funding_indicative=0.000000, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.18%, turnover=6408504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T20:00:00+00:00, last15m_closed_end=2026-10-14T20:00+00:00, prior8high=0.206300, depth_time=2026-10-14T20:00:10+00:00, book20_bid_proxy_usdt=950434, book20_ask_proxy_usdt=1105918, funding_indicative=0.000057, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-6.05%, turnover=10618127. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-14T20:00:00+00:00, last15m_closed_end=2026-10-14T20:00+00:00, prior8high=1.093500, depth_time=2026-10-14T20:00:34+00:00, book20_bid_proxy_usdt=306746, book20_ask_proxy_usdt=486307, funding_indicative=-0.000002, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=21339459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-14T20:00:00+00:00, last15m_closed_end=2026-10-14T20:00+00:00, prior8high=7.795000, depth_time=2026-10-14T20:00:21+00:00, book20_bid_proxy_usdt=152734, book20_ask_proxy_usdt=196807, funding_indicative=0.000036, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=36221973. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-14T20:00:00+00:00, last15m_closed_end=2026-10-14T20:00+00:00, prior8high=4.853000, depth_time=2026-10-14T20:00:17+00:00, book20_bid_proxy_usdt=635908, book20_ask_proxy_usdt=2172761, funding_indicative=0.000100, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.95%, turnover=175254126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-14T20:00:00+00:00, last15m_closed_end=2026-10-14T20:00+00:00, prior8high=0.004787, depth_time=2026-10-14T20:00:23+00:00, book20_bid_proxy_usdt=662292, book20_ask_proxy_usdt=1355724, funding_indicative=0.000050, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.98%, turnover=21176790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T20:00:00+00:00, last15m_closed_end=2026-10-14T20:00+00:00, prior8high=55.910000, depth_time=2026-10-14T20:00:32+00:00, book20_bid_proxy_usdt=50130294, book20_ask_proxy_usdt=40733206, funding_indicative=0.000116, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=405772146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T20:00:00+00:00, last15m_closed_end=2026-10-14T20:00+00:00, prior8high=0.076310, depth_time=2026-10-14T20:00:19+00:00, book20_bid_proxy_usdt=308130, book20_ask_proxy_usdt=323439, funding_indicative=0.000032, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=23846136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T20:00:00+00:00, last15m_closed_end=2026-10-14T20:00+00:00, prior8high=0.053070, depth_time=2026-10-14T20:00:15+00:00, book20_bid_proxy_usdt=94000, book20_ask_proxy_usdt=177331, funding_indicative=-0.000087, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.08%, turnover=6392575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-14T20:00:00+00:00, last15m_closed_end=2026-10-14T20:00+00:00, prior8high=1162.400000, depth_time=2026-10-14T20:00:28+00:00, book20_bid_proxy_usdt=210340, book20_ask_proxy_usdt=237501, funding_indicative=0.000085, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.22%, turnover=1536512207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-14T20:00:01+00:00, last15m_closed_end=2026-10-14T20:00+00:00, prior8high=1.931900, depth_time=2026-10-14T20:00:37+00:00, book20_bid_proxy_usdt=205737, book20_ask_proxy_usdt=30206, funding_indicative=0.000007, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.15%, turnover=10469445. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
