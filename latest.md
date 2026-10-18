# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T04:15:31Z**
- feed_generated_utc: 2026-10-18T04:15:33+00:00
- source_sha256: `efd71d3d5634b903d59129dc9b936b49ece3d8dfae7cec1c12af4818cac842f4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T04:15+00:00, close=81856.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.177100|-4.37|78.70|-5.03|14339129|5.65|
|STRK_USDT|0.063310|-4.29|-32.23|-4.95|14152366|1.58|
|TIA_USDT|0.635500|-3.41|23.87|-4.07|69713319|1.57|
|QNT_USDT|195.870000|-2.26|-20.09|-2.92|69926093|0.51|
|EIGEN_USDT|0.251100|-2.02|6.57|-2.68|9615416|3.98|
|FILECOIN_USDT|1.065600|-2.00|-5.51|-2.66|20786473|0.94|
|PUMPFUN_USDT|0.004351|-1.38|-24.00|-2.04|23251843|2.30|
|APT_USDT|0.792300|-0.65|-4.17|-1.31|10025040|1.26|
|DOT_USDT|1.110400|-0.62|-11.65|-1.28|16506800|0.90|
|OP_USDT|0.128260|-0.57|-7.42|-1.23|9447226|0.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.792300|0.788100|0.792300|3.84|N|Y/Y|Y/Y|N|N|
|DOT_USDT|1.110400|1.104200|1.110400|0.56|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.251100|0.247900|0.251100|0.17|N|Y/Y|N/Y|N|N|
|FILECOIN_USDT|1.065600|1.054300|1.065600|0.74|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.177100|0.152200|0.177100|0.97|N|Y/Y|N/N|N|N|
|OP_USDT|0.128260|0.127070|0.128260|1.01|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004351|0.004299|0.004351|0.52|N|Y/Y|Y/Y|N|N|
|QNT_USDT|195.870000|194.620000|195.870000|0.38|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.063310|0.063420|0.063310|2.44|Y|Y/Y|Y/Y|N|Y|
|TIA_USDT|0.635500|0.628300|0.635500|0.86|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T04:15:00+00:00, last15m_closed_end=2026-10-18T04:15+00:00, prior8high=0.800600, depth_time=2026-10-18T04:15:24+00:00, book20_bid_proxy_usdt=164578, book20_ask_proxy_usdt=124644, funding_indicative=-0.000079, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.65%, turnover=10025040. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T04:15:00+00:00, last15m_closed_end=2026-10-18T04:15+00:00, prior8high=1.120700, depth_time=2026-10-18T04:15:24+00:00, book20_bid_proxy_usdt=399579, book20_ask_proxy_usdt=349220, funding_indicative=0.000000, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.62%, turnover=16506800. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T04:15:00+00:00, last15m_closed_end=2026-10-18T04:15+00:00, prior8high=0.253900, depth_time=2026-10-18T04:15:16+00:00, book20_bid_proxy_usdt=725025, book20_ask_proxy_usdt=294166, funding_indicative=0.000005, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.02%, turnover=9615416. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T04:15:00+00:00, last15m_closed_end=2026-10-18T04:15+00:00, prior8high=1.074100, depth_time=2026-10-18T04:15:20+00:00, book20_bid_proxy_usdt=562962, book20_ask_proxy_usdt=525210, funding_indicative=-0.000087, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=20786473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T04:14:59+00:00, last15m_closed_end=2026-10-18T04:15+00:00, prior8high=0.179900, depth_time=2026-10-18T04:15:07+00:00, book20_bid_proxy_usdt=381176, book20_ask_proxy_usdt=163992, funding_indicative=-0.000003, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.37%, turnover=14339129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T04:15:00+00:00, last15m_closed_end=2026-10-18T04:15+00:00, prior8high=0.129950, depth_time=2026-10-18T04:15:30+00:00, book20_bid_proxy_usdt=50724, book20_ask_proxy_usdt=80706, funding_indicative=-0.000172, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.57%, turnover=9447226. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T04:15:00+00:00, last15m_closed_end=2026-10-18T04:15+00:00, prior8high=0.004401, depth_time=2026-10-18T04:15:23+00:00, book20_bid_proxy_usdt=1998318, book20_ask_proxy_usdt=1400792, funding_indicative=0.000030, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.38%, turnover=23251843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T04:14:59+00:00, last15m_closed_end=2026-10-18T04:15+00:00, prior8high=197.180000, depth_time=2026-10-18T04:15:14+00:00, book20_bid_proxy_usdt=75743, book20_ask_proxy_usdt=80201, funding_indicative=-0.000107, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=69926093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T04:15:00+00:00, last15m_closed_end=2026-10-18T04:15+00:00, prior8high=0.064400, depth_time=2026-10-18T04:15:10+00:00, book20_bid_proxy_usdt=318997, book20_ask_proxy_usdt=434396, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.29%, turnover=14152366. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T04:14:59+00:00, last15m_closed_end=2026-10-18T04:15+00:00, prior8high=0.638400, depth_time=2026-10-18T04:15:12+00:00, book20_bid_proxy_usdt=262302, book20_ask_proxy_usdt=252550, funding_indicative=-0.000008, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.41%, turnover=69713319. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
