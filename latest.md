# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T22:15:12Z**
- feed_generated_utc: 2026-11-06T22:15:13+00:00
- source_sha256: `ca64fd6668aa8436cb37aab94d6f60807cbade104dad89c2ce7c441c3fb56f72`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T22:15+00:00, close=75979.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T22:00+00:00, close=75895.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.137700|-27.52|-48.15|-27.71|33016986|7.24|
|ANTHROPIC_USDT|1351.800000|-5.54|-19.36|-5.73|6596715|3.48|
|LIT_USDT|3.333500|-1.73|18.03|-1.92|9932377|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1351.800000|1309.270000|1351.800000|0.74|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.333500|3.283100|3.333500|0.58|N|Y/Y|Y/N|Y|N|
|UAI_USDT|0.137700|0.122300|0.137800|0.60|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T22:15:01+00:00, last15m_closed_end=2026-11-06T22:15+00:00, prior8high=1364.300000, depth_time=2026-11-06T22:15:08+00:00, book20_bid_proxy_usdt=23156, book20_ask_proxy_usdt=37143, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.54%, turnover=6596715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T22:15:02+00:00, last15m_closed_end=2026-11-06T22:15+00:00, prior8high=3.356700, depth_time=2026-11-06T22:15:10+00:00, book20_bid_proxy_usdt=41809, book20_ask_proxy_usdt=31990, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.73%, turnover=9932377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T22:15:01+00:00, last15m_closed_end=2026-11-06T22:15+00:00, prior8high=0.149300, depth_time=2026-11-06T22:15:07+00:00, book20_bid_proxy_usdt=215717, book20_ask_proxy_usdt=150566, funding_indicative=0.000042, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-27.52%, turnover=33016986. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
