# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T16:30:10Z**
- feed_generated_utc: 2026-10-27T16:30:14+00:00
- source_sha256: `5b8b39c538e79e9e6e4e586606cb7edec9df65ce6f598ef510700ef710c27497`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T16:30+00:00, close=80566.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T16:00+00:00, close=80529.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T16:00+00:00, close=80529.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.061138|-3.84|-50.19|-3.89|59217083|5.73|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|Q_USDT|0.061138|0.062197|0.061323|2.43|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- Q_USDT: quote_utc=2026-10-27T16:30:02+00:00, last15m_closed_end=2026-10-27T16:30+00:00, prior8high=0.073809, depth_time=2026-10-27T16:30:10+00:00, book20_bid_proxy_usdt=2318, book20_ask_proxy_usdt=3114, funding_indicative=0.000050, next_funding_utc=2026-10-27T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.84%, turnover=59217083. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
