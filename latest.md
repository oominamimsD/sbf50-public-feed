# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T22:15:14Z**
- feed_generated_utc: 2026-11-09T22:15:15+00:00
- source_sha256: `e59413878ff9ce365818b0d322b6a77fa177c344af5f44f40a14fbd2eecea2ec`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T22:15+00:00, close=75058.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T22:00+00:00, close=75004.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1175.060000|-4.13|-6.30|-3.55|2471868925|0.09|
|DOT_USDT|0.858400|-3.64|-8.10|-3.06|11518027|4.66|
|QNT_USDT|195.680000|-2.17|-3.34|-1.59|42985603|0.51|
|XRP_USDT|1.096000|-1.60|-12.20|-1.02|301488682|0.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|0.858400|0.859200|0.858400|1.32|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|195.680000|194.710000|195.680000|1.28|N|Y/Y|Y/N|Y|N|
|XRP_USDT|1.096000|1.087800|1.096000|0.64|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1175.060000|1162.360000|1175.060000|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-11-09T22:15:00+00:00, last15m_closed_end=2026-11-09T22:15+00:00, prior8high=0.870800, depth_time=2026-11-09T22:15:06+00:00, book20_bid_proxy_usdt=528036, book20_ask_proxy_usdt=390510, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.64%, turnover=11518027. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-09T22:15:00+00:00, last15m_closed_end=2026-11-09T22:15+00:00, prior8high=197.100000, depth_time=2026-11-09T22:15:10+00:00, book20_bid_proxy_usdt=99150, book20_ask_proxy_usdt=79612, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=42985603. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T22:15:00+00:00, last15m_closed_end=2026-11-09T22:15+00:00, prior8high=1.099700, depth_time=2026-11-09T22:15:13+00:00, book20_bid_proxy_usdt=3293579, book20_ask_proxy_usdt=3409335, funding_indicative=0.000080, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=301488682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T22:15:00+00:00, last15m_closed_end=2026-11-09T22:15+00:00, prior8high=1186.440000, depth_time=2026-11-09T22:15:06+00:00, book20_bid_proxy_usdt=635369, book20_ask_proxy_usdt=245980, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.13%, turnover=2471868925. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
