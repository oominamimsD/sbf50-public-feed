# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T20:15:29Z**
- feed_generated_utc: 2026-11-03T20:15:32+00:00
- source_sha256: `284fe92fe356b13091c70437381f71295a110b20608ff625d2520a05bd4f6924`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T20:15+00:00, close=77593.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003874|-6.78|-81.66|-6.69|13349256|2.58|
|QNT_USDT|190.410000|-2.56|-3.77|-2.47|56835816|1.05|
|TRUMPOFFICIAL_USDT|1.572000|-2.23|-6.87|-2.14|5938357|6.36|
|TIA_USDT|0.428700|-1.62|-20.03|-1.53|11719932|2.33|
|OP_USDT|0.108650|-1.61|-2.39|-1.52|8735422|0.92|
|XLM_USDT|0.162420|-1.43|-4.01|-1.34|33321026|0.62|
|HBAR_USDT|0.069140|-1.27|-9.16|-1.18|5522210|1.45|
|NEAR_USDT|3.816000|-1.11|-16.35|-1.02|69300991|2.62|
|XPL_USDT|0.063340|-1.10|-14.19|-1.01|8977086|1.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003874|0.003757|0.003872|1.11|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.069140|0.069240|0.069140|1.46|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|3.816000|3.813000|3.814000|0.91|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.108650|0.109360|0.108650|2.42|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|190.410000|190.330000|190.410000|0.63|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.428700|0.429500|0.428900|1.50|Y|Y/Y|Y/Y|Y|Y|
|TRUMPOFFICIAL_USDT|1.572000|1.571000|1.572000|1.92|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.162420|0.162870|0.162420|1.56|Y|Y/Y|Y/Y|Y|Y|
|XPL_USDT|0.063340|0.062840|0.063350|1.51|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T20:15:00+00:00, last15m_closed_end=2026-11-03T20:15+00:00, prior8high=0.004019, depth_time=2026-11-03T20:15:08+00:00, book20_bid_proxy_usdt=59167, book20_ask_proxy_usdt=66025, funding_indicative=-0.000495, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.78%, turnover=13349256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-03T20:15:00+00:00, last15m_closed_end=2026-11-03T20:15+00:00, prior8high=0.069910, depth_time=2026-11-03T20:15:23+00:00, book20_bid_proxy_usdt=1071073, book20_ask_proxy_usdt=1423528, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=5522210. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T20:15:00+00:00, last15m_closed_end=2026-11-03T20:15+00:00, prior8high=3.894000, depth_time=2026-11-03T20:15:25+00:00, book20_bid_proxy_usdt=4014628, book20_ask_proxy_usdt=3521205, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=69300991. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-03T20:15:00+00:00, last15m_closed_end=2026-11-03T20:15+00:00, prior8high=0.110950, depth_time=2026-11-03T20:15:19+00:00, book20_bid_proxy_usdt=118082, book20_ask_proxy_usdt=111423, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.61%, turnover=8735422. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T20:15:00+00:00, last15m_closed_end=2026-11-03T20:15+00:00, prior8high=195.440000, depth_time=2026-11-03T20:15:11+00:00, book20_bid_proxy_usdt=103576, book20_ask_proxy_usdt=73996, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=56835816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T20:15:00+00:00, last15m_closed_end=2026-11-03T20:15+00:00, prior8high=0.433900, depth_time=2026-11-03T20:15:16+00:00, book20_bid_proxy_usdt=345170, book20_ask_proxy_usdt=377666, funding_indicative=-0.000051, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=11719932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T20:15:00+00:00, last15m_closed_end=2026-11-03T20:15+00:00, prior8high=1.592000, depth_time=2026-11-03T20:15:12+00:00, book20_bid_proxy_usdt=1839444, book20_ask_proxy_usdt=2343464, funding_indicative=0.000031, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.23%, turnover=5938357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T20:15:00+00:00, last15m_closed_end=2026-11-03T20:15+00:00, prior8high=0.164650, depth_time=2026-11-03T20:15:20+00:00, book20_bid_proxy_usdt=137031, book20_ask_proxy_usdt=243405, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=33321026. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T20:15:00+00:00, last15m_closed_end=2026-11-03T20:15+00:00, prior8high=0.064140, depth_time=2026-11-03T20:15:29+00:00, book20_bid_proxy_usdt=354641, book20_ask_proxy_usdt=323378, funding_indicative=0.000050, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=8977086. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
