# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T15:30:14Z**
- feed_generated_utc: 2026-11-04T15:30:16+00:00
- source_sha256: `742ff2fedd4dff4b38d973e5d35eb2e332661f17cbcef35e20de93660ecea93b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T15:30+00:00, close=80624, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T15:00+00:00, close=79318.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.035970|-33.15|-24.30|-36.96|7108304|2.78|
|TRUMPOFFICIAL_USDT|1.453000|-9.63|-13.92|-13.44|14801936|6.88|
|Q_USDT|0.028610|1.56|-55.00|-2.25|7060960|3.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.035970|0.033240|0.035970|1.65|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.028610|0.028830|0.028610|2.99|Y|N/N|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.453000|1.404000|1.453000|1.67|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T15:30:00+00:00, last15m_closed_end=2026-11-04T15:30+00:00, prior8high=0.037650, depth_time=2026-11-04T15:30:08+00:00, book20_bid_proxy_usdt=25281, book20_ask_proxy_usdt=21581, funding_indicative=0.000053, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-33.15%, turnover=7108304. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T15:30:00+00:00, last15m_closed_end=2026-11-04T15:30+00:00, prior8high=0.029920, depth_time=2026-11-04T15:30:13+00:00, book20_bid_proxy_usdt=115096, book20_ask_proxy_usdt=69041, funding_indicative=-0.000054, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=1.56%, turnover=7060960. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T15:30:00+00:00, last15m_closed_end=2026-11-04T15:30+00:00, prior8high=1.465000, depth_time=2026-11-04T15:30:11+00:00, book20_bid_proxy_usdt=1868268, book20_ask_proxy_usdt=1760651, funding_indicative=-0.000372, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.63%, turnover=14801936. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
