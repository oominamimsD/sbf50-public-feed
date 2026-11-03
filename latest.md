# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T13:30:24Z**
- feed_generated_utc: 2026-11-03T13:30:26+00:00
- source_sha256: `cf48cf0c2d5f43b74fb4dbec7c5ae250a3b4b33c791b950f32a7b0da6ae204b6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T13:30+00:00, close=77637.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T13:00+00:00, close=77400, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004294|-21.95|-86.04|-22.15|12225097|4.66|
|BTW_USDT|0.989100|-9.81|-17.27|-10.01|9412630|1.01|
|XPL_USDT|0.064930|-6.68|-12.59|-6.88|11612728|3.08|
|NEAR_USDT|3.899000|-2.76|-14.73|-2.96|80006591|2.56|
|TIA_USDT|0.445000|-2.60|-16.93|-2.80|13526972|2.25|
|DASH_USDT|46.430000|-1.63|-11.08|-1.83|9489372|2.16|
|ENA_USDT|0.172200|-1.62|-18.14|-1.82|72220403|0.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004294|0.004240|0.004289|1.98|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.989100|0.882300|0.989100|0.72|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.430000|45.680000|46.430000|0.67|N|N/Y|Y/Y|Y|N|
|ENA_USDT|0.172200|0.170120|0.172200|1.37|N|N/Y|Y/Y|Y|N|
|NEAR_USDT|3.899000|3.829000|3.899000|2.40|N|N/Y|Y/Y|Y|N|
|TIA_USDT|0.445000|0.438600|0.445000|1.99|N|N/Y|Y/Y|Y|N|
|XPL_USDT|0.064930|0.064160|0.064930|0.57|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T13:29:59+00:00, last15m_closed_end=2026-11-03T13:30+00:00, prior8high=0.004580, depth_time=2026-11-03T13:30:08+00:00, book20_bid_proxy_usdt=37677, book20_ask_proxy_usdt=20107, funding_indicative=-0.001681, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.95%, turnover=12225097. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T13:29:59+00:00, last15m_closed_end=2026-11-03T13:30+00:00, prior8high=1.032400, depth_time=2026-11-03T13:30:10+00:00, book20_bid_proxy_usdt=15685, book20_ask_proxy_usdt=15422, funding_indicative=-0.000051, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.81%, turnover=9412630. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T13:29:59+00:00, last15m_closed_end=2026-11-03T13:30+00:00, prior8high=46.650000, depth_time=2026-11-03T13:30:20+00:00, book20_bid_proxy_usdt=283906, book20_ask_proxy_usdt=480935, funding_indicative=0.000095, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=9489372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T13:29:59+00:00, last15m_closed_end=2026-11-03T13:30+00:00, prior8high=0.173500, depth_time=2026-11-03T13:30:23+00:00, book20_bid_proxy_usdt=113288, book20_ask_proxy_usdt=86679, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=72220403. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T13:29:59+00:00, last15m_closed_end=2026-11-03T13:30+00:00, prior8high=3.928000, depth_time=2026-11-03T13:30:16+00:00, book20_bid_proxy_usdt=1526840, book20_ask_proxy_usdt=3854467, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=80006591. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T13:29:59+00:00, last15m_closed_end=2026-11-03T13:30+00:00, prior8high=0.449000, depth_time=2026-11-03T13:30:18+00:00, book20_bid_proxy_usdt=158933, book20_ask_proxy_usdt=233202, funding_indicative=0.000009, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.60%, turnover=13526972. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T13:29:59+00:00, last15m_closed_end=2026-11-03T13:30+00:00, prior8high=0.065540, depth_time=2026-11-03T13:30:13+00:00, book20_bid_proxy_usdt=281892, book20_ask_proxy_usdt=365240, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.68%, turnover=11612728. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
