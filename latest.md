# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T18:45:17Z**
- feed_generated_utc: 2026-10-21T18:45:19+00:00
- source_sha256: `cad681c27893ccfc79af5381cb1b3ff23ce5bf4e6ddbdda4c68f199c08e57821`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T18:45+00:00, close=84659.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T18:00+00:00, close=84635.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002247|-20.99|58.46|-21.17|9112926|4.45|
|BR_USDT|0.518980|-4.16|27.27|-4.34|15451560|0.96|
|AKE_USDT|0.025748|-3.52|-0.51|-3.70|10097796|1.55|
|INJ_USDT|8.629000|-1.47|12.95|-1.65|55903082|2.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025748|0.025666|0.025745|0.65|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.518980|0.513880|0.519450|0.53|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002247|0.002080|0.002249|0.22|N|Y/Y|N/N|N|N|
|INJ_USDT|8.629000|8.565000|8.634000|1.45|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T18:45:03+00:00, last15m_closed_end=2026-10-21T18:45+00:00, prior8high=0.026672, depth_time=2026-10-21T18:45:14+00:00, book20_bid_proxy_usdt=18246, book20_ask_proxy_usdt=16178, funding_indicative=0.000050, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.52%, turnover=10097796. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T18:45:03+00:00, last15m_closed_end=2026-10-21T18:45+00:00, prior8high=0.535870, depth_time=2026-10-21T18:45:12+00:00, book20_bid_proxy_usdt=3905, book20_ask_proxy_usdt=2002, funding_indicative=-0.000171, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.16%, turnover=15451560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T18:45:03+00:00, last15m_closed_end=2026-10-21T18:45+00:00, prior8high=0.002424, depth_time=2026-10-21T18:45:09+00:00, book20_bid_proxy_usdt=110115, book20_ask_proxy_usdt=158177, funding_indicative=0.000012, next_funding_utc=2026-10-21T19:00:00+00:00, funding_cycle_h=1, 24h_change=-20.99%, turnover=9112926. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T18:45:03+00:00, last15m_closed_end=2026-10-21T18:45+00:00, prior8high=8.751000, depth_time=2026-10-21T18:45:16+00:00, book20_bid_proxy_usdt=221725, book20_ask_proxy_usdt=208564, funding_indicative=0.000059, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=55903082. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
