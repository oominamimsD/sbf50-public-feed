# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T20:00:13Z**
- feed_generated_utc: 2026-10-15T20:00:14+00:00
- source_sha256: `50d6857b14ec638dda9354df0b8ddd29b42e1ee0571f37641cd462ec1414f375`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T20:00+00:00, close=82350.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T20:00+00:00, close=82350.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T20:00+00:00, close=82350.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.051040|-6.26|53.31|-6.87|9541606|3.92|
|NIL_USDT|0.085190|-4.36|-1.61|-4.97|16578278|2.35|
|BTW_USDT|1.917300|-0.63|38.10|-1.24|24441659|2.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.917300|1.852200|1.917200|0.58|N|Y/Y|Y/Y|Y|N|
|NIL_USDT|0.085190|0.088720|0.085210|3.10|Y|Y/N|N/N|Y|N|
|WAL_USDT|0.051040|0.050510|0.051040|0.27|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-15T20:00:00+00:00, last15m_closed_end=2026-10-15T20:00+00:00, prior8high=1.924000, depth_time=2026-10-15T20:00:12+00:00, book20_bid_proxy_usdt=12280, book20_ask_proxy_usdt=8653, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.63%, turnover=24441659. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-15T20:00:00+00:00, last15m_closed_end=2026-10-15T20:00+00:00, prior8high=0.094970, depth_time=2026-10-15T20:00:09+00:00, book20_bid_proxy_usdt=12808, book20_ask_proxy_usdt=16924, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.36%, turnover=16578278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T20:00:00+00:00, last15m_closed_end=2026-10-15T20:00+00:00, prior8high=0.051600, depth_time=2026-10-15T20:00:05+00:00, book20_bid_proxy_usdt=117712, book20_ask_proxy_usdt=90478, funding_indicative=-0.000205, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.26%, turnover=9541606. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
