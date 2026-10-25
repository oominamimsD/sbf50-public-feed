# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T00:00:12Z**
- feed_generated_utc: 2026-10-25T00:00:16+00:00
- source_sha256: `2c56a4cca3f6611a14d744f6b98fa6974eb882bac44dac4fa346f14cef018564`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.040340|-12.39|216.14|-13.74|33219070|4.96|
|BIRB_USDT|0.086380|-11.55|78.02|-12.90|11670505|1.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.086380|0.083640|0.087240|2.04|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.040340|0.041280|0.040370|1.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T00:00:02+00:00, last15m_closed_end=2026-10-25T00:00+00:00, prior8high=0.092330, depth_time=2026-10-25T00:00:12+00:00, book20_bid_proxy_usdt=7586, book20_ask_proxy_usdt=21539, funding_indicative=-0.009339, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.55%, turnover=11670505. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T00:00:02+00:00, last15m_closed_end=2026-10-25T00:00+00:00, prior8high=0.045020, depth_time=2026-10-25T00:00:09+00:00, book20_bid_proxy_usdt=136184, book20_ask_proxy_usdt=56214, funding_indicative=-0.000033, next_funding_utc=2026-10-25T01:00:00+00:00, funding_cycle_h=1, 24h_change=-12.39%, turnover=33219070. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
