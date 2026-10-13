# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T17:00:19Z**
- feed_generated_utc: 2026-10-13T17:00:22+00:00
- source_sha256: `b2ba75cfb2f57d3a5ec94974b6ed3fa5485ae7101b717e0f9e2321c6985949ea`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T17:00+00:00, close=83347, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T17:00+00:00, close=83347, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.056880|-19.43|30.16|-19.36|22160470|1.76|
|W_USDT|0.016765|-6.71|15.52|-6.64|11534526|7.75|
|PYTH_USDT|0.079730|-3.75|2.44|-3.68|7824370|2.51|
|OGN_USDT|0.035300|-1.80|57.51|-1.73|7835899|2.83|
|STRK_USDT|0.084350|-1.25|61.62|-1.18|49436093|1.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|OGN_USDT|0.035300|0.034890|0.035290|0.14|N|Y/Y|N/N|N|N|
|PYTH_USDT|0.079730|0.077410|0.079730|0.34|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.084350|0.082420|0.084350|0.57|N|Y/Y|Y/Y|N|N|
|S_USDT|0.056880|0.052180|0.056880|0.67|N|Y/N|N/N|N|N|
|W_USDT|0.016765|0.016711|0.016765|0.90|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- OGN_USDT: quote_utc=2026-10-13T17:00:01+00:00, last15m_closed_end=2026-10-13T17:00+00:00, prior8high=0.036770, depth_time=2026-10-13T17:00:14+00:00, book20_bid_proxy_usdt=176436, book20_ask_proxy_usdt=186057, funding_indicative=-0.000786, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.80%, turnover=7835899. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-13T17:00:01+00:00, last15m_closed_end=2026-10-13T17:00+00:00, prior8high=0.083530, depth_time=2026-10-13T17:00:11+00:00, book20_bid_proxy_usdt=158450, book20_ask_proxy_usdt=65257, funding_indicative=0.000009, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.75%, turnover=7824370. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T17:00:01+00:00, last15m_closed_end=2026-10-13T17:00+00:00, prior8high=0.087530, depth_time=2026-10-13T17:00:18+00:00, book20_bid_proxy_usdt=136934, book20_ask_proxy_usdt=330333, funding_indicative=-0.000003, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.25%, turnover=49436093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-13T17:00:01+00:00, last15m_closed_end=2026-10-13T17:00+00:00, prior8high=0.071230, depth_time=2026-10-13T17:00:09+00:00, book20_bid_proxy_usdt=87816, book20_ask_proxy_usdt=96292, funding_indicative=-0.000195, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-19.43%, turnover=22160470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T17:00:01+00:00, last15m_closed_end=2026-10-13T17:00+00:00, prior8high=0.018134, depth_time=2026-10-13T17:00:11+00:00, book20_bid_proxy_usdt=57347, book20_ask_proxy_usdt=36973, funding_indicative=-0.000318, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.71%, turnover=11534526. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
