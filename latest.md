# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T14:45:18Z**
- feed_generated_utc: 2026-11-04T14:45:19+00:00
- source_sha256: `af8ccc328070c04660f68c4a3e7ce28f1ba837c481cfa95efb1927c1acb4d148`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T14:45+00:00, close=79428.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T14:00+00:00, close=78338.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.035740|-33.58|-24.78|-35.83|7883719|5.60|
|AKE_USDT|0.003222|-22.47|-84.74|-24.72|14949417|6.20|
|HOT_USDT|0.000473|-12.14|36.94|-14.39|5293610|2.11|
|TRUMPOFFICIAL_USDT|1.435000|-10.75|-14.98|-13.00|13546246|6.97|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.035740|0.032580|0.035740|1.24|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.003222|0.002758|0.003219|1.05|N|Y/Y|Y/Y|N|N|
|HOT_USDT|0.000473|0.000466|0.000474|0.55|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.435000|1.404000|1.438000|2.52|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T14:45:03+00:00, last15m_closed_end=2026-11-04T14:45+00:00, prior8high=0.037650, depth_time=2026-11-04T14:45:09+00:00, book20_bid_proxy_usdt=18627, book20_ask_proxy_usdt=23701, funding_indicative=0.000053, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-33.58%, turnover=7883719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T14:45:03+00:00, last15m_closed_end=2026-11-04T14:45+00:00, prior8high=0.003257, depth_time=2026-11-04T14:45:12+00:00, book20_bid_proxy_usdt=18435, book20_ask_proxy_usdt=46635, funding_indicative=-0.000060, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.47%, turnover=14949417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T14:45:03+00:00, last15m_closed_end=2026-11-04T14:45+00:00, prior8high=0.000498, depth_time=2026-11-04T14:45:14+00:00, book20_bid_proxy_usdt=76040, book20_ask_proxy_usdt=77846, funding_indicative=-0.000273, next_funding_utc=2026-11-04T15:00:00+00:00, funding_cycle_h=1, 24h_change=-12.14%, turnover=5293610. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T14:45:03+00:00, last15m_closed_end=2026-11-04T14:45+00:00, prior8high=1.448000, depth_time=2026-11-04T14:45:17+00:00, book20_bid_proxy_usdt=1512986, book20_ask_proxy_usdt=1908742, funding_indicative=-0.000389, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.75%, turnover=13546246. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
