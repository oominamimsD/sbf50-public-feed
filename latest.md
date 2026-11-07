# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T00:00:28Z**
- feed_generated_utc: 2026-11-07T00:00:29+00:00
- source_sha256: `2de2a79981251585f6226bec33407844fd7014537837029112d6848c154e0fe1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.140900|-25.84|-46.95|-25.82|34090001|7.10|
|ANTHROPIC_USDT|1334.870000|-6.73|-20.37|-6.71|7577686|1.72|
|CYBER_USDT|0.334400|-5.53|22.40|-5.51|7192898|2.99|
|PUMPFUN_USDT|0.003913|-3.26|-4.72|-3.24|13252979|2.56|
|TRUMPOFFICIAL_USDT|1.205000|-2.97|-23.34|-2.95|13481706|8.30|
|DOT_USDT|0.913000|-2.57|-5.79|-2.55|7828235|1.09|
|LIT_USDT|3.325200|-1.98|17.73|-1.96|9738411|0.30|
|HBAR_USDT|0.067580|-1.19|-5.94|-1.17|5850677|1.48|
|XLM_USDT|0.153270|-1.16|-11.01|-1.14|25066562|0.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1334.870000|1322.000000|1336.340000|0.06|N|Y/Y|Y/Y|Y|N|
|CYBER_USDT|0.334400|0.333800|0.334400|0.49|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.913000|0.912400|0.913000|0.69|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.067580|0.067360|0.067580|1.04|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.325200|3.292600|3.325200|0.57|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003913|0.003882|0.003913|0.16|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.205000|1.202000|1.205000|0.22|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.140900|0.132600|0.140900|0.18|N|Y/Y|N/N|Y|N|
|XLM_USDT|0.153270|0.153110|0.153270|0.32|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T23:59:59+00:00, last15m_closed_end=2026-11-07T00:00+00:00, prior8high=1364.960000, depth_time=2026-11-07T00:00:09+00:00, book20_bid_proxy_usdt=33013, book20_ask_proxy_usdt=11716, funding_indicative=0.000050, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.73%, turnover=7577686. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CYBER_USDT: quote_utc=2026-11-06T23:59:59+00:00, last15m_closed_end=2026-11-07T00:00+00:00, prior8high=0.356700, depth_time=2026-11-07T00:00:11+00:00, book20_bid_proxy_usdt=207460, book20_ask_proxy_usdt=141215, funding_indicative=-0.002144, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.53%, turnover=7192898. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-06T23:59:59+00:00, last15m_closed_end=2026-11-07T00:00+00:00, prior8high=0.925800, depth_time=2026-11-07T00:00:19+00:00, book20_bid_proxy_usdt=363683, book20_ask_proxy_usdt=466828, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.57%, turnover=7828235. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-06T23:59:59+00:00, last15m_closed_end=2026-11-07T00:00+00:00, prior8high=0.068220, depth_time=2026-11-07T00:00:22+00:00, book20_bid_proxy_usdt=819496, book20_ask_proxy_usdt=739138, funding_indicative=0.000012, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=5850677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T23:59:59+00:00, last15m_closed_end=2026-11-07T00:00+00:00, prior8high=3.375500, depth_time=2026-11-07T00:00:22+00:00, book20_bid_proxy_usdt=29804, book20_ask_proxy_usdt=29838, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.98%, turnover=9738411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-06T23:59:59+00:00, last15m_closed_end=2026-11-07T00:00+00:00, prior8high=0.003993, depth_time=2026-11-07T00:00:12+00:00, book20_bid_proxy_usdt=2389997, book20_ask_proxy_usdt=2232635, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.26%, turnover=13252979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-06T23:59:59+00:00, last15m_closed_end=2026-11-07T00:00+00:00, prior8high=1.229000, depth_time=2026-11-07T00:00:16+00:00, book20_bid_proxy_usdt=1412079, book20_ask_proxy_usdt=1405711, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.97%, turnover=13481706. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T23:59:59+00:00, last15m_closed_end=2026-11-07T00:00+00:00, prior8high=0.145700, depth_time=2026-11-07T00:00:07+00:00, book20_bid_proxy_usdt=127976, book20_ask_proxy_usdt=184671, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-25.84%, turnover=34090001. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-06T23:59:59+00:00, last15m_closed_end=2026-11-07T00:00+00:00, prior8high=0.155630, depth_time=2026-11-07T00:00:23+00:00, book20_bid_proxy_usdt=190061, book20_ask_proxy_usdt=231110, funding_indicative=-0.000003, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=25066562. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
