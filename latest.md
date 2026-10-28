# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T00:00:11Z**
- feed_generated_utc: 2026-10-28T00:00:14+00:00
- source_sha256: `69599504d6f92ae42da2d6c269b79bdfff72af200e119af30ea7f764d5ee6cf0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T00:00+00:00, close=80868.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T00:00+00:00, close=80868.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T00:00+00:00, close=80868.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.021635|-26.82|-30.41|-27.23|5174597|0.93|
|Q_USDT|0.053096|-19.53|-56.74|-19.94|42299318|0.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.021635|0.021424|0.021635|0.72|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.053096|0.051075|0.053096|0.80|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T00:00:03+00:00, last15m_closed_end=2026-10-28T00:00+00:00, prior8high=0.022038, depth_time=2026-10-28T00:00:08+00:00, book20_bid_proxy_usdt=8422, book20_ask_proxy_usdt=6075, funding_indicative=0.000050, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-26.82%, turnover=5174597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T00:00:03+00:00, last15m_closed_end=2026-10-28T00:00+00:00, prior8high=0.055318, depth_time=2026-10-28T00:00:10+00:00, book20_bid_proxy_usdt=30684, book20_ask_proxy_usdt=33151, funding_indicative=-0.000171, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-19.53%, turnover=42299318. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
