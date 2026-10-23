# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T01:45:21Z**
- feed_generated_utc: 2026-10-23T01:45:22+00:00
- source_sha256: `826a7dd67e2db9127d399f56931bc392034a1fa3eb6ac373c3d1d5a40d5b899d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T01:45+00:00, close=81452, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T01:00+00:00, close=81431.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.448200|-4.59|11.54|-4.37|12897778|0.29|
|PHA_USDT|0.059930|-3.41|18.62|-3.19|8347807|1.67|
|STRK_USDT|0.053040|-2.42|-44.95|-2.20|12632634|1.89|
|SILVER_USDT|54.230000|-1.86|-5.09|-1.64|378762166|1.84|
|ARB_USDT|0.180500|-1.70|-4.96|-1.48|31767622|0.55|
|XPL_USDT|0.076360|-1.47|-9.88|-1.25|5841571|1.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180500|0.178290|0.180500|0.26|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.448200|3.363100|3.448200|1.20|N|Y/Y|Y/N|Y|N|
|PHA_USDT|0.059930|0.059770|0.059930|0.87|N|Y/Y|N/N|Y|N|
|SILVER_USDT|54.230000|54.240000|54.230000|2.99|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.053040|0.052330|0.053040|0.89|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.076360|0.075130|0.076360|0.58|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T01:45:00+00:00, last15m_closed_end=2026-10-23T01:45+00:00, prior8high=0.181100, depth_time=2026-10-23T01:45:17+00:00, book20_bid_proxy_usdt=62193, book20_ask_proxy_usdt=64877, funding_indicative=-0.000118, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=31767622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T01:45:00+00:00, last15m_closed_end=2026-10-23T01:45+00:00, prior8high=3.445100, depth_time=2026-10-23T01:45:08+00:00, book20_bid_proxy_usdt=22392, book20_ask_proxy_usdt=25349, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.59%, turnover=12897778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T01:45:00+00:00, last15m_closed_end=2026-10-23T01:45+00:00, prior8high=0.061510, depth_time=2026-10-23T01:45:09+00:00, book20_bid_proxy_usdt=73330, book20_ask_proxy_usdt=59967, funding_indicative=-0.000591, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.41%, turnover=8347807. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T01:45:00+00:00, last15m_closed_end=2026-10-23T01:45+00:00, prior8high=54.870000, depth_time=2026-10-23T01:45:15+00:00, book20_bid_proxy_usdt=34616903, book20_ask_proxy_usdt=29052265, funding_indicative=0.000128, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=378762166. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T01:45:00+00:00, last15m_closed_end=2026-10-23T01:45+00:00, prior8high=0.053350, depth_time=2026-10-23T01:45:13+00:00, book20_bid_proxy_usdt=493373, book20_ask_proxy_usdt=570432, funding_indicative=0.000042, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.42%, turnover=12632634. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-23T01:45:01+00:00, last15m_closed_end=2026-10-23T01:45+00:00, prior8high=0.076330, depth_time=2026-10-23T01:45:20+00:00, book20_bid_proxy_usdt=436240, book20_ask_proxy_usdt=557914, funding_indicative=0.000015, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.47%, turnover=5841571. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
