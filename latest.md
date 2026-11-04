# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T07:45:16Z**
- feed_generated_utc: 2026-11-04T07:45:18+00:00
- source_sha256: `0d5a02e31173a5379a27c263e960d74ecb5d77970178afb4fb291188e256b284`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T07:45+00:00, close=78150.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T07:00+00:00, close=77970.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T04:00+00:00, close=76468.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.037370|-30.55|-21.35|-31.17|10881819|5.35|
|AKE_USDT|0.003060|-26.37|-85.51|-26.99|12500561|6.54|
|TRUMPOFFICIAL_USDT|1.506000|-6.34|-10.78|-6.96|9162453|6.64|
|Q_USDT|0.027920|-0.88|-56.08|-1.50|7406190|3.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.037370|0.036850|0.037370|0.97|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.003060|0.002979|0.003060|0.57|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.027920|0.027450|0.027920|0.57|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.506000|1.504000|1.506000|2.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T07:44:59+00:00, last15m_closed_end=2026-11-04T07:45+00:00, prior8high=0.038670, depth_time=2026-11-04T07:45:06+00:00, book20_bid_proxy_usdt=47167, book20_ask_proxy_usdt=24961, funding_indicative=0.000068, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-30.55%, turnover=10881819. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T07:44:59+00:00, last15m_closed_end=2026-11-04T07:45+00:00, prior8high=0.003323, depth_time=2026-11-04T07:45:10+00:00, book20_bid_proxy_usdt=72332, book20_ask_proxy_usdt=66694, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-26.37%, turnover=12500561. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T07:44:59+00:00, last15m_closed_end=2026-11-04T07:45+00:00, prior8high=0.028570, depth_time=2026-11-04T07:45:16+00:00, book20_bid_proxy_usdt=68441, book20_ask_proxy_usdt=39920, funding_indicative=-0.000352, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=7406190. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T07:45:00+00:00, last15m_closed_end=2026-11-04T07:45+00:00, prior8high=1.536000, depth_time=2026-11-04T07:45:13+00:00, book20_bid_proxy_usdt=2453295, book20_ask_proxy_usdt=2279107, funding_indicative=-0.000070, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.34%, turnover=9162453. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
