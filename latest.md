# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T00:15:15Z**
- feed_generated_utc: 2026-10-16T00:15:17+00:00
- source_sha256: `c9e37b51c9334818de8c9e41179b7421393c7caa17f9d56a1460ce1ca8293ac0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T00:15+00:00, close=82324.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T00:00+00:00, close=82195.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T00:00+00:00, close=82195.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.050250|-5.72|50.94|-5.66|6955331|1.99|
|ANTHROPIC_USDT|1847.410000|-5.52|-8.67|-5.46|7071035|7.09|
|NIL_USDT|0.084450|-2.79|-2.47|-2.73|12155886|3.55|
|BTW_USDT|1.858900|-2.54|33.89|-2.48|22678466|1.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1847.410000|1790.150000|1847.410000|0.55|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.858900|1.805400|1.859300|2.69|N|Y/Y|Y/Y|Y|N|
|NIL_USDT|0.084450|0.083520|0.084450|0.44|N|Y/Y|N/N|Y|N|
|WAL_USDT|0.050250|0.050140|0.050250|1.71|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-10-16T00:14:59+00:00, last15m_closed_end=2026-10-16T00:15+00:00, prior8high=1897.040000, depth_time=2026-10-16T00:15:08+00:00, book20_bid_proxy_usdt=16464, book20_ask_proxy_usdt=10818, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.52%, turnover=7071035. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T00:14:59+00:00, last15m_closed_end=2026-10-16T00:15+00:00, prior8high=1.930000, depth_time=2026-10-16T00:15:14+00:00, book20_bid_proxy_usdt=15444, book20_ask_proxy_usdt=10060, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.54%, turnover=22678466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T00:14:59+00:00, last15m_closed_end=2026-10-16T00:15+00:00, prior8high=0.085310, depth_time=2026-10-16T00:15:12+00:00, book20_bid_proxy_usdt=26221, book20_ask_proxy_usdt=22326, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.79%, turnover=12155886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-16T00:14:59+00:00, last15m_closed_end=2026-10-16T00:15+00:00, prior8high=0.051590, depth_time=2026-10-16T00:15:05+00:00, book20_bid_proxy_usdt=148258, book20_ask_proxy_usdt=116397, funding_indicative=-0.000460, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.72%, turnover=6955331. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
