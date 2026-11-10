# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T12:00:41Z**
- feed_generated_utc: 2026-11-10T12:00:43+00:00
- source_sha256: `64adc1f5cd17f5b9fb99b0db80eb955b45370e18ff66719a80e12c3e41d6f7e5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002485|-47.69|-54.83|-46.22|13442198|4.02|
|JCT_USDT|0.005950|-45.78|37.82|-44.31|24085058|1.68|
|ARB_USDT|0.162200|-10.03|1.80|-8.56|38169143|0.62|
|ANTHROPIC_USDT|1298.160000|-8.21|-22.67|-6.74|6320109|0.08|
|XMR_USDT|552.050000|-8.14|-8.79|-6.67|6032772|1.27|
|QNT_USDT|186.930000|-6.50|-7.66|-5.03|32812599|1.60|
|AVAX_USDT|8.308000|-6.23|-2.27|-4.76|51352092|1.20|
|ZEC_USDT|1150.410000|-6.14|-8.26|-4.67|2230001469|0.26|
|AAVE_USDT|124.940000|-5.71|-4.30|-4.24|10681712|0.80|
|PUMPFUN_USDT|0.003522|-4.21|-14.18|-2.74|7456100|2.84|
|DOT_USDT|0.854800|-3.49|-8.48|-2.02|8258586|1.17|
|SUI_USDT|0.831800|-3.18|-5.99|-1.71|35016382|1.20|
|SOL_USDT|84.660000|-3.02|-9.46|-1.55|635554117|1.18|
|HYPE_USDT|73.710000|-3.02|-14.00|-1.55|44985042|0.14|
|DASH_USDT|45.910000|-2.95|-2.73|-1.48|9700795|2.18|
|LINK_USDT|10.455000|-2.48|-6.93|-1.01|103361365|1.91|
|ETH_USDT|2093.560000|-2.47|-7.86|-1.00|1212029421|0.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|124.940000|124.140000|124.940000|0.58|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002485|0.002445|0.002485|3.52|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1298.160000|1257.660000|1298.070000|18.63|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.162200|0.161610|0.162200|0.80|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.308000|8.255000|8.308000|1.02|N|Y/Y|Y/N|Y|N|
|DASH_USDT|45.910000|45.400000|45.910000|0.21|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.854800|0.845000|0.854800|1.12|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.710000|73.342000|73.710000|0.39|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005950|0.005322|0.005950|0.38|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003522|0.003485|0.003522|1.16|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|186.930000|185.640000|186.930000|0.32|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|84.660000|84.170000|84.660000|0.60|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.831800|0.827600|0.831800|0.56|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|552.050000|539.060000|552.050000|1.18|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1150.410000|1131.050000|1150.460000|0.58|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=125.840000, depth_time=2026-11-10T12:00:25+00:00, book20_bid_proxy_usdt=441103, book20_ask_proxy_usdt=309008, funding_indicative=0.000070, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.71%, turnover=10681712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=0.002533, depth_time=2026-11-10T12:00:07+00:00, book20_bid_proxy_usdt=63846, book20_ask_proxy_usdt=59244, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-47.69%, turnover=13442198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=1386.950000, depth_time=2026-11-10T12:00:14+00:00, book20_bid_proxy_usdt=14574, book20_ask_proxy_usdt=22144, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.21%, turnover=6320109. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=0.167940, depth_time=2026-11-10T12:00:08+00:00, book20_bid_proxy_usdt=84598, book20_ask_proxy_usdt=68298, funding_indicative=-0.000222, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.03%, turnover=38169143. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=8.429000, depth_time=2026-11-10T12:00:19+00:00, book20_bid_proxy_usdt=817041, book20_ask_proxy_usdt=938175, funding_indicative=-0.000002, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.23%, turnover=51352092. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=46.340000, depth_time=2026-11-10T12:00:36+00:00, book20_bid_proxy_usdt=608512, book20_ask_proxy_usdt=625412, funding_indicative=0.000010, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.95%, turnover=9700795. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=0.854500, depth_time=2026-11-10T12:00:30+00:00, book20_bid_proxy_usdt=415194, book20_ask_proxy_usdt=424597, funding_indicative=0.000031, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.49%, turnover=8258586. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=74.581000, depth_time=2026-11-10T12:00:37+00:00, book20_bid_proxy_usdt=56685, book20_ask_proxy_usdt=62400, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=44985042. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=0.006488, depth_time=2026-11-10T12:00:09+00:00, book20_bid_proxy_usdt=26855, book20_ask_proxy_usdt=27054, funding_indicative=0.000302, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-45.78%, turnover=24085058. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=0.003552, depth_time=2026-11-10T12:00:25+00:00, book20_bid_proxy_usdt=2756031, book20_ask_proxy_usdt=3349647, funding_indicative=-0.000027, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.21%, turnover=7456100. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=189.450000, depth_time=2026-11-10T12:00:18+00:00, book20_bid_proxy_usdt=80013, book20_ask_proxy_usdt=71388, funding_indicative=-0.000064, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.50%, turnover=32812599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=85.660000, depth_time=2026-11-10T12:00:35+00:00, book20_bid_proxy_usdt=15394413, book20_ask_proxy_usdt=18326367, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.02%, turnover=635554117. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=0.842500, depth_time=2026-11-10T12:00:32+00:00, book20_bid_proxy_usdt=931020, book20_ask_proxy_usdt=1339396, funding_indicative=0.000093, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.18%, turnover=35016382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=554.150000, depth_time=2026-11-10T12:00:16+00:00, book20_bid_proxy_usdt=17993, book20_ask_proxy_usdt=13893, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.14%, turnover=6032772. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T12:00:01+00:00, last15m_closed_end=2026-11-10T12:00+00:00, prior8high=1154.630000, depth_time=2026-11-10T12:00:22+00:00, book20_bid_proxy_usdt=69430, book20_ask_proxy_usdt=311175, funding_indicative=0.000076, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.14%, turnover=2230001469. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
