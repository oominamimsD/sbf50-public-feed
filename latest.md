# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T06:30:17Z**
- feed_generated_utc: 2026-10-14T06:30:19+00:00
- source_sha256: `578e7721cc79891300ac70d601f49309a4aa0c3ee1f7c31e17ac43e360b05e50`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T06:30+00:00, close=83457.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T06:00+00:00, close=83434.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.080880|-6.95|54.97|-7.02|30568324|3.71|
|MAGIC_USDT|0.112420|-5.25|65.03|-5.32|5474723|2.67|
|W_USDT|0.016112|-4.11|11.02|-4.18|7070264|0.62|
|TIA_USDT|0.555700|-3.74|16.67|-3.81|44861937|1.80|
|UNI_USDT|7.381000|-2.52|-14.81|-2.59|19858691|1.35|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.112420|0.111620|0.112420|0.74|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.080880|0.080420|0.080880|2.00|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.555700|0.547400|0.555700|0.62|N|Y/Y|N/N|N|N|
|UNI_USDT|7.381000|7.259000|7.381000|0.67|N|Y/Y|Y/N|N|N|
|W_USDT|0.016112|0.015869|0.016112|1.31|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T06:30:01+00:00, last15m_closed_end=2026-10-14T06:30+00:00, prior8high=0.115610, depth_time=2026-10-14T06:30:09+00:00, book20_bid_proxy_usdt=170834, book20_ask_proxy_usdt=186599, funding_indicative=-0.000064, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.25%, turnover=5474723. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T06:30:01+00:00, last15m_closed_end=2026-10-14T06:30+00:00, prior8high=0.085530, depth_time=2026-10-14T06:30:07+00:00, book20_bid_proxy_usdt=179801, book20_ask_proxy_usdt=187768, funding_indicative=0.000050, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.95%, turnover=30568324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T06:30:01+00:00, last15m_closed_end=2026-10-14T06:30+00:00, prior8high=0.581500, depth_time=2026-10-14T06:30:14+00:00, book20_bid_proxy_usdt=139322, book20_ask_proxy_usdt=274782, funding_indicative=-0.000005, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.74%, turnover=44861937. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T06:30:01+00:00, last15m_closed_end=2026-10-14T06:30+00:00, prior8high=7.510000, depth_time=2026-10-14T06:30:16+00:00, book20_bid_proxy_usdt=1698382, book20_ask_proxy_usdt=1993662, funding_indicative=0.000100, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.52%, turnover=19858691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T06:30:01+00:00, last15m_closed_end=2026-10-14T06:30+00:00, prior8high=0.016644, depth_time=2026-10-14T06:30:12+00:00, book20_bid_proxy_usdt=36010, book20_ask_proxy_usdt=22170, funding_indicative=-0.000156, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.11%, turnover=7070264. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
