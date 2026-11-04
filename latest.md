# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T10:00:13Z**
- feed_generated_utc: 2026-11-04T10:00:14+00:00
- source_sha256: `2775d0703430b03cd883b8c031520daf291938c1661f48b671c36193962129c4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T10:00+00:00, close=78377.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T10:00+00:00, close=78377.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.032540|-39.52|-31.52|-40.43|10841130|6.14|
|AKE_USDT|0.002905|-30.10|-86.24|-31.01|12573179|6.89|
|TRUMPOFFICIAL_USDT|1.489000|-7.28|-11.78|-8.19|10425228|6.72|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.032540|0.032160|0.032540|1.91|N|Y/Y|Y/N|N|N|
|AKE_USDT|0.002905|0.002863|0.002904|0.88|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.489000|1.463000|1.489000|0.80|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T09:59:59+00:00, last15m_closed_end=2026-11-04T10:00+00:00, prior8high=0.037390, depth_time=2026-11-04T10:00:08+00:00, book20_bid_proxy_usdt=46440, book20_ask_proxy_usdt=47028, funding_indicative=0.000053, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-39.52%, turnover=10841130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T09:59:59+00:00, last15m_closed_end=2026-11-04T10:00+00:00, prior8high=0.003107, depth_time=2026-11-04T10:00:10+00:00, book20_bid_proxy_usdt=121707, book20_ask_proxy_usdt=58418, funding_indicative=0.000050, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-30.10%, turnover=12573179. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T10:00:00+00:00, last15m_closed_end=2026-11-04T10:00+00:00, prior8high=1.526000, depth_time=2026-11-04T10:00:12+00:00, book20_bid_proxy_usdt=2827676, book20_ask_proxy_usdt=1929624, funding_indicative=-0.000075, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.28%, turnover=10425228. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
