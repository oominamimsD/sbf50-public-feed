# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T14:15:32Z**
- feed_generated_utc: 2026-11-08T14:15:34+00:00
- source_sha256: `120f4470795f0d136c8ed6f51c33862527438afda9368b1d6677e42f7c4f6955`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T14:15+00:00, close=75938.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T14:00+00:00, close=75895.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005353|-10.52|-51.93|-10.80|26717107|1.87|
|ONE_USDT|0.001856|-8.86|58.07|-9.14|23051413|0.54|
|IDOL_USDT|0.030506|-8.38|74.11|-8.66|15694119|0.66|
|TIA_USDT|0.421000|-4.66|-14.09|-4.94|7055381|2.38|
|ENA_USDT|0.153260|-3.11|-21.00|-3.39|29283957|0.65|
|WLD_USDT|0.325200|-3.09|-19.58|-3.37|24437845|3.08|
|AAVE_USDT|128.870000|-2.54|-4.90|-2.82|9567099|0.78|
|LINK_USDT|10.713000|-1.20|-7.41|-1.48|60866681|1.87|
|SUI_USDT|0.847700|-1.09|-6.01|-1.37|23443310|1.18|
|ADA_USDT|0.179800|-0.99|-7.12|-1.27|10403922|5.56|
|ONDO_USDT|0.360300|-0.77|-12.63|-1.05|7280760|2.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|128.870000|128.940000|128.840000|4.31|Y|Y/Y|Y/N|Y|N|
|ADA_USDT|0.179800|0.179300|0.179800|0.50|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005353|0.005312|0.005353|0.73|N|Y/N|N/N|Y|N|
|ENA_USDT|0.153260|0.152800|0.153320|0.52|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.030506|0.028891|0.030531|1.08|N|Y/Y|N/N|Y|N|
|LINK_USDT|10.713000|10.691000|10.714000|0.92|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.360300|0.360300|0.360300|1.59|N|Y/N|Y/Y|Y|N|
|ONE_USDT|0.001856|0.001820|0.001858|0.60|N|Y/Y|N/N|Y|N|
|SUI_USDT|0.847700|0.848500|0.847800|1.79|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.421000|0.419200|0.421000|1.80|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.325200|0.323900|0.325200|0.59|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T14:15:02+00:00, last15m_closed_end=2026-11-08T14:15+00:00, prior8high=131.400000, depth_time=2026-11-08T14:15:20+00:00, book20_bid_proxy_usdt=425049, book20_ask_proxy_usdt=412929, funding_indicative=0.000066, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=9567099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T14:15:02+00:00, last15m_closed_end=2026-11-08T14:15+00:00, prior8high=0.181200, depth_time=2026-11-08T14:15:29+00:00, book20_bid_proxy_usdt=9991884, book20_ask_proxy_usdt=8342236, funding_indicative=-0.000038, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.99%, turnover=10403922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T14:15:02+00:00, last15m_closed_end=2026-11-08T14:15+00:00, prior8high=0.005766, depth_time=2026-11-08T14:15:07+00:00, book20_bid_proxy_usdt=43681, book20_ask_proxy_usdt=27426, funding_indicative=0.000050, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.52%, turnover=26717107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T14:15:02+00:00, last15m_closed_end=2026-11-08T14:15+00:00, prior8high=0.155690, depth_time=2026-11-08T14:15:16+00:00, book20_bid_proxy_usdt=284604, book20_ask_proxy_usdt=245756, funding_indicative=-0.000102, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=29283957. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T14:15:02+00:00, last15m_closed_end=2026-11-08T14:15+00:00, prior8high=0.031950, depth_time=2026-11-08T14:15:12+00:00, book20_bid_proxy_usdt=5800, book20_ask_proxy_usdt=3746, funding_indicative=0.000881, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.38%, turnover=15694119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T14:15:02+00:00, last15m_closed_end=2026-11-08T14:15+00:00, prior8high=10.794000, depth_time=2026-11-08T14:15:24+00:00, book20_bid_proxy_usdt=429916, book20_ask_proxy_usdt=417228, funding_indicative=-0.000001, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=60866681. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T14:15:02+00:00, last15m_closed_end=2026-11-08T14:15+00:00, prior8high=0.365700, depth_time=2026-11-08T14:15:31+00:00, book20_bid_proxy_usdt=1998436, book20_ask_proxy_usdt=1694304, funding_indicative=0.000042, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.77%, turnover=7280760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T14:15:02+00:00, last15m_closed_end=2026-11-08T14:15+00:00, prior8high=0.001927, depth_time=2026-11-08T14:15:09+00:00, book20_bid_proxy_usdt=6392, book20_ask_proxy_usdt=15138, funding_indicative=-0.000695, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.86%, turnover=23051413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T14:15:02+00:00, last15m_closed_end=2026-11-08T14:15+00:00, prior8high=0.859000, depth_time=2026-11-08T14:15:26+00:00, book20_bid_proxy_usdt=1618926, book20_ask_proxy_usdt=2095136, funding_indicative=0.000035, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=23443310. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T14:15:02+00:00, last15m_closed_end=2026-11-08T14:15+00:00, prior8high=0.427000, depth_time=2026-11-08T14:15:11+00:00, book20_bid_proxy_usdt=232263, book20_ask_proxy_usdt=366808, funding_indicative=-0.000029, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.66%, turnover=7055381. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T14:15:02+00:00, last15m_closed_end=2026-11-08T14:15+00:00, prior8high=0.329500, depth_time=2026-11-08T14:15:17+00:00, book20_bid_proxy_usdt=4295415, book20_ask_proxy_usdt=3879278, funding_indicative=-0.000067, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.09%, turnover=24437845. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
