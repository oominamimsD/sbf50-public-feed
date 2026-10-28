# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T21:45:14Z**
- feed_generated_utc: 2026-10-28T21:45:17+00:00
- source_sha256: `4805a27488cfb7521a2dd1a2565e40e24f98b5131e659023614d220511d32ffc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T21:45+00:00, close=81217.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T21:00+00:00, close=81291.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|289.780000|-1.07|0.03|-1.92|5911748|5.52|
|XMR_USDT|598.560000|-0.91|0.39|-1.76|5419499|0.67|
|HBAR_USDT|0.075520|-0.51|-12.12|-1.36|13215490|1.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|289.780000|286.690000|289.810000|0.56|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.075520|0.075110|0.075520|1.19|N|Y/Y|Y/Y|N|N|
|XMR_USDT|598.560000|595.790000|598.570000|0.12|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-28T21:45:02+00:00, last15m_closed_end=2026-10-28T21:45+00:00, prior8high=292.510000, depth_time=2026-10-28T21:45:08+00:00, book20_bid_proxy_usdt=52559, book20_ask_proxy_usdt=69278, funding_indicative=0.000021, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=5911748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T21:45:02+00:00, last15m_closed_end=2026-10-28T21:45+00:00, prior8high=0.076980, depth_time=2026-10-28T21:45:08+00:00, book20_bid_proxy_usdt=521894, book20_ask_proxy_usdt=1212144, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.51%, turnover=13215490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T21:45:02+00:00, last15m_closed_end=2026-10-28T21:45+00:00, prior8high=604.680000, depth_time=2026-10-28T21:45:10+00:00, book20_bid_proxy_usdt=50523, book20_ask_proxy_usdt=15463, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.91%, turnover=5419499. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
