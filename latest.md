# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T17:45:25Z**
- feed_generated_utc: 2026-11-08T17:45:26+00:00
- source_sha256: `a3ac3c06eb0ea3514286212145b90820e5a7844a25458298fa723bdf7aa095d3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T17:45+00:00, close=75737.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T17:00+00:00, close=75741.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001781|-9.02|52.95|-8.63|19125382|0.56|
|NEAR_USDT|3.604000|-2.62|-16.78|-2.23|31072742|2.77|
|PUMPFUN_USDT|0.003664|-1.95|-13.13|-1.56|10445528|2.73|
|ZEC_USDT|1248.180000|-1.77|0.82|-1.38|1409229892|0.08|
|AKE_USDT|0.005262|-1.77|-42.55|-1.38|21055279|1.90|
|WLD_USDT|0.320200|-1.74|-19.08|-1.35|24764016|3.12|
|INJ_USDT|7.994000|-1.68|11.15|-1.29|18613718|1.25|
|LIT_USDT|3.145600|-1.49|-2.61|-1.10|7865510|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005262|0.005192|0.005263|0.51|N|Y/Y|N/N|Y|N|
|INJ_USDT|7.994000|7.946000|7.994000|0.86|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.145600|3.140100|3.145600|2.63|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.604000|3.586000|3.604000|1.14|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001781|0.001693|0.001781|0.62|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003664|0.003635|0.003664|0.37|N|Y/N|Y/Y|Y|N|
|WLD_USDT|0.320200|0.319600|0.320200|0.93|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1248.180000|1238.290000|1248.180000|1.33|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T17:45:00+00:00, last15m_closed_end=2026-11-08T17:45+00:00, prior8high=0.005442, depth_time=2026-11-08T17:45:17+00:00, book20_bid_proxy_usdt=69518, book20_ask_proxy_usdt=66855, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.77%, turnover=21055279. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-08T17:45:00+00:00, last15m_closed_end=2026-11-08T17:45+00:00, prior8high=8.160000, depth_time=2026-11-08T17:45:17+00:00, book20_bid_proxy_usdt=308682, book20_ask_proxy_usdt=280933, funding_indicative=0.000261, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=18613718. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-08T17:45:00+00:00, last15m_closed_end=2026-11-08T17:45+00:00, prior8high=3.246600, depth_time=2026-11-08T17:45:23+00:00, book20_bid_proxy_usdt=18561, book20_ask_proxy_usdt=24229, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.49%, turnover=7865510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T17:45:00+00:00, last15m_closed_end=2026-11-08T17:45+00:00, prior8high=3.715000, depth_time=2026-11-08T17:45:09+00:00, book20_bid_proxy_usdt=3892637, book20_ask_proxy_usdt=4751746, funding_indicative=0.000046, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=31072742. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T17:45:00+00:00, last15m_closed_end=2026-11-08T17:45+00:00, prior8high=0.001987, depth_time=2026-11-08T17:45:07+00:00, book20_bid_proxy_usdt=11102, book20_ask_proxy_usdt=18969, funding_indicative=-0.001346, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.02%, turnover=19125382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-08T17:45:00+00:00, last15m_closed_end=2026-11-08T17:45+00:00, prior8high=0.003757, depth_time=2026-11-08T17:45:12+00:00, book20_bid_proxy_usdt=1614819, book20_ask_proxy_usdt=1989819, funding_indicative=0.000006, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=10445528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T17:45:00+00:00, last15m_closed_end=2026-11-08T17:45+00:00, prior8high=0.327500, depth_time=2026-11-08T17:45:18+00:00, book20_bid_proxy_usdt=4684259, book20_ask_proxy_usdt=4267646, funding_indicative=-0.000149, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=24764016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T17:45:00+00:00, last15m_closed_end=2026-11-08T17:45+00:00, prior8high=1275.980000, depth_time=2026-11-08T17:45:14+00:00, book20_bid_proxy_usdt=385293, book20_ask_proxy_usdt=95244, funding_indicative=0.000032, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=1409229892. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
