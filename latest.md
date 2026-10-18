# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T16:15:11Z**
- feed_generated_utc: 2026-10-18T16:15:13+00:00
- source_sha256: `b93801208ae1165d98e756b1423418a6dc101716f2f8b8d426142d5c13b57db0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T16:15+00:00, close=81133.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PUMPFUN_USDT|0.004123|-1.71|-28.60|-1.70|29961003|2.42|
|BTW_USDT|2.274400|-1.34|35.20|-1.33|28110903|1.76|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.274400|2.282100|2.274400|1.84|Y|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004123|0.004146|0.004123|11.89|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-18T16:15:01+00:00, last15m_closed_end=2026-10-18T16:15+00:00, prior8high=2.424600, depth_time=2026-10-18T16:15:10+00:00, book20_bid_proxy_usdt=12290, book20_ask_proxy_usdt=10480, funding_indicative=-0.000281, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=28110903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T16:15:01+00:00, last15m_closed_end=2026-10-18T16:15+00:00, prior8high=0.004275, depth_time=2026-10-18T16:15:08+00:00, book20_bid_proxy_usdt=1972549, book20_ask_proxy_usdt=1420511, funding_indicative=0.000009, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=29961003. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
