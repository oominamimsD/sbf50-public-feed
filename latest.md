# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T03:15:12Z**
- feed_generated_utc: 2026-10-28T03:15:15+00:00
- source_sha256: `2285a097905cbf7d7b6cb9c8cb88906dc29188917c81e304e8679f976c620ede`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T03:15+00:00, close=80919.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T03:00+00:00, close=80917.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T00:00+00:00, close=80868.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.054292|-14.61|-55.77|-15.09|35768499|1.29|
|INJ_USDT|7.935000|-3.13|-7.73|-3.61|24539153|1.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|INJ_USDT|7.935000|7.922000|7.935000|2.29|N|Y/N|N/N|N|N|
|Q_USDT|0.054292|0.052383|0.054306|0.74|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- INJ_USDT: quote_utc=2026-10-28T03:15:01+00:00, last15m_closed_end=2026-10-28T03:15+00:00, prior8high=8.060000, depth_time=2026-10-28T03:15:10+00:00, book20_bid_proxy_usdt=270440, book20_ask_proxy_usdt=278374, funding_indicative=0.000197, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.13%, turnover=24539153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T03:15:01+00:00, last15m_closed_end=2026-10-28T03:15+00:00, prior8high=0.055511, depth_time=2026-10-28T03:15:09+00:00, book20_bid_proxy_usdt=30349, book20_ask_proxy_usdt=28928, funding_indicative=-0.000048, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.61%, turnover=35768499. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
