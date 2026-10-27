# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T02:00:39Z**
- feed_generated_utc: 2026-10-27T02:00:43+00:00
- source_sha256: `73f484ac9facd48e8c61e65a201397dc2e1a21a93e6c8b785f225f0c5a39cab1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T02:00+00:00, close=80041.9, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T02:00+00:00, close=80041.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.613200|-5.98|-15.18|-5.56|5192002|0.62|
|QNT_USDT|202.010000|-5.27|3.22|-4.85|120098321|0.99|
|BR_USDT|0.492700|-4.70|-20.01|-4.28|8229889|4.06|
|NEAR_USDT|4.471000|-3.95|-8.82|-3.53|103409941|2.24|
|DOT_USDT|0.999100|-3.11|-12.87|-2.69|10627728|1.00|
|ARB_USDT|0.167600|-2.50|-14.32|-2.08|19878077|0.60|
|AAVE_USDT|134.630000|-2.35|-8.55|-1.93|23599588|0.74|
|FILECOIN_USDT|0.904700|-2.35|-10.60|-1.93|6428035|1.11|
|FET_USDT|0.173900|-2.13|-7.98|-1.71|6061220|5.75|
|LINK_USDT|11.328000|-2.04|-5.14|-1.62|103762830|0.88|
|TAO_USDT|250.050000|-1.88|-6.80|-1.46|46029459|1.20|
|WLD_USDT|0.439900|-1.85|-13.11|-1.43|69061690|2.27|
|PEPE_USDT|0.000004|-1.53|4.57|-1.11|76606504|0.23|
|SOL_USDT|100.610000|-1.44|-3.34|-1.02|703343820|0.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|134.630000|134.550000|134.630000|1.70|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167600|0.167160|0.167600|0.59|N|Y/Y|Y/Y|Y|N|
|BR_USDT|0.492700|0.487500|0.492700|1.10|N|N/N|N/N|Y|N|
|DOT_USDT|0.999100|0.996300|0.999100|0.97|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.173900|0.173800|0.173900|1.45|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.904700|0.903600|0.904700|0.57|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.328000|11.321000|11.328000|1.39|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.471000|4.446000|4.471000|0.60|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.09|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|202.010000|200.280000|202.010000|0.80|N|Y/N|N/N|Y|N|
|SOL_USDT|100.610000|100.470000|100.610000|0.95|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|250.050000|249.270000|250.050000|0.95|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.439900|0.439400|0.439900|0.41|N|Y/N|Y/Y|Y|N|
|ZRO_USDT|1.613200|1.608300|1.613200|0.16|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T02:00:00+00:00, last15m_closed_end=2026-10-27T02:00+00:00, prior8high=136.180000, depth_time=2026-10-27T02:00:22+00:00, book20_bid_proxy_usdt=1199111, book20_ask_proxy_usdt=400809, funding_indicative=0.000086, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.35%, turnover=23599588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T02:00:00+00:00, last15m_closed_end=2026-10-27T02:00+00:00, prior8high=0.169780, depth_time=2026-10-27T02:00:19+00:00, book20_bid_proxy_usdt=68822, book20_ask_proxy_usdt=71644, funding_indicative=-0.000030, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=19878077. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-27T02:00:00+00:00, last15m_closed_end=2026-10-27T02:00+00:00, prior8high=0.508300, depth_time=2026-10-27T02:00:12+00:00, book20_bid_proxy_usdt=29877, book20_ask_proxy_usdt=39387, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.70%, turnover=8229889. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T02:00:00+00:00, last15m_closed_end=2026-10-27T02:00+00:00, prior8high=1.013800, depth_time=2026-10-27T02:00:17+00:00, book20_bid_proxy_usdt=293880, book20_ask_proxy_usdt=428834, funding_indicative=-0.000077, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=10627728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T02:00:00+00:00, last15m_closed_end=2026-10-27T02:00+00:00, prior8high=0.176400, depth_time=2026-10-27T02:00:23+00:00, book20_bid_proxy_usdt=1821026, book20_ask_proxy_usdt=981028, funding_indicative=0.000100, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=6061220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T02:00:00+00:00, last15m_closed_end=2026-10-27T02:00+00:00, prior8high=0.916600, depth_time=2026-10-27T02:00:20+00:00, book20_bid_proxy_usdt=1256455, book20_ask_proxy_usdt=1145500, funding_indicative=0.000069, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.35%, turnover=6428035. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T02:00:00+00:00, last15m_closed_end=2026-10-27T02:00+00:00, prior8high=11.421000, depth_time=2026-10-27T02:00:27+00:00, book20_bid_proxy_usdt=466401, book20_ask_proxy_usdt=531859, funding_indicative=0.000090, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=103762830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T02:00:00+00:00, last15m_closed_end=2026-10-27T02:00+00:00, prior8high=4.536000, depth_time=2026-10-27T02:00:14+00:00, book20_bid_proxy_usdt=3653669, book20_ask_proxy_usdt=4308936, funding_indicative=0.000058, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.95%, turnover=103409941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-27T02:00:00+00:00, last15m_closed_end=2026-10-27T02:00+00:00, prior8high=0.000004, depth_time=2026-10-27T02:00:36+00:00, book20_bid_proxy_usdt=65779, book20_ask_proxy_usdt=63614, funding_indicative=0.000026, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=76606504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T02:00:00+00:00, last15m_closed_end=2026-10-27T02:00+00:00, prior8high=204.430000, depth_time=2026-10-27T02:00:10+00:00, book20_bid_proxy_usdt=51062, book20_ask_proxy_usdt=81242, funding_indicative=-0.000083, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.27%, turnover=120098321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T02:00:00+00:00, last15m_closed_end=2026-10-27T02:00+00:00, prior8high=101.110000, depth_time=2026-10-27T02:00:38+00:00, book20_bid_proxy_usdt=16066015, book20_ask_proxy_usdt=20232192, funding_indicative=0.000100, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=703343820. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T02:00:00+00:00, last15m_closed_end=2026-10-27T02:00+00:00, prior8high=252.300000, depth_time=2026-10-27T02:00:31+00:00, book20_bid_proxy_usdt=177444, book20_ask_proxy_usdt=116834, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.88%, turnover=46029459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T02:00:00+00:00, last15m_closed_end=2026-10-27T02:00+00:00, prior8high=0.446900, depth_time=2026-10-27T02:00:33+00:00, book20_bid_proxy_usdt=2710232, book20_ask_proxy_usdt=3539555, funding_indicative=-0.000167, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=69061690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T02:00:00+00:00, last15m_closed_end=2026-10-27T02:00+00:00, prior8high=1.647700, depth_time=2026-10-27T02:00:07+00:00, book20_bid_proxy_usdt=33961, book20_ask_proxy_usdt=24452, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.98%, turnover=5192002. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
