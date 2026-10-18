# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T04:45:36Z**
- feed_generated_utc: 2026-10-18T04:45:38+00:00
- source_sha256: `d1f680ede44db818c17efa753db0bcbdc34c18d779d0be6fa161b4ced3b43ba9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T04:45+00:00, close=81764, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.063170|-4.50|-32.38|-5.05|14286804|1.58|
|TIA_USDT|0.630700|-4.14|22.94|-4.69|70200335|1.59|
|EIGEN_USDT|0.248400|-3.08|5.43|-3.63|9687846|4.03|
|QNT_USDT|194.300000|-3.04|-20.73|-3.59|70705528|0.52|
|FILECOIN_USDT|1.057500|-2.74|-6.23|-3.29|21085165|0.95|
|PUMPFUN_USDT|0.004329|-1.88|-24.38|-2.43|23509831|2.31|
|DOT_USDT|1.103000|-1.28|-12.24|-1.83|16647306|0.91|
|OP_USDT|0.127340|-1.28|-8.09|-1.83|9499308|0.79|
|WLD_USDT|0.490600|-1.00|-12.23|-1.55|64116001|2.04|
|APT_USDT|0.789700|-0.97|-4.48|-1.52|10075116|1.27|
|ARB_USDT|0.182330|-0.86|-2.32|-1.41|31281922|0.55|
|ZRO_USDT|1.870800|-0.76|-7.41|-1.31|7327223|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.789700|0.789000|0.789700|1.03|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.182330|0.181310|0.182330|1.29|N|N/Y|Y/Y|N|N|
|DOT_USDT|1.103000|1.104700|1.103000|1.15|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.248400|0.247900|0.248400|2.78|N|Y/Y|N/Y|N|N|
|FILECOIN_USDT|1.057500|1.056600|1.057500|2.29|N|Y/Y|Y/Y|N|N|
|OP_USDT|0.127340|0.127320|0.127340|1.41|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004329|0.004315|0.004329|1.96|N|Y/Y|Y/Y|N|N|
|QNT_USDT|194.300000|194.620000|194.300000|1.42|Y|Y/Y|Y/Y|N|Y|
|STRK_USDT|0.063170|0.063200|0.063170|2.16|Y|Y/Y|Y/Y|N|Y|
|TIA_USDT|0.630700|0.628300|0.630700|1.00|N|Y/Y|Y/N|N|N|
|WLD_USDT|0.490600|0.489400|0.490600|1.86|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.870800|1.867700|1.870800|1.68|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T04:45:00+00:00, last15m_closed_end=2026-10-18T04:45+00:00, prior8high=0.800600, depth_time=2026-10-18T04:45:30+00:00, book20_bid_proxy_usdt=95716, book20_ask_proxy_usdt=175842, funding_indicative=-0.000099, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.97%, turnover=10075116. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-18T04:45:00+00:00, last15m_closed_end=2026-10-18T04:45+00:00, prior8high=0.185600, depth_time=2026-10-18T04:45:33+00:00, book20_bid_proxy_usdt=153924, book20_ask_proxy_usdt=71990, funding_indicative=-0.000008, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.86%, turnover=31281922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T04:45:00+00:00, last15m_closed_end=2026-10-18T04:45+00:00, prior8high=1.120700, depth_time=2026-10-18T04:45:22+00:00, book20_bid_proxy_usdt=347994, book20_ask_proxy_usdt=352936, funding_indicative=-0.000039, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=16647306. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T04:45:00+00:00, last15m_closed_end=2026-10-18T04:45+00:00, prior8high=0.253900, depth_time=2026-10-18T04:45:11+00:00, book20_bid_proxy_usdt=536027, book20_ask_proxy_usdt=359812, funding_indicative=0.000009, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=9687846. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T04:45:00+00:00, last15m_closed_end=2026-10-18T04:45+00:00, prior8high=1.074100, depth_time=2026-10-18T04:45:17+00:00, book20_bid_proxy_usdt=457746, book20_ask_proxy_usdt=668989, funding_indicative=-0.000103, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=21085165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T04:45:00+00:00, last15m_closed_end=2026-10-18T04:45+00:00, prior8high=0.129950, depth_time=2026-10-18T04:45:25+00:00, book20_bid_proxy_usdt=33405, book20_ask_proxy_usdt=84181, funding_indicative=-0.000187, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=9499308. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T04:45:00+00:00, last15m_closed_end=2026-10-18T04:45+00:00, prior8high=0.004401, depth_time=2026-10-18T04:45:18+00:00, book20_bid_proxy_usdt=1594552, book20_ask_proxy_usdt=1820870, funding_indicative=0.000022, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.88%, turnover=23509831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T04:45:00+00:00, last15m_closed_end=2026-10-18T04:45+00:00, prior8high=197.180000, depth_time=2026-10-18T04:45:14+00:00, book20_bid_proxy_usdt=112623, book20_ask_proxy_usdt=79298, funding_indicative=-0.000125, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.04%, turnover=70705528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T04:45:00+00:00, last15m_closed_end=2026-10-18T04:45+00:00, prior8high=0.064400, depth_time=2026-10-18T04:45:08+00:00, book20_bid_proxy_usdt=424518, book20_ask_proxy_usdt=369001, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.50%, turnover=14286804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T04:45:00+00:00, last15m_closed_end=2026-10-18T04:45+00:00, prior8high=0.638400, depth_time=2026-10-18T04:45:10+00:00, book20_bid_proxy_usdt=241310, book20_ask_proxy_usdt=265975, funding_indicative=-0.000008, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.14%, turnover=70200335. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T04:45:00+00:00, last15m_closed_end=2026-10-18T04:45+00:00, prior8high=0.498500, depth_time=2026-10-18T04:45:27+00:00, book20_bid_proxy_usdt=2327394, book20_ask_proxy_usdt=2097921, funding_indicative=-0.000161, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=64116001. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T04:45:01+00:00, last15m_closed_end=2026-10-18T04:45+00:00, prior8high=1.918400, depth_time=2026-10-18T04:45:35+00:00, book20_bid_proxy_usdt=47020, book20_ask_proxy_usdt=75521, funding_indicative=0.000024, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.76%, turnover=7327223. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
