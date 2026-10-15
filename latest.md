# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T23:15:14Z**
- feed_generated_utc: 2026-10-15T23:15:16+00:00
- source_sha256: `d2773dbd48a6aa2249950ff81d9c86f3ed762764f2c178b2f0345765e8b29908`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T23:15+00:00, close=82159.9, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T23:00+00:00, close=82414, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T20:00+00:00, close=82350.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ANTHROPIC_USDT|1841.700000|-5.81|-8.95|-5.55|6932721|8.74|
|WAL_USDT|0.050380|-5.47|51.33|-5.21|7438559|1.99|
|BTW_USDT|1.853400|-2.83|33.50|-2.57|22891273|2.69|
|NIL_USDT|0.084580|-2.64|-2.32|-2.38|12848404|3.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1841.700000|1771.200000|1841.700000|4.81|N|Y/Y|N/Y|Y|N|
|BTW_USDT|1.853400|1.861800|1.853900|1.64|Y|Y/Y|Y/Y|Y|Y|
|NIL_USDT|0.084580|0.082010|0.084580|0.22|N|Y/Y|N/N|Y|N|
|WAL_USDT|0.050380|0.050300|0.050380|0.18|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-10-15T23:15:01+00:00, last15m_closed_end=2026-10-15T23:15+00:00, prior8high=1906.630000, depth_time=2026-10-15T23:15:07+00:00, book20_bid_proxy_usdt=21027, book20_ask_proxy_usdt=9241, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.81%, turnover=6932721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-15T23:15:01+00:00, last15m_closed_end=2026-10-15T23:15+00:00, prior8high=1.944100, depth_time=2026-10-15T23:15:11+00:00, book20_bid_proxy_usdt=13322, book20_ask_proxy_usdt=11303, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.83%, turnover=22891273. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-15T23:15:01+00:00, last15m_closed_end=2026-10-15T23:15+00:00, prior8high=0.084450, depth_time=2026-10-15T23:15:14+00:00, book20_bid_proxy_usdt=34581, book20_ask_proxy_usdt=27245, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.64%, turnover=12848404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T23:15:01+00:00, last15m_closed_end=2026-10-15T23:15+00:00, prior8high=0.051730, depth_time=2026-10-15T23:15:10+00:00, book20_bid_proxy_usdt=149057, book20_ask_proxy_usdt=146498, funding_indicative=-0.000309, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.47%, turnover=7438559. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
