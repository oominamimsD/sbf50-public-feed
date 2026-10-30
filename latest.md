# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T12:45:43Z**
- feed_generated_utc: 2026-10-30T12:45:46+00:00
- source_sha256: `45312e870e46777a1443a34ebe77b680cb0892a9b20c4176b623467e9f95e5ef`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T12:45+00:00, close=77291.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T12:00+00:00, close=77345.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T12:00+00:00, close=77345.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.277000|-22.04|-28.65|-16.61|9855034|3.91|
|PYTH_USDT|0.060590|-17.21|-18.32|-11.78|5320271|1.65|
|TIA_USDT|0.459400|-16.35|-19.17|-10.92|20562811|2.18|
|LIT_USDT|2.752800|-15.47|-23.83|-10.04|17745887|0.36|
|CRV_USDT|0.284500|-15.32|-22.54|-9.89|9452681|3.52|
|FARTCOIN_USDT|0.118070|-12.15|-17.34|-6.72|15661623|0.85|
|LDO_USDT|0.334300|-11.65|-12.60|-6.22|6479514|2.99|
|APT_USDT|0.624700|-11.17|-19.10|-5.74|11644727|1.60|
|INJ_USDT|7.233000|-11.05|-8.81|-5.62|31739744|1.38|
|ETHFI_USDT|0.604600|-11.02|-8.71|-5.59|5888066|1.65|
|PUMPFUN_USDT|0.004056|-10.36|-13.31|-4.93|30931983|2.46|
|TRUMPOFFICIAL_USDT|1.552000|-10.18|-11.00|-4.75|10864932|6.45|
|TAO_USDT|232.570000|-10.12|-9.73|-4.69|87700345|1.29|
|JUP_USDT|0.254100|-9.82|-18.03|-4.39|6914328|3.94|
|ONDO_USDT|0.389700|-9.32|-9.58|-3.89|33998969|2.56|
|SEI_USDT|0.048600|-9.05|-16.30|-3.62|6971788|2.06|
|AVAX_USDT|8.229000|-8.60|-10.22|-3.17|37775408|1.22|
|ZEC_USDT|1243.620000|-8.38|0.75|-2.95|2218271898|0.08|
|BNB_USDT|699.600000|-6.98|-4.33|-1.55|56468627|1.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.624700|0.620200|0.624700|1.46|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.277000|1.248100|1.278200|2.05|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.284500|0.283100|0.284400|0.49|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.604600|0.604300|0.604600|1.54|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118070|0.117170|0.118070|0.50|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.233000|7.131000|7.233000|1.04|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.254100|0.254000|0.254100|0.08|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.334300|0.329900|0.334300|2.96|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.752800|2.768600|2.752800|1.23|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.389700|0.388700|0.389700|1.02|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004056|0.004052|0.004056|2.35|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.060590|0.060360|0.060590|0.98|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|232.570000|231.510000|232.570000|0.83|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.459400|0.458700|0.459400|0.72|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.552000|1.548000|1.552000|0.23|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=0.632500, depth_time=2026-10-30T12:45:24+00:00, book20_bid_proxy_usdt=127965, book20_ask_proxy_usdt=122964, funding_indicative=0.000097, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.17%, turnover=11644727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=1.549900, depth_time=2026-10-30T12:45:08+00:00, book20_bid_proxy_usdt=8146, book20_ask_proxy_usdt=10453, funding_indicative=0.000012, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.04%, turnover=9855034. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=0.288300, depth_time=2026-10-30T12:45:17+00:00, book20_bid_proxy_usdt=457286, book20_ask_proxy_usdt=496325, funding_indicative=-0.000208, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.32%, turnover=9452681. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=0.613800, depth_time=2026-10-30T12:45:29+00:00, book20_bid_proxy_usdt=213235, book20_ask_proxy_usdt=172321, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.02%, turnover=5888066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=0.119010, depth_time=2026-10-30T12:45:19+00:00, book20_bid_proxy_usdt=49587, book20_ask_proxy_usdt=42021, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.15%, turnover=15661623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=7.269000, depth_time=2026-10-30T12:45:27+00:00, book20_bid_proxy_usdt=260592, book20_ask_proxy_usdt=248701, funding_indicative=0.000068, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.05%, turnover=31739744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=0.257100, depth_time=2026-10-30T12:45:39+00:00, book20_bid_proxy_usdt=390464, book20_ask_proxy_usdt=359271, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.82%, turnover=6914328. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=0.336300, depth_time=2026-10-30T12:45:20+00:00, book20_bid_proxy_usdt=390668, book20_ask_proxy_usdt=260085, funding_indicative=0.000068, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.65%, turnover=6479514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=2.848700, depth_time=2026-10-30T12:45:15+00:00, book20_bid_proxy_usdt=38289, book20_ask_proxy_usdt=28099, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-15.47%, turnover=17745887. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=0.394100, depth_time=2026-10-30T12:45:41+00:00, book20_bid_proxy_usdt=1457188, book20_ask_proxy_usdt=1700470, funding_indicative=0.000036, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.32%, turnover=33998969. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=0.004139, depth_time=2026-10-30T12:45:32+00:00, book20_bid_proxy_usdt=1617429, book20_ask_proxy_usdt=1103980, funding_indicative=0.000017, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.36%, turnover=30931983. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=0.061880, depth_time=2026-10-30T12:45:08+00:00, book20_bid_proxy_usdt=183681, book20_ask_proxy_usdt=231566, funding_indicative=-0.000118, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-17.21%, turnover=5320271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=235.330000, depth_time=2026-10-30T12:45:36+00:00, book20_bid_proxy_usdt=87021, book20_ask_proxy_usdt=39810, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.12%, turnover=87700345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=0.470200, depth_time=2026-10-30T12:45:12+00:00, book20_bid_proxy_usdt=109572, book20_ask_proxy_usdt=333354, funding_indicative=0.000040, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-16.35%, turnover=20562811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T12:45:01+00:00, last15m_closed_end=2026-10-30T12:45+00:00, prior8high=1.573000, depth_time=2026-10-30T12:45:33+00:00, book20_bid_proxy_usdt=1358390, book20_ask_proxy_usdt=1571082, funding_indicative=0.000014, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.18%, turnover=10864932. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
