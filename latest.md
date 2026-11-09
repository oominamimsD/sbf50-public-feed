# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T02:30:20Z**
- feed_generated_utc: 2026-11-09T02:30:21+00:00
- source_sha256: `619557b433a99d8ca5cbaf4d66984237b873220bdf5c64295d758e815fcc95d2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T02:30+00:00, close=75487.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T02:00+00:00, close=75130.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001702|-13.07|46.14|-12.36|11287552|0.59|
|AKE_USDT|0.005019|-6.30|-45.20|-5.59|13025517|3.99|
|AIOT_USDT|0.141670|-6.27|61.46|-5.56|6419753|9.91|
|JCT_USDT|0.009464|-3.76|90.07|-3.05|64411643|3.17|
|HYPE_USDT|75.165000|-2.92|-14.28|-2.21|40096259|0.53|
|LIT_USDT|3.130700|-1.96|-3.07|-1.25|12490517|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIOT_USDT|0.141670|0.146370|0.141670|1.38|Y|N/N|N/N|Y|N|
|AKE_USDT|0.005019|0.004921|0.005019|0.17|N|Y/Y|N/N|Y|N|
|HYPE_USDT|75.165000|74.059000|75.165000|0.33|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.009464|0.009338|0.009464|0.70|N|Y/N|N/N|Y|N|
|LIT_USDT|3.130700|3.031200|3.130700|0.53|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001702|0.001687|0.001702|0.34|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AIOT_USDT: quote_utc=2026-11-09T02:30:01+00:00, last15m_closed_end=2026-11-09T02:30+00:00, prior8high=0.168520, depth_time=2026-11-09T02:30:12+00:00, book20_bid_proxy_usdt=3431, book20_ask_proxy_usdt=6996, funding_indicative=0.000405, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.27%, turnover=6419753. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-09T02:30:01+00:00, last15m_closed_end=2026-11-09T02:30+00:00, prior8high=0.005297, depth_time=2026-11-09T02:30:09+00:00, book20_bid_proxy_usdt=43394, book20_ask_proxy_usdt=42885, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.30%, turnover=13025517. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T02:30:01+00:00, last15m_closed_end=2026-11-09T02:30+00:00, prior8high=75.415000, depth_time=2026-11-09T02:30:16+00:00, book20_bid_proxy_usdt=85995, book20_ask_proxy_usdt=56045, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.92%, turnover=40096259. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T02:30:01+00:00, last15m_closed_end=2026-11-09T02:30+00:00, prior8high=0.012446, depth_time=2026-11-09T02:30:14+00:00, book20_bid_proxy_usdt=14830, book20_ask_proxy_usdt=17132, funding_indicative=0.001717, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.76%, turnover=64411643. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T02:30:01+00:00, last15m_closed_end=2026-11-09T02:30+00:00, prior8high=3.157600, depth_time=2026-11-09T02:30:17+00:00, book20_bid_proxy_usdt=24507, book20_ask_proxy_usdt=19586, funding_indicative=0.000017, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=12490517. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T02:30:01+00:00, last15m_closed_end=2026-11-09T02:30+00:00, prior8high=0.001763, depth_time=2026-11-09T02:30:07+00:00, book20_bid_proxy_usdt=9852, book20_ask_proxy_usdt=11585, funding_indicative=-0.000795, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.07%, turnover=11287552. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
