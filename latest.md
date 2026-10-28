# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T21:00:11Z**
- feed_generated_utc: 2026-10-28T21:00:15+00:00
- source_sha256: `531db714275fe866ed516fe406401cc12844e45367af639bffecb5238c3fd24d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T21:00+00:00, close=81291.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T21:00+00:00, close=81291.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|289.830000|-1.06|0.05|-2.00|5806802|4.49|
|BTW_USDT|1.726200|-0.90|17.44|-1.84|13328905|5.79|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|289.830000|283.930000|289.880000|0.56|N|Y/Y|N/N|N|N|
|BTW_USDT|1.726200|1.697300|1.726200|1.30|N|N/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-28T21:00:01+00:00, last15m_closed_end=2026-10-28T21:00+00:00, prior8high=292.510000, depth_time=2026-10-28T21:00:08+00:00, book20_bid_proxy_usdt=45249, book20_ask_proxy_usdt=73188, funding_indicative=0.000029, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=5806802. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-28T21:00:00+00:00, last15m_closed_end=2026-10-28T21:00+00:00, prior8high=1.745400, depth_time=2026-10-28T21:00:10+00:00, book20_bid_proxy_usdt=16756, book20_ask_proxy_usdt=14007, funding_indicative=0.000050, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.90%, turnover=13328905. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
