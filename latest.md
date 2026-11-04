# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T09:15:16Z**
- feed_generated_utc: 2026-11-04T09:15:18+00:00
- source_sha256: `56d2910ae3483af10df5c4b9fe77e5588a26dfdd8a0c1ebe720b806277b6b706`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T09:15+00:00, close=78412.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T09:00+00:00, close=78473.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.034290|-36.27|-27.84|-37.23|10497934|2.92|
|AKE_USDT|0.002948|-29.06|-86.04|-30.02|12013929|6.79|
|TRUMPOFFICIAL_USDT|1.485000|-7.64|-12.02|-8.60|10147000|6.73|
|Q_USDT|0.028020|-0.53|-55.93|-1.49|7281404|3.57|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.034290|0.034150|0.034290|1.39|N|Y/Y|Y/N|N|N|
|AKE_USDT|0.002948|0.002924|0.002950|1.39|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.028020|0.027670|0.028020|4.30|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.485000|1.490000|1.485000|0.81|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T09:14:59+00:00, last15m_closed_end=2026-11-04T09:15+00:00, prior8high=0.038390, depth_time=2026-11-04T09:15:07+00:00, book20_bid_proxy_usdt=19221, book20_ask_proxy_usdt=28762, funding_indicative=0.000053, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-36.27%, turnover=10497934. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T09:15:00+00:00, last15m_closed_end=2026-11-04T09:15+00:00, prior8high=0.003205, depth_time=2026-11-04T09:15:10+00:00, book20_bid_proxy_usdt=55421, book20_ask_proxy_usdt=64862, funding_indicative=0.000050, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-29.06%, turnover=12013929. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T09:15:00+00:00, last15m_closed_end=2026-11-04T09:15+00:00, prior8high=0.028570, depth_time=2026-11-04T09:15:15+00:00, book20_bid_proxy_usdt=54737, book20_ask_proxy_usdt=38927, funding_indicative=-0.000452, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.53%, turnover=7281404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T09:15:00+00:00, last15m_closed_end=2026-11-04T09:15+00:00, prior8high=1.526000, depth_time=2026-11-04T09:15:11+00:00, book20_bid_proxy_usdt=2794292, book20_ask_proxy_usdt=2569795, funding_indicative=-0.000067, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.64%, turnover=10147000. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
