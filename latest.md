# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T18:30:17Z**
- feed_generated_utc: 2026-10-21T18:30:19+00:00
- source_sha256: `f68aecd3a481c388c7d1b11bb39313e739934dad4944b92592a9a9d1e320f82f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T18:30+00:00, close=84704.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T18:00+00:00, close=84635.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002266|-20.32|59.80|-20.56|9084969|4.42|
|AKE_USDT|0.025717|-3.64|-0.63|-3.88|10052851|5.83|
|BR_USDT|0.523650|-3.30|28.42|-3.54|15375745|1.53|
|INJ_USDT|8.665000|-1.06|13.43|-1.30|55432260|1.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025717|0.025666|0.025722|0.58|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.523650|0.513880|0.523600|0.62|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002266|0.002080|0.002254|0.12|N|Y/Y|N/N|N|N|
|INJ_USDT|8.665000|8.565000|8.665000|0.55|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T18:30:04+00:00, last15m_closed_end=2026-10-21T18:30+00:00, prior8high=0.026672, depth_time=2026-10-21T18:30:12+00:00, book20_bid_proxy_usdt=9143, book20_ask_proxy_usdt=10675, funding_indicative=0.000050, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.64%, turnover=10052851. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T18:30:04+00:00, last15m_closed_end=2026-10-21T18:30+00:00, prior8high=0.535870, depth_time=2026-10-21T18:30:13+00:00, book20_bid_proxy_usdt=4394, book20_ask_proxy_usdt=1582, funding_indicative=-0.000151, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.30%, turnover=15375745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T18:30:04+00:00, last15m_closed_end=2026-10-21T18:30+00:00, prior8high=0.002551, depth_time=2026-10-21T18:30:09+00:00, book20_bid_proxy_usdt=117586, book20_ask_proxy_usdt=129352, funding_indicative=0.000012, next_funding_utc=2026-10-21T19:00:00+00:00, funding_cycle_h=1, 24h_change=-20.32%, turnover=9084969. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T18:30:04+00:00, last15m_closed_end=2026-10-21T18:30+00:00, prior8high=8.751000, depth_time=2026-10-21T18:30:16+00:00, book20_bid_proxy_usdt=212407, book20_ask_proxy_usdt=261829, funding_indicative=0.000059, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=55432260. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
