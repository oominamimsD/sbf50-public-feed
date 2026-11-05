# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T20:30:09Z**
- feed_generated_utc: 2026-11-05T20:30:10+00:00
- source_sha256: `c3a614006cfebf254c520031a5fae5598450a32973eab7d1a1accb5d3a9adc4f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T20:30+00:00, close=76065.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002125|-17.63|-89.91|-17.69|19408532|4.72|
|FLUID_USDT|2.375000|-6.20|15.06|-6.26|8585864|4.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002125|0.001878|0.002125|0.62|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.375000|2.359000|2.375000|0.36|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T20:30:01+00:00, last15m_closed_end=2026-11-05T20:30+00:00, prior8high=0.002495, depth_time=2026-11-05T20:30:06+00:00, book20_bid_proxy_usdt=36593, book20_ask_proxy_usdt=46075, funding_indicative=-0.006258, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-17.63%, turnover=19408532. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T20:30:01+00:00, last15m_closed_end=2026-11-05T20:30+00:00, prior8high=2.440000, depth_time=2026-11-05T20:30:08+00:00, book20_bid_proxy_usdt=169027, book20_ask_proxy_usdt=186672, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.20%, turnover=8585864. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
