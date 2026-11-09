# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T17:30:10Z**
- feed_generated_utc: 2026-11-09T17:30:11+00:00
- source_sha256: `7c67c4b07b3183a6db680f6a9c51c164acb936aa2efe456cb77efc6fb1b792c3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T17:30+00:00, close=74822.2, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T17:00+00:00, close=75035.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T16:00+00:00, close=75500.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1171.800000|-4.39|-6.56|-3.50|2462096268|0.09|
|QNT_USDT|195.020000|-2.50|-3.67|-1.61|43134924|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|QNT_USDT|195.020000|194.800000|195.020000|1.60|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1171.800000|1172.890000|1171.800000|1.38|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- QNT_USDT: quote_utc=2026-11-09T17:30:00+00:00, last15m_closed_end=2026-11-09T17:30+00:00, prior8high=201.280000, depth_time=2026-11-09T17:30:09+00:00, book20_bid_proxy_usdt=75118, book20_ask_proxy_usdt=67824, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=43134924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T17:30:00+00:00, last15m_closed_end=2026-11-09T17:30+00:00, prior8high=1233.770000, depth_time=2026-11-09T17:30:07+00:00, book20_bid_proxy_usdt=233901, book20_ask_proxy_usdt=263562, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.39%, turnover=2462096268. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
