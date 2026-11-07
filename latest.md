# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T13:30:49Z**
- feed_generated_utc: 2026-11-07T13:30:51+00:00
- source_sha256: `3ebfe0ddd2d1c773082f809e02bf92913fdca88741422fd81f87a439915b0004`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T13:30+00:00, close=75863.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T13:00+00:00, close=75860.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T12:00+00:00, close=75945.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.125000|-34.21|-52.93|-34.25|27892045|8.00|
|PUMPFUN_USDT|0.003779|-6.57|-7.98|-6.61|13243399|2.65|
|ZEC_USDT|1275.370000|-5.55|3.95|-5.59|2141450967|0.08|
|LIT_USDT|3.218200|-5.13|13.95|-5.17|12040061|0.31|
|DOT_USDT|0.904400|-3.48|-6.68|-3.52|6042890|1.11|
|TRUMPOFFICIAL_USDT|1.200000|-3.38|-23.66|-3.42|9050574|8.34|
|ENA_USDT|0.162200|-3.16|-14.57|-3.20|27726658|0.62|
|DASH_USDT|46.510000|-2.98|-5.15|-3.02|10410890|2.15|
|FARTCOIN_USDT|0.116530|-2.91|-3.13|-2.95|8644061|0.86|
|PEPE_USDT|0.000005|-2.81|-2.42|-2.85|74596931|3.03|
|ONDO_USDT|0.366000|-2.78|-8.36|-2.82|10700971|2.73|
|ADA_USDT|0.182900|-2.76|-5.03|-2.80|23619282|5.47|
|XRP_USDT|1.164900|-1.89|-7.14|-1.93|288145194|0.86|
|XLM_USDT|0.152200|-1.85|-11.63|-1.89|21073662|0.66|
|DOGE_USDT|0.071850|-1.69|-5.23|-1.73|65383614|1.39|
|AVAX_USDT|8.266000|-1.68|-0.98|-1.72|11485609|1.21|
|WLD_USDT|0.339500|-1.53|-17.57|-1.57|29209521|2.95|
|NEAR_USDT|3.704000|-1.43|-14.29|-1.47|33134841|2.70|
|SUI_USDT|0.862600|-1.20|-2.98|-1.24|30234034|1.16|
|INJ_USDT|8.214000|-1.17|15.31|-1.21|29587378|1.22|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.182900|0.182100|0.182900|0.96|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.510000|46.410000|46.510000|11.50|N|Y/Y|N/N|Y|N|
|DOGE_USDT|0.071850|0.071650|0.071850|0.68|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.904400|0.899300|0.904400|0.98|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.162200|0.160270|0.162200|0.46|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.116530|0.115570|0.116530|0.53|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.218200|3.199900|3.218200|0.41|N|Y/Y|Y/N|Y|N|
|ONDO_USDT|0.366000|0.363400|0.366000|0.59|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|3.17|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003779|0.003742|0.003779|1.35|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.200000|1.180000|1.200000|0.08|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.125000|0.120800|0.125000|0.86|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.152200|0.151770|0.152200|0.92|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.164900|1.158500|1.164900|1.54|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1275.370000|1270.270000|1275.370000|1.12|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=0.183500, depth_time=2026-11-07T13:30:38+00:00, book20_bid_proxy_usdt=10672131, book20_ask_proxy_usdt=9916518, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=23619282. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=47.080000, depth_time=2026-11-07T13:30:25+00:00, book20_bid_proxy_usdt=704359, book20_ask_proxy_usdt=491269, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.98%, turnover=10410890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=0.071990, depth_time=2026-11-07T13:30:47+00:00, book20_bid_proxy_usdt=5290188, book20_ask_proxy_usdt=6154189, funding_indicative=-0.000001, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=65383614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=0.905600, depth_time=2026-11-07T13:30:17+00:00, book20_bid_proxy_usdt=558339, book20_ask_proxy_usdt=551498, funding_indicative=-0.000070, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=6042890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=0.162090, depth_time=2026-11-07T13:30:22+00:00, book20_bid_proxy_usdt=193134, book20_ask_proxy_usdt=241254, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.16%, turnover=27726658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=0.117250, depth_time=2026-11-07T13:30:26+00:00, book20_bid_proxy_usdt=47790, book20_ask_proxy_usdt=42585, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.91%, turnover=8644061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=3.262700, depth_time=2026-11-07T13:30:14+00:00, book20_bid_proxy_usdt=29824, book20_ask_proxy_usdt=23610, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.13%, turnover=12040061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=0.366600, depth_time=2026-11-07T13:30:36+00:00, book20_bid_proxy_usdt=3110887, book20_ask_proxy_usdt=1498373, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.78%, turnover=10700971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=0.000005, depth_time=2026-11-07T13:30:32+00:00, book20_bid_proxy_usdt=38272, book20_ask_proxy_usdt=13423, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.81%, turnover=74596931. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=0.003862, depth_time=2026-11-07T13:30:10+00:00, book20_bid_proxy_usdt=2180129, book20_ask_proxy_usdt=2942763, funding_indicative=-0.000012, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.57%, turnover=13243399. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=1.202000, depth_time=2026-11-07T13:30:18+00:00, book20_bid_proxy_usdt=1028756, book20_ask_proxy_usdt=1142427, funding_indicative=0.000004, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.38%, turnover=9050574. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=0.126700, depth_time=2026-11-07T13:30:07+00:00, book20_bid_proxy_usdt=124101, book20_ask_proxy_usdt=106604, funding_indicative=-0.000023, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-34.21%, turnover=27892045. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=0.153040, depth_time=2026-11-07T13:30:43+00:00, book20_bid_proxy_usdt=170746, book20_ask_proxy_usdt=294770, funding_indicative=-0.000110, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=21073662. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=1.173100, depth_time=2026-11-07T13:30:42+00:00, book20_bid_proxy_usdt=3581205, book20_ask_proxy_usdt=3696191, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=288145194. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-07T13:30:00+00:00, last15m_closed_end=2026-11-07T13:30+00:00, prior8high=1298.240000, depth_time=2026-11-07T13:30:13+00:00, book20_bid_proxy_usdt=1108829, book20_ask_proxy_usdt=227705, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.55%, turnover=2141450967. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
