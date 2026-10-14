# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T00:45:17Z**
- feed_generated_utc: 2026-10-14T00:45:19+00:00
- source_sha256: `6ef91d420423218483a4da571dd055c9d13b1dfef110767519d5d1f98cc95d51`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T00:45+00:00, close=83569.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|1000RATS_USDT|0.016740|-9.46|-58.32|-9.67|5268593|5.98|
|RLC_USDT|0.892400|-3.33|8.85|-3.54|5070121|3.36|
|CT_USDT|0.364910|-1.84|-1.80|-2.05|5383982|2.74|
|STRK_USDT|0.085700|-1.41|64.20|-1.62|36047690|1.17|
|OGN_USDT|0.034890|-0.88|55.68|-1.09|5345833|2.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|1000RATS_USDT|0.016740|0.015990|0.016740|0.60|N|Y/Y|Y/Y|N|N|
|CT_USDT|0.364910|0.356040|0.364910|0.75|N|Y/Y|N/N|N|N|
|OGN_USDT|0.034890|0.034530|0.034890|4.82|N|Y/Y|Y/N|N|N|
|RLC_USDT|0.892400|0.883900|0.892400|2.96|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085700|0.083570|0.085700|0.98|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- 1000RATS_USDT: quote_utc=2026-10-14T00:45:00+00:00, last15m_closed_end=2026-10-14T00:45+00:00, prior8high=0.017060, depth_time=2026-10-14T00:45:07+00:00, book20_bid_proxy_usdt=46232, book20_ask_proxy_usdt=71289, funding_indicative=0.000050, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.46%, turnover=5268593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-14T00:45:00+00:00, last15m_closed_end=2026-10-14T00:45+00:00, prior8high=0.366370, depth_time=2026-10-14T00:45:12+00:00, book20_bid_proxy_usdt=7666, book20_ask_proxy_usdt=8368, funding_indicative=0.000050, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.84%, turnover=5383982. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-14T00:45:00+00:00, last15m_closed_end=2026-10-14T00:45+00:00, prior8high=0.035070, depth_time=2026-10-14T00:45:16+00:00, book20_bid_proxy_usdt=196522, book20_ask_proxy_usdt=148750, funding_indicative=-0.000071, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=5345833. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-14T00:45:00+00:00, last15m_closed_end=2026-10-14T00:45+00:00, prior8high=0.901200, depth_time=2026-10-14T00:45:08+00:00, book20_bid_proxy_usdt=72573, book20_ask_proxy_usdt=90171, funding_indicative=-0.000423, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.33%, turnover=5070121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T00:45:00+00:00, last15m_closed_end=2026-10-14T00:45+00:00, prior8high=0.085960, depth_time=2026-10-14T00:45:14+00:00, book20_bid_proxy_usdt=306050, book20_ask_proxy_usdt=140796, funding_indicative=-0.000002, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.41%, turnover=36047690. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
