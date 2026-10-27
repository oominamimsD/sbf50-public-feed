# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T23:00:13Z**
- feed_generated_utc: 2026-10-27T23:00:16+00:00
- source_sha256: `9ad78656594bb938ae518eb0ee387930c0cd6d97c56a90c31d92232325e8403e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T23:00+00:00, close=80874.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T23:00+00:00, close=80874.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T20:00+00:00, close=80778.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.054050|-14.99|-55.96|-15.42|44569070|0.74|
|INJ_USDT|7.931000|-3.18|-7.77|-3.61|22922336|1.26|
|ARB_USDT|0.166380|-1.25|-11.94|-1.68|14680200|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.166380|0.165630|0.166420|0.98|N|Y/Y|Y/Y|N|N|
|INJ_USDT|7.931000|7.915000|7.929000|0.53|N|Y/N|N/N|N|N|
|Q_USDT|0.054050|0.052810|0.054109|0.47|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-27T23:00:03+00:00, last15m_closed_end=2026-10-27T23:00+00:00, prior8high=0.169030, depth_time=2026-10-27T23:00:11+00:00, book20_bid_proxy_usdt=90721, book20_ask_proxy_usdt=91551, funding_indicative=-0.000018, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=14680200. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-27T23:00:03+00:00, last15m_closed_end=2026-10-27T23:00+00:00, prior8high=8.171000, depth_time=2026-10-27T23:00:10+00:00, book20_bid_proxy_usdt=397865, book20_ask_proxy_usdt=311606, funding_indicative=0.000231, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.18%, turnover=22922336. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-27T23:00:02+00:00, last15m_closed_end=2026-10-27T23:00+00:00, prior8high=0.055980, depth_time=2026-10-27T23:00:06+00:00, book20_bid_proxy_usdt=3612, book20_ask_proxy_usdt=3141, funding_indicative=-0.000028, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-14.99%, turnover=44569070. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
