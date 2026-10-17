# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T08:15:44Z**
- feed_generated_utc: 2026-10-17T08:15:48+00:00
- source_sha256: `efe77c696e2e8f13a3ebd6609e6567fa14d615fb9e717309fb2035760168f056`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T08:15+00:00, close=81687, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T08:00+00:00, close=81697, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T08:00+00:00, close=81697, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.955100|-6.95|-4.01|-7.39|12396361|0.51|
|OP_USDT|0.135110|-3.49|9.64|-3.93|14890538|0.74|
|ARB_USDT|0.188180|-3.46|4.08|-3.90|27281521|0.53|
|APT_USDT|0.827300|-3.36|3.34|-3.80|11770709|1.21|
|STRK_USDT|0.071560|-3.23|-4.97|-3.67|20144344|2.79|
|RIVER_USDT|1.092000|-3.01|-7.61|-3.45|5028776|9.16|
|FET_USDT|0.194200|-2.70|-10.50|-3.14|12130459|5.15|
|INJ_USDT|8.790000|-2.09|26.85|-2.53|92904249|3.41|
|TAO_USDT|274.960000|-2.01|0.10|-2.45|64110605|1.09|
|ZEC_USDT|1167.380000|-1.73|-4.18|-2.17|1324097149|0.09|
|ICP_USDT|2.996000|-1.38|-0.76|-1.82|8405385|3.34|
|SEI_USDT|0.063430|-1.35|-3.13|-1.79|19157862|1.58|
|SUI_USDT|1.007100|-1.31|-4.77|-1.75|91628622|0.99|
|FARTCOIN_USDT|0.152760|-1.26|-6.49|-1.70|7174192|0.66|
|FILECOIN_USDT|1.152400|-1.23|7.70|-1.67|24210359|0.87|
|ENA_USDT|0.197550|-1.19|-8.36|-1.63|37999135|0.51|
|DOT_USDT|1.158200|-1.07|-2.50|-1.51|19423420|0.86|
|LTC_USDT|59.360000|-0.83|-6.66|-1.27|8415115|3.37|
|XLM_USDT|0.179360|-0.72|-6.92|-1.16|14716498|0.56|
|ONDO_USDT|0.453900|-0.70|-5.45|-1.14|28184639|2.20|
|LINK_USDT|12.244000|-0.59|-4.41|-1.03|61783571|0.82|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.827300|0.823300|0.827400|1.46|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.188180|0.188080|0.188180|1.26|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.152760|0.151850|0.152810|0.91|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.194200|0.193700|0.194200|0.79|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.152400|1.161900|1.152600|2.13|Y|N/N|N/N|Y|N|
|ICP_USDT|2.996000|2.988000|2.996000|1.88|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.790000|8.818000|8.784000|1.84|Y|N/N|N/N|Y|N|
|OP_USDT|0.135110|0.135350|0.135110|6.10|Y|Y/Y|Y/Y|Y|Y|
|RIVER_USDT|1.092000|1.070000|1.092000|4.03|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.063430|0.063040|0.063390|0.74|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.071560|0.070610|0.071540|1.29|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.007100|1.005500|1.007100|0.90|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|274.960000|274.030000|274.960000|1.42|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1167.380000|1159.990000|1167.020000|0.84|N|N/Y|Y/Y|Y|N|
|ZRO_USDT|1.955100|1.942800|1.955200|1.00|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-17T08:15:02+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=0.842500, depth_time=2026-10-17T08:15:15+00:00, book20_bid_proxy_usdt=108493, book20_ask_proxy_usdt=141148, funding_indicative=0.000064, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.36%, turnover=11770709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T08:15:02+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=0.189960, depth_time=2026-10-17T08:15:14+00:00, book20_bid_proxy_usdt=60618, book20_ask_proxy_usdt=54807, funding_indicative=-0.000019, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.46%, turnover=27281521. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T08:15:03+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=0.154340, depth_time=2026-10-17T08:15:41+00:00, book20_bid_proxy_usdt=70592, book20_ask_proxy_usdt=66976, funding_indicative=0.000100, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.26%, turnover=7174192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T08:15:03+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=0.195600, depth_time=2026-10-17T08:15:22+00:00, book20_bid_proxy_usdt=1833432, book20_ask_proxy_usdt=1106181, funding_indicative=0.000100, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=12130459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T08:15:02+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=1.184600, depth_time=2026-10-17T08:15:43+00:00, book20_bid_proxy_usdt=277763, book20_ask_proxy_usdt=674360, funding_indicative=0.000064, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=24210359. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-17T08:15:03+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=3.031000, depth_time=2026-10-17T08:15:31+00:00, book20_bid_proxy_usdt=1006959, book20_ask_proxy_usdt=824454, funding_indicative=0.000033, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=8405385. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T08:15:02+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=8.953000, depth_time=2026-10-17T08:15:26+00:00, book20_bid_proxy_usdt=207015, book20_ask_proxy_usdt=320577, funding_indicative=0.000234, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=92904249. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-17T08:15:02+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=0.137400, depth_time=2026-10-17T08:15:11+00:00, book20_bid_proxy_usdt=64060, book20_ask_proxy_usdt=56000, funding_indicative=-0.000021, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.49%, turnover=14890538. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T08:15:03+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=1.091000, depth_time=2026-10-17T08:15:19+00:00, book20_bid_proxy_usdt=473142, book20_ask_proxy_usdt=405281, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=5028776. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-17T08:15:03+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=0.064140, depth_time=2026-10-17T08:15:36+00:00, book20_bid_proxy_usdt=204508, book20_ask_proxy_usdt=226597, funding_indicative=0.000100, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=19157862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T08:15:02+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=0.071400, depth_time=2026-10-17T08:15:18+00:00, book20_bid_proxy_usdt=241458, book20_ask_proxy_usdt=240570, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=20144344. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T08:15:02+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=1.012200, depth_time=2026-10-17T08:15:38+00:00, book20_bid_proxy_usdt=848272, book20_ask_proxy_usdt=1548360, funding_indicative=0.000100, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=91628622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T08:15:02+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=276.220000, depth_time=2026-10-17T08:15:28+00:00, book20_bid_proxy_usdt=87219, book20_ask_proxy_usdt=74054, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=64110605. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T08:15:02+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=1174.140000, depth_time=2026-10-17T08:15:31+00:00, book20_bid_proxy_usdt=733068, book20_ask_proxy_usdt=436193, funding_indicative=0.000030, next_funding_utc=2026-10-17T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=1324097149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T08:15:02+00:00, last15m_closed_end=2026-10-17T08:15+00:00, prior8high=1.972100, depth_time=2026-10-17T08:15:08+00:00, book20_bid_proxy_usdt=64058, book20_ask_proxy_usdt=44201, funding_indicative=0.000050, next_funding_utc=2026-10-17T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.95%, turnover=12396361. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
