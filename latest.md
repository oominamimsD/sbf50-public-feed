# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T00:45:11Z**
- feed_generated_utc: 2026-10-20T00:45:13+00:00
- source_sha256: `373386144d7ce534a960697b05467a7ba28a24f1102a3c45b3bb60bcebe592a0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T00:45+00:00, close=81658.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|SAND_USDT|0.058250|-1.50|-6.18|-1.19|8762115|3.43|
|CT_USDT|0.325160|-1.49|-4.96|-1.18|5191317|0.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.325160|0.315910|0.325160|0.36|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.058250|0.058460|0.058250|2.84|Y|N/Y|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-20T00:45:00+00:00, last15m_closed_end=2026-10-20T00:45+00:00, prior8high=0.328280, depth_time=2026-10-20T00:45:10+00:00, book20_bid_proxy_usdt=7523, book20_ask_proxy_usdt=9172, funding_indicative=-0.001456, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.49%, turnover=5191317. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T00:45:01+00:00, last15m_closed_end=2026-10-20T00:45+00:00, prior8high=0.059370, depth_time=2026-10-20T00:45:07+00:00, book20_bid_proxy_usdt=448356, book20_ask_proxy_usdt=509970, funding_indicative=-0.002431, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=8762115. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
