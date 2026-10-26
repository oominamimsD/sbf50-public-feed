# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T09:15:31Z**
- feed_generated_utc: 2026-10-26T09:15:34+00:00
- source_sha256: `9ed9d133cd259e4c693a160a0fbb2a72ad511acaf69491959d799c734ba1aa29`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T09:15+00:00, close=80204.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T09:00+00:00, close=80203.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.029490|-23.28|141.72|-22.79|12818889|3.40|
|CAP_USDT|0.085510|-20.44|28.58|-19.95|7123580|2.34|
|APR_USDT|0.037120|-10.14|36.27|-9.65|8878949|5.38|
|BTW_USDT|1.514600|-8.69|-34.30|-8.20|10900571|0.66|
|WLD_USDT|0.438600|-3.94|-7.91|-3.45|64499563|2.28|
|LIT_USDT|3.076100|-3.21|4.97|-2.72|5672071|0.33|
|XMR_USDT|588.610000|-3.07|1.04|-2.58|5966148|1.19|
|DOT_USDT|1.016200|-2.21|-4.97|-1.72|10431022|0.98|
|DASH_USDT|51.460000|-1.81|7.47|-1.32|11719320|1.94|
|PUMPFUN_USDT|0.004214|-1.65|0.45|-1.16|17222006|2.37|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.037120|0.032200|0.036980|1.57|N|N/Y|N/N|Y|N|
|BTW_USDT|1.514600|1.440500|1.513300|1.71|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.085510|0.074320|0.085590|3.08|N|Y/Y|N/N|Y|N|
|DASH_USDT|51.460000|50.720000|51.440000|2.38|N|N/Y|Y/Y|Y|N|
|DOT_USDT|1.016200|1.002700|1.016200|0.31|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.029490|0.028610|0.029490|0.69|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.076100|3.052200|3.076100|0.38|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004214|0.004136|0.004212|0.79|N|N/Y|Y/Y|Y|N|
|WLD_USDT|0.438600|0.434300|0.438600|1.58|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|588.610000|583.530000|588.610000|2.47|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T09:15:01+00:00, last15m_closed_end=2026-10-26T09:15+00:00, prior8high=0.039060, depth_time=2026-10-26T09:15:14+00:00, book20_bid_proxy_usdt=100202, book20_ask_proxy_usdt=44029, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.14%, turnover=8878949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T09:15:01+00:00, last15m_closed_end=2026-10-26T09:15+00:00, prior8high=1.621200, depth_time=2026-10-26T09:15:16+00:00, book20_bid_proxy_usdt=15730, book20_ask_proxy_usdt=18936, funding_indicative=-0.008456, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.69%, turnover=10900571. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T09:15:01+00:00, last15m_closed_end=2026-10-26T09:15+00:00, prior8high=0.101810, depth_time=2026-10-26T09:15:11+00:00, book20_bid_proxy_usdt=49328, book20_ask_proxy_usdt=55219, funding_indicative=0.000131, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-20.44%, turnover=7123580. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T09:15:01+00:00, last15m_closed_end=2026-10-26T09:15+00:00, prior8high=51.950000, depth_time=2026-10-26T09:15:27+00:00, book20_bid_proxy_usdt=956695, book20_ask_proxy_usdt=590174, funding_indicative=0.000038, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=11719320. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T09:15:01+00:00, last15m_closed_end=2026-10-26T09:15+00:00, prior8high=1.025400, depth_time=2026-10-26T09:15:25+00:00, book20_bid_proxy_usdt=364995, book20_ask_proxy_usdt=274655, funding_indicative=-0.000017, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=10431022. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T09:15:01+00:00, last15m_closed_end=2026-10-26T09:15+00:00, prior8high=0.031910, depth_time=2026-10-26T09:15:08+00:00, book20_bid_proxy_usdt=62630, book20_ask_proxy_usdt=59444, funding_indicative=-0.000219, next_funding_utc=2026-10-26T10:00:00+00:00, funding_cycle_h=1, 24h_change=-23.28%, turnover=12818889. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T09:15:01+00:00, last15m_closed_end=2026-10-26T09:15+00:00, prior8high=3.131600, depth_time=2026-10-26T09:15:20+00:00, book20_bid_proxy_usdt=26062, book20_ask_proxy_usdt=16699, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.21%, turnover=5672071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T09:15:01+00:00, last15m_closed_end=2026-10-26T09:15+00:00, prior8high=0.004261, depth_time=2026-10-26T09:15:30+00:00, book20_bid_proxy_usdt=2273326, book20_ask_proxy_usdt=2178146, funding_indicative=-0.000008, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.65%, turnover=17222006. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T09:15:01+00:00, last15m_closed_end=2026-10-26T09:15+00:00, prior8high=0.444800, depth_time=2026-10-26T09:15:18+00:00, book20_bid_proxy_usdt=2385650, book20_ask_proxy_usdt=2495340, funding_indicative=-0.000098, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.94%, turnover=64499563. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T09:15:01+00:00, last15m_closed_end=2026-10-26T09:15+00:00, prior8high=592.000000, depth_time=2026-10-26T09:15:22+00:00, book20_bid_proxy_usdt=17749, book20_ask_proxy_usdt=20334, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.07%, turnover=5966148. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
