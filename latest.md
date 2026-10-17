# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T05:45:41Z**
- feed_generated_utc: 2026-10-17T05:45:44+00:00
- source_sha256: `dbe344b77eeec18e10b96a0d8caee78a97c6828b86d4e0426e0eb71e3f7b958b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T05:45+00:00, close=81562.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T05:00+00:00, close=81500.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.965100|-6.48|-3.52|-6.77|14533395|0.51|
|STRK_USDT|0.070650|-4.46|-6.18|-4.75|21697706|1.42|
|BAT_USDT|0.196760|-4.03|61.72|-4.32|14654015|3.56|
|RIVER_USDT|1.081000|-3.99|-8.54|-4.28|5040467|9.26|
|ARB_USDT|0.190140|-2.46|5.16|-2.75|32993105|0.53|
|FET_USDT|0.194800|-2.40|-10.23|-2.69|11638653|5.14|
|ZEC_USDT|1160.770000|-2.29|-4.72|-2.58|1388522182|0.09|
|OP_USDT|0.137200|-2.00|11.34|-2.29|14629913|0.73|
|TAO_USDT|275.180000|-1.93|0.18|-2.22|75162500|1.09|
|APT_USDT|0.840700|-1.79|5.02|-2.08|12477075|1.19|
|FARTCOIN_USDT|0.153090|-1.05|-6.29|-1.34|6989461|1.31|
|AAVE_USDT|155.730000|-0.98|-8.30|-1.27|28647290|0.64|
|SUI_USDT|1.010600|-0.97|-4.44|-1.26|93965297|0.99|
|AVAX_USDT|9.995000|-0.87|-1.93|-1.16|119249370|1.00|
|XLM_USDT|0.179360|-0.72|-6.92|-1.01|14608158|0.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.730000|155.550000|155.740000|1.47|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.840700|0.837900|0.840700|1.41|N|N/Y|N/N|Y|N|
|ARB_USDT|0.190140|0.188880|0.190140|2.39|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|9.995000|9.968000|9.995000|1.06|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.196760|0.195330|0.196760|2.58|N|Y/N|N/N|Y|N|
|FARTCOIN_USDT|0.153090|0.153000|0.153170|0.24|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.194800|0.194100|0.194800|2.12|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.137200|0.137560|0.137300|1.51|Y|N/N|Y/Y|Y|N|
|RIVER_USDT|1.081000|1.071000|1.081000|3.63|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.070650|0.070260|0.070750|0.24|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.010600|1.009800|1.010600|0.90|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.180000|274.400000|275.160000|0.59|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.179360|0.179310|0.179360|3.51|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1160.770000|1150.950000|1161.470000|0.96|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.965100|1.960500|1.965100|0.89|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=156.680000, depth_time=2026-10-17T05:45:33+00:00, book20_bid_proxy_usdt=390560, book20_ask_proxy_usdt=409856, funding_indicative=0.000040, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=28647290. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=0.856200, depth_time=2026-10-17T05:45:29+00:00, book20_bid_proxy_usdt=163734, book20_ask_proxy_usdt=108545, funding_indicative=0.000058, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=12477075. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=0.192330, depth_time=2026-10-17T05:45:16+00:00, book20_bid_proxy_usdt=57089, book20_ask_proxy_usdt=52238, funding_indicative=-0.000018, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.46%, turnover=32993105. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=10.037000, depth_time=2026-10-17T05:45:38+00:00, book20_bid_proxy_usdt=1479308, book20_ask_proxy_usdt=739851, funding_indicative=0.000054, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.87%, turnover=119249370. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=0.203660, depth_time=2026-10-17T05:45:12+00:00, book20_bid_proxy_usdt=27995, book20_ask_proxy_usdt=23836, funding_indicative=-0.000058, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.03%, turnover=14654015. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=0.154160, depth_time=2026-10-17T05:45:31+00:00, book20_bid_proxy_usdt=56067, book20_ask_proxy_usdt=67723, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.05%, turnover=6989461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=0.196500, depth_time=2026-10-17T05:45:19+00:00, book20_bid_proxy_usdt=1781762, book20_ask_proxy_usdt=1382900, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=11638653. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=0.140730, depth_time=2026-10-17T05:45:24+00:00, book20_bid_proxy_usdt=52395, book20_ask_proxy_usdt=41950, funding_indicative=-0.000054, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=14629913. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=1.090000, depth_time=2026-10-17T05:45:13+00:00, book20_bid_proxy_usdt=498389, book20_ask_proxy_usdt=467783, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.99%, turnover=5040467. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=0.072130, depth_time=2026-10-17T05:45:09+00:00, book20_bid_proxy_usdt=231072, book20_ask_proxy_usdt=287809, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=21697706. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=1.019400, depth_time=2026-10-17T05:45:35+00:00, book20_bid_proxy_usdt=1053050, book20_ask_proxy_usdt=1218895, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.97%, turnover=93965297. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=277.190000, depth_time=2026-10-17T05:45:26+00:00, book20_bid_proxy_usdt=94060, book20_ask_proxy_usdt=146761, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=75162500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=0.180460, depth_time=2026-10-17T05:45:40+00:00, book20_bid_proxy_usdt=362802, book20_ask_proxy_usdt=193768, funding_indicative=0.000034, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.72%, turnover=14608158. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=1168.180000, depth_time=2026-10-17T05:45:21+00:00, book20_bid_proxy_usdt=308215, book20_ask_proxy_usdt=266586, funding_indicative=0.000014, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.29%, turnover=1388522182. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T05:45:01+00:00, last15m_closed_end=2026-10-17T05:45+00:00, prior8high=1.992900, depth_time=2026-10-17T05:45:07+00:00, book20_bid_proxy_usdt=56398, book20_ask_proxy_usdt=34787, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.48%, turnover=14533395. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
