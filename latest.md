# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T14:15:13Z**
- feed_generated_utc: 2026-10-16T14:15:15+00:00
- source_sha256: `04d38365ba7bb1714e4960b12e34c2c264d9f2ed3e970ded819a8f60df63c49b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T14:15+00:00, close=82178.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T14:00+00:00, close=81992.1, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.076910|-20.18|27.84|-19.95|38993025|1.30|
|PYTH_USDT|0.088390|-9.19|20.09|-8.96|9198104|1.13|
|AKE_USDT|0.028750|-9.03|-0.94|-8.80|15819911|0.35|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028750|0.029184|0.028750|2.13|Y|Y/Y|N/N|N|N|
|PYTH_USDT|0.088390|0.086360|0.088390|0.83|N|Y/Y|N/N|N|N|
|STRK_USDT|0.076910|0.075410|0.076910|0.82|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T14:14:59+00:00, last15m_closed_end=2026-10-16T14:15+00:00, prior8high=0.030019, depth_time=2026-10-16T14:15:13+00:00, book20_bid_proxy_usdt=14915, book20_ask_proxy_usdt=14987, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.03%, turnover=15819911. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T14:14:59+00:00, last15m_closed_end=2026-10-16T14:15+00:00, prior8high=0.091480, depth_time=2026-10-16T14:15:10+00:00, book20_bid_proxy_usdt=97486, book20_ask_proxy_usdt=73894, funding_indicative=0.000004, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.19%, turnover=9198104. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T14:14:59+00:00, last15m_closed_end=2026-10-16T14:15+00:00, prior8high=0.079390, depth_time=2026-10-16T14:15:07+00:00, book20_bid_proxy_usdt=422105, book20_ask_proxy_usdt=338158, funding_indicative=0.000009, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.18%, turnover=38993025. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
