# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T13:15:16Z**
- feed_generated_utc: 2026-11-04T13:15:17+00:00
- source_sha256: `8bdb863b63da64ac436831c38ca082d52a19412fd6311a4afc8f60a5c2c08180`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T13:15+00:00, close=78361.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T13:00+00:00, close=78272, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.033420|-37.89|-29.67|-38.76|9448079|2.99|
|AKE_USDT|0.003003|-27.74|-85.78|-28.61|14126757|3.33|
|TRUMPOFFICIAL_USDT|1.418000|-11.81|-15.99|-12.68|12368593|7.05|
|HOT_USDT|0.000485|-9.91|40.41|-10.78|5986230|2.06|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.033420|0.032170|0.033420|0.71|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.003003|0.002758|0.003003|1.25|N|Y/Y|Y/Y|N|N|
|HOT_USDT|0.000485|0.000479|0.000485|1.68|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.418000|1.413000|1.420000|2.09|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T13:15:02+00:00, last15m_closed_end=2026-11-04T13:15+00:00, prior8high=0.033920, depth_time=2026-11-04T13:15:07+00:00, book20_bid_proxy_usdt=17942, book20_ask_proxy_usdt=29947, funding_indicative=0.000053, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-37.89%, turnover=9448079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T13:15:02+00:00, last15m_closed_end=2026-11-04T13:15+00:00, prior8high=0.003257, depth_time=2026-11-04T13:15:10+00:00, book20_bid_proxy_usdt=51121, book20_ask_proxy_usdt=63042, funding_indicative=0.000004, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-27.74%, turnover=14126757. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T13:15:02+00:00, last15m_closed_end=2026-11-04T13:15+00:00, prior8high=0.000516, depth_time=2026-11-04T13:15:14+00:00, book20_bid_proxy_usdt=71894, book20_ask_proxy_usdt=84725, funding_indicative=-0.000113, next_funding_utc=2026-11-04T14:00:00+00:00, funding_cycle_h=1, 24h_change=-9.91%, turnover=5986230. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T13:15:02+00:00, last15m_closed_end=2026-11-04T13:15+00:00, prior8high=1.490000, depth_time=2026-11-04T13:15:12+00:00, book20_bid_proxy_usdt=1797471, book20_ask_proxy_usdt=1484613, funding_indicative=-0.000358, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.81%, turnover=12368593. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
