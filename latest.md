# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T14:45:12Z**
- feed_generated_utc: 2026-10-20T14:45:14+00:00
- source_sha256: `f6fb2977decc4c92bb380af3868da88d48299408f892b81628e174d78faaeb02`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T14:45+00:00, close=83095.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T14:00+00:00, close=82114, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.064541|-25.84|287.35|-27.27|8576397|2.32|
|AKE_USDT|0.030461|-0.99|29.40|-2.42|6712204|0.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.064541|0.064572|0.064541|1.08|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.030461|0.029930|0.030515|0.91|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T14:44:59+00:00, last15m_closed_end=2026-10-20T14:45+00:00, prior8high=0.069150, depth_time=2026-10-20T14:45:06+00:00, book20_bid_proxy_usdt=12130, book20_ask_proxy_usdt=12984, funding_indicative=0.000073, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-25.84%, turnover=8576397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-20T14:44:59+00:00, last15m_closed_end=2026-10-20T14:45+00:00, prior8high=0.030823, depth_time=2026-10-20T14:45:11+00:00, book20_bid_proxy_usdt=11360, book20_ask_proxy_usdt=13876, funding_indicative=0.000075, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.99%, turnover=6712204. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
