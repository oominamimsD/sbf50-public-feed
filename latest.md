# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T16:30:12Z**
- feed_generated_utc: 2026-11-09T16:30:13+00:00
- source_sha256: `5df2cd9b45a9f212a340f2de3463f7cec43424c7b084966122e0b3d82c8a3253`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T16:30+00:00, close=74804.2, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T16:00+00:00, close=75500.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T16:00+00:00, close=75500.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1188.180000|-3.06|-5.25|-2.14|2425040824|0.08|
|HYPE_USDT|74.450000|-2.44|-13.14|-1.52|62541320|0.13|
|TRUMPOFFICIAL_USDT|1.119000|-2.01|-31.60|-1.09|6337705|8.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|HYPE_USDT|74.450000|73.709000|74.450000|3.95|N|N/N|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.119000|1.113000|1.119000|1.35|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1188.180000|1206.460000|1187.930000|1.79|Y|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- HYPE_USDT: quote_utc=2026-11-09T16:29:58+00:00, last15m_closed_end=2026-11-09T16:30+00:00, prior8high=76.709000, depth_time=2026-11-09T16:30:09+00:00, book20_bid_proxy_usdt=51822, book20_ask_proxy_usdt=129236, funding_indicative=0.000044, next_funding_utc=2026-11-09T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.44%, turnover=62541320. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T16:29:59+00:00, last15m_closed_end=2026-11-09T16:30+00:00, prior8high=1.145000, depth_time=2026-11-09T16:30:11+00:00, book20_bid_proxy_usdt=2937073, book20_ask_proxy_usdt=2203152, funding_indicative=-0.000064, next_funding_utc=2026-11-09T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=6337705. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T16:29:58+00:00, last15m_closed_end=2026-11-09T16:30+00:00, prior8high=1235.450000, depth_time=2026-11-09T16:30:07+00:00, book20_bid_proxy_usdt=454841, book20_ask_proxy_usdt=130542, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=2425040824. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
