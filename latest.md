# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T16:30:13Z**
- feed_generated_utc: 2026-11-08T16:30:14+00:00
- source_sha256: `a2bf1fbdbe82a8872a88a020b5b4702cfa038d58a5d5582a7fa278a07778ec0b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T16:30+00:00, close=76019.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.029893|-3.13|51.94|-3.11|14265890|7.03|
|AKE_USDT|0.005265|-1.71|-42.52|-1.69|23336462|3.80|
|ONE_USDT|0.001935|-1.16|66.17|-1.14|21170254|0.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005265|0.005272|0.005265|0.81|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.029893|0.029571|0.029896|0.77|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001935|0.001818|0.001935|0.27|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T16:29:59+00:00, last15m_closed_end=2026-11-08T16:30+00:00, prior8high=0.005501, depth_time=2026-11-08T16:30:09+00:00, book20_bid_proxy_usdt=43371, book20_ask_proxy_usdt=56199, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=23336462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T16:29:59+00:00, last15m_closed_end=2026-11-08T16:30+00:00, prior8high=0.031336, depth_time=2026-11-08T16:30:07+00:00, book20_bid_proxy_usdt=13278, book20_ask_proxy_usdt=10124, funding_indicative=0.000917, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.13%, turnover=14265890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T16:29:59+00:00, last15m_closed_end=2026-11-08T16:30+00:00, prior8high=0.001987, depth_time=2026-11-08T16:30:12+00:00, book20_bid_proxy_usdt=12851, book20_ask_proxy_usdt=9724, funding_indicative=-0.001450, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.16%, turnover=21170254. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
