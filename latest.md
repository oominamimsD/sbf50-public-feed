# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T07:45:31Z**
- feed_generated_utc: 2026-11-08T07:45:33+00:00
- source_sha256: `808462b881f39e8adda1ef3c0c036924028a9222e36692431d57e37c406ac6e7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T07:45+00:00, close=75878.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T07:00+00:00, close=75801.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005221|-12.73|-53.12|-12.92|37778206|3.83|
|ONE_USDT|0.001963|-3.62|67.16|-3.81|26292066|0.51|
|TIA_USDT|0.430800|-2.44|-12.09|-2.63|7791763|2.32|
|ENA_USDT|0.154390|-2.39|-20.42|-2.58|29352573|0.65|
|WLD_USDT|0.329400|-1.84|-18.54|-2.03|23871764|3.04|
|AAVE_USDT|130.270000|-1.48|-3.86|-1.67|10756888|0.77|
|QNT_USDT|196.090000|-1.38|-2.46|-1.57|45680121|0.51|
|ONDO_USDT|0.359100|-1.10|-12.92|-1.29|8609101|2.79|
|LINK_USDT|10.728000|-1.06|-7.28|-1.25|67345736|0.93|
|ADA_USDT|0.180100|-0.82|-6.97|-1.01|9763388|5.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.270000|129.910000|130.270000|1.97|N|Y/Y|N/N|Y|N|
|ADA_USDT|0.180100|0.179600|0.180100|2.35|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005221|0.005067|0.005221|0.62|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.154390|0.153450|0.154390|0.54|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.728000|10.711000|10.728000|0.74|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359100|0.357600|0.359000|0.32|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001963|0.001905|0.001963|0.48|N|N/Y|N/N|Y|N|
|QNT_USDT|196.090000|194.160000|196.090000|0.36|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.430800|0.429800|0.430800|0.47|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.329400|0.328600|0.329400|1.71|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T07:44:59+00:00, last15m_closed_end=2026-11-08T07:45+00:00, prior8high=131.110000, depth_time=2026-11-08T07:45:18+00:00, book20_bid_proxy_usdt=375788, book20_ask_proxy_usdt=987516, funding_indicative=0.000020, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=10756888. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T07:44:59+00:00, last15m_closed_end=2026-11-08T07:45+00:00, prior8high=0.180500, depth_time=2026-11-08T07:45:29+00:00, book20_bid_proxy_usdt=9791458, book20_ask_proxy_usdt=8574596, funding_indicative=0.000000, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.82%, turnover=9763388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T07:44:59+00:00, last15m_closed_end=2026-11-08T07:45+00:00, prior8high=0.005300, depth_time=2026-11-08T07:45:05+00:00, book20_bid_proxy_usdt=75319, book20_ask_proxy_usdt=76598, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.73%, turnover=37778206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T07:44:59+00:00, last15m_closed_end=2026-11-08T07:45+00:00, prior8high=0.155160, depth_time=2026-11-08T07:45:11+00:00, book20_bid_proxy_usdt=191430, book20_ask_proxy_usdt=246999, funding_indicative=0.000049, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.39%, turnover=29352573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T07:44:59+00:00, last15m_closed_end=2026-11-08T07:45+00:00, prior8high=10.766000, depth_time=2026-11-08T07:45:27+00:00, book20_bid_proxy_usdt=351374, book20_ask_proxy_usdt=354983, funding_indicative=0.000072, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=67345736. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T07:44:59+00:00, last15m_closed_end=2026-11-08T07:45+00:00, prior8high=0.359900, depth_time=2026-11-08T07:45:24+00:00, book20_bid_proxy_usdt=1394926, book20_ask_proxy_usdt=1994606, funding_indicative=-0.000002, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=8609101. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T07:44:59+00:00, last15m_closed_end=2026-11-08T07:45+00:00, prior8high=0.002049, depth_time=2026-11-08T07:45:10+00:00, book20_bid_proxy_usdt=12884, book20_ask_proxy_usdt=16038, funding_indicative=-0.000582, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.62%, turnover=26292066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T07:44:59+00:00, last15m_closed_end=2026-11-08T07:45+00:00, prior8high=196.790000, depth_time=2026-11-08T07:45:22+00:00, book20_bid_proxy_usdt=88880, book20_ask_proxy_usdt=76169, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=45680121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T07:44:59+00:00, last15m_closed_end=2026-11-08T07:45+00:00, prior8high=0.434500, depth_time=2026-11-08T07:45:06+00:00, book20_bid_proxy_usdt=400400, book20_ask_proxy_usdt=318777, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.44%, turnover=7791763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T07:44:59+00:00, last15m_closed_end=2026-11-08T07:45+00:00, prior8high=0.332200, depth_time=2026-11-08T07:45:17+00:00, book20_bid_proxy_usdt=4211710, book20_ask_proxy_usdt=3619331, funding_indicative=-0.000154, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=23871764. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
