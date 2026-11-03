# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T00:30:46Z**
- feed_generated_utc: 2026-11-03T00:30:48+00:00
- source_sha256: `112f38f832856b4a23a1dac4a04c0049586db723e52c4df98a44a515fcaa7ae9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T00:30+00:00, close=77038, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-03T00:00+00:00, close=76791.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-03T00:00+00:00, close=76791.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|0.947800|-13.58|-20.73|-13.03|10010854|5.28|
|ZEC_USDT|1154.000000|-7.98|-7.51|-7.43|1894529883|0.09|
|AKE_USDT|0.005143|-6.52|-83.29|-5.97|14060455|1.95|
|XPL_USDT|0.066660|-4.19|-10.27|-3.64|11112904|1.50|
|QNT_USDT|194.460000|-3.94|-7.52|-3.39|46958946|0.51|
|NEAR_USDT|3.883000|-3.16|-15.08|-2.61|79915707|2.57|
|AAVE_USDT|126.580000|-3.04|-7.42|-2.49|23317377|0.79|
|XLM_USDT|0.163010|-2.73|-3.87|-2.18|34601303|1.23|
|PUMPFUN_USDT|0.003994|-2.68|-7.71|-2.13|9209398|2.50|
|TIA_USDT|0.445300|-2.53|-16.87|-1.98|12502474|2.25|
|TRUMPOFFICIAL_USDT|1.595000|-2.50|-5.56|-1.95|11626227|6.27|
|ZRO_USDT|1.724000|-2.49|0.98|-1.94|6208262|1.74|
|ARB_USDT|0.155580|-2.35|-8.47|-1.80|13509072|0.64|
|OP_USDT|0.109920|-2.23|-1.59|-1.68|11836269|0.91|
|ENA_USDT|0.171780|-1.86|-18.34|-1.31|73686409|0.58|
|DASH_USDT|46.370000|-1.75|-11.20|-1.20|10004741|2.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.580000|126.210000|126.580000|1.29|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005143|0.004935|0.005143|1.23|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.155580|0.155020|0.155620|2.39|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.947800|0.957600|0.949000|1.77|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.171780|0.169920|0.171780|0.49|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.883000|3.853000|3.883000|0.60|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.109920|0.109570|0.109920|0.32|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003994|0.003942|0.003994|0.35|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.460000|193.300000|194.480000|1.89|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.445300|0.443000|0.445200|0.74|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.595000|1.592000|1.595000|0.34|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.163010|0.162110|0.163010|0.65|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.066660|0.066060|0.066660|0.70|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1154.000000|1131.050000|1154.000000|0.86|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.724000|1.700600|1.723700|0.67|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=127.620000, depth_time=2026-11-03T00:30:22+00:00, book20_bid_proxy_usdt=823694, book20_ask_proxy_usdt=468257, funding_indicative=0.000100, next_funding_utc=2026-11-03T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.04%, turnover=23317377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=0.005937, depth_time=2026-11-03T00:30:13+00:00, book20_bid_proxy_usdt=35983, book20_ask_proxy_usdt=20707, funding_indicative=-0.004734, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.52%, turnover=14060455. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=0.156860, depth_time=2026-11-03T00:30:39+00:00, book20_bid_proxy_usdt=102314, book20_ask_proxy_usdt=95167, funding_indicative=0.000100, next_funding_utc=2026-11-03T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.35%, turnover=13509072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=1.057400, depth_time=2026-11-03T00:30:07+00:00, book20_bid_proxy_usdt=22337, book20_ask_proxy_usdt=39364, funding_indicative=0.000050, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.58%, turnover=10010854. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=0.172110, depth_time=2026-11-03T00:30:45+00:00, book20_bid_proxy_usdt=245835, book20_ask_proxy_usdt=156594, funding_indicative=0.000050, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=73686409. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=3.904000, depth_time=2026-11-03T00:30:19+00:00, book20_bid_proxy_usdt=5556825, book20_ask_proxy_usdt=4215716, funding_indicative=0.000100, next_funding_utc=2026-11-03T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=79915707. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=0.110950, depth_time=2026-11-03T00:30:42+00:00, book20_bid_proxy_usdt=148994, book20_ask_proxy_usdt=98611, funding_indicative=0.000100, next_funding_utc=2026-11-03T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=11836269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=0.003989, depth_time=2026-11-03T00:30:27+00:00, book20_bid_proxy_usdt=3147608, book20_ask_proxy_usdt=1954972, funding_indicative=0.000050, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=9209398. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=195.810000, depth_time=2026-11-03T00:30:16+00:00, book20_bid_proxy_usdt=78828, book20_ask_proxy_usdt=46500, funding_indicative=0.000100, next_funding_utc=2026-11-03T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.94%, turnover=46958946. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=0.450800, depth_time=2026-11-03T00:30:31+00:00, book20_bid_proxy_usdt=287071, book20_ask_proxy_usdt=308542, funding_indicative=0.000050, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=12502474. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=1.612000, depth_time=2026-11-03T00:30:32+00:00, book20_bid_proxy_usdt=1891559, book20_ask_proxy_usdt=1681134, funding_indicative=0.000050, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=11626227. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=0.164090, depth_time=2026-11-03T00:30:23+00:00, book20_bid_proxy_usdt=201614, book20_ask_proxy_usdt=247241, funding_indicative=0.000100, next_funding_utc=2026-11-03T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=34601303. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=0.067060, depth_time=2026-11-03T00:30:15+00:00, book20_bid_proxy_usdt=386492, book20_ask_proxy_usdt=507098, funding_indicative=0.000050, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.19%, turnover=11112904. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=1159.040000, depth_time=2026-11-03T00:30:10+00:00, book20_bid_proxy_usdt=223607, book20_ask_proxy_usdt=1411854, funding_indicative=0.000100, next_funding_utc=2026-11-03T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.98%, turnover=1894529883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-03T00:30:02+00:00, last15m_closed_end=2026-11-03T00:30+00:00, prior8high=1.734500, depth_time=2026-11-03T00:30:36+00:00, book20_bid_proxy_usdt=58705, book20_ask_proxy_usdt=34558, funding_indicative=0.000050, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.49%, turnover=6208262. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
