# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T04:30:14Z**
- feed_generated_utc: 2026-10-14T04:30:16+00:00
- source_sha256: `d91e60d70c78d3d34fb591f95cb758c01618eddd5fc85913a59a053b6f2bcd96`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T04:30+00:00, close=83759.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.082710|-4.85|58.47|-5.28|30080608|1.21|
|W_USDT|0.016202|-3.57|11.64|-4.00|7072149|4.32|
|MAGIC_USDT|0.114550|-3.45|68.15|-3.88|5644467|1.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.114550|0.113190|0.114550|1.13|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.082710|0.081770|0.082730|2.18|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016202|0.016116|0.016202|1.34|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T04:29:59+00:00, last15m_closed_end=2026-10-14T04:30+00:00, prior8high=0.118420, depth_time=2026-10-14T04:30:13+00:00, book20_bid_proxy_usdt=180099, book20_ask_proxy_usdt=188925, funding_indicative=-0.000178, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.45%, turnover=5644467. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T04:29:59+00:00, last15m_closed_end=2026-10-14T04:30+00:00, prior8high=0.085270, depth_time=2026-10-14T04:30:08+00:00, book20_bid_proxy_usdt=186753, book20_ask_proxy_usdt=288196, funding_indicative=0.000040, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.85%, turnover=30080608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T04:29:59+00:00, last15m_closed_end=2026-10-14T04:30+00:00, prior8high=0.016697, depth_time=2026-10-14T04:30:07+00:00, book20_bid_proxy_usdt=39743, book20_ask_proxy_usdt=39394, funding_indicative=-0.000184, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.57%, turnover=7072149. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
