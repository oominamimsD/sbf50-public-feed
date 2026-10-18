# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T05:00:40Z**
- feed_generated_utc: 2026-10-18T05:00:42+00:00
- source_sha256: `31ff0dc41b697668ace4c73409dfa2eca7989a458dc600e5a15215da5a2598df`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T05:00+00:00, close=81766.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T05:00+00:00, close=81766.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EIGEN_USDT|0.248100|-4.46|5.30|-5.01|8951650|4.03|
|TIA_USDT|0.629500|-4.33|22.70|-4.88|70253126|1.59|
|STRK_USDT|0.063330|-4.26|-32.21|-4.81|14322140|1.58|
|FILECOIN_USDT|1.056300|-2.86|-6.33|-3.41|21220185|0.95|
|QNT_USDT|195.440000|-2.47|-20.27|-3.02|70916982|0.51|
|APT_USDT|0.789800|-2.37|-4.47|-2.92|9908962|1.27|
|OP_USDT|0.127170|-2.20|-8.21|-2.75|9321849|3.15|
|PUMPFUN_USDT|0.004317|-2.15|-24.59|-2.70|23545738|2.32|
|ZRO_USDT|1.865600|-1.77|-7.67|-2.32|7186225|0.54|
|DOT_USDT|1.101700|-1.40|-12.34|-1.95|16980441|0.91|
|ICP_USDT|2.921000|-1.21|-7.24|-1.76|6412947|3.42|
|WLD_USDT|0.490600|-1.00|-12.23|-1.55|64408237|2.04|
|SEI_USDT|0.062530|-0.93|-9.97|-1.48|8367943|1.60|
|ARB_USDT|0.182250|-0.90|-2.36|-1.45|31357229|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.789800|0.788500|0.789800|1.54|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.182250|0.181320|0.182250|0.61|N|Y/Y|Y/Y|N|N|
|DOT_USDT|1.101700|1.101100|1.101700|4.35|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.248100|0.248200|0.248100|1.28|N|Y/Y|N/Y|N|N|
|FILECOIN_USDT|1.056300|1.053400|1.056300|1.39|N|Y/Y|Y/Y|N|N|
|ICP_USDT|2.921000|2.917000|2.921000|0.34|N|Y/Y|Y/Y|N|N|
|OP_USDT|0.127170|0.127140|0.127170|0.60|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004317|0.004319|0.004317|0.35|N|Y/Y|Y/Y|N|N|
|QNT_USDT|195.440000|193.320000|195.440000|0.43|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.062530|0.062180|0.062530|0.12|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.063330|0.062790|0.063330|0.73|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.629500|0.626300|0.629500|0.21|N|Y/Y|Y/N|N|N|
|WLD_USDT|0.490600|0.489400|0.490600|0.95|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.865600|1.862500|1.865600|0.24|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T05:00:00+00:00, last15m_closed_end=2026-10-18T05:00+00:00, prior8high=0.800600, depth_time=2026-10-18T05:00:19+00:00, book20_bid_proxy_usdt=132598, book20_ask_proxy_usdt=147847, funding_indicative=-0.000099, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.37%, turnover=9908962. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-18T04:59:59+00:00, last15m_closed_end=2026-10-18T05:00+00:00, prior8high=0.185600, depth_time=2026-10-18T05:00:39+00:00, book20_bid_proxy_usdt=106904, book20_ask_proxy_usdt=58332, funding_indicative=-0.000016, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.90%, turnover=31357229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T05:00:00+00:00, last15m_closed_end=2026-10-18T05:00+00:00, prior8high=1.120700, depth_time=2026-10-18T05:00:29+00:00, book20_bid_proxy_usdt=399931, book20_ask_proxy_usdt=286852, funding_indicative=-0.000036, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=16980441. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T05:00:00+00:00, last15m_closed_end=2026-10-18T05:00+00:00, prior8high=0.253900, depth_time=2026-10-18T05:00:06+00:00, book20_bid_proxy_usdt=519961, book20_ask_proxy_usdt=394094, funding_indicative=-0.000004, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=8951650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T04:59:59+00:00, last15m_closed_end=2026-10-18T05:00+00:00, prior8high=1.074100, depth_time=2026-10-18T05:00:12+00:00, book20_bid_proxy_usdt=490169, book20_ask_proxy_usdt=806128, funding_indicative=-0.000110, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=21220185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T05:00:00+00:00, last15m_closed_end=2026-10-18T05:00+00:00, prior8high=2.955000, depth_time=2026-10-18T05:00:32+00:00, book20_bid_proxy_usdt=1063050, book20_ask_proxy_usdt=826118, funding_indicative=0.000029, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.21%, turnover=6412947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T05:00:00+00:00, last15m_closed_end=2026-10-18T05:00+00:00, prior8high=0.129950, depth_time=2026-10-18T05:00:22+00:00, book20_bid_proxy_usdt=57617, book20_ask_proxy_usdt=55376, funding_indicative=-0.000181, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=9321849. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T04:59:59+00:00, last15m_closed_end=2026-10-18T05:00+00:00, prior8high=0.004401, depth_time=2026-10-18T05:00:24+00:00, book20_bid_proxy_usdt=1922375, book20_ask_proxy_usdt=1347011, funding_indicative=0.000017, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.15%, turnover=23545738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T04:59:59+00:00, last15m_closed_end=2026-10-18T05:00+00:00, prior8high=197.180000, depth_time=2026-10-18T05:00:15+00:00, book20_bid_proxy_usdt=78094, book20_ask_proxy_usdt=74713, funding_indicative=-0.000114, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=70916982. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-18T05:00:00+00:00, last15m_closed_end=2026-10-18T05:00+00:00, prior8high=0.063260, depth_time=2026-10-18T05:00:35+00:00, book20_bid_proxy_usdt=228391, book20_ask_proxy_usdt=201270, funding_indicative=-0.000001, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=8367943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T04:59:59+00:00, last15m_closed_end=2026-10-18T05:00+00:00, prior8high=0.064400, depth_time=2026-10-18T05:00:12+00:00, book20_bid_proxy_usdt=373669, book20_ask_proxy_usdt=409682, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.26%, turnover=14322140. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T04:59:59+00:00, last15m_closed_end=2026-10-18T05:00+00:00, prior8high=0.638400, depth_time=2026-10-18T05:00:10+00:00, book20_bid_proxy_usdt=244811, book20_ask_proxy_usdt=311228, funding_indicative=-0.000005, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.33%, turnover=70253126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T04:59:59+00:00, last15m_closed_end=2026-10-18T05:00+00:00, prior8high=0.498500, depth_time=2026-10-18T05:00:34+00:00, book20_bid_proxy_usdt=2465881, book20_ask_proxy_usdt=2190784, funding_indicative=-0.000155, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=64408237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T05:00:00+00:00, last15m_closed_end=2026-10-18T05:00+00:00, prior8high=1.918400, depth_time=2026-10-18T05:00:27+00:00, book20_bid_proxy_usdt=68411, book20_ask_proxy_usdt=40508, funding_indicative=0.000017, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.77%, turnover=7186225. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
