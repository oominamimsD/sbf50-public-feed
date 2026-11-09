# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T04:15:19Z**
- feed_generated_utc: 2026-11-09T04:15:21+00:00
- source_sha256: `594ca5e8ea6bdc6c6c5770efe612554954b4e06080174455a11a8e7badd9bdbb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T04:15+00:00, close=74978.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001648|-15.85|41.47|-14.46|10388395|0.61|
|JCT_USDT|0.008354|-15.04|67.78|-13.65|66552768|4.78|
|AKE_USDT|0.004855|-9.37|-46.99|-7.98|11473572|2.06|
|XRP_USDT|1.112700|-3.72|-10.97|-2.33|228301751|0.90|
|HYPE_USDT|74.659000|-3.57|-14.85|-2.18|40018878|0.13|
|LIT_USDT|3.115400|-2.44|-3.55|-1.05|13386989|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004855|0.004718|0.004855|3.01|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|74.659000|74.391000|74.660000|0.29|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008354|0.008067|0.008366|0.99|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.115400|3.102200|3.115400|1.84|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001648|0.001669|0.001648|0.66|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.112700|1.103000|1.112700|1.38|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T04:15:01+00:00, last15m_closed_end=2026-11-09T04:15+00:00, prior8high=0.005144, depth_time=2026-11-09T04:15:12+00:00, book20_bid_proxy_usdt=168075, book20_ask_proxy_usdt=36154, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.37%, turnover=11473572. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T04:15:01+00:00, last15m_closed_end=2026-11-09T04:15+00:00, prior8high=75.262000, depth_time=2026-11-09T04:15:15+00:00, book20_bid_proxy_usdt=42437, book20_ask_proxy_usdt=99614, funding_indicative=0.000041, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.57%, turnover=40018878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T04:15:01+00:00, last15m_closed_end=2026-11-09T04:15+00:00, prior8high=0.010567, depth_time=2026-11-09T04:15:10+00:00, book20_bid_proxy_usdt=43749, book20_ask_proxy_usdt=18141, funding_indicative=0.001251, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.04%, turnover=66552768. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T04:15:01+00:00, last15m_closed_end=2026-11-09T04:15+00:00, prior8high=3.158500, depth_time=2026-11-09T04:15:17+00:00, book20_bid_proxy_usdt=21905, book20_ask_proxy_usdt=25843, funding_indicative=-0.000042, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.44%, turnover=13386989. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T04:15:01+00:00, last15m_closed_end=2026-11-09T04:15+00:00, prior8high=0.001728, depth_time=2026-11-09T04:15:07+00:00, book20_bid_proxy_usdt=8316, book20_ask_proxy_usdt=9943, funding_indicative=-0.000445, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.85%, turnover=10388395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T04:15:01+00:00, last15m_closed_end=2026-11-09T04:15+00:00, prior8high=1.123100, depth_time=2026-11-09T04:15:13+00:00, book20_bid_proxy_usdt=3866475, book20_ask_proxy_usdt=4148625, funding_indicative=-0.000007, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=228301751. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
