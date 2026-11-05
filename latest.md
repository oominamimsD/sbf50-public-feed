# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T21:45:17Z**
- feed_generated_utc: 2026-11-05T21:45:18+00:00
- source_sha256: `9fdc7255931b00974d8faad91e7f10f7a06f5f193b7118e79727c5b5fdae2c42`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T21:45+00:00, close=75916.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T21:00+00:00, close=76205.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002160|-16.27|-89.74|-16.16|19776829|4.63|
|FLUID_USDT|2.370000|-6.39|14.82|-6.28|8312819|4.22|
|BCH_USDT|274.040000|-1.82|-4.93|-1.71|10287192|2.19|
|XRP_USDT|1.225300|-1.55|-6.42|-1.44|441114889|0.82|
|ATOM_USDT|1.404000|-1.12|-13.91|-1.01|5197207|7.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002160|0.002009|0.002162|0.45|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.404000|1.400000|1.404000|0.45|N|Y/Y|Y/N|Y|N|
|BCH_USDT|274.040000|271.110000|274.090000|0.27|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.370000|2.355000|2.370000|1.03|N|Y/Y|N/N|Y|N|
|XRP_USDT|1.225300|1.217300|1.225300|0.95|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T21:45:02+00:00, last15m_closed_end=2026-11-05T21:45+00:00, prior8high=0.002390, depth_time=2026-11-05T21:45:06+00:00, book20_bid_proxy_usdt=27079, book20_ask_proxy_usdt=39405, funding_indicative=-0.001222, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-16.27%, turnover=19776829. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-05T21:45:02+00:00, last15m_closed_end=2026-11-05T21:45+00:00, prior8high=1.448000, depth_time=2026-11-05T21:45:15+00:00, book20_bid_proxy_usdt=1950385, book20_ask_proxy_usdt=2140987, funding_indicative=-0.000013, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=5197207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T21:45:02+00:00, last15m_closed_end=2026-11-05T21:45+00:00, prior8high=278.650000, depth_time=2026-11-05T21:45:11+00:00, book20_bid_proxy_usdt=66474, book20_ask_proxy_usdt=65474, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=10287192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T21:45:02+00:00, last15m_closed_end=2026-11-05T21:45+00:00, prior8high=2.424000, depth_time=2026-11-05T21:45:08+00:00, book20_bid_proxy_usdt=228862, book20_ask_proxy_usdt=175674, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.39%, turnover=8312819. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-05T21:45:02+00:00, last15m_closed_end=2026-11-05T21:45+00:00, prior8high=1.245300, depth_time=2026-11-05T21:45:13+00:00, book20_bid_proxy_usdt=3372062, book20_ask_proxy_usdt=2841827, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=441114889. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
