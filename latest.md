# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T20:15:16Z**
- feed_generated_utc: 2026-10-13T20:15:19+00:00
- source_sha256: `a6e543969311b561f91f0b1aa5e98523b1b08e8f410f9c79dc3f7fcb2f804896`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T20:15+00:00, close=83223.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CT_USDT|0.354560|-4.62|-4.58|-4.42|5776885|0.56|
|RLC_USDT|0.887400|-3.87|8.24|-3.67|5630510|2.25|
|DOS_USDT|0.208700|-3.06|-3.15|-2.86|9325887|4.80|
|STRK_USDT|0.085260|-1.92|63.36|-1.72|41672613|1.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.354560|0.351000|0.354490|0.72|N|Y/Y|N/N|N|N|
|DOS_USDT|0.208700|0.206400|0.208700|0.47|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.887400|0.874600|0.887400|1.34|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085260|0.084020|0.085260|0.36|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T20:14:59+00:00, last15m_closed_end=2026-10-13T20:15+00:00, prior8high=0.372120, depth_time=2026-10-13T20:15:08+00:00, book20_bid_proxy_usdt=6802, book20_ask_proxy_usdt=7740, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.62%, turnover=5776885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T20:14:59+00:00, last15m_closed_end=2026-10-13T20:15+00:00, prior8high=0.214000, depth_time=2026-10-13T20:15:12+00:00, book20_bid_proxy_usdt=145016, book20_ask_proxy_usdt=117768, funding_indicative=-0.000123, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.06%, turnover=9325887. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T20:14:59+00:00, last15m_closed_end=2026-10-13T20:15+00:00, prior8high=0.908000, depth_time=2026-10-13T20:15:10+00:00, book20_bid_proxy_usdt=64312, book20_ask_proxy_usdt=60140, funding_indicative=-0.000556, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.87%, turnover=5630510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T20:14:59+00:00, last15m_closed_end=2026-10-13T20:15+00:00, prior8high=0.089710, depth_time=2026-10-13T20:15:14+00:00, book20_bid_proxy_usdt=193004, book20_ask_proxy_usdt=291928, funding_indicative=0.000044, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=41672613. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
