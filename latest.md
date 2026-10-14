# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T23:30:17Z**
- feed_generated_utc: 2026-10-14T23:30:19+00:00
- source_sha256: `eb409549b55260ec2cf5fc2406a472542d19c7b1a9727f300a12afeefefef5a9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T23:30+00:00, close=81503.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T23:00+00:00, close=81624.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FET_USDT|0.197800|-2.99|-12.67|-2.88|10797537|5.06|
|BAT_USDT|0.170160|-2.44|71.60|-2.33|25086732|0.59|
|S_USDT|0.053720|-1.95|34.83|-1.84|5317874|1.86|
|AAVE_USDT|153.990000|-1.21|-10.34|-1.10|26464365|0.65|
|LDO_USDT|0.401100|-1.15|-6.15|-1.04|5125400|2.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|153.990000|152.860000|153.990000|0.52|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.170160|0.167700|0.170160|1.23|N|Y/Y|Y/N|Y|N|
|FET_USDT|0.197800|0.196000|0.197800|0.72|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.401100|0.398100|0.401100|1.46|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053720|0.052410|0.053720|0.62|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T23:29:59+00:00, last15m_closed_end=2026-10-14T23:30+00:00, prior8high=154.420000, depth_time=2026-10-14T23:30:14+00:00, book20_bid_proxy_usdt=214368, book20_ask_proxy_usdt=387391, funding_indicative=0.000077, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.21%, turnover=26464365. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T23:29:59+00:00, last15m_closed_end=2026-10-14T23:30+00:00, prior8high=0.171730, depth_time=2026-10-14T23:30:09+00:00, book20_bid_proxy_usdt=36408, book20_ask_proxy_usdt=29108, funding_indicative=0.000053, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=25086732. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T23:29:59+00:00, last15m_closed_end=2026-10-14T23:30+00:00, prior8high=0.198600, depth_time=2026-10-14T23:30:05+00:00, book20_bid_proxy_usdt=1301236, book20_ask_proxy_usdt=1187046, funding_indicative=0.000046, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.99%, turnover=10797537. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-14T23:30:00+00:00, last15m_closed_end=2026-10-14T23:30+00:00, prior8high=0.402400, depth_time=2026-10-14T23:30:14+00:00, book20_bid_proxy_usdt=675935, book20_ask_proxy_usdt=555299, funding_indicative=-0.000050, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.15%, turnover=5125400. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T23:29:59+00:00, last15m_closed_end=2026-10-14T23:30+00:00, prior8high=0.053820, depth_time=2026-10-14T23:30:11+00:00, book20_bid_proxy_usdt=129683, book20_ask_proxy_usdt=194144, funding_indicative=-0.000095, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=5317874. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
