# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T19:30:18Z**
- feed_generated_utc: 2026-11-04T19:30:20+00:00
- source_sha256: `c01b7739d601de61e6344aabc075eebe84652f9b04ec5751ddf48ccb25c72cf6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T19:30+00:00, close=80278.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T19:00+00:00, close=80313.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.032430|-9.66|-28.07|-9.67|5287201|3.08|
|TRUMPOFFICIAL_USDT|1.298000|-8.84|-24.04|-8.85|24402816|7.70|
|AKE_USDT|0.002579|-8.22|-87.16|-8.23|17059605|3.88|
|PUMPFUN_USDT|0.004214|-5.30|0.16|-5.31|18834336|2.37|
|ZRO_USDT|1.798300|-3.56|5.04|-3.57|11221580|0.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.032430|0.031770|0.032430|0.43|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002579|0.002421|0.002579|0.25|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004214|0.004138|0.004212|0.44|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.298000|1.215000|1.299000|0.44|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.798300|1.786400|1.798300|0.19|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T19:30:00+00:00, last15m_closed_end=2026-11-04T19:30+00:00, prior8high=0.034600, depth_time=2026-11-04T19:30:08+00:00, book20_bid_proxy_usdt=36405, book20_ask_proxy_usdt=21390, funding_indicative=0.000053, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.66%, turnover=5287201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T19:30:00+00:00, last15m_closed_end=2026-11-04T19:30+00:00, prior8high=0.002842, depth_time=2026-11-04T19:30:12+00:00, book20_bid_proxy_usdt=97085, book20_ask_proxy_usdt=47695, funding_indicative=-0.000343, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.22%, turnover=17059605. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T19:30:01+00:00, last15m_closed_end=2026-11-04T19:30+00:00, prior8high=0.004333, depth_time=2026-11-04T19:30:14+00:00, book20_bid_proxy_usdt=2428570, book20_ask_proxy_usdt=2395380, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.30%, turnover=18834336. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T19:30:01+00:00, last15m_closed_end=2026-11-04T19:30+00:00, prior8high=1.355000, depth_time=2026-11-04T19:30:10+00:00, book20_bid_proxy_usdt=1252078, book20_ask_proxy_usdt=1053554, funding_indicative=-0.000373, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.84%, turnover=24402816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T19:30:01+00:00, last15m_closed_end=2026-11-04T19:30+00:00, prior8high=1.845000, depth_time=2026-11-04T19:30:17+00:00, book20_bid_proxy_usdt=18208, book20_ask_proxy_usdt=63612, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.56%, turnover=11221580. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
