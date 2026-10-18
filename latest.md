# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T01:15:30Z**
- feed_generated_utc: 2026-10-18T01:15:31+00:00
- source_sha256: `8171a840ce54eb328d3669cf39fa7b16a22b6af6b6f095c68ffc55f51f011fcb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T01:15+00:00, close=81530.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T01:00+00:00, close=81513.3, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.159600|-13.82|61.04|-14.08|14799002|6.26|
|SAND_USDT|0.058190|-7.69|-13.52|-7.95|27312193|1.72|
|STRK_USDT|0.063890|-3.41|-31.61|-3.67|15738352|1.57|
|FILECOIN_USDT|1.063100|-2.23|-5.73|-2.49|20038316|0.94|
|DNA_USDT|0.266500|-2.05|UNKNOWN|-2.31|5325827|3.75|
|QNT_USDT|196.350000|-2.02|-19.89|-2.28|67497975|0.51|
|TIA_USDT|0.645500|-1.89|25.82|-2.15|72379058|1.55|
|EIGEN_USDT|0.251900|-1.71|6.91|-1.97|10753965|3.97|
|PUMPFUN_USDT|0.004355|-1.29|-23.93|-1.55|23519069|2.30|
|ARB_USDT|0.182070|-1.00|-2.46|-1.26|31360862|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.182070|0.179900|0.182070|2.16|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.266500|0.255400|0.266700|0.26|N|N/Y|?|Y|N|
|EIGEN_USDT|0.251900|0.247800|0.251900|0.30|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|1.063100|1.056500|1.063100|3.03|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.159600|0.157300|0.159600|0.82|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004355|0.004297|0.004354|0.82|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|196.350000|193.740000|196.350000|1.72|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.058190|0.057980|0.058190|0.71|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.063890|0.063700|0.063870|0.52|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.645500|0.639600|0.646000|0.94|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-18T01:15:02+00:00, last15m_closed_end=2026-10-18T01:15+00:00, prior8high=0.181710, depth_time=2026-10-18T01:15:29+00:00, book20_bid_proxy_usdt=45392, book20_ask_proxy_usdt=69422, funding_indicative=0.000034, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=31360862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-18T01:15:02+00:00, last15m_closed_end=2026-10-18T01:15+00:00, prior8high=0.269200, depth_time=2026-10-18T01:15:16+00:00, book20_bid_proxy_usdt=83901, book20_ask_proxy_usdt=86000, funding_indicative=-0.002141, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.05%, turnover=5325827. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T01:15:02+00:00, last15m_closed_end=2026-10-18T01:15+00:00, prior8high=0.252000, depth_time=2026-10-18T01:15:23+00:00, book20_bid_proxy_usdt=423128, book20_ask_proxy_usdt=311287, funding_indicative=-0.000006, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=10753965. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T01:15:02+00:00, last15m_closed_end=2026-10-18T01:15+00:00, prior8high=1.066900, depth_time=2026-10-18T01:15:15+00:00, book20_bid_proxy_usdt=542363, book20_ask_proxy_usdt=833292, funding_indicative=-0.000028, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=20038316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T01:15:02+00:00, last15m_closed_end=2026-10-18T01:15+00:00, prior8high=0.174200, depth_time=2026-10-18T01:15:07+00:00, book20_bid_proxy_usdt=386784, book20_ask_proxy_usdt=188632, funding_indicative=-0.000071, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.82%, turnover=14799002. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T01:15:02+00:00, last15m_closed_end=2026-10-18T01:15+00:00, prior8high=0.004355, depth_time=2026-10-18T01:15:27+00:00, book20_bid_proxy_usdt=1432848, book20_ask_proxy_usdt=1819084, funding_indicative=0.000036, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.29%, turnover=23519069. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T01:15:02+00:00, last15m_closed_end=2026-10-18T01:15+00:00, prior8high=195.730000, depth_time=2026-10-18T01:15:20+00:00, book20_bid_proxy_usdt=74780, book20_ask_proxy_usdt=98032, funding_indicative=-0.000062, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.02%, turnover=67497975. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T01:15:02+00:00, last15m_closed_end=2026-10-18T01:15+00:00, prior8high=0.060240, depth_time=2026-10-18T01:15:09+00:00, book20_bid_proxy_usdt=666795, book20_ask_proxy_usdt=601764, funding_indicative=-0.002865, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.69%, turnover=27312193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T01:15:02+00:00, last15m_closed_end=2026-10-18T01:15+00:00, prior8high=0.064870, depth_time=2026-10-18T01:15:12+00:00, book20_bid_proxy_usdt=303039, book20_ask_proxy_usdt=371543, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.41%, turnover=15738352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T01:15:02+00:00, last15m_closed_end=2026-10-18T01:15+00:00, prior8high=0.651200, depth_time=2026-10-18T01:15:21+00:00, book20_bid_proxy_usdt=142367, book20_ask_proxy_usdt=198650, funding_indicative=0.000009, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.89%, turnover=72379058. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
