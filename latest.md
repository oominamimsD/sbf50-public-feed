# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T11:45:14Z**
- feed_generated_utc: 2026-11-04T11:45:15+00:00
- source_sha256: `7e7eee028cc8892ffa3a1fbe36731dd5dd79b9040bef3dd634b8528e793f3735`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T11:45+00:00, close=78641.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T11:00+00:00, close=78590.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.032780|-39.08|-31.01|-40.33|10677473|6.10|
|TRUMPOFFICIAL_USDT|1.474000|-8.33|-12.67|-9.58|10636582|6.78|
|HOT_USDT|0.000494|-8.17|43.13|-9.42|8861400|2.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.032780|0.032150|0.032790|0.94|N|Y/Y|Y/N|N|N|
|HOT_USDT|0.000494|0.000496|0.000495|1.60|Y|N/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.474000|1.468000|1.474000|0.84|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T11:45:03+00:00, last15m_closed_end=2026-11-04T11:45+00:00, prior8high=0.034540, depth_time=2026-11-04T11:45:07+00:00, book20_bid_proxy_usdt=30874, book20_ask_proxy_usdt=21115, funding_indicative=0.000053, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-39.08%, turnover=10677473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T11:45:03+00:00, last15m_closed_end=2026-11-04T11:45+00:00, prior8high=0.000534, depth_time=2026-11-04T11:45:13+00:00, book20_bid_proxy_usdt=103586, book20_ask_proxy_usdt=96939, funding_indicative=-0.000175, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=1, 24h_change=-8.17%, turnover=8861400. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T11:45:03+00:00, last15m_closed_end=2026-11-04T11:45+00:00, prior8high=1.497000, depth_time=2026-11-04T11:45:09+00:00, book20_bid_proxy_usdt=2478973, book20_ask_proxy_usdt=2021938, funding_indicative=-0.000235, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.33%, turnover=10636582. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
