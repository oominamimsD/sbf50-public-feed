# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T18:00:10Z**
- feed_generated_utc: 2026-10-15T18:00:12+00:00
- source_sha256: `4cf38467343d871401f2a0d917d69fede50b7f88725dfec07770e03a2c4978be`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T18:00+00:00, close=82393.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T18:00+00:00, close=82393.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T16:00+00:00, close=82375.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.051490|-3.39|54.67|-3.39|10983402|7.78|
|BTW_USDT|1.887300|-1.05|35.94|-1.05|27009370|1.59|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.887300|1.835000|1.887600|0.47|N|Y/Y|Y/Y|Y|N|
|WAL_USDT|0.051490|0.050240|0.051600|0.25|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-15T18:00:02+00:00, last15m_closed_end=2026-10-15T18:00+00:00, prior8high=1.928900, depth_time=2026-10-15T18:00:09+00:00, book20_bid_proxy_usdt=6595, book20_ask_proxy_usdt=4905, funding_indicative=0.000050, next_funding_utc=2026-10-15T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.05%, turnover=27009370. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T18:00:02+00:00, last15m_closed_end=2026-10-15T18:00+00:00, prior8high=0.053900, depth_time=2026-10-15T18:00:07+00:00, book20_bid_proxy_usdt=119176, book20_ask_proxy_usdt=124977, funding_indicative=-0.000490, next_funding_utc=2026-10-15T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.39%, turnover=10983402. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
