# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T09:15:43Z**
- feed_generated_utc: 2026-10-17T09:15:46+00:00
- source_sha256: `0369dbfdb576439a985f8c5a8344f5e1b24042b2ecf5705992548a85b474f383`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T09:15+00:00, close=81679.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T09:00+00:00, close=81682.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-17T08:00+00:00, close=81697, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.944700|-7.45|-4.52|-7.88|12110821|1.03|
|BAT_USDT|0.196990|-3.92|61.91|-4.35|13849269|1.52|
|OP_USDT|0.135210|-3.42|9.73|-3.85|14972296|1.48|
|APT_USDT|0.828900|-3.17|3.54|-3.60|11626454|1.21|
|ARB_USDT|0.188840|-3.12|4.44|-3.55|26831885|0.53|
|FET_USDT|0.194600|-2.50|-10.32|-2.93|12026543|5.14|
|INJ_USDT|8.763000|-2.39|26.46|-2.82|90301781|1.14|
|TAO_USDT|275.680000|-1.76|0.36|-2.19|62354974|2.18|
|FILECOIN_USDT|1.146200|-1.76|7.12|-2.19|24631998|0.87|
|STRK_USDT|0.072800|-1.55|-3.33|-1.98|19483671|4.12|
|FARTCOIN_USDT|0.152380|-1.51|-6.72|-1.94|6844126|0.66|
|SUI_USDT|1.005700|-1.45|-4.90|-1.88|89886600|0.99|
|ENA_USDT|0.197430|-1.25|-8.41|-1.68|37214607|0.51|
|DOT_USDT|1.156700|-1.20|-2.63|-1.63|19540517|0.86|
|ZEC_USDT|1175.520000|-1.05|-3.51|-1.48|1308453104|0.09|
|ICP_USDT|3.006000|-1.05|-0.43|-1.48|7947875|3.33|
|SEI_USDT|0.063640|-1.02|-2.81|-1.45|18651471|1.57|
|ONDO_USDT|0.452600|-0.98|-5.72|-1.41|27513590|2.21|
|XLM_USDT|0.179160|-0.83|-7.02|-1.26|14788551|0.56|
|LTC_USDT|59.400000|-0.76|-6.60|-1.19|8319740|1.68|
|AAVE_USDT|156.100000|-0.75|-8.08|-1.18|25851513|1.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.828900|0.823300|0.828400|0.31|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.188840|0.188080|0.188840|1.17|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.196990|0.198110|0.196990|2.18|Y|Y/N|N/N|Y|N|
|DOT_USDT|1.156700|1.154000|1.156700|1.10|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.197430|0.197040|0.197420|2.32|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.152380|0.151850|0.152380|2.56|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.194600|0.193500|0.194600|1.29|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.146200|1.145200|1.146200|1.08|N|Y/N|N/N|Y|N|
|INJ_USDT|8.763000|8.733000|8.763000|0.58|N|Y/N|N/N|Y|N|
|OP_USDT|0.135210|0.134820|0.135210|1.40|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.072800|0.070660|0.072800|2.68|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.005700|1.004200|1.005700|0.99|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.680000|274.030000|275.710000|0.87|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1175.520000|1160.990000|1175.520000|1.56|N|N/N|Y/Y|Y|N|
|ZRO_USDT|1.944700|1.942800|1.944700|5.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=0.833200, depth_time=2026-10-17T09:15:16+00:00, book20_bid_proxy_usdt=108573, book20_ask_proxy_usdt=135438, funding_indicative=0.000071, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=11626454. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=0.189530, depth_time=2026-10-17T09:15:19+00:00, book20_bid_proxy_usdt=98206, book20_ask_proxy_usdt=52826, funding_indicative=-0.000006, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=26831885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=0.207360, depth_time=2026-10-17T09:15:11+00:00, book20_bid_proxy_usdt=31960, book20_ask_proxy_usdt=33076, funding_indicative=0.000022, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.92%, turnover=13849269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=1.168700, depth_time=2026-10-17T09:15:40+00:00, book20_bid_proxy_usdt=271451, book20_ask_proxy_usdt=216530, funding_indicative=-0.000012, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=19540517. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=0.199230, depth_time=2026-10-17T09:15:38+00:00, book20_bid_proxy_usdt=206207, book20_ask_proxy_usdt=144078, funding_indicative=0.000024, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.25%, turnover=37214607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=0.153490, depth_time=2026-10-17T09:15:31+00:00, book20_bid_proxy_usdt=58643, book20_ask_proxy_usdt=71950, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=6844126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=0.195600, depth_time=2026-10-17T09:15:21+00:00, book20_bid_proxy_usdt=1826198, book20_ask_proxy_usdt=1179576, funding_indicative=0.000100, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=12026543. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=1.175300, depth_time=2026-10-17T09:15:27+00:00, book20_bid_proxy_usdt=668112, book20_ask_proxy_usdt=559708, funding_indicative=0.000017, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=24631998. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=8.946000, depth_time=2026-10-17T09:15:23+00:00, book20_bid_proxy_usdt=278369, book20_ask_proxy_usdt=272906, funding_indicative=0.000280, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=90301781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=0.136980, depth_time=2026-10-17T09:15:12+00:00, book20_bid_proxy_usdt=53025, book20_ask_proxy_usdt=52717, funding_indicative=0.000011, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.42%, turnover=14972296. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=0.072350, depth_time=2026-10-17T09:15:31+00:00, book20_bid_proxy_usdt=183660, book20_ask_proxy_usdt=151895, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.55%, turnover=19483671. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=1.012200, depth_time=2026-10-17T09:15:35+00:00, book20_bid_proxy_usdt=1623559, book20_ask_proxy_usdt=835644, funding_indicative=0.000100, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=89886600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=276.090000, depth_time=2026-10-17T09:15:26+00:00, book20_bid_proxy_usdt=114492, book20_ask_proxy_usdt=48709, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.76%, turnover=62354974. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=1175.780000, depth_time=2026-10-17T09:15:42+00:00, book20_bid_proxy_usdt=521355, book20_ask_proxy_usdt=927232, funding_indicative=0.000040, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=1308453104. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T09:14:59+00:00, last15m_closed_end=2026-10-17T09:15+00:00, prior8high=1.961400, depth_time=2026-10-17T09:15:08+00:00, book20_bid_proxy_usdt=35990, book20_ask_proxy_usdt=44210, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.45%, turnover=12110821. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
