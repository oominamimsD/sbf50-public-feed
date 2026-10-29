# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T16:45:10Z**
- feed_generated_utc: 2026-10-29T16:45:12+00:00
- source_sha256: `bebe6e99859d61761133e057f063f3b9995ea407b3c68fb75c0874670e426de9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T16:45+00:00, close=81370.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.602600|-2.16|-10.46|-1.72|9658809|0.62|
|AKE_USDT|0.020640|-1.99|-33.03|-1.55|6095813|3.40|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020640|0.020617|0.020640|0.70|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.602600|1.570500|1.602600|3.27|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-29T16:44:59+00:00, last15m_closed_end=2026-10-29T16:45+00:00, prior8high=0.021549, depth_time=2026-10-29T16:45:10+00:00, book20_bid_proxy_usdt=4284, book20_ask_proxy_usdt=3753, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=6095813. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T16:44:59+00:00, last15m_closed_end=2026-10-29T16:45+00:00, prior8high=1.714700, depth_time=2026-10-29T16:45:07+00:00, book20_bid_proxy_usdt=20812, book20_ask_proxy_usdt=13625, funding_indicative=-0.000025, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.16%, turnover=9658809. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
