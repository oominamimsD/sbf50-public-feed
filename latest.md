# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T04:45:11Z**
- feed_generated_utc: 2026-10-16T04:45:13+00:00
- source_sha256: `64f803fc420933693fe7275b6c108c122397419ec1d067f4f1fa10305e749ad7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T04:45+00:00, close=82000.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEREBRO_USDT|0.039735|-22.53|44.71|-22.10|7085517|2.01|
|WAL_USDT|0.046470|-12.81|39.59|-12.38|5073137|2.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|WAL_USDT|0.046470|0.044820|0.046470|0.99|N|Y/Y|Y/N|Y|N|
|ZEREBRO_USDT|0.039735|0.038865|0.039731|0.82|N|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- WAL_USDT: quote_utc=2026-10-16T04:45:00+00:00, last15m_closed_end=2026-10-16T04:45+00:00, prior8high=0.046110, depth_time=2026-10-16T04:45:10+00:00, book20_bid_proxy_usdt=189800, book20_ask_proxy_usdt=212179, funding_indicative=-0.000566, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.81%, turnover=5073137. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T04:45:00+00:00, last15m_closed_end=2026-10-16T04:45+00:00, prior8high=0.053456, depth_time=2026-10-16T04:45:08+00:00, book20_bid_proxy_usdt=7563, book20_ask_proxy_usdt=6266, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-22.53%, turnover=7085517. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
