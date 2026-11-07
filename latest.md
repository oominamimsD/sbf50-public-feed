# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T03:00:42Z**
- feed_generated_utc: 2026-11-07T03:00:44+00:00
- source_sha256: `87aacb91d6e8517d4e5050f5938615c8fa98afa9e46bcbbe64b0da6aa233d2bb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T03:00+00:00, close=76008, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T03:00+00:00, close=76008, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.148100|-20.37|-44.23|-20.60|35102086|6.77|
|CYBER_USDT|0.312400|-18.79|14.34|-19.02|6183581|3.20|
|TRUMPOFFICIAL_USDT|1.195000|-4.70|-23.98|-4.93|10790490|8.37|
|PUMPFUN_USDT|0.003926|-4.24|-4.40|-4.47|12215144|2.55|
|DOT_USDT|0.904600|-3.46|-6.66|-3.69|6830626|1.11|
|ENA_USDT|0.164150|-3.14|-13.55|-3.37|30287526|0.61|
|OP_USDT|0.104290|-2.82|-3.62|-3.05|5748539|0.96|
|ANTHROPIC_USDT|1393.810000|-2.61|-16.85|-2.84|7236957|1.65|
|ARB_USDT|0.164030|-2.49|1.17|-2.72|25894544|1.22|
|WLD_USDT|0.341200|-2.23|-17.16|-2.46|29413218|2.93|
|FARTCOIN_USDT|0.118090|-2.16|-1.83|-2.39|12177629|0.85|
|ONDO_USDT|0.369000|-1.93|-7.61|-2.16|10795407|2.71|
|ADA_USDT|0.184300|-1.91|-4.30|-2.14|26709668|5.43|
|AAVE_USDT|129.500000|-1.89|3.07|-2.12|17499177|0.77|
|HBAR_USDT|0.067170|-1.79|-6.51|-2.02|5070430|2.98|
|XLM_USDT|0.152590|-1.59|-11.40|-1.82|23168503|0.66|
|XRP_USDT|1.168000|-1.51|-6.89|-1.74|342014134|0.86|
|AVAX_USDT|8.295000|-1.39|-0.63|-1.62|12272111|1.21|
|LINK_USDT|10.793000|-1.29|-2.34|-1.52|118075369|0.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.500000|129.970000|129.520000|1.08|N|Y/Y|N/N|Y|N|
|ADA_USDT|0.184300|0.183900|0.184300|0.28|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1393.810000|1333.530000|1393.650000|2.56|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164030|0.164120|0.164050|2.24|Y|Y/Y|N/N|Y|N|
|CYBER_USDT|0.312400|0.310400|0.312400|0.90|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.904600|0.903700|0.904500|0.72|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.164150|0.163570|0.164150|0.83|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118090|0.117970|0.118090|2.20|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.067170|0.067190|0.067160|1.62|Y|Y/Y|Y/Y|Y|Y|
|ONDO_USDT|0.369000|0.370100|0.369000|3.86|Y|Y/Y|Y/Y|Y|Y|
|OP_USDT|0.104290|0.104420|0.104270|2.34|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.003926|0.003912|0.003926|1.48|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.195000|1.192000|1.195000|0.42|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.148100|0.135500|0.148100|0.71|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.341200|0.341300|0.341200|1.79|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=131.020000, depth_time=2026-11-07T03:00:31+00:00, book20_bid_proxy_usdt=684625, book20_ask_proxy_usdt=728612, funding_indicative=0.000054, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=17499177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=0.185600, depth_time=2026-11-07T03:00:36+00:00, book20_bid_proxy_usdt=9146722, book20_ask_proxy_usdt=8612354, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=26709668. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=1357.240000, depth_time=2026-11-07T03:00:25+00:00, book20_bid_proxy_usdt=14857, book20_ask_proxy_usdt=12570, funding_indicative=0.000050, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=7236957. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=0.165540, depth_time=2026-11-07T03:00:27+00:00, book20_bid_proxy_usdt=76585, book20_ask_proxy_usdt=74439, funding_indicative=-0.000038, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.49%, turnover=25894544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CYBER_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=0.327600, depth_time=2026-11-07T03:00:08+00:00, book20_bid_proxy_usdt=150208, book20_ask_proxy_usdt=179916, funding_indicative=-0.002000, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-18.79%, turnover=6183581. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=0.910000, depth_time=2026-11-07T03:00:14+00:00, book20_bid_proxy_usdt=790209, book20_ask_proxy_usdt=451607, funding_indicative=0.000060, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.46%, turnover=6830626. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=0.164840, depth_time=2026-11-07T03:00:19+00:00, book20_bid_proxy_usdt=2709151, book20_ask_proxy_usdt=121250, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.14%, turnover=30287526. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=0.119090, depth_time=2026-11-07T03:00:32+00:00, book20_bid_proxy_usdt=77250, book20_ask_proxy_usdt=76569, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.16%, turnover=12177629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=0.067850, depth_time=2026-11-07T03:00:37+00:00, book20_bid_proxy_usdt=687085, book20_ask_proxy_usdt=635532, funding_indicative=-0.000072, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=5070430. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=0.372500, depth_time=2026-11-07T03:00:33+00:00, book20_bid_proxy_usdt=1633352, book20_ask_proxy_usdt=1613971, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=10795407. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=0.105700, depth_time=2026-11-07T03:00:21+00:00, book20_bid_proxy_usdt=57174, book20_ask_proxy_usdt=138259, funding_indicative=-0.000034, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=5748539. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=0.003956, depth_time=2026-11-07T03:00:14+00:00, book20_bid_proxy_usdt=2539589, book20_ask_proxy_usdt=2475085, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.24%, turnover=12215144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=1.206000, depth_time=2026-11-07T03:00:10+00:00, book20_bid_proxy_usdt=1255003, book20_ask_proxy_usdt=1652827, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.70%, turnover=10790490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=0.151100, depth_time=2026-11-07T03:00:07+00:00, book20_bid_proxy_usdt=155534, book20_ask_proxy_usdt=131352, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-20.37%, turnover=35102086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T03:00:02+00:00, last15m_closed_end=2026-11-07T03:00+00:00, prior8high=0.344300, depth_time=2026-11-07T03:00:27+00:00, book20_bid_proxy_usdt=3668396, book20_ask_proxy_usdt=2750215, funding_indicative=-0.000217, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=29413218. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
