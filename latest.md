# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T22:00:14Z**
- feed_generated_utc: 2026-10-28T22:00:18+00:00
- source_sha256: `617c540504950ee10d9758b20cb7d1fee3979df79be0fdc672c6945ecf5ba638`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T22:00+00:00, close=81323.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T22:00+00:00, close=81323.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|290.450000|-1.16|0.26|-2.12|5828978|4.48|
|BTW_USDT|1.728200|-0.78|17.58|-1.74|12127689|0.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|290.450000|286.690000|290.450000|0.41|N|Y/Y|N/N|N|N|
|BTW_USDT|1.728200|1.721700|1.728200|1.03|N|N/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-28T22:00:03+00:00, last15m_closed_end=2026-10-28T22:00+00:00, prior8high=292.510000, depth_time=2026-10-28T22:00:10+00:00, book20_bid_proxy_usdt=48469, book20_ask_proxy_usdt=91693, funding_indicative=0.000018, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=5828978. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-28T22:00:02+00:00, last15m_closed_end=2026-10-28T22:00+00:00, prior8high=1.751000, depth_time=2026-10-28T22:00:13+00:00, book20_bid_proxy_usdt=18327, book20_ask_proxy_usdt=15410, funding_indicative=0.000050, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.78%, turnover=12127689. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
