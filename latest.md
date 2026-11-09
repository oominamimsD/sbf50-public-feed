# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T04:30:22Z**
- feed_generated_utc: 2026-11-09T04:30:23+00:00
- source_sha256: `eb158fb1b186a1c98e196dc148efb4c84f714132d84e002aa55c34e7d312c075`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T04:30+00:00, close=74933.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001651|-15.65|41.81|-14.20|10400760|0.60|
|JCT_USDT|0.008353|-15.05|67.76|-13.60|66805195|7.18|
|AKE_USDT|0.004719|-11.90|-48.48|-10.45|11551171|2.12|
|PUMPFUN_USDT|0.003585|-4.06|-15.00|-2.61|9298603|2.79|
|XRP_USDT|1.111100|-3.86|-11.10|-2.41|231039762|0.90|
|HYPE_USDT|74.738000|-3.47|-14.76|-2.02|40072866|0.13|
|LIT_USDT|3.106700|-2.71|-3.82|-1.26|13420767|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004719|0.004627|0.004719|1.55|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|74.738000|74.350000|74.738000|0.22|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008353|0.007861|0.008355|0.77|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.106700|3.086100|3.106700|0.19|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001651|0.001639|0.001651|0.36|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003585|0.003583|0.003585|0.94|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.111100|1.103000|1.111100|1.31|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T04:30:00+00:00, last15m_closed_end=2026-11-09T04:30+00:00, prior8high=0.005144, depth_time=2026-11-09T04:30:12+00:00, book20_bid_proxy_usdt=54540, book20_ask_proxy_usdt=30366, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.90%, turnover=11551171. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T04:30:00+00:00, last15m_closed_end=2026-11-09T04:30+00:00, prior8high=75.262000, depth_time=2026-11-09T04:30:19+00:00, book20_bid_proxy_usdt=213186, book20_ask_proxy_usdt=26049, funding_indicative=0.000038, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.47%, turnover=40072866. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T04:30:00+00:00, last15m_closed_end=2026-11-09T04:30+00:00, prior8high=0.010158, depth_time=2026-11-09T04:30:10+00:00, book20_bid_proxy_usdt=27101, book20_ask_proxy_usdt=25960, funding_indicative=0.001360, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.05%, turnover=66805195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T04:30:00+00:00, last15m_closed_end=2026-11-09T04:30+00:00, prior8high=3.158500, depth_time=2026-11-09T04:30:21+00:00, book20_bid_proxy_usdt=25393, book20_ask_proxy_usdt=19977, funding_indicative=-0.000042, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=13420767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T04:30:00+00:00, last15m_closed_end=2026-11-09T04:30+00:00, prior8high=0.001715, depth_time=2026-11-09T04:30:07+00:00, book20_bid_proxy_usdt=9657, book20_ask_proxy_usdt=8278, funding_indicative=-0.000387, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.65%, turnover=10400760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T04:30:00+00:00, last15m_closed_end=2026-11-09T04:30+00:00, prior8high=0.003675, depth_time=2026-11-09T04:30:14+00:00, book20_bid_proxy_usdt=2794850, book20_ask_proxy_usdt=2961826, funding_indicative=-0.000001, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.06%, turnover=9298603. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T04:30:00+00:00, last15m_closed_end=2026-11-09T04:30+00:00, prior8high=1.123100, depth_time=2026-11-09T04:30:16+00:00, book20_bid_proxy_usdt=4251902, book20_ask_proxy_usdt=2909014, funding_indicative=-0.000004, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.86%, turnover=231039762. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
