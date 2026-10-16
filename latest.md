# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T02:45:13Z**
- feed_generated_utc: 2026-10-16T02:45:15+00:00
- source_sha256: `33fcdf831614b97f2cfa891a79371aef8c41d62210157c7f2845dc04d6464683`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T02:45+00:00, close=82153.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T02:00+00:00, close=82052.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T00:00+00:00, close=82195.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.045620|-14.40|37.03|-14.14|6300558|4.38|
|RLC_USDT|0.866000|-5.44|18.12|-5.18|5003318|1.16|
|BTW_USDT|1.862100|-2.37|34.12|-2.11|22179647|3.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.862100|1.800900|1.863600|0.55|N|Y/Y|Y/Y|Y|N|
|RLC_USDT|0.866000|0.864200|0.866000|1.16|N|Y/N|Y/Y|Y|N|
|WAL_USDT|0.045620|0.044820|0.045620|1.99|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-16T02:44:59+00:00, last15m_closed_end=2026-10-16T02:45+00:00, prior8high=1.909400, depth_time=2026-10-16T02:45:12+00:00, book20_bid_proxy_usdt=10427, book20_ask_proxy_usdt=9882, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.37%, turnover=22179647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-16T02:44:59+00:00, last15m_closed_end=2026-10-16T02:45+00:00, prior8high=0.884100, depth_time=2026-10-16T02:45:09+00:00, book20_bid_proxy_usdt=90532, book20_ask_proxy_usdt=77282, funding_indicative=-0.000628, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.44%, turnover=5003318. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-16T02:44:59+00:00, last15m_closed_end=2026-10-16T02:45+00:00, prior8high=0.051850, depth_time=2026-10-16T02:45:07+00:00, book20_bid_proxy_usdt=177812, book20_ask_proxy_usdt=152895, funding_indicative=-0.000598, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.40%, turnover=6300558. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
