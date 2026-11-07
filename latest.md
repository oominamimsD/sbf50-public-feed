# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T01:30:38Z**
- feed_generated_utc: 2026-11-07T01:30:39+00:00
- source_sha256: `eae8fa13126e3c5e6ffd49345c7d04e0ff9328fd0f7451963a50d6597c5bb421`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T01:30+00:00, close=75867.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T01:00+00:00, close=75871, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.141700|-25.42|-46.64|-25.46|34712105|7.04|
|CYBER_USDT|0.318700|-9.97|16.65|-10.01|6723683|3.14|
|ANTHROPIC_USDT|1340.460000|-6.34|-20.04|-6.38|7287867|1.86|
|DOT_USDT|0.905100|-3.41|-6.61|-3.45|6826789|1.10|
|TRUMPOFFICIAL_USDT|1.200000|-3.38|-23.66|-3.42|11668056|8.34|
|PUMPFUN_USDT|0.003914|-3.23|-4.69|-3.27|12472913|2.56|
|APT_USDT|0.602500|-2.41|-4.01|-2.45|5068203|1.66|
|ARB_USDT|0.164480|-2.22|1.45|-2.26|26425219|0.61|
|OP_USDT|0.104950|-2.20|-3.01|-2.24|5809332|0.95|
|ENA_USDT|0.163850|-2.18|-13.70|-2.22|31558579|0.61|
|ADA_USDT|0.184400|-1.96|-4.25|-2.00|27513084|5.42|
|ONDO_USDT|0.371000|-1.46|-7.11|-1.50|11193892|2.69|
|FARTCOIN_USDT|0.118510|-1.26|-1.48|-1.30|12729578|0.84|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.184400|0.183700|0.184400|0.17|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1340.460000|1322.000000|1340.460000|0.07|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.602500|0.602100|0.602500|0.53|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164480|0.164290|0.164480|0.38|N|Y/Y|N/N|Y|N|
|CYBER_USDT|0.318700|0.316100|0.318700|1.16|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.905100|0.906500|0.905000|0.51|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.163850|0.163260|0.163850|1.02|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118510|0.117630|0.118510|0.18|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.371000|0.369900|0.371000|0.43|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.104950|0.104850|0.104950|0.58|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003914|0.003882|0.003914|0.05|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.200000|1.196000|1.200000|1.28|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.141700|0.130700|0.141700|0.59|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T01:29:59+00:00, last15m_closed_end=2026-11-07T01:30+00:00, prior8high=0.184900, depth_time=2026-11-07T01:30:32+00:00, book20_bid_proxy_usdt=11253062, book20_ask_proxy_usdt=9295887, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=27513084. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-07T01:29:59+00:00, last15m_closed_end=2026-11-07T01:30+00:00, prior8high=1354.930000, depth_time=2026-11-07T01:30:11+00:00, book20_bid_proxy_usdt=5106, book20_ask_proxy_usdt=14375, funding_indicative=0.000050, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.34%, turnover=7287867. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-11-07T01:29:59+00:00, last15m_closed_end=2026-11-07T01:30+00:00, prior8high=0.606000, depth_time=2026-11-07T01:30:20+00:00, book20_bid_proxy_usdt=237438, book20_ask_proxy_usdt=156248, funding_indicative=0.000029, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.41%, turnover=5068203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T01:29:59+00:00, last15m_closed_end=2026-11-07T01:30+00:00, prior8high=0.165910, depth_time=2026-11-07T01:30:23+00:00, book20_bid_proxy_usdt=92025, book20_ask_proxy_usdt=88565, funding_indicative=0.000014, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.22%, turnover=26425219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CYBER_USDT: quote_utc=2026-11-07T01:29:59+00:00, last15m_closed_end=2026-11-07T01:30+00:00, prior8high=0.340600, depth_time=2026-11-07T01:30:08+00:00, book20_bid_proxy_usdt=131856, book20_ask_proxy_usdt=123607, funding_indicative=-0.002288, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.97%, turnover=6723683. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T01:29:59+00:00, last15m_closed_end=2026-11-07T01:30+00:00, prior8high=0.916800, depth_time=2026-11-07T01:30:14+00:00, book20_bid_proxy_usdt=557025, book20_ask_proxy_usdt=387274, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.41%, turnover=6826789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T01:29:59+00:00, last15m_closed_end=2026-11-07T01:30+00:00, prior8high=0.164540, depth_time=2026-11-07T01:30:22+00:00, book20_bid_proxy_usdt=159928, book20_ask_proxy_usdt=225488, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.18%, turnover=31558579. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T01:29:59+00:00, last15m_closed_end=2026-11-07T01:30+00:00, prior8high=0.118900, depth_time=2026-11-07T01:30:34+00:00, book20_bid_proxy_usdt=78222, book20_ask_proxy_usdt=81263, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.26%, turnover=12729578. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T01:29:59+00:00, last15m_closed_end=2026-11-07T01:30+00:00, prior8high=0.372400, depth_time=2026-11-07T01:30:31+00:00, book20_bid_proxy_usdt=1553206, book20_ask_proxy_usdt=1253788, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.46%, turnover=11193892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-07T01:29:59+00:00, last15m_closed_end=2026-11-07T01:30+00:00, prior8high=0.105740, depth_time=2026-11-07T01:30:27+00:00, book20_bid_proxy_usdt=116766, book20_ask_proxy_usdt=108804, funding_indicative=-0.000010, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=5809332. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T01:29:59+00:00, last15m_closed_end=2026-11-07T01:30+00:00, prior8high=0.003941, depth_time=2026-11-07T01:30:15+00:00, book20_bid_proxy_usdt=2302340, book20_ask_proxy_usdt=2209456, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=12472913. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T01:29:59+00:00, last15m_closed_end=2026-11-07T01:30+00:00, prior8high=1.210000, depth_time=2026-11-07T01:30:15+00:00, book20_bid_proxy_usdt=1539077, book20_ask_proxy_usdt=1437943, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.38%, turnover=11668056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T01:29:59+00:00, last15m_closed_end=2026-11-07T01:30+00:00, prior8high=0.145700, depth_time=2026-11-07T01:30:07+00:00, book20_bid_proxy_usdt=175239, book20_ask_proxy_usdt=105630, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-25.42%, turnover=34712105. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
