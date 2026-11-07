# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T23:15:10Z**
- feed_generated_utc: 2026-11-07T23:15:11+00:00
- source_sha256: `479fab8ad58017a5ff9ddd575f8fe37acefd1da111648eedf9b086ccae9bf20b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T23:15+00:00, close=75747.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T23:00+00:00, close=75749.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T20:00+00:00, close=75772.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001966|-3.46|67.44|-3.48|30075964|2.54|
|QNT_USDT|195.740000|-1.56|-2.64|-1.58|41750396|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ONE_USDT|0.001966|0.002023|0.001963|1.06|N|N/N|N/N|Y|N|
|QNT_USDT|195.740000|195.370000|195.740000|2.03|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ONE_USDT: quote_utc=2026-11-07T23:15:01+00:00, last15m_closed_end=2026-11-07T23:15+00:00, prior8high=0.002423, depth_time=2026-11-07T23:15:07+00:00, book20_bid_proxy_usdt=16656, book20_ask_proxy_usdt=27504, funding_indicative=-0.000043, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.46%, turnover=30075964. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-07T23:15:01+00:00, last15m_closed_end=2026-11-07T23:15+00:00, prior8high=197.260000, depth_time=2026-11-07T23:15:09+00:00, book20_bid_proxy_usdt=72681, book20_ask_proxy_usdt=91249, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=41750396. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
