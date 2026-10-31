# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T17:30:16Z**
- feed_generated_utc: 2026-10-31T17:30:18+00:00
- source_sha256: `906e8c21004621352055cbf173f7ba0eef6e83fdc5034efab204e31c3cc45f71`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T17:30+00:00, close=77563.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T17:00+00:00, close=77578.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WLD_USDT|0.397900|-1.60|-13.87|-1.60|41412420|2.51|
|BTW_USDT|1.107800|-1.25|-36.38|-1.25|7649846|2.71|
|FET_USDT|0.161500|-1.10|-6.26|-1.10|5835526|6.19|
|DASH_USDT|48.100000|-1.06|-2.82|-1.06|5591864|2.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.107800|1.083700|1.107800|0.95|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.100000|48.350000|48.100000|1.90|Y|N/N|Y/Y|Y|N|
|FET_USDT|0.161500|0.161700|0.161400|4.82|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.397900|0.397900|0.397900|1.43|N|Y/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-31T17:30:03+00:00, last15m_closed_end=2026-10-31T17:30+00:00, prior8high=1.143900, depth_time=2026-10-31T17:30:11+00:00, book20_bid_proxy_usdt=25802, book20_ask_proxy_usdt=9428, funding_indicative=-0.000276, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.25%, turnover=7649846. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T17:30:00+00:00, last15m_closed_end=2026-10-31T17:30+00:00, prior8high=48.980000, depth_time=2026-10-31T17:30:15+00:00, book20_bid_proxy_usdt=744746, book20_ask_proxy_usdt=770926, funding_indicative=0.000019, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=5591864. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T17:30:03+00:00, last15m_closed_end=2026-10-31T17:30+00:00, prior8high=0.163800, depth_time=2026-10-31T17:30:13+00:00, book20_bid_proxy_usdt=1382819, book20_ask_proxy_usdt=878969, funding_indicative=-0.000022, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=5835526. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T17:30:03+00:00, last15m_closed_end=2026-10-31T17:30+00:00, prior8high=0.405900, depth_time=2026-10-31T17:30:08+00:00, book20_bid_proxy_usdt=3395554, book20_ask_proxy_usdt=2342584, funding_indicative=0.000018, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=41412420. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
