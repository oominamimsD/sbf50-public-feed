# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T01:00:17Z**
- feed_generated_utc: 2026-10-20T01:00:19+00:00
- source_sha256: `1e4f43054cbc80f9d1ed8ed67924ae9bf1d0d681bc9e4dd52508e80e763cdea8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T01:00+00:00, close=81700.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T01:00+00:00, close=81700.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|193.270000|-2.15|-15.37|-1.88|73571877|2.07|
|SAND_USDT|0.058150|-1.67|-6.34|-1.40|8581143|1.72|
|NEAR_USDT|4.828000|-1.54|-12.99|-1.27|168317304|6.21|
|TAO_USDT|266.160000|-1.44|-7.03|-1.17|53877459|1.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NEAR_USDT|4.828000|4.833000|4.826000|1.51|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|193.270000|192.920000|193.270000|0.69|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.058150|0.058140|0.058190|5.01|N|Y/Y|N/Y|Y|N|
|TAO_USDT|266.160000|265.540000|266.160000|0.39|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NEAR_USDT: quote_utc=2026-10-20T01:00:02+00:00, last15m_closed_end=2026-10-20T01:00+00:00, prior8high=4.944000, depth_time=2026-10-20T01:00:13+00:00, book20_bid_proxy_usdt=2014249, book20_ask_proxy_usdt=2625145, funding_indicative=0.000018, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=168317304. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T01:00:02+00:00, last15m_closed_end=2026-10-20T01:00+00:00, prior8high=195.340000, depth_time=2026-10-20T01:00:08+00:00, book20_bid_proxy_usdt=57991, book20_ask_proxy_usdt=93200, funding_indicative=0.000062, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=73571877. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T01:00:02+00:00, last15m_closed_end=2026-10-20T01:00+00:00, prior8high=0.059370, depth_time=2026-10-20T01:00:10+00:00, book20_bid_proxy_usdt=454534, book20_ask_proxy_usdt=782880, funding_indicative=-0.002391, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=8581143. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T01:00:02+00:00, last15m_closed_end=2026-10-20T01:00+00:00, prior8high=269.030000, depth_time=2026-10-20T01:00:16+00:00, book20_bid_proxy_usdt=79718, book20_ask_proxy_usdt=62993, funding_indicative=0.000038, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.44%, turnover=53877459. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
