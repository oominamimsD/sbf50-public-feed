# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T03:00:13Z**
- feed_generated_utc: 2026-10-16T03:00:14+00:00
- source_sha256: `b2a5426165e792218b7ffca0c9cb0351460deea77d337867d418d648494ea509`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T03:00+00:00, close=82016.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T03:00+00:00, close=82016.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T00:00+00:00, close=82195.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.045500|-14.63|36.67|-14.19|5521506|2.20|
|ZKSYNC_USDT|0.016474|-4.17|48.13|-3.73|7908676|1.21|
|NIL_USDT|0.086590|-2.79|0.00|-2.35|10413329|2.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NIL_USDT|0.086590|0.085120|0.086590|7.19|N|N/N|N/N|Y|N|
|WAL_USDT|0.045500|0.044820|0.045490|1.36|N|Y/Y|N/N|Y|N|
|ZKSYNC_USDT|0.016474|0.016384|0.016474|1.37|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NIL_USDT: quote_utc=2026-10-16T03:00:00+00:00, last15m_closed_end=2026-10-16T03:00+00:00, prior8high=0.087720, depth_time=2026-10-16T03:00:11+00:00, book20_bid_proxy_usdt=19702, book20_ask_proxy_usdt=26167, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.79%, turnover=10413329. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-16T03:00:00+00:00, last15m_closed_end=2026-10-16T03:00+00:00, prior8high=0.051850, depth_time=2026-10-16T03:00:07+00:00, book20_bid_proxy_usdt=171570, book20_ask_proxy_usdt=138548, funding_indicative=-0.000608, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.63%, turnover=5521506. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZKSYNC_USDT: quote_utc=2026-10-16T03:00:00+00:00, last15m_closed_end=2026-10-16T03:00+00:00, prior8high=0.016842, depth_time=2026-10-16T03:00:08+00:00, book20_bid_proxy_usdt=31900, book20_ask_proxy_usdt=5586, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.17%, turnover=7908676. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
