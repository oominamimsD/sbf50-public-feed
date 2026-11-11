# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T02:15:16Z**
- feed_generated_utc: 2026-11-11T02:15:17+00:00
- source_sha256: `2f37cf6c7bcad656201f21890ea104e54054c7b0c08e719ec95984dde4eb380b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T02:15+00:00, close=73415.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T02:00+00:00, close=73573.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.208150|-17.05|54.78|-17.37|59413001|2.40|
|PIEVERSE_USDT|1.689200|-16.62|43.71|-16.94|5057369|1.78|
|ZEC_USDT|1009.700000|-7.65|-16.12|-7.97|2180357823|0.10|
|DASH_USDT|42.900000|-4.96|-7.02|-5.28|13993825|2.33|
|UNI_USDT|6.651000|-2.62|-9.54|-2.94|35294344|1.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|42.900000|42.810000|42.900000|0.83|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.208150|0.192760|0.208150|1.22|N|Y/Y|N/N|Y|N|
|PIEVERSE_USDT|1.689200|1.756100|1.689200|5.55|Y|Y/Y|N/N|Y|N|
|UNI_USDT|6.651000|6.658000|6.651000|2.88|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1009.700000|1016.660000|1009.700000|1.66|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-11T02:15:00+00:00, last15m_closed_end=2026-11-11T02:15+00:00, prior8high=44.600000, depth_time=2026-11-11T02:15:11+00:00, book20_bid_proxy_usdt=811463, book20_ask_proxy_usdt=767157, funding_indicative=-0.000203, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.96%, turnover=13993825. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T02:14:59+00:00, last15m_closed_end=2026-11-11T02:15+00:00, prior8high=0.226550, depth_time=2026-11-11T02:15:07+00:00, book20_bid_proxy_usdt=7693, book20_ask_proxy_usdt=11816, funding_indicative=-0.011023, next_funding_utc=2026-11-11T03:00:00+00:00, funding_cycle_h=1, 24h_change=-17.05%, turnover=59413001. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-11T02:14:59+00:00, last15m_closed_end=2026-11-11T02:15+00:00, prior8high=1.870000, depth_time=2026-11-11T02:15:09+00:00, book20_bid_proxy_usdt=38564, book20_ask_proxy_usdt=15804, funding_indicative=0.000103, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-16.62%, turnover=5057369. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T02:15:00+00:00, last15m_closed_end=2026-11-11T02:15+00:00, prior8high=6.820000, depth_time=2026-11-11T02:15:11+00:00, book20_bid_proxy_usdt=3000990, book20_ask_proxy_usdt=3457625, funding_indicative=0.000011, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=35294344. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T02:14:59+00:00, last15m_closed_end=2026-11-11T02:15+00:00, prior8high=1049.410000, depth_time=2026-11-11T02:15:11+00:00, book20_bid_proxy_usdt=225745, book20_ask_proxy_usdt=215734, funding_indicative=0.000096, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.65%, turnover=2180357823. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
