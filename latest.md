# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T15:30:31Z**
- feed_generated_utc: 2026-10-29T15:30:33+00:00
- source_sha256: `5bf6ba2e1faa77ecc8091f210519803dd5c7bb1948b5285f11c533286f535426`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T15:30+00:00, close=81404.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T15:00+00:00, close=81149.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T12:00+00:00, close=80133.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.039320|-36.85|-66.15|-37.94|34705981|7.63|
|EVAA_USDT|1.162100|-21.74|106.19|-22.83|17060721|7.74|
|BTW_USDT|1.594500|-8.25|8.48|-9.34|9452174|1.88|
|JASMY_USDT|0.003902|-7.90|-19.97|-8.99|7801483|5.12|
|DASH_USDT|51.050000|-3.75|-4.16|-4.84|16347750|1.96|
|SILVER_USDT|52.590000|-2.01|-8.79|-3.10|546628370|1.90|
|HBAR_USDT|0.074430|-1.94|-13.39|-3.03|15507772|1.34|
|XRP_USDT|1.303700|-0.57|-5.54|-1.66|304284384|0.77|
|XAU_USDT|4031.190000|-0.45|-2.61|-1.54|621599361|0.05|
|XAUT_USDT|4020.960000|-0.39|-2.64|-1.48|268447465|0.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.594500|1.606100|1.599700|3.03|Y|Y/Y|N/N|Y|N|
|DASH_USDT|51.050000|50.040000|51.050000|0.65|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.162100|1.161100|1.158500|0.54|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.074430|0.073740|0.074430|1.73|N|N/N|Y/Y|Y|N|
|JASMY_USDT|0.003902|0.003843|0.003902|0.39|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.039320|0.039260|0.039300|2.52|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.590000|52.110000|52.570000|0.21|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4020.960000|4015.260000|4020.420000|1.51|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4031.190000|4025.280000|4029.950000|0.86|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.303700|1.285100|1.303700|2.62|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-29T15:30:01+00:00, last15m_closed_end=2026-10-29T15:30+00:00, prior8high=1.785400, depth_time=2026-10-29T15:30:12+00:00, book20_bid_proxy_usdt=10669, book20_ask_proxy_usdt=12441, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.25%, turnover=9452174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-29T15:30:01+00:00, last15m_closed_end=2026-10-29T15:30+00:00, prior8high=51.150000, depth_time=2026-10-29T15:30:12+00:00, book20_bid_proxy_usdt=619086, book20_ask_proxy_usdt=533644, funding_indicative=-0.000005, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.75%, turnover=16347750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T15:30:01+00:00, last15m_closed_end=2026-10-29T15:30+00:00, prior8high=1.249100, depth_time=2026-10-29T15:30:10+00:00, book20_bid_proxy_usdt=15269, book20_ask_proxy_usdt=16503, funding_indicative=0.000159, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.74%, turnover=17060721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T15:30:01+00:00, last15m_closed_end=2026-10-29T15:30+00:00, prior8high=0.075160, depth_time=2026-10-29T15:30:22+00:00, book20_bid_proxy_usdt=608635, book20_ask_proxy_usdt=1241032, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=15507772. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JASMY_USDT: quote_utc=2026-10-29T15:30:01+00:00, last15m_closed_end=2026-10-29T15:30+00:00, prior8high=0.003940, depth_time=2026-10-29T15:30:15+00:00, book20_bid_proxy_usdt=160412, book20_ask_proxy_usdt=160408, funding_indicative=-0.000446, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.90%, turnover=7801483. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T15:30:01+00:00, last15m_closed_end=2026-10-29T15:30+00:00, prior8high=0.042860, depth_time=2026-10-29T15:30:07+00:00, book20_bid_proxy_usdt=61995, book20_ask_proxy_usdt=79814, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-36.85%, turnover=34705981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-29T15:30:01+00:00, last15m_closed_end=2026-10-29T15:30+00:00, prior8high=52.890000, depth_time=2026-10-29T15:30:20+00:00, book20_bid_proxy_usdt=48725835, book20_ask_proxy_usdt=36532172, funding_indicative=0.000081, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=546628370. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-29T15:30:01+00:00, last15m_closed_end=2026-10-29T15:30+00:00, prior8high=4033.370000, depth_time=2026-10-29T15:30:29+00:00, book20_bid_proxy_usdt=131550, book20_ask_proxy_usdt=159854, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.39%, turnover=268447465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-29T15:30:01+00:00, last15m_closed_end=2026-10-29T15:30+00:00, prior8high=4044.990000, depth_time=2026-10-29T15:30:27+00:00, book20_bid_proxy_usdt=4631420, book20_ask_proxy_usdt=806631, funding_indicative=0.000057, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.45%, turnover=621599361. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-10-29T15:30:01+00:00, last15m_closed_end=2026-10-29T15:30+00:00, prior8high=1.312300, depth_time=2026-10-29T15:30:24+00:00, book20_bid_proxy_usdt=3222130, book20_ask_proxy_usdt=3176727, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.57%, turnover=304284384. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
