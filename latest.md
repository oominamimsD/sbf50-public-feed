# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T09:45:45Z**
- feed_generated_utc: 2026-10-25T09:45:48+00:00
- source_sha256: `2b20847443bf7b084078e163ba340325b82f7a47a8bbd3f92d71ea71731ff0c9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T09:45+00:00, close=80236.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T09:00+00:00, close=80374.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.051500|-23.59|66.39|-24.18|13509946|1.94|
|IRYS_USDT|0.035340|-23.25|176.95|-23.84|33406885|2.83|
|BTW_USDT|1.642800|-5.65|-27.61|-6.24|11673349|1.22|
|WLD_USDT|0.445600|-3.54|-10.08|-4.13|96463258|2.24|
|STRK_USDT|0.045500|-2.63|-31.21|-3.22|9401875|2.20|
|AKE_USDT|0.028640|-2.01|-1.11|-2.60|5727210|1.05|
|SUI_USDT|0.909800|-1.64|-7.33|-2.23|69164261|1.10|
|DOT_USDT|1.022000|-1.64|-8.53|-2.23|12557682|0.98|
|APT_USDT|0.693900|-1.13|-12.99|-1.72|6021258|1.44|
|SEI_USDT|0.052330|-1.04|-15.61|-1.63|7864099|1.91|
|PENGU_USDT|0.007365|-1.04|-1.18|-1.63|5901426|1.36|
|ARB_USDT|0.164340|-0.84|-10.64|-1.43|15606760|0.61|
|LINK_USDT|11.314000|-0.59|-4.97|-1.18|50197629|0.88|
|ONDO_USDT|0.399300|-0.52|-9.16|-1.11|15398913|2.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028640|0.028536|0.028640|0.49|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.693900|0.687600|0.693900|0.16|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164340|0.163130|0.164340|0.26|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.642800|1.636300|1.642800|0.48|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.022000|1.011600|1.022000|0.57|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.035340|0.034520|0.035340|0.69|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.314000|11.255000|11.314000|0.39|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.399300|0.396800|0.399300|0.38|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.051500|0.048370|0.051500|0.61|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007365|0.007294|0.007365|2.62|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052330|0.051870|0.052330|0.36|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045500|0.045060|0.045500|1.86|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.909800|0.903500|0.909600|0.39|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.445600|0.431900|0.445600|1.26|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-25T09:44:59+00:00, last15m_closed_end=2026-10-25T09:45+00:00, prior8high=0.029186, depth_time=2026-10-25T09:45:23+00:00, book20_bid_proxy_usdt=21162, book20_ask_proxy_usdt=13072, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=5727210. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-25T09:44:59+00:00, last15m_closed_end=2026-10-25T09:45+00:00, prior8high=0.703200, depth_time=2026-10-25T09:45:29+00:00, book20_bid_proxy_usdt=138520, book20_ask_proxy_usdt=188193, funding_indicative=-0.000077, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=6021258. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T09:44:59+00:00, last15m_closed_end=2026-10-25T09:45+00:00, prior8high=0.166810, depth_time=2026-10-25T09:45:39+00:00, book20_bid_proxy_usdt=86283, book20_ask_proxy_usdt=101395, funding_indicative=0.000053, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.84%, turnover=15606760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T09:44:59+00:00, last15m_closed_end=2026-10-25T09:45+00:00, prior8high=1.708300, depth_time=2026-10-25T09:45:15+00:00, book20_bid_proxy_usdt=10675, book20_ask_proxy_usdt=6414, funding_indicative=-0.015435, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.65%, turnover=11673349. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T09:44:59+00:00, last15m_closed_end=2026-10-25T09:45+00:00, prior8high=1.032000, depth_time=2026-10-25T09:45:28+00:00, book20_bid_proxy_usdt=297953, book20_ask_proxy_usdt=346254, funding_indicative=-0.000051, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=12557682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T09:44:59+00:00, last15m_closed_end=2026-10-25T09:45+00:00, prior8high=0.039040, depth_time=2026-10-25T09:45:12+00:00, book20_bid_proxy_usdt=42579, book20_ask_proxy_usdt=55606, funding_indicative=-0.001385, next_funding_utc=2026-10-25T10:00:00+00:00, funding_cycle_h=1, 24h_change=-23.25%, turnover=33406885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T09:44:59+00:00, last15m_closed_end=2026-10-25T09:45+00:00, prior8high=11.417000, depth_time=2026-10-25T09:45:41+00:00, book20_bid_proxy_usdt=480269, book20_ask_proxy_usdt=462313, funding_indicative=0.000039, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.59%, turnover=50197629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-25T09:44:59+00:00, last15m_closed_end=2026-10-25T09:45+00:00, prior8high=0.405500, depth_time=2026-10-25T09:45:44+00:00, book20_bid_proxy_usdt=2410278, book20_ask_proxy_usdt=3268883, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.52%, turnover=15398913. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T09:44:59+00:00, last15m_closed_end=2026-10-25T09:45+00:00, prior8high=0.054700, depth_time=2026-10-25T09:45:09+00:00, book20_bid_proxy_usdt=55920, book20_ask_proxy_usdt=74058, funding_indicative=-0.001304, next_funding_utc=2026-10-25T10:00:00+00:00, funding_cycle_h=1, 24h_change=-23.59%, turnover=13509946. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T09:44:59+00:00, last15m_closed_end=2026-10-25T09:45+00:00, prior8high=0.007475, depth_time=2026-10-25T09:45:35+00:00, book20_bid_proxy_usdt=175888, book20_ask_proxy_usdt=274862, funding_indicative=-0.000070, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.04%, turnover=5901426. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T09:44:59+00:00, last15m_closed_end=2026-10-25T09:45+00:00, prior8high=0.052970, depth_time=2026-10-25T09:45:33+00:00, book20_bid_proxy_usdt=282623, book20_ask_proxy_usdt=397190, funding_indicative=-0.000102, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=7864099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T09:44:59+00:00, last15m_closed_end=2026-10-25T09:45+00:00, prior8high=0.046630, depth_time=2026-10-25T09:45:20+00:00, book20_bid_proxy_usdt=846827, book20_ask_proxy_usdt=757527, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.63%, turnover=9401875. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T09:44:59+00:00, last15m_closed_end=2026-10-25T09:45+00:00, prior8high=0.921100, depth_time=2026-10-25T09:45:25+00:00, book20_bid_proxy_usdt=1265317, book20_ask_proxy_usdt=1379103, funding_indicative=0.000050, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=69164261. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-25T09:44:59+00:00, last15m_closed_end=2026-10-25T09:45+00:00, prior8high=0.466600, depth_time=2026-10-25T09:45:16+00:00, book20_bid_proxy_usdt=2074499, book20_ask_proxy_usdt=2246321, funding_indicative=0.000007, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.54%, turnover=96463258. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
