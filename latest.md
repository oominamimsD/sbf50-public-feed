# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T20:45:12Z**
- feed_generated_utc: 2026-11-05T20:45:13+00:00
- source_sha256: `c8d6dd77d7f57904320b56ee3406ae7961ea5bce25b11ba385a950de9b45a470`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T20:45+00:00, close=76179.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002115|-18.02|-89.95|-18.23|19546208|9.46|
|FLUID_USDT|2.379000|-6.04|15.26|-6.25|8598545|4.20|
|QNT_USDT|189.940000|-0.98|-4.42|-1.19|43802320|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002115|0.001878|0.002117|0.34|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.379000|2.359000|2.379000|0.57|N|Y/Y|N/N|Y|N|
|QNT_USDT|189.940000|187.630000|189.940000|0.91|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T20:44:59+00:00, last15m_closed_end=2026-11-05T20:45+00:00, prior8high=0.002495, depth_time=2026-11-05T20:45:07+00:00, book20_bid_proxy_usdt=43573, book20_ask_proxy_usdt=49512, funding_indicative=-0.005393, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-18.02%, turnover=19546208. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T20:44:59+00:00, last15m_closed_end=2026-11-05T20:45+00:00, prior8high=2.424000, depth_time=2026-11-05T20:45:04+00:00, book20_bid_proxy_usdt=215564, book20_ask_proxy_usdt=165062, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.04%, turnover=8598545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-05T20:44:59+00:00, last15m_closed_end=2026-11-05T20:45+00:00, prior8high=193.570000, depth_time=2026-11-05T20:45:11+00:00, book20_bid_proxy_usdt=62223, book20_ask_proxy_usdt=55195, funding_indicative=0.000028, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=43802320. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
