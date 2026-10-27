# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T06:00:42Z**
- feed_generated_utc: 2026-10-27T06:00:46+00:00
- source_sha256: `5158965f4da92990ce209a731d4271368a9a0817f8bbf74ffc2b0931d747afad`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T06:00+00:00, close=79935.6, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T06:00+00:00, close=79935.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|198.750000|-6.80|1.55|-6.23|125070396|2.52|
|NEAR_USDT|4.446000|-4.48|-9.33|-3.91|98081293|2.25|
|AAVE_USDT|132.150000|-4.15|-10.23|-3.58|23893410|0.76|
|PUMPFUN_USDT|0.004176|-4.15|-6.28|-3.58|21137450|2.40|
|DOT_USDT|0.991100|-3.88|-13.57|-3.31|11117731|1.01|
|FILECOIN_USDT|0.898900|-2.97|-11.17|-2.40|6421432|1.11|
|TIA_USDT|0.526400|-2.80|-13.49|-2.23|17929551|1.90|
|FET_USDT|0.173000|-2.64|-8.46|-2.07|6679578|5.78|
|ONDO_USDT|0.408300|-2.50|-5.61|-1.93|22494009|2.45|
|AVAX_USDT|8.780000|-2.45|-8.17|-1.88|48691773|1.14|
|ZEC_USDT|1221.980000|-2.39|8.60|-1.82|1440337877|0.08|
|WLD_USDT|0.438000|-2.27|-13.49|-1.70|68475212|2.28|
|ARB_USDT|0.167990|-2.27|-14.12|-1.70|20367731|0.59|
|TAO_USDT|249.140000|-2.24|-7.14|-1.67|44671322|0.80|
|PENGU_USDT|0.007451|-2.11|-0.53|-1.54|5446172|2.69|
|SOL_USDT|100.160000|-1.89|-3.77|-1.32|665784248|1.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.150000|131.800000|132.160000|4.16|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167990|0.165970|0.167990|2.71|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.780000|8.656000|8.780000|1.71|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.991100|0.984100|0.991100|0.83|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.173000|0.171100|0.173000|1.12|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.898900|0.888900|0.898900|2.10|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.446000|4.405000|4.446000|1.12|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.408300|0.404900|0.408400|1.27|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007451|0.007397|0.007451|0.65|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004176|0.004134|0.004176|1.66|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|198.750000|196.820000|198.750000|0.82|N|Y/Y|N/N|Y|N|
|TAO_USDT|249.140000|247.340000|249.100000|2.40|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.526400|0.520900|0.526400|1.36|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.438000|0.434300|0.438000|0.81|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1221.980000|1212.160000|1221.960000|1.12|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T06:00:00+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=133.020000, depth_time=2026-10-27T06:00:12+00:00, book20_bid_proxy_usdt=409955, book20_ask_proxy_usdt=468825, funding_indicative=0.000081, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.15%, turnover=23893410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T06:00:00+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=0.167570, depth_time=2026-10-27T06:00:35+00:00, book20_bid_proxy_usdt=72429, book20_ask_proxy_usdt=86780, funding_indicative=0.000038, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=20367731. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T06:00:00+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=8.809000, depth_time=2026-10-27T06:00:28+00:00, book20_bid_proxy_usdt=1072536, book20_ask_proxy_usdt=809350, funding_indicative=-0.000088, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=48691773. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T06:00:00+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=0.994000, depth_time=2026-10-27T06:00:15+00:00, book20_bid_proxy_usdt=793182, book20_ask_proxy_usdt=542279, funding_indicative=-0.000123, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.88%, turnover=11117731. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T06:00:00+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=0.172900, depth_time=2026-10-27T06:00:23+00:00, book20_bid_proxy_usdt=1355444, book20_ask_proxy_usdt=903736, funding_indicative=-0.000015, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=6679578. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T06:00:00+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=0.899800, depth_time=2026-10-27T06:00:17+00:00, book20_bid_proxy_usdt=1010697, book20_ask_proxy_usdt=1430646, funding_indicative=-0.000035, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=6421432. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T06:00:00+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=4.443000, depth_time=2026-10-27T06:00:09+00:00, book20_bid_proxy_usdt=4292106, book20_ask_proxy_usdt=3483411, funding_indicative=0.000023, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.48%, turnover=98081293. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T06:00:00+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=0.408700, depth_time=2026-10-27T06:00:25+00:00, book20_bid_proxy_usdt=2435806, book20_ask_proxy_usdt=3493032, funding_indicative=0.000012, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=22494009. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-27T06:00:01+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=0.007462, depth_time=2026-10-27T06:00:37+00:00, book20_bid_proxy_usdt=214569, book20_ask_proxy_usdt=224822, funding_indicative=0.000028, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=5446172. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T06:00:00+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=0.004177, depth_time=2026-10-27T06:00:14+00:00, book20_bid_proxy_usdt=2205072, book20_ask_proxy_usdt=2718158, funding_indicative=0.000016, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.15%, turnover=21137450. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T06:00:00+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=202.560000, depth_time=2026-10-27T06:00:08+00:00, book20_bid_proxy_usdt=67550, book20_ask_proxy_usdt=87619, funding_indicative=-0.000125, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.80%, turnover=125070396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T06:00:00+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=249.550000, depth_time=2026-10-27T06:00:36+00:00, book20_bid_proxy_usdt=135116, book20_ask_proxy_usdt=113903, funding_indicative=0.000028, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=44671322. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T06:00:00+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=0.531100, depth_time=2026-10-27T06:00:22+00:00, book20_bid_proxy_usdt=332608, book20_ask_proxy_usdt=327283, funding_indicative=0.000024, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.80%, turnover=17929551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T06:00:00+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=0.438500, depth_time=2026-10-27T06:00:33+00:00, book20_bid_proxy_usdt=3751892, book20_ask_proxy_usdt=3977493, funding_indicative=-0.000235, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=68475212. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-27T06:00:00+00:00, last15m_closed_end=2026-10-27T06:00+00:00, prior8high=1229.280000, depth_time=2026-10-27T06:00:31+00:00, book20_bid_proxy_usdt=750810, book20_ask_proxy_usdt=271718, funding_indicative=0.000074, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=1440337877. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
