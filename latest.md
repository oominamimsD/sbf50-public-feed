# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T17:15:11Z**
- feed_generated_utc: 2026-10-29T17:15:12+00:00
- source_sha256: `29efed9ff72eaaf858745aa943bb787b2a8b06ce77931d6fe0015ebad4f0b75d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T17:15+00:00, close=80918.7, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T17:00+00:00, close=81232.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.541200|-5.91|-13.89|-4.92|9667818|4.55|
|AKE_USDT|0.020567|-2.34|-33.27|-1.35|5675862|6.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020567|0.020487|0.020567|1.32|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.541200|1.509900|1.541200|1.92|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-29T17:15:01+00:00, last15m_closed_end=2026-10-29T17:15+00:00, prior8high=0.021549, depth_time=2026-10-29T17:15:10+00:00, book20_bid_proxy_usdt=2776, book20_ask_proxy_usdt=4984, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=5675862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T17:15:01+00:00, last15m_closed_end=2026-10-29T17:15+00:00, prior8high=1.711300, depth_time=2026-10-29T17:15:08+00:00, book20_bid_proxy_usdt=8648, book20_ask_proxy_usdt=17473, funding_indicative=-0.000068, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.91%, turnover=9667818. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
