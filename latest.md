# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T01:15:12Z**
- feed_generated_utc: 2026-10-14T01:15:14+00:00
- source_sha256: `c48014ef67d008e090960868a08d87ef13feea41be156a59083e2734150848c0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T01:15+00:00, close=83296.6, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T01:00+00:00, close=83370.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CT_USDT|0.362520|-2.48|-2.44|-2.36|5137753|0.28|
|STRK_USDT|0.085500|-1.64|63.82|-1.52|33973607|1.17|
|OGN_USDT|0.034710|-1.39|54.88|-1.27|5199056|5.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.362520|0.356040|0.362520|0.22|N|Y/Y|N/N|N|N|
|OGN_USDT|0.034710|0.034490|0.034710|0.88|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.085500|0.084050|0.085500|0.72|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-14T01:15:01+00:00, last15m_closed_end=2026-10-14T01:15+00:00, prior8high=0.364910, depth_time=2026-10-14T01:15:07+00:00, book20_bid_proxy_usdt=10453, book20_ask_proxy_usdt=9566, funding_indicative=0.000050, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.48%, turnover=5137753. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-14T01:15:01+00:00, last15m_closed_end=2026-10-14T01:15+00:00, prior8high=0.035070, depth_time=2026-10-14T01:15:11+00:00, book20_bid_proxy_usdt=195270, book20_ask_proxy_usdt=136538, funding_indicative=-0.000089, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.39%, turnover=5199056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T01:15:01+00:00, last15m_closed_end=2026-10-14T01:15+00:00, prior8high=0.086530, depth_time=2026-10-14T01:15:09+00:00, book20_bid_proxy_usdt=171505, book20_ask_proxy_usdt=143132, funding_indicative=0.000005, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.64%, turnover=33973607. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
