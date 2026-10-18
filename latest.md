# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T03:00:36Z**
- feed_generated_utc: 2026-10-18T03:00:38+00:00
- source_sha256: `1627a91c28d1a44c70e3a2fc7f86d819747fd439d9bdb845a45f1750002c3dd1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T03:00+00:00, close=81790, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T03:00+00:00, close=81790, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.631600|-4.01|23.11|-4.59|74289774|1.58|
|STRK_USDT|0.063890|-3.41|-31.61|-3.99|15683400|1.56|
|EIGEN_USDT|0.249800|-2.53|6.02|-3.11|10781060|4.00|
|QNT_USDT|195.660000|-2.37|-20.18|-2.95|70991328|1.02|
|XPL_USDT|0.078880|-2.33|-9.08|-2.91|5085911|1.27|
|FILECOIN_USDT|1.063000|-2.24|-5.74|-2.82|21195184|0.94|
|PUMPFUN_USDT|0.004351|-1.38|-24.00|-1.96|23826552|2.30|
|ICP_USDT|2.924000|-1.11|-7.14|-1.69|6626771|3.42|
|ARB_USDT|0.182350|-0.85|-2.31|-1.43|32810712|0.55|
|OP_USDT|0.128030|-0.75|-7.59|-1.33|9701857|0.78|
|DOT_USDT|1.110300|-0.63|-11.66|-1.21|16879185|0.90|
|WLD_USDT|0.492500|-0.62|-11.89|-1.20|66452608|2.03|
|APT_USDT|0.792600|-0.61|-4.13|-1.19|10239558|1.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.792600|0.788100|0.792600|0.68|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.182350|0.180450|0.182350|7.73|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.110300|1.104200|1.110300|1.30|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.249800|0.247900|0.249800|0.09|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|1.063000|1.054300|1.063000|3.85|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.924000|2.909000|2.924000|0.70|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.128030|0.127070|0.128030|0.45|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004351|0.004299|0.004351|0.26|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.660000|194.380000|195.660000|0.52|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.063890|0.063420|0.063880|1.25|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.631600|0.628300|0.631600|0.93|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.492500|0.489200|0.492500|0.54|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.078880|0.078630|0.078880|0.37|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T02:59:59+00:00, last15m_closed_end=2026-10-18T03:00+00:00, prior8high=0.800100, depth_time=2026-10-18T03:00:33+00:00, book20_bid_proxy_usdt=132318, book20_ask_proxy_usdt=128190, funding_indicative=-0.000075, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.61%, turnover=10239558. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-18T02:59:59+00:00, last15m_closed_end=2026-10-18T03:00+00:00, prior8high=0.183400, depth_time=2026-10-18T03:00:25+00:00, book20_bid_proxy_usdt=67607, book20_ask_proxy_usdt=40338, funding_indicative=0.000017, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.85%, turnover=32810712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T02:59:59+00:00, last15m_closed_end=2026-10-18T03:00+00:00, prior8high=1.119300, depth_time=2026-10-18T03:00:30+00:00, book20_bid_proxy_usdt=226687, book20_ask_proxy_usdt=314057, funding_indicative=0.000030, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.63%, turnover=16879185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T02:59:59+00:00, last15m_closed_end=2026-10-18T03:00+00:00, prior8high=0.253300, depth_time=2026-10-18T03:00:10+00:00, book20_bid_proxy_usdt=458604, book20_ask_proxy_usdt=360405, funding_indicative=0.000005, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=10781060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T02:59:59+00:00, last15m_closed_end=2026-10-18T03:00+00:00, prior8high=1.071500, depth_time=2026-10-18T03:00:19+00:00, book20_bid_proxy_usdt=396144, book20_ask_proxy_usdt=671313, funding_indicative=-0.000066, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=21195184. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T03:00:00+00:00, last15m_closed_end=2026-10-18T03:00+00:00, prior8high=2.959000, depth_time=2026-10-18T03:00:22+00:00, book20_bid_proxy_usdt=1027160, book20_ask_proxy_usdt=958812, funding_indicative=0.000052, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=6626771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T02:59:59+00:00, last15m_closed_end=2026-10-18T03:00+00:00, prior8high=0.129000, depth_time=2026-10-18T03:00:28+00:00, book20_bid_proxy_usdt=72721, book20_ask_proxy_usdt=88660, funding_indicative=-0.000141, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.75%, turnover=9701857. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T02:59:59+00:00, last15m_closed_end=2026-10-18T03:00+00:00, prior8high=0.004390, depth_time=2026-10-18T03:00:21+00:00, book20_bid_proxy_usdt=1465803, book20_ask_proxy_usdt=1711500, funding_indicative=0.000020, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.38%, turnover=23826552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T02:59:59+00:00, last15m_closed_end=2026-10-18T03:00+00:00, prior8high=198.820000, depth_time=2026-10-18T03:00:14+00:00, book20_bid_proxy_usdt=66724, book20_ask_proxy_usdt=48994, funding_indicative=-0.000125, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.37%, turnover=70991328. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T02:59:59+00:00, last15m_closed_end=2026-10-18T03:00+00:00, prior8high=0.064470, depth_time=2026-10-18T03:00:09+00:00, book20_bid_proxy_usdt=264099, book20_ask_proxy_usdt=417591, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.41%, turnover=15683400. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T02:59:59+00:00, last15m_closed_end=2026-10-18T03:00+00:00, prior8high=0.649100, depth_time=2026-10-18T03:00:06+00:00, book20_bid_proxy_usdt=171152, book20_ask_proxy_usdt=332862, funding_indicative=-0.000024, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.01%, turnover=74289774. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T02:59:59+00:00, last15m_closed_end=2026-10-18T03:00+00:00, prior8high=0.496400, depth_time=2026-10-18T03:00:33+00:00, book20_bid_proxy_usdt=1973575, book20_ask_proxy_usdt=1878812, funding_indicative=-0.000140, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.62%, turnover=66452608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T03:00:00+00:00, last15m_closed_end=2026-10-18T03:00+00:00, prior8high=0.079650, depth_time=2026-10-18T03:00:15+00:00, book20_bid_proxy_usdt=389542, book20_ask_proxy_usdt=534371, funding_indicative=0.000042, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=5085911. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
