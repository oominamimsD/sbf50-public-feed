# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T07:45:14Z**
- feed_generated_utc: 2026-10-28T07:45:16+00:00
- source_sha256: `6d23826bfa2fd970fdda09959920541bb789e066c4af326ac1a1852ef9c3db7e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T07:45+00:00, close=80941.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T07:00+00:00, close=80839.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T04:00+00:00, close=81110.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|NIL_USDT|0.085680|-7.56|-3.57|-8.07|6105773|5.84|
|Q_USDT|0.059290|-6.75|-51.70|-7.26|31906941|5.06|
|AKE_USDT|0.020526|-2.83|-33.98|-3.34|5863832|3.41|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020526|0.020512|0.020528|1.92|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.085680|0.083440|0.085680|0.52|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.059290|0.048389|0.059300|0.62|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T07:45:00+00:00, last15m_closed_end=2026-10-28T07:45+00:00, prior8high=0.021690, depth_time=2026-10-28T07:45:12+00:00, book20_bid_proxy_usdt=10860, book20_ask_proxy_usdt=17439, funding_indicative=0.000050, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.83%, turnover=5863832. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-28T07:45:00+00:00, last15m_closed_end=2026-10-28T07:45+00:00, prior8high=0.085880, depth_time=2026-10-28T07:45:08+00:00, book20_bid_proxy_usdt=2775, book20_ask_proxy_usdt=2454, funding_indicative=-0.000655, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.56%, turnover=6105773. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T07:45:00+00:00, last15m_closed_end=2026-10-28T07:45+00:00, prior8high=0.074627, depth_time=2026-10-28T07:45:11+00:00, book20_bid_proxy_usdt=36160, book20_ask_proxy_usdt=23031, funding_indicative=-0.001132, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.75%, turnover=31906941. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
