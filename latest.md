# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T20:15:11Z**
- feed_generated_utc: 2026-10-15T20:15:13+00:00
- source_sha256: `712022ce12a182148795ce17c3f5b9e0ad85e3a8e186c229b2ee2b3817408840`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T20:15+00:00, close=82269.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T20:00+00:00, close=82350.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T20:00+00:00, close=82350.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.051090|-4.14|53.46|-4.02|9556029|1.96|
|NIL_USDT|0.083630|-3.74|-3.41|-3.62|16754803|2.39|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NIL_USDT|0.083630|0.084640|0.083580|2.67|Y|Y/N|N/N|Y|N|
|WAL_USDT|0.051090|0.050510|0.051040|0.76|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NIL_USDT: quote_utc=2026-10-15T20:15:01+00:00, last15m_closed_end=2026-10-15T20:15+00:00, prior8high=0.094970, depth_time=2026-10-15T20:15:10+00:00, book20_bid_proxy_usdt=14492, book20_ask_proxy_usdt=13820, funding_indicative=0.000042, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.74%, turnover=16754803. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T20:15:01+00:00, last15m_closed_end=2026-10-15T20:15+00:00, prior8high=0.051600, depth_time=2026-10-15T20:15:08+00:00, book20_bid_proxy_usdt=88498, book20_ask_proxy_usdt=84230, funding_indicative=-0.000188, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.14%, turnover=9556029. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
