# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T22:45:18Z**
- feed_generated_utc: 2026-10-25T22:45:20+00:00
- source_sha256: `f5e3f282157d2dca8e7a56f173080db5a14abc725e5a49dab8dfb40d83573074`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T22:45+00:00, close=80525, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T22:00+00:00, close=80235.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.006354|-8.86|244.76|-8.77|9973672|3.15|
|XMR_USDT|595.650000|-1.91|2.25|-1.82|6733983|0.17|
|USELESS_USDT|0.169600|-1.72|19.90|-1.63|5144480|1.18|
|PEPE_USDT|0.000004|-1.17|12.69|-1.08|74794000|0.23|
|DASH_USDT|51.810000|-1.14|8.20|-1.05|14356878|1.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|51.810000|51.310000|51.810000|1.05|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.006354|0.006729|0.006352|8.68|Y|N/N|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.77|N|Y/Y|Y/Y|Y|N|
|USELESS_USDT|0.169600|0.167580|0.169600|0.86|N|Y/Y|N/N|Y|N|
|XMR_USDT|595.650000|593.960000|595.650000|1.50|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-25T22:45:00+00:00, last15m_closed_end=2026-10-25T22:45+00:00, prior8high=52.000000, depth_time=2026-10-25T22:45:16+00:00, book20_bid_proxy_usdt=475478, book20_ask_proxy_usdt=589310, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.14%, turnover=14356878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-25T22:44:59+00:00, last15m_closed_end=2026-10-25T22:45+00:00, prior8high=0.006991, depth_time=2026-10-25T22:45:08+00:00, book20_bid_proxy_usdt=24413, book20_ask_proxy_usdt=21266, funding_indicative=0.000190, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.86%, turnover=9973672. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-25T22:45:00+00:00, last15m_closed_end=2026-10-25T22:45+00:00, prior8high=0.000004, depth_time=2026-10-25T22:45:15+00:00, book20_bid_proxy_usdt=73057, book20_ask_proxy_usdt=40096, funding_indicative=0.000042, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=74794000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T22:45:00+00:00, last15m_closed_end=2026-10-25T22:45+00:00, prior8high=0.171640, depth_time=2026-10-25T22:45:12+00:00, book20_bid_proxy_usdt=27556, book20_ask_proxy_usdt=17144, funding_indicative=0.000050, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=5144480. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T22:44:59+00:00, last15m_closed_end=2026-10-25T22:45+00:00, prior8high=603.940000, depth_time=2026-10-25T22:45:07+00:00, book20_bid_proxy_usdt=20250, book20_ask_proxy_usdt=13892, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=6733983. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
