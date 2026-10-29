# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T13:00:26Z**
- feed_generated_utc: 2026-10-29T13:00:29+00:00
- source_sha256: `206c6e46aea8911095796ea4044227cb8643c7fbd7a5101b5bcca79e5435fba7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T13:00+00:00, close=80026.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-29T13:00+00:00, close=80026.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-29T12:00+00:00, close=80133.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.040800|-34.47|-64.87|-33.85|33955862|7.35|
|EVAA_USDT|1.226400|-17.41|117.60|-16.79|21313452|9.78|
|DASH_USDT|50.130000|-5.41|-5.89|-4.79|13539656|2.00|
|NEAR_USDT|4.450000|-3.86|-17.36|-3.24|110603634|2.25|
|WLD_USDT|0.421500|-2.61|-26.51|-1.99|85959227|2.37|
|SILVER_USDT|52.500000|-2.17|-8.94|-1.55|509851873|1.91|
|HBAR_USDT|0.074120|-1.80|-13.75|-1.18|15188791|1.35|
|XRP_USDT|1.288600|-1.72|-6.64|-1.10|296300618|0.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|50.130000|49.890000|50.130000|1.63|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.226400|1.101000|1.226400|0.58|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.074120|0.073220|0.074120|1.37|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.450000|4.381000|4.450000|1.35|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.040800|0.039240|0.040800|0.33|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.500000|52.450000|52.500000|1.19|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.421500|0.416800|0.421500|0.57|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.288600|1.285700|1.288600|0.65|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-29T13:00:00+00:00, last15m_closed_end=2026-10-29T13:00+00:00, prior8high=50.850000, depth_time=2026-10-29T13:00:10+00:00, book20_bid_proxy_usdt=413020, book20_ask_proxy_usdt=667022, funding_indicative=0.000025, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.41%, turnover=13539656. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T12:59:59+00:00, last15m_closed_end=2026-10-29T13:00+00:00, prior8high=1.285900, depth_time=2026-10-29T13:00:09+00:00, book20_bid_proxy_usdt=19204, book20_ask_proxy_usdt=21335, funding_indicative=0.000189, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-17.41%, turnover=21313452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T13:00:00+00:00, last15m_closed_end=2026-10-29T13:00+00:00, prior8high=0.074130, depth_time=2026-10-29T13:00:22+00:00, book20_bid_proxy_usdt=866922, book20_ask_proxy_usdt=1104405, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=15188791. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T12:59:59+00:00, last15m_closed_end=2026-10-29T13:00+00:00, prior8high=4.445000, depth_time=2026-10-29T13:00:14+00:00, book20_bid_proxy_usdt=6307860, book20_ask_proxy_usdt=3374318, funding_indicative=0.000060, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.86%, turnover=110603634. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T12:59:59+00:00, last15m_closed_end=2026-10-29T13:00+00:00, prior8high=0.045970, depth_time=2026-10-29T13:00:07+00:00, book20_bid_proxy_usdt=85201, book20_ask_proxy_usdt=41594, funding_indicative=0.000136, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-34.47%, turnover=33955862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-29T12:59:59+00:00, last15m_closed_end=2026-10-29T13:00+00:00, prior8high=53.180000, depth_time=2026-10-29T13:00:19+00:00, book20_bid_proxy_usdt=43440378, book20_ask_proxy_usdt=48636620, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=509851873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T12:59:59+00:00, last15m_closed_end=2026-10-29T13:00+00:00, prior8high=0.426400, depth_time=2026-10-29T13:00:17+00:00, book20_bid_proxy_usdt=2754996, book20_ask_proxy_usdt=4105301, funding_indicative=0.000074, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=85959227. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-10-29T12:59:59+00:00, last15m_closed_end=2026-10-29T13:00+00:00, prior8high=1.296500, depth_time=2026-10-29T13:00:25+00:00, book20_bid_proxy_usdt=3516297, book20_ask_proxy_usdt=3599367, funding_indicative=0.000098, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=296300618. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
