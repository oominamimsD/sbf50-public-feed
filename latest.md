# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T01:30:12Z**
- feed_generated_utc: 2026-10-14T01:30:13+00:00
- source_sha256: `0b9cd8e047328a39a09b2fbae8cc6ec4a8106935ff2bf22d24a2f6028c054e15`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T01:30+00:00, close=83281.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T01:00+00:00, close=83370.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CT_USDT|0.361900|-2.65|-2.61|-2.53|5143159|0.28|
|OGN_USDT|0.034660|-1.53|54.66|-1.41|5202907|2.88|
|STRK_USDT|0.085750|-1.35|64.30|-1.23|34001877|1.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.361900|0.356040|0.361900|0.73|N|Y/Y|N/N|N|N|
|OGN_USDT|0.034660|0.034490|0.034660|0.90|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.085750|0.084060|0.085750|0.15|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-14T01:30:00+00:00, last15m_closed_end=2026-10-14T01:30+00:00, prior8high=0.364910, depth_time=2026-10-14T01:30:04+00:00, book20_bid_proxy_usdt=6811, book20_ask_proxy_usdt=6684, funding_indicative=0.000050, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.65%, turnover=5143159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-14T01:30:00+00:00, last15m_closed_end=2026-10-14T01:30+00:00, prior8high=0.035070, depth_time=2026-10-14T01:30:07+00:00, book20_bid_proxy_usdt=168942, book20_ask_proxy_usdt=161631, funding_indicative=-0.000121, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=5202907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T01:30:00+00:00, last15m_closed_end=2026-10-14T01:30+00:00, prior8high=0.086530, depth_time=2026-10-14T01:30:11+00:00, book20_bid_proxy_usdt=176048, book20_ask_proxy_usdt=253816, funding_indicative=0.000010, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.35%, turnover=34001877. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
