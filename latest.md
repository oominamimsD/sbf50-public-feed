# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-22T00:15:52Z**
- feed_generated_utc: 2026-10-22T00:15:58+00:00
- source_sha256: `b056f9554aa7630c084bb65fd9e84a8e1a68204a999da4cb0493eb3bc52a4e75`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.11 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-22T00:15+00:00, close=84231.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-22T00:00+00:00, close=84050, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-22T00:00+00:00, close=84050, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IOST_USDT|0.000955|-34.79|19.28|-34.48|15074401|3.15|
|DOOD_USDT|0.002320|-18.42|63.61|-18.11|9102078|4.31|
|BR_USDT|0.485730|-10.30|19.12|-9.99|14359607|0.41|
|AKE_USDT|0.024071|-9.81|-6.99|-9.50|10882924|2.49|
|STRK_USDT|0.057440|-7.30|-25.57|-6.99|24261865|1.74|
|ZRO_USDT|1.955600|-6.75|3.25|-6.44|7289497|0.51|
|TIA_USDT|0.600900|-4.99|12.63|-4.68|40008240|3.33|
|ARB_USDT|0.189200|-3.76|3.87|-3.45|31642944|0.53|
|ICP_USDT|2.893000|-2.46|-3.47|-2.15|5624947|3.46|
|DOT_USDT|1.153100|-2.27|2.54|-1.96|17043560|1.74|
|AVAX_USDT|9.702000|-2.15|-1.17|-1.84|157132886|2.06|
|FET_USDT|0.196300|-2.14|-3.72|-1.83|7543180|5.09|
|LDO_USDT|0.406900|-1.99|0.27|-1.68|5221870|2.46|
|INJ_USDT|8.599000|-1.81|12.56|-1.50|50467392|1.16|
|OP_USDT|0.129550|-1.78|-6.35|-1.47|6810900|0.77|
|AAVE_USDT|155.750000|-1.74|-0.08|-1.43|131755227|0.64|
|TAO_USDT|272.930000|-1.65|1.85|-1.34|61499406|1.10|
|DOGE_USDT|0.082120|-1.59|0.17|-1.28|83085633|1.22|
|APT_USDT|0.823400|-1.46|4.13|-1.15|8035425|1.22|
|UNI_USDT|7.512000|-1.41|5.15|-1.10|26356159|1.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.024071|0.023696|0.024071|0.50|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.189200|0.187540|0.189200|2.73|N|Y/Y|Y/N|N|N|
|AVAX_USDT|9.702000|9.639000|9.702000|1.05|N|Y/Y|Y/N|N|N|
|BR_USDT|0.485730|0.479330|0.485730|0.53|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002320|0.002241|0.002315|0.98|N|Y/Y|N/N|N|N|
|DOT_USDT|1.153100|1.139000|1.153100|0.99|N|Y/Y|Y/N|N|N|
|FET_USDT|0.196300|0.195000|0.196300|0.91|N|Y/Y|N/N|N|N|
|ICP_USDT|2.893000|2.880000|2.894000|2.63|N|Y/Y|Y/N|N|N|
|INJ_USDT|8.599000|8.575000|8.600000|1.32|N|Y/Y|Y/Y|N|N|
|IOST_USDT|0.000955|0.000984|0.000956|4.51|Y|Y/Y|Y/N|N|N|
|LDO_USDT|0.406900|0.402400|0.406900|0.36|N|Y/Y|N/N|N|N|
|OP_USDT|0.129550|0.128270|0.129550|0.54|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.057440|0.057210|0.057440|0.40|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.600900|0.595900|0.600700|0.84|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.955600|1.932700|1.955600|0.95|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=0.025019, depth_time=2026-10-22T00:15:16+00:00, book20_bid_proxy_usdt=24120, book20_ask_proxy_usdt=12178, funding_indicative=0.000050, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.81%, turnover=10882924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=0.193600, depth_time=2026-10-22T00:15:30+00:00, book20_bid_proxy_usdt=55678, book20_ask_proxy_usdt=79603, funding_indicative=0.000039, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.76%, turnover=31642944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=9.826000, depth_time=2026-10-22T00:15:38+00:00, book20_bid_proxy_usdt=1511179, book20_ask_proxy_usdt=950771, funding_indicative=0.000029, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=157132886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=0.502240, depth_time=2026-10-22T00:15:13+00:00, book20_bid_proxy_usdt=2967, book20_ask_proxy_usdt=3996, funding_indicative=-0.000248, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.30%, turnover=14359607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=0.002499, depth_time=2026-10-22T00:15:11+00:00, book20_bid_proxy_usdt=219079, book20_ask_proxy_usdt=166799, funding_indicative=-0.000131, next_funding_utc=2026-10-22T01:00:00+00:00, funding_cycle_h=1, 24h_change=-18.42%, turnover=9102078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=1.163500, depth_time=2026-10-22T00:15:35+00:00, book20_bid_proxy_usdt=305891, book20_ask_proxy_usdt=262656, funding_indicative=-0.000117, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=17043560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=0.198500, depth_time=2026-10-22T00:15:40+00:00, book20_bid_proxy_usdt=1548729, book20_ask_proxy_usdt=1207350, funding_indicative=0.000100, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=7543180. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=2.944000, depth_time=2026-10-22T00:15:31+00:00, book20_bid_proxy_usdt=1093357, book20_ask_proxy_usdt=1015809, funding_indicative=0.000025, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.46%, turnover=5624947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=8.735000, depth_time=2026-10-22T00:15:47+00:00, book20_bid_proxy_usdt=366482, book20_ask_proxy_usdt=210502, funding_indicative=0.000218, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=50467392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IOST_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=0.001521, depth_time=2026-10-22T00:15:08+00:00, book20_bid_proxy_usdt=9819, book20_ask_proxy_usdt=12841, funding_indicative=-0.009876, next_funding_utc=2026-10-22T01:00:00+00:00, funding_cycle_h=1, 24h_change=-34.79%, turnover=15074401. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=0.410200, depth_time=2026-10-22T00:15:45+00:00, book20_bid_proxy_usdt=560659, book20_ask_proxy_usdt=431709, funding_indicative=0.000012, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=5221870. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=0.131020, depth_time=2026-10-22T00:15:50+00:00, book20_bid_proxy_usdt=84682, book20_ask_proxy_usdt=57660, funding_indicative=-0.000020, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=6810900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=0.059630, depth_time=2026-10-22T00:15:19+00:00, book20_bid_proxy_usdt=492432, book20_ask_proxy_usdt=454019, funding_indicative=-0.000034, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.30%, turnover=24261865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=0.619200, depth_time=2026-10-22T00:15:24+00:00, book20_bid_proxy_usdt=252058, book20_ask_proxy_usdt=212149, funding_indicative=-0.000147, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.99%, turnover=40008240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-22T00:15:02+00:00, last15m_closed_end=2026-10-22T00:15+00:00, prior8high=1.989400, depth_time=2026-10-22T00:15:20+00:00, book20_bid_proxy_usdt=71510, book20_ask_proxy_usdt=39726, funding_indicative=0.000008, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.75%, turnover=7289497. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
