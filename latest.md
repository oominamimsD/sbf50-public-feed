# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-12T14:00:42Z**
- feed_generated_utc: 2026-10-12T14:00:46+00:00
- source_sha256: `57b2a87def847db642bbf2da57fb133071992a7308c6dd52a83a7f49f6cbc554`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-12T14:00+00:00, close=82918.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-12T14:00+00:00, close=82918.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-12T12:00+00:00, close=83359.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.095750|-19.71|67.13|-18.58|83936527|3.13|
|US_USDT|0.011562|-13.10|-20.38|-11.97|5883623|0.86|
|CFX_USDT|0.061770|-12.75|15.54|-11.62|12753397|3.24|
|BR_USDT|0.445430|-11.44|-6.06|-10.31|5294030|0.90|
|CHIP_USDT|0.062110|-9.72|32.88|-8.59|15065428|3.22|
|WLD_USDT|0.534400|-7.73|-7.86|-6.60|85036378|1.87|
|ATOM_USDT|1.860000|-7.69|5.20|-6.56|16083064|5.38|
|APT_USDT|0.869700|-7.63|7.15|-6.50|32561597|2.30|
|JUP_USDT|0.350700|-6.22|6.56|-5.09|9467428|2.85|
|SAND_USDT|0.062180|-5.91|-19.16|-4.78|7137644|1.61|
|QNT_USDT|230.290000|-5.16|-10.53|-4.03|79822587|0.43|
|OP_USDT|0.137580|-3.58|3.44|-2.45|15237248|0.73|
|ARB_USDT|0.191770|-3.21|-4.80|-2.08|37601105|0.52|
|MAGIC_USDT|0.123300|-2.88|95.86|-1.75|14532598|4.05|
|RLC_USDT|1.020200|-2.77|182.36|-1.64|15019253|1.96|
|XPL_USDT|0.085590|-2.73|-11.21|-1.60|6465441|1.17|
|SUI_USDT|1.102500|-2.70|-12.15|-1.57|103386535|1.81|
|ADA_USDT|0.247700|-2.44|0.00|-1.31|70206338|4.04|
|XRP_USDT|1.390600|-2.40|-7.55|-1.27|415633137|0.72|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.869700|0.862400|0.869800|1.27|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.191770|0.190250|0.191770|0.86|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.860000|1.839000|1.860000|1.17|N|Y/Y|Y/Y|Y|N|
|BR_USDT|0.445430|0.435010|0.445430|0.45|N|Y/Y|Y/Y|Y|N|
|CFX_USDT|0.061770|0.061080|0.061770|0.43|N|Y/Y|N/N|Y|N|
|CHIP_USDT|0.062110|0.061420|0.062110|0.72|N|Y/Y|N/N|Y|N|
|JUP_USDT|0.350700|0.351100|0.350700|3.22|Y|Y/Y|Y/Y|Y|Y|
|MAGIC_USDT|0.123300|0.120140|0.123300|0.80|N|Y/Y|N/N|Y|N|
|OP_USDT|0.137580|0.136520|0.137580|2.12|N|Y/Y|N/N|Y|N|
|QNT_USDT|230.290000|228.150000|230.290000|0.72|N|Y/Y|Y/Y|Y|N|
|RLC_USDT|1.020200|0.983100|1.020200|1.48|N|N/Y|N/N|Y|N|
|SAND_USDT|0.062180|0.062050|0.062180|1.07|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.095750|0.093090|0.095750|2.42|N|Y/Y|N/N|Y|N|
|US_USDT|0.011562|0.011370|0.011562|1.14|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.534400|0.533100|0.534400|0.96|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-12T13:59:59+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=0.875100, depth_time=2026-10-12T14:00:24+00:00, book20_bid_proxy_usdt=118351, book20_ask_proxy_usdt=171106, funding_indicative=0.000014, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.63%, turnover=32561597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-12T14:00:00+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=0.193770, depth_time=2026-10-12T14:00:36+00:00, book20_bid_proxy_usdt=94109, book20_ask_proxy_usdt=33363, funding_indicative=0.000086, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=37601105. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-12T14:00:00+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=1.865000, depth_time=2026-10-12T14:00:21+00:00, book20_bid_proxy_usdt=668614, book20_ask_proxy_usdt=532405, funding_indicative=-0.000040, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.69%, turnover=16083064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-12T14:00:00+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=0.451000, depth_time=2026-10-12T14:00:14+00:00, book20_bid_proxy_usdt=3216, book20_ask_proxy_usdt=2354, funding_indicative=0.000050, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.44%, turnover=5294030. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CFX_USDT: quote_utc=2026-10-12T14:00:00+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=0.062910, depth_time=2026-10-12T14:00:12+00:00, book20_bid_proxy_usdt=232964, book20_ask_proxy_usdt=199487, funding_indicative=0.000048, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=8, 24h_change=-12.75%, turnover=12753397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CHIP_USDT: quote_utc=2026-10-12T13:59:59+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=0.064180, depth_time=2026-10-12T14:00:15+00:00, book20_bid_proxy_usdt=22203, book20_ask_proxy_usdt=26536, funding_indicative=0.000036, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.72%, turnover=15065428. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-12T14:00:00+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=0.357100, depth_time=2026-10-12T14:00:26+00:00, book20_bid_proxy_usdt=441950, book20_ask_proxy_usdt=470733, funding_indicative=0.000050, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.22%, turnover=9467428. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGIC_USDT: quote_utc=2026-10-12T13:59:59+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=0.139500, depth_time=2026-10-12T14:00:38+00:00, book20_bid_proxy_usdt=175193, book20_ask_proxy_usdt=170899, funding_indicative=-0.000155, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.88%, turnover=14532598. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-12T14:00:00+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=0.139700, depth_time=2026-10-12T14:00:34+00:00, book20_bid_proxy_usdt=34467, book20_ask_proxy_usdt=50359, funding_indicative=0.000024, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.58%, turnover=15237248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-12T13:59:59+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=234.450000, depth_time=2026-10-12T14:00:31+00:00, book20_bid_proxy_usdt=63757, book20_ask_proxy_usdt=62011, funding_indicative=-0.000077, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.16%, turnover=79822587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-12T13:59:59+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=1.013700, depth_time=2026-10-12T14:00:42+00:00, book20_bid_proxy_usdt=34310, book20_ask_proxy_usdt=44118, funding_indicative=-0.001874, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=15019253. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-12T14:00:00+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=0.063340, depth_time=2026-10-12T14:00:29+00:00, book20_bid_proxy_usdt=583621, book20_ask_proxy_usdt=471460, funding_indicative=-0.000045, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.91%, turnover=7137644. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-12T13:59:59+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=0.106560, depth_time=2026-10-12T14:00:08+00:00, book20_bid_proxy_usdt=108456, book20_ask_proxy_usdt=195808, funding_indicative=0.000050, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=4, 24h_change=-19.71%, turnover=83936527. target_RR/account_short_permission/settled_funding=UNKNOWN.
- US_USDT: quote_utc=2026-10-12T13:59:59+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=0.012435, depth_time=2026-10-12T14:00:09+00:00, book20_bid_proxy_usdt=13299, book20_ask_proxy_usdt=15165, funding_indicative=0.000050, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.10%, turnover=5883623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-12T13:59:59+00:00, last15m_closed_end=2026-10-12T14:00+00:00, prior8high=0.541500, depth_time=2026-10-12T14:00:19+00:00, book20_bid_proxy_usdt=1169725, book20_ask_proxy_usdt=2128680, funding_indicative=0.000072, next_funding_utc=2026-10-12T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.73%, turnover=85036378. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
