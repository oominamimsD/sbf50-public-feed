# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T23:30:12Z**
- feed_generated_utc: 2026-10-15T23:30:14+00:00
- source_sha256: `30cd4284e47f70f955e0a615824e87a8ca2d6523fe979b62413ddfa8fba124d9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T23:30+00:00, close=82200.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-15T23:00+00:00, close=82414, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T20:00+00:00, close=82350.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.050630|-5.00|52.08|-4.79|7440923|9.88|
|BTW_USDT|1.821500|-4.50|31.20|-4.29|23064533|1.65|
|NIL_USDT|0.084630|-2.58|-2.26|-2.37|12865145|1.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.821500|1.847900|1.821500|1.82|Y|Y/Y|Y/Y|Y|Y|
|NIL_USDT|0.084630|0.082350|0.084630|0.54|N|Y/Y|N/N|Y|N|
|WAL_USDT|0.050630|0.050140|0.050630|0.17|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-15T23:30:00+00:00, last15m_closed_end=2026-10-15T23:30+00:00, prior8high=1.944100, depth_time=2026-10-15T23:30:09+00:00, book20_bid_proxy_usdt=11089, book20_ask_proxy_usdt=16202, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.50%, turnover=23064533. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-15T23:30:00+00:00, last15m_closed_end=2026-10-15T23:30+00:00, prior8high=0.084580, depth_time=2026-10-15T23:30:11+00:00, book20_bid_proxy_usdt=30473, book20_ask_proxy_usdt=19002, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.58%, turnover=12865145. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T23:30:00+00:00, last15m_closed_end=2026-10-15T23:30+00:00, prior8high=0.051730, depth_time=2026-10-15T23:30:04+00:00, book20_bid_proxy_usdt=150894, book20_ask_proxy_usdt=152072, funding_indicative=-0.000327, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.00%, turnover=7440923. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
