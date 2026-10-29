# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T13:15:24Z**
- feed_generated_utc: 2026-10-29T13:15:25+00:00
- source_sha256: `dd4c7c4c52dae94f9df163900a33923414fad07222c1cb56c2fdff6386850c24`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T13:15+00:00, close=80084, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-29T13:00+00:00, close=80026.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-29T12:00+00:00, close=80133.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.041690|-33.04|-64.11|-32.49|33580985|4.80|
|EVAA_USDT|1.222400|-17.68|116.89|-17.13|19787385|5.73|
|DASH_USDT|50.190000|-5.37|-5.78|-4.82|13983647|3.98|
|NEAR_USDT|4.481000|-3.19|-16.78|-2.64|106083746|2.23|
|WLD_USDT|0.421900|-2.51|-26.44|-1.96|78449863|2.37|
|HBAR_USDT|0.074290|-2.13|-13.55|-1.58|15348115|2.69|
|SILVER_USDT|52.650000|-1.90|-8.68|-1.35|481294875|1.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|50.190000|49.890000|50.190000|3.58|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.222400|1.101000|1.222400|0.56|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.074290|0.073220|0.074290|2.22|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.481000|4.381000|4.480000|1.84|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.041690|0.039240|0.041720|0.50|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.650000|52.440000|52.630000|5.72|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.421900|0.416800|0.421900|1.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-29T13:15:01+00:00, last15m_closed_end=2026-10-29T13:15+00:00, prior8high=50.810000, depth_time=2026-10-29T13:15:13+00:00, book20_bid_proxy_usdt=549795, book20_ask_proxy_usdt=560175, funding_indicative=0.000018, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.37%, turnover=13983647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T13:15:00+00:00, last15m_closed_end=2026-10-29T13:15+00:00, prior8high=1.285900, depth_time=2026-10-29T13:15:10+00:00, book20_bid_proxy_usdt=17758, book20_ask_proxy_usdt=9951, funding_indicative=0.000169, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-17.68%, turnover=19787385. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T13:15:00+00:00, last15m_closed_end=2026-10-29T13:15+00:00, prior8high=0.074160, depth_time=2026-10-29T13:15:20+00:00, book20_bid_proxy_usdt=1125028, book20_ask_proxy_usdt=942477, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=15348115. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T13:15:00+00:00, last15m_closed_end=2026-10-29T13:15+00:00, prior8high=4.450000, depth_time=2026-10-29T13:15:15+00:00, book20_bid_proxy_usdt=3846163, book20_ask_proxy_usdt=4741564, funding_indicative=0.000066, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.19%, turnover=106083746. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T13:15:00+00:00, last15m_closed_end=2026-10-29T13:15+00:00, prior8high=0.045390, depth_time=2026-10-29T13:15:07+00:00, book20_bid_proxy_usdt=42143, book20_ask_proxy_usdt=65092, funding_indicative=0.000069, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-33.04%, turnover=33580985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-29T13:15:00+00:00, last15m_closed_end=2026-10-29T13:15+00:00, prior8high=53.180000, depth_time=2026-10-29T13:15:23+00:00, book20_bid_proxy_usdt=49629339, book20_ask_proxy_usdt=41116594, funding_indicative=0.000095, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=481294875. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T13:15:00+00:00, last15m_closed_end=2026-10-29T13:15+00:00, prior8high=0.424800, depth_time=2026-10-29T13:15:18+00:00, book20_bid_proxy_usdt=3746648, book20_ask_proxy_usdt=3955776, funding_indicative=0.000063, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=78449863. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
