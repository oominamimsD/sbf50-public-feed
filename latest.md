# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T13:45:47Z**
- feed_generated_utc: 2026-11-07T13:45:49+00:00
- source_sha256: `aade2bb4e075ca15450bfa90e1a3d937c43cb8b62ad6f1d4c2e8a9609c121594`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T13:45+00:00, close=75905, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T13:00+00:00, close=75860.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T12:00+00:00, close=75945.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.125000|-34.21|-52.93|-34.30|27929690|8.00|
|PUMPFUN_USDT|0.003779|-6.57|-7.98|-6.66|13396545|2.65|
|ZEC_USDT|1277.420000|-5.40|4.11|-5.49|2160997047|0.08|
|LIT_USDT|3.219300|-5.10|13.98|-5.19|12058196|0.31|
|ANTHROPIC_USDT|1381.770000|-3.45|-17.57|-3.54|8319553|2.53|
|DOT_USDT|0.906000|-3.31|-6.52|-3.40|6095961|1.10|
|TRUMPOFFICIAL_USDT|1.204000|-3.05|-23.40|-3.14|9070787|8.30|
|ENA_USDT|0.162550|-2.96|-14.39|-3.05|28030090|0.61|
|FARTCOIN_USDT|0.116620|-2.84|-3.05|-2.93|8695883|0.86|
|DASH_USDT|46.610000|-2.77|-4.95|-2.86|10488199|2.15|
|ADA_USDT|0.183000|-2.71|-4.98|-2.80|23788779|5.47|
|ONDO_USDT|0.366500|-2.65|-8.23|-2.74|10773626|2.73|
|PEPE_USDT|0.000005|-2.48|-2.10|-2.57|75025025|0.20|
|XRP_USDT|1.165400|-1.85|-7.10|-1.94|289662410|2.57|
|XLM_USDT|0.152370|-1.74|-11.53|-1.83|21181460|1.31|
|AVAX_USDT|8.274000|-1.59|-0.88|-1.68|11563624|1.21|
|DOGE_USDT|0.071950|-1.55|-5.10|-1.64|65775454|1.39|
|WLD_USDT|0.339500|-1.53|-17.57|-1.62|29517623|2.94|
|SUI_USDT|0.864200|-1.01|-2.80|-1.10|30823184|1.16|
|INJ_USDT|8.234000|-0.93|15.59|-1.02|29768835|1.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.183000|0.182100|0.182900|1.46|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1381.770000|1368.750000|1381.770000|1.01|N|N/N|Y/Y|Y|N|
|DASH_USDT|46.610000|46.370000|46.610000|7.32|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.906000|0.899300|0.906000|1.23|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.162550|0.160270|0.162550|1.27|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.116620|0.115570|0.116620|1.27|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.219300|3.199900|3.219300|0.13|N|Y/Y|Y/N|Y|N|
|ONDO_USDT|0.366500|0.363400|0.366500|0.66|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.06|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003779|0.003737|0.003779|1.42|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.204000|1.188000|1.204000|0.85|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.125000|0.121200|0.125000|0.47|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.152370|0.151770|0.152350|0.77|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.165400|1.158500|1.165600|0.84|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1277.420000|1269.810000|1277.600000|0.83|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=0.183500, depth_time=2026-11-07T13:45:35+00:00, book20_bid_proxy_usdt=9076797, book20_ask_proxy_usdt=7631236, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.71%, turnover=23788779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=1405.020000, depth_time=2026-11-07T13:45:18+00:00, book20_bid_proxy_usdt=23443, book20_ask_proxy_usdt=32552, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=8319553. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=47.080000, depth_time=2026-11-07T13:45:31+00:00, book20_bid_proxy_usdt=763550, book20_ask_proxy_usdt=562946, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.77%, turnover=10488199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=0.905600, depth_time=2026-11-07T13:45:20+00:00, book20_bid_proxy_usdt=546057, book20_ask_proxy_usdt=296635, funding_indicative=-0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.31%, turnover=6095961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=0.162210, depth_time=2026-11-07T13:45:23+00:00, book20_bid_proxy_usdt=312606, book20_ask_proxy_usdt=217790, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.96%, turnover=28030090. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=0.117250, depth_time=2026-11-07T13:45:26+00:00, book20_bid_proxy_usdt=42389, book20_ask_proxy_usdt=54727, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=8695883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=3.262700, depth_time=2026-11-07T13:45:14+00:00, book20_bid_proxy_usdt=55143, book20_ask_proxy_usdt=28268, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.10%, turnover=12058196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=0.366600, depth_time=2026-11-07T13:45:38+00:00, book20_bid_proxy_usdt=2099691, book20_ask_proxy_usdt=1519083, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.65%, turnover=10773626. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=0.000005, depth_time=2026-11-07T13:45:40+00:00, book20_bid_proxy_usdt=42371, book20_ask_proxy_usdt=33148, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=75025025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=0.003854, depth_time=2026-11-07T13:45:09+00:00, book20_bid_proxy_usdt=2776668, book20_ask_proxy_usdt=2751685, funding_indicative=-0.000016, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.57%, turnover=13396545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=1.202000, depth_time=2026-11-07T13:45:24+00:00, book20_bid_proxy_usdt=1353582, book20_ask_proxy_usdt=1184185, funding_indicative=0.000000, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=9070787. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=0.126700, depth_time=2026-11-07T13:45:07+00:00, book20_bid_proxy_usdt=147924, book20_ask_proxy_usdt=114398, funding_indicative=-0.000103, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-34.21%, turnover=27929690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=0.153040, depth_time=2026-11-07T13:45:46+00:00, book20_bid_proxy_usdt=222255, book20_ask_proxy_usdt=168017, funding_indicative=-0.000107, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=21181460. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=1.173100, depth_time=2026-11-07T13:45:44+00:00, book20_bid_proxy_usdt=3377423, book20_ask_proxy_usdt=3685473, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=289662410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-07T13:44:59+00:00, last15m_closed_end=2026-11-07T13:45+00:00, prior8high=1298.240000, depth_time=2026-11-07T13:45:13+00:00, book20_bid_proxy_usdt=423107, book20_ask_proxy_usdt=156390, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.40%, turnover=2160997047. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
