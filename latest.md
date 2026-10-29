# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T20:00:42Z**
- feed_generated_utc: 2026-10-29T20:00:44+00:00
- source_sha256: `ac0dab63c598875cb82ac24c381777a97d0c8928aa089eddb6b3deab44555b21`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T20:00+00:00, close=80810, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-29T20:00+00:00, close=80810, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T20:00+00:00, close=80810, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.450300|-14.42|-18.97|-14.01|9693473|0.69|
|Q_USDT|0.035520|-11.70|-72.43|-11.29|23446337|2.81|
|PENGU_USDT|0.007728|-4.95|0.00|-4.54|6662843|1.29|
|EVAA_USDT|1.129600|-4.72|117.23|-4.31|11529553|7.08|
|FET_USDT|0.177900|-2.94|-3.99|-2.53|9114597|5.62|
|SOL_USDT|99.780000|-2.78|-4.58|-2.37|622941616|1.00|
|NEAR_USDT|4.401000|-2.63|-10.98|-2.22|111268029|2.27|
|QNT_USDT|191.240000|-2.54|0.27|-2.13|61445942|0.52|
|TRUMPOFFICIAL_USDT|1.667000|-2.22|-4.41|-1.81|6030229|6.00|
|APT_USDT|0.671800|-2.16|-13.00|-1.75|9448621|1.49|
|XRP_USDT|1.281600|-2.13|-3.02|-1.72|296022252|0.78|
|FILECOIN_USDT|0.892000|-2.13|-7.27|-1.72|9175781|1.12|
|ARB_USDT|0.168190|-2.08|-8.41|-1.67|24272724|0.59|
|DOT_USDT|0.984200|-1.92|-12.46|-1.51|10117027|1.02|
|SEI_USDT|0.051430|-1.88|-11.43|-1.47|5334696|1.94|
|WLD_USDT|0.417700|-1.87|-21.49|-1.46|82331300|2.39|
|HBAR_USDT|0.073120|-1.76|-8.72|-1.35|14842679|1.37|
|OP_USDT|0.110020|-1.67|-8.20|-1.26|6546489|0.91|
|FARTCOIN_USDT|0.128820|-1.55|-9.81|-1.14|9928856|0.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.671800|0.666900|0.671800|0.52|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.168190|0.167330|0.168190|0.29|N|Y/Y|Y/N|N|N|
|BTW_USDT|1.450300|1.454400|1.450300|0.79|N|Y/Y|Y/Y|N|N|
|DOT_USDT|0.984200|0.977200|0.984200|1.19|N|Y/Y|Y/Y|N|N|
|EVAA_USDT|1.129600|1.094400|1.129600|0.52|N|Y/Y|N/N|N|N|
|FET_USDT|0.177900|0.176800|0.177900|0.54|N|Y/Y|Y/N|N|N|
|FILECOIN_USDT|0.892000|0.887600|0.892000|0.02|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|4.401000|4.381000|4.401000|0.51|N|Y/Y|Y/Y|N|N|
|PENGU_USDT|0.007728|0.007696|0.007723|0.13|N|Y/Y|N/N|N|N|
|QNT_USDT|191.240000|188.850000|191.240000|0.31|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.035520|0.035730|0.035520|1.09|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.051430|0.051390|0.051430|0.73|N|Y/Y|Y/Y|N|N|
|SOL_USDT|99.780000|100.080000|99.780000|1.29|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.667000|1.654000|1.667000|1.55|N|Y/Y|Y/Y|N|N|
|XRP_USDT|1.281600|1.278000|1.281500|0.88|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-29T20:00:01+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=0.681100, depth_time=2026-10-29T20:00:29+00:00, book20_bid_proxy_usdt=179928, book20_ask_proxy_usdt=176198, funding_indicative=0.000062, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=9448621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-29T20:00:00+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=0.170370, depth_time=2026-10-29T20:00:36+00:00, book20_bid_proxy_usdt=54009, book20_ask_proxy_usdt=52496, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=24272724. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T20:00:00+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=1.539400, depth_time=2026-10-29T20:00:08+00:00, book20_bid_proxy_usdt=23779, book20_ask_proxy_usdt=23379, funding_indicative=0.000011, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=4, 24h_change=-14.42%, turnover=9693473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-29T20:00:01+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=0.994400, depth_time=2026-10-29T20:00:38+00:00, book20_bid_proxy_usdt=512551, book20_ask_proxy_usdt=372010, funding_indicative=0.000056, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=10117027. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T20:00:00+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=1.170100, depth_time=2026-10-29T20:00:12+00:00, book20_bid_proxy_usdt=17401, book20_ask_proxy_usdt=11560, funding_indicative=0.000050, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.72%, turnover=11529553. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-29T20:00:01+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=0.180400, depth_time=2026-10-29T20:00:14+00:00, book20_bid_proxy_usdt=1435700, book20_ask_proxy_usdt=837118, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=9114597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-29T20:00:01+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=0.902300, depth_time=2026-10-29T20:00:33+00:00, book20_bid_proxy_usdt=1065277, book20_ask_proxy_usdt=1273498, funding_indicative=0.000053, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=9175781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T20:00:00+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=4.509000, depth_time=2026-10-29T20:00:21+00:00, book20_bid_proxy_usdt=3903706, book20_ask_proxy_usdt=2042781, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.63%, turnover=111268029. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-29T20:00:01+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=0.007887, depth_time=2026-10-29T20:00:11+00:00, book20_bid_proxy_usdt=180169, book20_ask_proxy_usdt=123975, funding_indicative=0.000050, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.95%, turnover=6662843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-29T20:00:00+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=192.730000, depth_time=2026-10-29T20:00:24+00:00, book20_bid_proxy_usdt=68316, book20_ask_proxy_usdt=76850, funding_indicative=-0.000133, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=61445942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T20:00:00+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=0.038560, depth_time=2026-10-29T20:00:10+00:00, book20_bid_proxy_usdt=48135, book20_ask_proxy_usdt=102810, funding_indicative=0.000036, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.70%, turnover=23446337. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-29T20:00:01+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=0.052230, depth_time=2026-10-29T20:00:40+00:00, book20_bid_proxy_usdt=395941, book20_ask_proxy_usdt=244095, funding_indicative=0.000062, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=5334696. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-29T20:00:00+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=101.180000, depth_time=2026-10-29T20:00:19+00:00, book20_bid_proxy_usdt=19667219, book20_ask_proxy_usdt=20336682, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.78%, turnover=622941616. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-29T20:00:01+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=1.685000, depth_time=2026-10-29T20:00:25+00:00, book20_bid_proxy_usdt=1040644, book20_ask_proxy_usdt=1114758, funding_indicative=-0.000030, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=6030229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-10-29T20:00:00+00:00, last15m_closed_end=2026-10-29T20:00+00:00, prior8high=1.294800, depth_time=2026-10-29T20:00:32+00:00, book20_bid_proxy_usdt=1918078, book20_ask_proxy_usdt=3010433, funding_indicative=0.000070, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=296022252. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
