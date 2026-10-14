# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T20:15:19Z**
- feed_generated_utc: 2026-10-14T20:15:20+00:00
- source_sha256: `393bbd15ed1ae35e992725499194534b92dee0109e631200c78e51f93c7033dd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T20:15+00:00, close=81898.5, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.205900|-7.26|78.42|-7.62|60947166|2.72|
|FET_USDT|0.196900|-3.43|-13.06|-3.79|10788732|5.08|
|S_USDT|0.053240|-2.82|33.63|-3.18|6432552|1.88|
|BAT_USDT|0.169730|-2.68|71.16|-3.04|32560936|1.18|
|COPPER_USDT|6.619000|-0.82|-0.98|-1.18|6410146|1.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.169730|0.167120|0.169950|0.63|N|Y/Y|Y/N|Y|N|
|BTW_USDT|2.205900|2.065400|2.205900|0.62|N|Y/Y|N/N|Y|N|
|COPPER_USDT|6.619000|6.606000|6.619000|0.04|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.196900|0.192700|0.196900|0.84|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053240|0.052350|0.053240|0.83|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-14T20:14:59+00:00, last15m_closed_end=2026-10-14T20:15+00:00, prior8high=0.173100, depth_time=2026-10-14T20:15:15+00:00, book20_bid_proxy_usdt=23402, book20_ask_proxy_usdt=27438, funding_indicative=0.000008, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.68%, turnover=32560936. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T20:14:59+00:00, last15m_closed_end=2026-10-14T20:15+00:00, prior8high=2.275500, depth_time=2026-10-14T20:15:08+00:00, book20_bid_proxy_usdt=8150, book20_ask_proxy_usdt=10143, funding_indicative=0.000017, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.26%, turnover=60947166. target_RR/account_short_permission/settled_funding=UNKNOWN.
- COPPER_USDT: quote_utc=2026-10-14T20:15:00+00:00, last15m_closed_end=2026-10-14T20:15+00:00, prior8high=6.650000, depth_time=2026-10-14T20:15:17+00:00, book20_bid_proxy_usdt=1238722, book20_ask_proxy_usdt=1883611, funding_indicative=0.000000, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.82%, turnover=6410146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T20:14:59+00:00, last15m_closed_end=2026-10-14T20:15+00:00, prior8high=0.205900, depth_time=2026-10-14T20:15:10+00:00, book20_bid_proxy_usdt=933364, book20_ask_proxy_usdt=1380363, funding_indicative=0.000062, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.43%, turnover=10788732. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T20:14:59+00:00, last15m_closed_end=2026-10-14T20:15+00:00, prior8high=0.053350, depth_time=2026-10-14T20:15:12+00:00, book20_bid_proxy_usdt=176216, book20_ask_proxy_usdt=152333, funding_indicative=-0.000092, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.82%, turnover=6432552. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
