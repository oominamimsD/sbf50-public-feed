# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T07:30:17Z**
- feed_generated_utc: 2026-10-16T07:30:19+00:00
- source_sha256: `3130fc141b0c2758b15e01eab266ec109089abd6e95d1c46942dff6c0458a64f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T07:30+00:00, close=82187.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T07:00+00:00, close=82146.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.081430|-15.49|35.35|-15.27|47553184|1.23|
|ZEREBRO_USDT|0.045420|-11.45|65.42|-11.23|6767413|0.22|
|BTW_USDT|1.790000|-6.15|28.93|-5.93|20889394|1.11|
|AKE_USDT|0.030551|-3.33|5.26|-3.11|21047549|1.64|
|NIL_USDT|0.085210|-1.92|-1.59|-1.70|9109559|1.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030551|0.030300|0.030547|0.81|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.790000|1.822100|1.790000|2.92|Y|Y/N|Y/Y|Y|N|
|NIL_USDT|0.085210|0.085330|0.085210|1.23|N|Y/N|N/N|Y|N|
|STRK_USDT|0.081430|0.082190|0.081430|2.26|Y|Y/Y|N/N|Y|N|
|ZEREBRO_USDT|0.045420|0.038862|0.045425|0.60|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T07:30:00+00:00, last15m_closed_end=2026-10-16T07:30+00:00, prior8high=0.032366, depth_time=2026-10-16T07:30:14+00:00, book20_bid_proxy_usdt=14409, book20_ask_proxy_usdt=11302, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.33%, turnover=21047549. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T07:30:00+00:00, last15m_closed_end=2026-10-16T07:30+00:00, prior8high=2.047500, depth_time=2026-10-16T07:30:12+00:00, book20_bid_proxy_usdt=11190, book20_ask_proxy_usdt=18434, funding_indicative=-0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.15%, turnover=20889394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T07:30:00+00:00, last15m_closed_end=2026-10-16T07:30+00:00, prior8high=0.087950, depth_time=2026-10-16T07:30:16+00:00, book20_bid_proxy_usdt=18192, book20_ask_proxy_usdt=25151, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=9109559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T07:30:00+00:00, last15m_closed_end=2026-10-16T07:30+00:00, prior8high=0.084950, depth_time=2026-10-16T07:30:07+00:00, book20_bid_proxy_usdt=269068, book20_ask_proxy_usdt=392778, funding_indicative=-0.000033, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.49%, turnover=47553184. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T07:30:00+00:00, last15m_closed_end=2026-10-16T07:30+00:00, prior8high=0.044481, depth_time=2026-10-16T07:30:09+00:00, book20_bid_proxy_usdt=6594, book20_ask_proxy_usdt=3892, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.45%, turnover=6767413. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
