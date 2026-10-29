# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T17:30:14Z**
- feed_generated_utc: 2026-10-29T17:30:15+00:00
- source_sha256: `352164bee685b22def35d2f636b1abc47c6592904cfaeb9cd30c006182c5b4cf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T17:30+00:00, close=81049, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T17:00+00:00, close=81232.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.542100|-5.86|-13.84|-5.05|9728692|1.30|
|QNT_USDT|194.340000|-2.21|1.90|-1.40|63048801|0.52|
|AKE_USDT|0.020661|-1.89|-32.97|-1.08|5689859|4.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020661|0.020451|0.020661|0.59|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.542100|1.509900|1.541400|0.80|N|Y/Y|Y/N|N|N|
|QNT_USDT|194.340000|195.100000|194.340000|1.15|N|N/N|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-29T17:30:02+00:00, last15m_closed_end=2026-10-29T17:30+00:00, prior8high=0.021525, depth_time=2026-10-29T17:30:13+00:00, book20_bid_proxy_usdt=5224, book20_ask_proxy_usdt=3038, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.89%, turnover=5689859. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T17:30:02+00:00, last15m_closed_end=2026-10-29T17:30+00:00, prior8high=1.692600, depth_time=2026-10-29T17:30:08+00:00, book20_bid_proxy_usdt=14800, book20_ask_proxy_usdt=14817, funding_indicative=-0.000063, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.86%, turnover=9728692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-29T17:30:02+00:00, last15m_closed_end=2026-10-29T17:30+00:00, prior8high=199.910000, depth_time=2026-10-29T17:30:11+00:00, book20_bid_proxy_usdt=118724, book20_ask_proxy_usdt=150387, funding_indicative=-0.000044, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=63048801. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
