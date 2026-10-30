# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T20:00:15Z**
- feed_generated_utc: 2026-10-30T20:00:17+00:00
- source_sha256: `d0d99f023f8457d6df90e9861c8f1f9a0fc3a0f1f581219881a908090c771c8b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.126000|-12.17|114.51|-11.28|6787732|6.21|
|BLESS_USDT|0.009100|-7.62|11.50|-6.73|15206822|3.30|
|Q_USDT|0.044620|-6.02|-62.29|-5.13|23651778|2.24|
|LIT_USDT|2.757400|-2.36|-17.04|-1.47|12516094|0.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009100|0.008786|0.009100|0.51|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.126000|1.072200|1.126000|0.88|N|Y/Y|Y/N|Y|N|
|LIT_USDT|2.757400|2.683300|2.757400|1.29|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.044620|0.044090|0.044670|0.45|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T19:59:59+00:00, last15m_closed_end=2026-10-30T20:00+00:00, prior8high=0.009789, depth_time=2026-10-30T20:00:10+00:00, book20_bid_proxy_usdt=15678, book20_ask_proxy_usdt=11830, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.62%, turnover=15206822. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T19:59:59+00:00, last15m_closed_end=2026-10-30T20:00+00:00, prior8high=1.289400, depth_time=2026-10-30T20:00:07+00:00, book20_bid_proxy_usdt=5964, book20_ask_proxy_usdt=10258, funding_indicative=0.000114, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.17%, turnover=6787732. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T19:59:59+00:00, last15m_closed_end=2026-10-30T20:00+00:00, prior8high=2.764100, depth_time=2026-10-30T20:00:13+00:00, book20_bid_proxy_usdt=29372, book20_ask_proxy_usdt=24472, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.36%, turnover=12516094. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T20:00:03+00:00, last15m_closed_end=2026-10-30T20:00+00:00, prior8high=0.047530, depth_time=2026-10-30T20:00:12+00:00, book20_bid_proxy_usdt=27986, book20_ask_proxy_usdt=25014, funding_indicative=0.000069, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.02%, turnover=23651778. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
