# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T22:15:41Z**
- feed_generated_utc: 2026-10-26T22:15:45+00:00
- source_sha256: `8aad8863fe3f3f6ddf883bc41cb7f498036c8c23f11d5256b438214770be9c22`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T22:15+00:00, close=79963.9, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T22:00+00:00, close=80070.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BR_USDT|0.475300|-4.84|-22.84|-4.30|12068996|2.10|
|ZRO_USDT|1.627700|-4.65|-14.42|-4.11|5381933|0.61|
|LIT_USDT|2.993900|-3.98|-1.25|-3.44|5219232|0.33|
|NEAR_USDT|4.452000|-2.64|-9.21|-2.10|117392393|2.25|
|PUMPFUN_USDT|0.004220|-2.49|-5.29|-1.95|21819709|2.37|
|BTW_USDT|1.167400|-2.36|-33.36|-1.82|20950919|2.58|
|IRYS_USDT|0.026940|-2.32|119.38|-1.78|9346709|3.71|
|FILECOIN_USDT|0.900700|-2.17|-10.99|-1.63|6398567|1.11|
|PEPE_USDT|0.000004|-2.06|3.96|-1.52|79950828|0.23|
|WLD_USDT|0.436300|-1.95|-13.82|-1.41|72572133|2.29|
|DOT_USDT|1.003300|-1.88|-12.51|-1.34|10481660|1.00|
|ARB_USDT|0.166840|-1.85|-14.71|-1.31|20645379|0.60|
|LINK_USDT|11.322000|-1.78|-5.19|-1.24|98935774|0.88|
|TAO_USDT|249.050000|-1.75|-7.17|-1.21|45619897|1.20|
|PENGU_USDT|0.007442|-1.74|-0.65|-1.20|5987647|1.34|
|FET_USDT|0.173800|-1.58|-8.04|-1.04|6456114|5.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.166840|0.166370|0.166840|1.62|N|Y/Y|Y/Y|Y|N|
|BR_USDT|0.475300|0.472600|0.475300|0.64|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.167400|1.108000|1.167400|0.70|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.003300|0.999300|1.003300|0.35|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.900700|0.895300|0.900700|0.14|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026940|0.025640|0.026940|1.83|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.322000|11.304000|11.322000|0.73|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.993900|2.972000|2.993900|0.46|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.452000|4.437000|4.452000|0.69|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007442|0.007419|0.007443|2.09|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.14|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004220|0.004178|0.004220|0.09|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|249.050000|248.640000|249.040000|0.70|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.436300|0.432200|0.436300|0.89|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.627700|1.608700|1.627700|3.17|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-26T22:15:01+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=0.168330, depth_time=2026-10-26T22:15:32+00:00, book20_bid_proxy_usdt=84192, book20_ask_proxy_usdt=47370, funding_indicative=-0.000035, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=20645379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-26T22:15:01+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=0.481400, depth_time=2026-10-26T22:15:07+00:00, book20_bid_proxy_usdt=36599, book20_ask_proxy_usdt=38897, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.84%, turnover=12068996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T22:15:00+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=1.218200, depth_time=2026-10-26T22:15:19+00:00, book20_bid_proxy_usdt=11679, book20_ask_proxy_usdt=11817, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.36%, turnover=20950919. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T22:15:01+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=1.011200, depth_time=2026-10-26T22:15:30+00:00, book20_bid_proxy_usdt=290896, book20_ask_proxy_usdt=387402, funding_indicative=-0.000059, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=10481660. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T22:15:01+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=0.909400, depth_time=2026-10-26T22:15:17+00:00, book20_bid_proxy_usdt=1189359, book20_ask_proxy_usdt=1267660, funding_indicative=0.000083, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=6398567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T22:15:00+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=0.026780, depth_time=2026-10-26T22:15:21+00:00, book20_bid_proxy_usdt=91196, book20_ask_proxy_usdt=91837, funding_indicative=-0.001152, next_funding_utc=2026-10-26T23:00:00+00:00, funding_cycle_h=1, 24h_change=-2.32%, turnover=9346709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-26T22:15:01+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=11.397000, depth_time=2026-10-26T22:15:35+00:00, book20_bid_proxy_usdt=573212, book20_ask_proxy_usdt=534609, funding_indicative=0.000098, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=98935774. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T22:15:01+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=3.045600, depth_time=2026-10-26T22:15:11+00:00, book20_bid_proxy_usdt=22278, book20_ask_proxy_usdt=38083, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.98%, turnover=5219232. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T22:15:00+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=4.492000, depth_time=2026-10-26T22:15:13+00:00, book20_bid_proxy_usdt=5087076, book20_ask_proxy_usdt=5141469, funding_indicative=0.000062, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=117392393. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-26T22:15:01+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=0.007510, depth_time=2026-10-26T22:15:40+00:00, book20_bid_proxy_usdt=160196, book20_ask_proxy_usdt=319356, funding_indicative=0.000032, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=5987647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T22:15:01+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=0.000004, depth_time=2026-10-26T22:15:26+00:00, book20_bid_proxy_usdt=63603, book20_ask_proxy_usdt=45701, funding_indicative=0.000073, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.06%, turnover=79950828. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T22:15:01+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=0.004251, depth_time=2026-10-26T22:15:17+00:00, book20_bid_proxy_usdt=2142254, book20_ask_proxy_usdt=1893432, funding_indicative=-0.000005, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.49%, turnover=21819709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-26T22:15:01+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=251.140000, depth_time=2026-10-26T22:15:38+00:00, book20_bid_proxy_usdt=131248, book20_ask_proxy_usdt=162266, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.75%, turnover=45619897. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T22:15:01+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=0.439900, depth_time=2026-10-26T22:15:27+00:00, book20_bid_proxy_usdt=3017791, book20_ask_proxy_usdt=2548152, funding_indicative=-0.000127, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=72572133. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-26T22:15:01+00:00, last15m_closed_end=2026-10-26T22:15+00:00, prior8high=1.637100, depth_time=2026-10-26T22:15:09+00:00, book20_bid_proxy_usdt=29200, book20_ask_proxy_usdt=40029, funding_indicative=-0.000063, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.65%, turnover=5381933. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
