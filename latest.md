# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T01:00:14Z**
- feed_generated_utc: 2026-10-16T01:00:16+00:00
- source_sha256: `9e65b795bc06d080853dcbf7f14693e6df137f23795314bdccb44fe92fdfc452`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T01:00+00:00, close=82297.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T01:00+00:00, close=82297.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T00:00+00:00, close=82195.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.846000|-4.33|32.96|-4.24|22027798|1.63|
|WAL_USDT|0.051230|-3.88|53.89|-3.79|6556557|7.80|
|NIL_USDT|0.086360|-3.05|-0.26|-2.96|11158583|3.48|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.846000|1.805400|1.846000|0.56|N|Y/Y|Y/Y|Y|N|
|NIL_USDT|0.086360|0.083630|0.086360|3.49|N|N/Y|N/N|Y|N|
|WAL_USDT|0.051230|0.050140|0.051200|1.71|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-16T01:00:00+00:00, last15m_closed_end=2026-10-16T01:00+00:00, prior8high=1.901700, depth_time=2026-10-16T01:00:08+00:00, book20_bid_proxy_usdt=9949, book20_ask_proxy_usdt=7564, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.33%, turnover=22027798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T01:00:01+00:00, last15m_closed_end=2026-10-16T01:00+00:00, prior8high=0.086490, depth_time=2026-10-16T01:00:13+00:00, book20_bid_proxy_usdt=20995, book20_ask_proxy_usdt=16744, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=11158583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-16T01:00:00+00:00, last15m_closed_end=2026-10-16T01:00+00:00, prior8high=0.051320, depth_time=2026-10-16T01:00:08+00:00, book20_bid_proxy_usdt=156417, book20_ask_proxy_usdt=128484, funding_indicative=-0.000493, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.88%, turnover=6556557. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
