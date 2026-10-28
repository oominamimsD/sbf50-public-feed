# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T05:45:11Z**
- feed_generated_utc: 2026-10-28T05:45:13+00:00
- source_sha256: `702fe41a02cf87eaa54a2b1794df29cc293e7724e87dc677a61ec6f1241ec888`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T05:45+00:00, close=80923.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T05:00+00:00, close=80965.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T04:00+00:00, close=81110.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.048812|-23.23|-60.23|-23.71|34534993|4.51|
|NIL_USDT|0.084110|-9.25|-5.34|-9.73|6016675|8.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NIL_USDT|0.084110|0.081520|0.084110|0.47|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.048812|0.047660|0.048812|0.98|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- NIL_USDT: quote_utc=2026-10-28T05:45:03+00:00, last15m_closed_end=2026-10-28T05:45+00:00, prior8high=0.085080, depth_time=2026-10-28T05:45:10+00:00, book20_bid_proxy_usdt=11934, book20_ask_proxy_usdt=3238, funding_indicative=-0.000349, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.25%, turnover=6016675. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T05:45:02+00:00, last15m_closed_end=2026-10-28T05:45+00:00, prior8high=0.053904, depth_time=2026-10-28T05:45:08+00:00, book20_bid_proxy_usdt=29411, book20_ask_proxy_usdt=32202, funding_indicative=-0.000124, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-23.23%, turnover=34534993. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
