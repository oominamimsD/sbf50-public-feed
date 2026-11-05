# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T03:15:18Z**
- feed_generated_utc: 2026-11-05T03:15:19+00:00
- source_sha256: `416bc39802a8c4e16823f38c685e895bfbdab510cb0a891809d74ec750cc9e44`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T03:15+00:00, close=80588, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T03:00+00:00, close=80544.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002483|-11.63|-87.64|-12.01|16869364|4.04|
|TRUMPOFFICIAL_USDT|1.270000|-10.81|-25.68|-11.19|26696100|7.87|
|CLANKER_USDT|16.750000|-9.99|25.37|-10.37|20169456|5.96|
|IDOL_USDT|0.021488|-8.43|148.21|-8.81|5758996|1.40|
|VVV_USDT|21.634000|-6.56|-9.16|-6.94|5014079|0.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002483|0.002197|0.002483|1.47|N|Y/Y|Y/Y|N|N|
|CLANKER_USDT|16.750000|15.780000|16.770000|0.23|N|Y/Y|N/N|N|N|
|IDOL_USDT|0.021488|0.020956|0.021488|0.21|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.270000|1.228000|1.270000|0.32|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.634000|21.043000|21.634000|2.22|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T03:15:02+00:00, last15m_closed_end=2026-11-05T03:15+00:00, prior8high=0.002642, depth_time=2026-11-05T03:15:07+00:00, book20_bid_proxy_usdt=43153, book20_ask_proxy_usdt=45460, funding_indicative=-0.000549, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.63%, turnover=16869364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T03:15:02+00:00, last15m_closed_end=2026-11-05T03:15+00:00, prior8high=17.830000, depth_time=2026-11-05T03:15:09+00:00, book20_bid_proxy_usdt=147103, book20_ask_proxy_usdt=108410, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.99%, turnover=20169456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T03:15:02+00:00, last15m_closed_end=2026-11-05T03:15+00:00, prior8high=0.021639, depth_time=2026-11-05T03:15:14+00:00, book20_bid_proxy_usdt=9402, book20_ask_proxy_usdt=3868, funding_indicative=0.000087, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.43%, turnover=5758996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T03:15:02+00:00, last15m_closed_end=2026-11-05T03:15+00:00, prior8high=1.276000, depth_time=2026-11-05T03:15:09+00:00, book20_bid_proxy_usdt=1414251, book20_ask_proxy_usdt=1212772, funding_indicative=-0.000296, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.81%, turnover=26696100. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T03:15:02+00:00, last15m_closed_end=2026-11-05T03:15+00:00, prior8high=21.576000, depth_time=2026-11-05T03:15:17+00:00, book20_bid_proxy_usdt=28468, book20_ask_proxy_usdt=18984, funding_indicative=-0.000261, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.56%, turnover=5014079. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
