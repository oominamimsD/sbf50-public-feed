# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T13:15:28Z**
- feed_generated_utc: 2026-11-08T13:15:29+00:00
- source_sha256: `188b141add0fc544daf3fb2684049604c27d9a447859b836fa5cbdc983962365`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T13:15+00:00, close=76091, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T13:00+00:00, close=75946.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.030021|-9.83|71.34|-10.31|15843133|2.00|
|AKE_USDT|0.005396|-9.81|-51.55|-10.29|28438297|3.71|
|ONE_USDT|0.001878|-7.78|59.95|-8.26|24559361|0.53|
|TIA_USDT|0.423900|-4.00|-13.50|-4.48|6959007|2.36|
|WLD_USDT|0.327400|-2.44|-19.04|-2.92|23195930|3.06|
|ENA_USDT|0.155100|-1.94|-20.05|-2.42|29805744|0.65|
|LINK_USDT|10.767000|-0.71|-6.94|-1.19|62565813|0.93|
|ADA_USDT|0.180600|-0.55|-6.71|-1.03|9335680|5.54|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.180600|0.179600|0.180600|3.61|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005396|0.005417|0.005391|0.78|N|Y/N|N/N|Y|N|
|ENA_USDT|0.155100|0.152500|0.155090|3.23|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.030021|0.027111|0.030033|0.63|N|Y/Y|N/N|Y|N|
|LINK_USDT|10.767000|10.706000|10.769000|2.23|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001878|0.001872|0.001878|0.23|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.423900|0.421400|0.423900|1.47|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.327400|0.324800|0.327400|1.71|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-08T13:15:02+00:00, last15m_closed_end=2026-11-08T13:15+00:00, prior8high=0.181000, depth_time=2026-11-08T13:15:27+00:00, book20_bid_proxy_usdt=10934782, book20_ask_proxy_usdt=8848884, funding_indicative=-0.000025, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.55%, turnover=9335680. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T13:15:02+00:00, last15m_closed_end=2026-11-08T13:15+00:00, prior8high=0.005831, depth_time=2026-11-08T13:15:09+00:00, book20_bid_proxy_usdt=104019, book20_ask_proxy_usdt=36825, funding_indicative=0.000050, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.81%, turnover=28438297. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T13:15:02+00:00, last15m_closed_end=2026-11-08T13:15+00:00, prior8high=0.155490, depth_time=2026-11-08T13:15:20+00:00, book20_bid_proxy_usdt=201872, book20_ask_proxy_usdt=159176, funding_indicative=-0.000038, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.94%, turnover=29805744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T13:15:02+00:00, last15m_closed_end=2026-11-08T13:15+00:00, prior8high=0.033952, depth_time=2026-11-08T13:15:07+00:00, book20_bid_proxy_usdt=6539, book20_ask_proxy_usdt=7445, funding_indicative=0.000767, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.83%, turnover=15843133. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T13:15:02+00:00, last15m_closed_end=2026-11-08T13:15+00:00, prior8high=10.807000, depth_time=2026-11-08T13:15:24+00:00, book20_bid_proxy_usdt=425020, book20_ask_proxy_usdt=432829, funding_indicative=0.000003, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.71%, turnover=62565813. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T13:15:02+00:00, last15m_closed_end=2026-11-08T13:15+00:00, prior8high=0.001956, depth_time=2026-11-08T13:15:13+00:00, book20_bid_proxy_usdt=9726, book20_ask_proxy_usdt=12998, funding_indicative=-0.000865, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.78%, turnover=24559361. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T13:15:02+00:00, last15m_closed_end=2026-11-08T13:15+00:00, prior8high=0.427700, depth_time=2026-11-08T13:15:15+00:00, book20_bid_proxy_usdt=218214, book20_ask_proxy_usdt=415214, funding_indicative=-0.000045, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.00%, turnover=6959007. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T13:15:02+00:00, last15m_closed_end=2026-11-08T13:15+00:00, prior8high=0.330100, depth_time=2026-11-08T13:15:18+00:00, book20_bid_proxy_usdt=3560261, book20_ask_proxy_usdt=4655568, funding_indicative=-0.000070, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=23195930. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
