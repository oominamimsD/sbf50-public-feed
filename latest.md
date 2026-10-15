# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T15:00:15Z**
- feed_generated_utc: 2026-10-15T15:00:16+00:00
- source_sha256: `68635f4f7421a9704ca75766567a6e0893c85c60ab5164a3a13872b616f1b3be`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T15:00+00:00, close=81844.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T15:00+00:00, close=81844.8, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-15T12:00+00:00, close=80940.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.927600|-18.96|55.91|-19.25|31206568|3.11|
|PUMPFUN_USDT|0.004436|-5.97|-29.26|-6.26|24695810|2.25|
|LIT_USDT|3.031000|-5.25|-13.39|-5.54|6059984|0.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.927600|1.906000|1.929600|0.67|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.031000|2.918900|3.031000|2.14|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004436|0.004236|0.004437|3.19|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-15T15:00:01+00:00, last15m_closed_end=2026-10-15T15:00+00:00, prior8high=2.057800, depth_time=2026-10-15T15:00:07+00:00, book20_bid_proxy_usdt=8463, book20_ask_proxy_usdt=12131, funding_indicative=0.000050, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=4, 24h_change=-18.96%, turnover=31206568. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-15T15:00:01+00:00, last15m_closed_end=2026-10-15T15:00+00:00, prior8high=3.048900, depth_time=2026-10-15T15:00:14+00:00, book20_bid_proxy_usdt=38289, book20_ask_proxy_usdt=22091, funding_indicative=0.000050, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.25%, turnover=6059984. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-15T15:00:01+00:00, last15m_closed_end=2026-10-15T15:00+00:00, prior8high=0.004447, depth_time=2026-10-15T15:00:11+00:00, book20_bid_proxy_usdt=1847432, book20_ask_proxy_usdt=845878, funding_indicative=0.000000, next_funding_utc=2026-10-15T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.97%, turnover=24695810. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
