# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T15:15:11Z**
- feed_generated_utc: 2026-10-15T15:15:12+00:00
- source_sha256: `9b5cec6993ea38cdb2f31aa04e5055edf661e46b851be2e57e7e4153c38e7318`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T15:15+00:00, close=82280.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T15:00+00:00, close=81844.8, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-15T12:00+00:00, close=80940.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.943600|-18.29|57.21|-19.09|31448107|1.55|
|LIT_USDT|3.042500|-5.08|-13.06|-5.88|6227122|0.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.943600|1.906000|1.943600|0.72|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.042500|2.918900|3.042500|1.92|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-15T15:15:00+00:00, last15m_closed_end=2026-10-15T15:15+00:00, prior8high=2.057800, depth_time=2026-10-15T15:15:07+00:00, book20_bid_proxy_usdt=16871, book20_ask_proxy_usdt=11259, funding_indicative=0.000050, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=4, 24h_change=-18.29%, turnover=31448107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-15T15:15:01+00:00, last15m_closed_end=2026-10-15T15:15+00:00, prior8high=3.052500, depth_time=2026-10-15T15:15:07+00:00, book20_bid_proxy_usdt=25684, book20_ask_proxy_usdt=21020, funding_indicative=0.000050, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.08%, turnover=6227122. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
