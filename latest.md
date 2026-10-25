# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T16:15:08Z**
- feed_generated_utc: 2026-10-25T16:15:11+00:00
- source_sha256: `e6ed150101de2cdc633303ac0684a167725d825e06e42045c6e55a23806de94a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T16:15+00:00, close=80573.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T16:00+00:00, close=80602.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T16:00+00:00, close=80602.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.592100|-4.02|-30.94|-3.99|12646081|1.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.592100|1.650000|1.592100|6.35|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-25T16:15:02+00:00, last15m_closed_end=2026-10-25T16:15+00:00, prior8high=1.699100, depth_time=2026-10-25T16:15:08+00:00, book20_bid_proxy_usdt=31628, book20_ask_proxy_usdt=12414, funding_indicative=-0.007985, next_funding_utc=2026-10-25T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.02%, turnover=12646081. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
