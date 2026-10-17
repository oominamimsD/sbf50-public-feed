# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T06:00:42Z**
- feed_generated_utc: 2026-10-17T06:00:45+00:00
- source_sha256: `d542405461974947316fe7902644f5f9b102baa0eff0878a0fc48c13a1fd0644`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T06:00+00:00, close=81542.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T06:00+00:00, close=81542.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.968100|-9.05|-3.37|-9.30|13940630|0.51|
|STRK_USDT|0.070890|-7.11|-5.86|-7.36|21515043|1.41|
|FET_USDT|0.194600|-4.88|-10.32|-5.13|11654496|5.14|
|BAT_USDT|0.197160|-4.62|62.05|-4.87|14198894|1.52|
|ARB_USDT|0.189940|-3.69|5.05|-3.94|32100728|0.53|
|SEI_USDT|0.064060|-3.11|-2.16|-3.36|19155830|1.56|
|APT_USDT|0.839800|-3.08|4.90|-3.33|11683987|1.19|
|AAVE_USDT|155.760000|-2.74|-8.29|-2.99|27366400|0.64|
|OP_USDT|0.137120|-2.73|11.28|-2.98|14535949|0.73|
|ENA_USDT|0.199350|-2.50|-7.52|-2.75|38398876|0.50|
|FARTCOIN_USDT|0.153490|-2.31|-6.04|-2.56|6821277|1.96|
|ZEC_USDT|1162.200000|-2.17|-4.61|-2.42|1345726658|0.09|
|HBAR_USDT|0.083870|-1.95|-7.69|-2.20|18088606|1.19|
|LINK_USDT|12.288000|-1.82|-4.06|-2.07|62623265|0.81|
|TAO_USDT|276.000000|-1.64|0.48|-1.89|70209406|1.09|
|ADA_USDT|0.224200|-1.45|-5.56|-1.70|37109201|4.46|
|LTC_USDT|59.640000|-1.43|-6.22|-1.68|8670535|1.68|
|XRP_USDT|1.309300|-1.37|-5.28|-1.62|336014415|0.76|
|SILVER_USDT|57.080000|-1.34|-6.39|-1.59|176852960|3.50|
|DOGE_USDT|0.080480|-1.16|-4.86|-1.41|119662349|1.24|
|SUI_USDT|1.011200|-0.91|-4.38|-1.16|92446431|0.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.760000|155.650000|155.760000|1.01|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.839800|0.837900|0.839800|0.31|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189940|0.189070|0.189940|0.73|N|Y/Y|Y/N|Y|N|
|BAT_USDT|0.197160|0.194790|0.197160|1.76|N|Y/N|N/N|Y|N|
|ENA_USDT|0.199350|0.197750|0.199350|0.60|N|N/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.153490|0.153000|0.153510|0.20|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.194600|0.194100|0.194600|4.56|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.083870|0.083680|0.083870|0.32|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|12.288000|12.261000|12.288000|0.61|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.137120|0.137080|0.137160|1.47|N|Y/N|Y/Y|Y|N|
|SEI_USDT|0.064060|0.063830|0.064060|0.99|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.070890|0.070680|0.070890|0.75|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|276.000000|274.400000|276.070000|0.88|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1162.200000|1150.950000|1162.410000|0.58|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.968100|1.960500|1.968100|0.18|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=156.680000, depth_time=2026-10-17T06:00:23+00:00, book20_bid_proxy_usdt=862037, book20_ask_proxy_usdt=226048, funding_indicative=0.000039, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=27366400. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=0.856200, depth_time=2026-10-17T06:00:21+00:00, book20_bid_proxy_usdt=149674, book20_ask_proxy_usdt=120274, funding_indicative=0.000065, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.08%, turnover=11683987. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=0.192330, depth_time=2026-10-17T06:00:16+00:00, book20_bid_proxy_usdt=71489, book20_ask_proxy_usdt=66721, funding_indicative=-0.000016, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=32100728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=0.203660, depth_time=2026-10-17T06:00:14+00:00, book20_bid_proxy_usdt=21970, book20_ask_proxy_usdt=15531, funding_indicative=-0.000063, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.62%, turnover=14198894. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=0.200460, depth_time=2026-10-17T06:00:29+00:00, book20_bid_proxy_usdt=208777, book20_ask_proxy_usdt=156782, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=38398876. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=0.154160, depth_time=2026-10-17T06:00:30+00:00, book20_bid_proxy_usdt=60448, book20_ask_proxy_usdt=69606, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=6821277. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=0.196300, depth_time=2026-10-17T06:00:11+00:00, book20_bid_proxy_usdt=1573868, book20_ask_proxy_usdt=1352147, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.88%, turnover=11654496. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=0.084240, depth_time=2026-10-17T06:00:36+00:00, book20_bid_proxy_usdt=1120375, book20_ask_proxy_usdt=1178958, funding_indicative=0.000052, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=18088606. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=12.368000, depth_time=2026-10-17T06:00:37+00:00, book20_bid_proxy_usdt=841415, book20_ask_proxy_usdt=364833, funding_indicative=0.000003, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=62623265. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=0.140730, depth_time=2026-10-17T06:00:26+00:00, book20_bid_proxy_usdt=39021, book20_ask_proxy_usdt=77338, funding_indicative=-0.000053, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=14535949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=0.064750, depth_time=2026-10-17T06:00:18+00:00, book20_bid_proxy_usdt=220480, book20_ask_proxy_usdt=208813, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=19155830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=0.072130, depth_time=2026-10-17T06:00:09+00:00, book20_bid_proxy_usdt=510754, book20_ask_proxy_usdt=248020, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.11%, turnover=21515043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=277.150000, depth_time=2026-10-17T06:00:42+00:00, book20_bid_proxy_usdt=68570, book20_ask_proxy_usdt=84902, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.64%, turnover=70209406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=1168.180000, depth_time=2026-10-17T06:00:34+00:00, book20_bid_proxy_usdt=1207479, book20_ask_proxy_usdt=145123, funding_indicative=0.000012, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=1345726658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T06:00:02+00:00, last15m_closed_end=2026-10-17T06:00+00:00, prior8high=1.992900, depth_time=2026-10-17T06:00:07+00:00, book20_bid_proxy_usdt=42655, book20_ask_proxy_usdt=40408, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.05%, turnover=13940630. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
