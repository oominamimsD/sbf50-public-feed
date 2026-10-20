# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T19:45:16Z**
- feed_generated_utc: 2026-10-20T19:45:18+00:00
- source_sha256: `966c13a9e4b83a6798c07f9c3b6a15fcba635dc918509643d54088cbed2cc495`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T19:45+00:00, close=82576.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T19:00+00:00, close=82503.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T16:00+00:00, close=82581.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.669800|-9.72|-14.47|-9.72|30933057|0.60|
|AGT_USDT|0.059302|-8.24|266.58|-8.24|7494079|8.25|
|AKE_USDT|0.030500|-1.90|21.67|-1.90|6574943|1.31|
|SEI_USDT|0.060950|-1.10|-2.27|-1.10|6369039|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.059302|0.058100|0.059192|1.00|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.030500|0.030496|0.030500|0.66|N|Y/N|N/N|N|N|
|BTW_USDT|1.669800|1.665000|1.669800|0.55|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.060950|0.060550|0.060950|0.74|N|N/N|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T19:45:01+00:00, last15m_closed_end=2026-10-20T19:45+00:00, prior8high=0.063192, depth_time=2026-10-20T19:45:11+00:00, book20_bid_proxy_usdt=12961, book20_ask_proxy_usdt=7841, funding_indicative=0.000047, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.24%, turnover=7494079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-20T19:45:02+00:00, last15m_closed_end=2026-10-20T19:45+00:00, prior8high=0.031294, depth_time=2026-10-20T19:45:13+00:00, book20_bid_proxy_usdt=15599, book20_ask_proxy_usdt=10122, funding_indicative=0.000050, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=6574943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T19:45:01+00:00, last15m_closed_end=2026-10-20T19:45+00:00, prior8high=1.770200, depth_time=2026-10-20T19:45:08+00:00, book20_bid_proxy_usdt=15977, book20_ask_proxy_usdt=9332, funding_indicative=-0.002416, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.72%, turnover=30933057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T19:45:02+00:00, last15m_closed_end=2026-10-20T19:45+00:00, prior8high=0.061830, depth_time=2026-10-20T19:45:12+00:00, book20_bid_proxy_usdt=241385, book20_ask_proxy_usdt=377285, funding_indicative=0.000032, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=6369039. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
