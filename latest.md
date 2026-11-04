# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T12:45:17Z**
- feed_generated_utc: 2026-11-04T12:45:19+00:00
- source_sha256: `5aed9c3e3df5229cec2d03326825a46ff40613fb684d000e079aadfa27d8c285`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T12:45+00:00, close=78249.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.033500|-37.74|-29.50|-38.49|10588871|2.99|
|AKE_USDT|0.002985|-28.17|-85.86|-28.92|13879816|3.35|
|TRUMPOFFICIAL_USDT|1.433000|-10.88|-15.10|-11.63|11908131|6.98|
|HOT_USDT|0.000486|-9.80|40.59|-10.55|7360930|4.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.033500|0.032170|0.033400|1.08|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002985|0.002804|0.002988|2.74|N|Y/Y|Y/Y|N|N|
|HOT_USDT|0.000486|0.000486|0.000485|0.96|N|Y/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.433000|1.439000|1.434000|2.89|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T12:45:02+00:00, last15m_closed_end=2026-11-04T12:45+00:00, prior8high=0.033970, depth_time=2026-11-04T12:45:08+00:00, book20_bid_proxy_usdt=24022, book20_ask_proxy_usdt=17425, funding_indicative=0.000053, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-37.74%, turnover=10588871. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T12:45:02+00:00, last15m_closed_end=2026-11-04T12:45+00:00, prior8high=0.003000, depth_time=2026-11-04T12:45:11+00:00, book20_bid_proxy_usdt=30850, book20_ask_proxy_usdt=44075, funding_indicative=0.000050, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-28.17%, turnover=13879816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T12:45:02+00:00, last15m_closed_end=2026-11-04T12:45+00:00, prior8high=0.000530, depth_time=2026-11-04T12:45:17+00:00, book20_bid_proxy_usdt=76788, book20_ask_proxy_usdt=83445, funding_indicative=-0.000122, next_funding_utc=2026-11-04T13:00:00+00:00, funding_cycle_h=1, 24h_change=-9.80%, turnover=7360930. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T12:45:02+00:00, last15m_closed_end=2026-11-04T12:45+00:00, prior8high=1.490000, depth_time=2026-11-04T12:45:12+00:00, book20_bid_proxy_usdt=2590684, book20_ask_proxy_usdt=2436240, funding_indicative=-0.000333, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.88%, turnover=11908131. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
