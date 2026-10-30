# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T17:45:20Z**
- feed_generated_utc: 2026-10-30T17:45:22+00:00
- source_sha256: `d3feceec4fa8560ec190d3e747c0b9dd751843a36d9a61fc5bda6e106ac08c08`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T17:45+00:00, close=77300.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T17:00+00:00, close=77318.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.009183|-6.78|12.52|-6.43|18287489|1.09|
|LIT_USDT|2.763900|-2.13|-16.85|-1.78|12977223|0.36|
|BTW_USDT|1.175600|-1.99|-30.94|-1.64|9957892|3.40|
|XMR_USDT|591.020000|-1.74|-2.62|-1.39|19018260|0.17|
|PUMPFUN_USDT|0.004044|-1.53|-11.37|-1.18|26791762|2.47|
|CRV_USDT|0.282000|-1.43|-23.03|-1.08|8329870|7.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009183|0.008535|0.009183|1.16|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.175600|1.120800|1.175600|1.62|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.282000|0.281800|0.282000|0.07|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.763900|2.757900|2.763900|1.39|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004044|0.004028|0.004044|0.58|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|591.020000|593.110000|591.020000|2.86|Y|Y/N|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T17:44:59+00:00, last15m_closed_end=2026-10-30T17:45+00:00, prior8high=0.012169, depth_time=2026-10-30T17:45:08+00:00, book20_bid_proxy_usdt=11371, book20_ask_proxy_usdt=15808, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.78%, turnover=18287489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T17:45:00+00:00, last15m_closed_end=2026-10-30T17:45+00:00, prior8high=1.223800, depth_time=2026-10-30T17:45:12+00:00, book20_bid_proxy_usdt=13456, book20_ask_proxy_usdt=11602, funding_indicative=-0.000128, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=9957892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T17:45:00+00:00, last15m_closed_end=2026-10-30T17:45+00:00, prior8high=0.288100, depth_time=2026-10-30T17:45:19+00:00, book20_bid_proxy_usdt=469168, book20_ask_proxy_usdt=362542, funding_indicative=-0.000083, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=8329870. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T17:45:00+00:00, last15m_closed_end=2026-10-30T17:45+00:00, prior8high=2.883200, depth_time=2026-10-30T17:45:10+00:00, book20_bid_proxy_usdt=19826, book20_ask_proxy_usdt=39684, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=12977223. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T17:44:59+00:00, last15m_closed_end=2026-10-30T17:45+00:00, prior8high=0.004129, depth_time=2026-10-30T17:45:17+00:00, book20_bid_proxy_usdt=1963300, book20_ask_proxy_usdt=870706, funding_indicative=0.000018, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=26791762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-30T17:45:00+00:00, last15m_closed_end=2026-10-30T17:45+00:00, prior8high=602.170000, depth_time=2026-10-30T17:45:12+00:00, book20_bid_proxy_usdt=23351, book20_ask_proxy_usdt=8794, funding_indicative=0.000332, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=19018260. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
