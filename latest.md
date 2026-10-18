# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T03:30:31Z**
- feed_generated_utc: 2026-10-18T03:30:33+00:00
- source_sha256: `67365181b4321ad46f5b7a3d3a6f3ea5593c95001bab51c7ec4f435e977705a6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T03:30+00:00, close=81807.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T03:00+00:00, close=81790, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.164600|-11.12|66.09|-11.72|14456473|6.08|
|TIA_USDT|0.631800|-3.98|23.15|-4.58|72543333|1.58|
|STRK_USDT|0.063760|-3.61|-31.75|-4.21|14663944|1.57|
|QNT_USDT|195.260000|-2.56|-20.34|-3.16|70327619|0.51|
|FILECOIN_USDT|1.067900|-1.79|-5.31|-2.39|21090512|0.94|
|EIGEN_USDT|0.251900|-1.71|6.91|-2.31|10526339|3.97|
|XPL_USDT|0.078920|-1.51|-9.03|-2.11|5133085|1.27|
|PUMPFUN_USDT|0.004370|-0.95|-23.66|-1.55|23227661|2.29|
|ARB_USDT|0.182780|-0.61|-2.08|-1.21|31056983|0.55|
|DOT_USDT|1.112600|-0.42|-11.48|-1.02|16772462|0.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.182780|0.180850|0.182780|0.24|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.112600|1.104200|1.112600|0.09|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.251900|0.247900|0.251900|0.42|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|1.067900|1.054300|1.067900|2.57|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.164600|0.152200|0.164600|1.05|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004370|0.004299|0.004370|0.18|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.260000|194.660000|195.260000|0.73|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.063760|0.063420|0.063760|0.98|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.631800|0.628300|0.631800|1.68|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.078920|0.078640|0.078920|0.68|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-18T03:29:59+00:00, last15m_closed_end=2026-10-18T03:30+00:00, prior8high=0.183850, depth_time=2026-10-18T03:30:27+00:00, book20_bid_proxy_usdt=95973, book20_ask_proxy_usdt=53579, funding_indicative=0.000011, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.61%, turnover=31056983. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T03:29:59+00:00, last15m_closed_end=2026-10-18T03:30+00:00, prior8high=1.119300, depth_time=2026-10-18T03:30:31+00:00, book20_bid_proxy_usdt=495271, book20_ask_proxy_usdt=230612, funding_indicative=0.000007, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.42%, turnover=16772462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T03:29:59+00:00, last15m_closed_end=2026-10-18T03:30+00:00, prior8high=0.252800, depth_time=2026-10-18T03:30:20+00:00, book20_bid_proxy_usdt=456971, book20_ask_proxy_usdt=352423, funding_indicative=-0.000006, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=10526339. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T03:29:59+00:00, last15m_closed_end=2026-10-18T03:30+00:00, prior8high=1.072600, depth_time=2026-10-18T03:30:17+00:00, book20_bid_proxy_usdt=496785, book20_ask_proxy_usdt=630637, funding_indicative=-0.000077, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=21090512. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T03:29:59+00:00, last15m_closed_end=2026-10-18T03:30+00:00, prior8high=0.169600, depth_time=2026-10-18T03:30:08+00:00, book20_bid_proxy_usdt=223245, book20_ask_proxy_usdt=129431, funding_indicative=-0.000024, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.12%, turnover=14456473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T03:29:59+00:00, last15m_closed_end=2026-10-18T03:30+00:00, prior8high=0.004390, depth_time=2026-10-18T03:30:25+00:00, book20_bid_proxy_usdt=1757233, book20_ask_proxy_usdt=1360462, funding_indicative=0.000027, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.95%, turnover=23227661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T03:29:59+00:00, last15m_closed_end=2026-10-18T03:30+00:00, prior8high=198.820000, depth_time=2026-10-18T03:30:15+00:00, book20_bid_proxy_usdt=63918, book20_ask_proxy_usdt=77176, funding_indicative=-0.000124, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=70327619. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T03:29:59+00:00, last15m_closed_end=2026-10-18T03:30+00:00, prior8high=0.064470, depth_time=2026-10-18T03:30:12+00:00, book20_bid_proxy_usdt=413785, book20_ask_proxy_usdt=294216, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.61%, turnover=14663944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T03:29:59+00:00, last15m_closed_end=2026-10-18T03:30+00:00, prior8high=0.646900, depth_time=2026-10-18T03:30:11+00:00, book20_bid_proxy_usdt=235186, book20_ask_proxy_usdt=343785, funding_indicative=-0.000027, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.98%, turnover=72543333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T03:29:59+00:00, last15m_closed_end=2026-10-18T03:30+00:00, prior8high=0.079650, depth_time=2026-10-18T03:30:23+00:00, book20_bid_proxy_usdt=395412, book20_ask_proxy_usdt=474224, funding_indicative=0.000033, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=5133085. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
