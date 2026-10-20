# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T15:00:12Z**
- feed_generated_utc: 2026-10-20T15:00:14+00:00
- source_sha256: `ea4637dbfc0a8e3b0723ebd4d671ba631b5fd52d0cf9cace762cf678a2bb4bfa`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T15:00+00:00, close=83242.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T15:00+00:00, close=83242.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.063674|-26.84|282.15|-28.48|8036302|0.94|
|AKE_USDT|0.030546|0.17|29.76|-1.47|6640477|0.66|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.063674|0.064283|0.063674|1.29|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.030546|0.029930|0.030546|1.00|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T15:00:03+00:00, last15m_closed_end=2026-10-20T15:00+00:00, prior8high=0.069150, depth_time=2026-10-20T15:00:08+00:00, book20_bid_proxy_usdt=7877, book20_ask_proxy_usdt=5784, funding_indicative=0.000084, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-26.84%, turnover=8036302. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-20T15:00:03+00:00, last15m_closed_end=2026-10-20T15:00+00:00, prior8high=0.030823, depth_time=2026-10-20T15:00:11+00:00, book20_bid_proxy_usdt=13367, book20_ask_proxy_usdt=10133, funding_indicative=0.000073, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=0.17%, turnover=6640477. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
