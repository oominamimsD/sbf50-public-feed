# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T08:00:11Z**
- feed_generated_utc: 2026-10-16T08:00:13+00:00
- source_sha256: `c18ec5647fc61a20456c1c7b3b4dd1019ce1f33c1f2886d21228475e0de0e9e4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.079650|-6.38|32.39|-6.88|47050893|1.25|
|NIL_USDT|0.084030|-5.66|-2.95|-6.16|8297174|4.76|
|ZEREBRO_USDT|0.046589|-0.95|69.67|-1.45|6565416|3.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NIL_USDT|0.084030|0.083680|0.084030|1.16|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.079650|0.080360|0.079650|3.29|Y|Y/Y|Y/Y|Y|Y|
|ZEREBRO_USDT|0.046589|0.040007|0.046589|0.59|N|N/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NIL_USDT: quote_utc=2026-10-16T08:00:00+00:00, last15m_closed_end=2026-10-16T08:00+00:00, prior8high=0.086860, depth_time=2026-10-16T08:00:08+00:00, book20_bid_proxy_usdt=26404, book20_ask_proxy_usdt=23011, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.66%, turnover=8297174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T08:00:00+00:00, last15m_closed_end=2026-10-16T08:00+00:00, prior8high=0.084530, depth_time=2026-10-16T08:00:06+00:00, book20_bid_proxy_usdt=309059, book20_ask_proxy_usdt=449386, funding_indicative=-0.000020, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.38%, turnover=47050893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T08:00:00+00:00, last15m_closed_end=2026-10-16T08:00+00:00, prior8high=0.046028, depth_time=2026-10-16T08:00:11+00:00, book20_bid_proxy_usdt=6283, book20_ask_proxy_usdt=5986, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.95%, turnover=6565416. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
