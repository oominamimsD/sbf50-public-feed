# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T22:45:14Z**
- feed_generated_utc: 2026-11-03T22:45:16+00:00
- source_sha256: `fc7e2afc8ae0b87c4dc59a5491ad70c551e0681a22aabd673924034854ffc4a2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T22:45+00:00, close=77797, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T22:00+00:00, close=77870.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.443700|-4.80|106.62|-4.97|5252126|2.08|
|AKE_USDT|0.003962|-4.66|-81.24|-4.83|13794613|5.05|
|QNT_USDT|192.380000|-1.55|-2.78|-1.72|59530218|1.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003962|0.003890|0.003962|0.53|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.443700|1.427900|1.443700|0.76|N|Y/Y|N/N|Y|N|
|QNT_USDT|192.380000|191.150000|192.380000|1.18|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T22:45:03+00:00, last15m_closed_end=2026-11-03T22:45+00:00, prior8high=0.004140, depth_time=2026-11-03T22:45:08+00:00, book20_bid_proxy_usdt=31003, book20_ask_proxy_usdt=56484, funding_indicative=-0.000780, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.66%, turnover=13794613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-11-03T22:45:03+00:00, last15m_closed_end=2026-11-03T22:45+00:00, prior8high=1.469200, depth_time=2026-11-03T22:45:05+00:00, book20_bid_proxy_usdt=8788, book20_ask_proxy_usdt=9942, funding_indicative=0.000050, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.80%, turnover=5252126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T22:45:03+00:00, last15m_closed_end=2026-11-03T22:45+00:00, prior8high=194.210000, depth_time=2026-11-03T22:45:13+00:00, book20_bid_proxy_usdt=57495, book20_ask_proxy_usdt=71831, funding_indicative=0.000061, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=59530218. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
