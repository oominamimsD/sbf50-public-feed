# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T07:30:45Z**
- feed_generated_utc: 2026-10-13T07:30:48+00:00
- source_sha256: `5c66d05d7ecb9eae242d8668579affc881ebd53b144feaa18f73d392e52e6f20`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T07:30+00:00, close=83698, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T07:00+00:00, close=83732.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T04:00+00:00, close=83297.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|W_USDT|0.019254|-19.97|36.13|-21.20|32656465|8.31|
|DOS_USDT|0.232300|-19.75|9.06|-20.98|9347700|4.31|
|STRK_USDT|0.083770|-7.61|60.75|-8.84|62721187|1.19|
|NEAR_USDT|5.172000|-6.79|2.98|-8.02|276473853|1.93|
|ZRO_USDT|2.110800|-6.64|3.18|-7.87|27794414|0.47|
|RLC_USDT|0.927000|-6.23|69.16|-7.46|6740242|1.08|
|LIT_USDT|3.428200|-5.43|-9.83|-6.66|10349178|0.29|
|PUMPFUN_USDT|0.005054|-4.80|-20.22|-6.03|31504729|3.96|
|ONDO_USDT|0.476900|-4.25|-2.43|-5.48|63273799|2.10|
|HBAR_USDT|0.087560|-3.24|-13.04|-4.47|22388953|1.14|
|ICP_USDT|3.190000|-3.18|-7.96|-4.41|17644502|3.13|
|SEI_USDT|0.064280|-3.14|-10.61|-4.37|9418895|1.55|
|JUP_USDT|0.334400|-2.47|-1.03|-3.70|8621074|2.99|
|USELESS_USDT|0.177300|-2.36|-21.80|-3.59|6450019|2.25|
|HYPE_USDT|82.529000|-2.18|-10.92|-3.41|85796699|0.12|
|PONS_USDT|0.291400|-1.11|-24.01|-2.34|6248793|6.85|
|MAGIC_USDT|0.121950|0.00|96.72|-1.23|10323611|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.232300|0.227700|0.232300|1.58|N|Y/Y|Y/N|N|N|
|HBAR_USDT|0.087560|0.087480|0.087560|1.47|N|Y/Y|Y/Y|N|N|
|HYPE_USDT|82.529000|82.647000|82.529000|0.58|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.190000|3.155000|3.190000|2.37|N|N/Y|Y/Y|N|N|
|JUP_USDT|0.334400|0.335300|0.334400|1.61|Y|Y/Y|Y/Y|N|Y|
|LIT_USDT|3.428200|3.407500|3.426900|0.65|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.172000|5.227000|5.172000|2.58|Y|Y/Y|Y/Y|N|Y|
|ONDO_USDT|0.476900|0.478700|0.476900|1.93|Y|Y/Y|Y/Y|N|Y|
|PUMPFUN_USDT|0.005054|0.005057|0.005054|1.34|Y|Y/Y|Y/Y|N|Y|
|RLC_USDT|0.927000|0.938800|0.927000|2.02|Y|Y/Y|Y/Y|N|Y|
|SEI_USDT|0.064280|0.064110|0.064280|2.03|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.083770|0.084160|0.083770|1.08|N|Y/Y|Y/Y|N|N|
|USELESS_USDT|0.177300|0.176460|0.177300|1.72|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019254|0.019044|0.019265|1.33|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.110800|2.075100|2.111000|1.09|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T07:30:00+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=0.239000, depth_time=2026-10-13T07:30:11+00:00, book20_bid_proxy_usdt=85912, book20_ask_proxy_usdt=87234, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.75%, turnover=9347700. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T07:30:01+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=0.088580, depth_time=2026-10-13T07:30:31+00:00, book20_bid_proxy_usdt=355478, book20_ask_proxy_usdt=924668, funding_indicative=-0.000016, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.24%, turnover=22388953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-13T07:30:00+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=83.352000, depth_time=2026-10-13T07:30:44+00:00, book20_bid_proxy_usdt=286818, book20_ask_proxy_usdt=113307, funding_indicative=-0.000002, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.18%, turnover=85796699. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T07:30:01+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=3.275000, depth_time=2026-10-13T07:30:34+00:00, book20_bid_proxy_usdt=758941, book20_ask_proxy_usdt=1017970, funding_indicative=-0.000048, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.18%, turnover=17644502. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T07:30:01+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=0.339200, depth_time=2026-10-13T07:30:39+00:00, book20_bid_proxy_usdt=474821, book20_ask_proxy_usdt=615076, funding_indicative=-0.000005, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.47%, turnover=8621074. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T07:30:01+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=3.476600, depth_time=2026-10-13T07:30:23+00:00, book20_bid_proxy_usdt=31418, book20_ask_proxy_usdt=20928, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.43%, turnover=10349178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T07:30:00+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=5.363000, depth_time=2026-10-13T07:30:15+00:00, book20_bid_proxy_usdt=2949998, book20_ask_proxy_usdt=3555833, funding_indicative=-0.000062, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.79%, turnover=276473853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-13T07:30:00+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=0.487600, depth_time=2026-10-13T07:30:28+00:00, book20_bid_proxy_usdt=2129609, book20_ask_proxy_usdt=2060186, funding_indicative=0.000029, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=63273799. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T07:30:01+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=0.005124, depth_time=2026-10-13T07:30:26+00:00, book20_bid_proxy_usdt=1437844, book20_ask_proxy_usdt=1774623, funding_indicative=0.000014, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.80%, turnover=31504729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T07:30:01+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=0.963500, depth_time=2026-10-13T07:30:21+00:00, book20_bid_proxy_usdt=43910, book20_ask_proxy_usdt=81307, funding_indicative=-0.000740, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.23%, turnover=6740242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T07:30:01+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=0.064870, depth_time=2026-10-13T07:30:36+00:00, book20_bid_proxy_usdt=163062, book20_ask_proxy_usdt=266902, funding_indicative=0.000000, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.14%, turnover=9418895. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T07:30:00+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=0.088540, depth_time=2026-10-13T07:30:14+00:00, book20_bid_proxy_usdt=144600, book20_ask_proxy_usdt=330654, funding_indicative=0.000010, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.61%, turnover=62721187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T07:30:01+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=0.179420, depth_time=2026-10-13T07:30:42+00:00, book20_bid_proxy_usdt=12226, book20_ask_proxy_usdt=79958, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.36%, turnover=6450019. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T07:30:00+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=0.019841, depth_time=2026-10-13T07:30:07+00:00, book20_bid_proxy_usdt=28003, book20_ask_proxy_usdt=33500, funding_indicative=-0.000505, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.97%, turnover=32656465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T07:30:01+00:00, last15m_closed_end=2026-10-13T07:30+00:00, prior8high=2.149200, depth_time=2026-10-13T07:30:19+00:00, book20_bid_proxy_usdt=46051, book20_ask_proxy_usdt=61728, funding_indicative=-0.000021, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.64%, turnover=27794414. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
