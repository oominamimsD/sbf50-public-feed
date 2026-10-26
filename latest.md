# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T04:00:26Z**
- feed_generated_utc: 2026-10-26T04:00:29+00:00
- source_sha256: `39ddae317297e2bb661caffb873509e25a376faac8526be52a25af2e45acd5c7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005132|-25.67|178.45|-24.39|11471110|5.83|
|APR_USDT|0.034870|-14.36|28.01|-13.08|12068793|5.74|
|T_USDT|0.004964|-8.96|5.57|-7.68|6426313|2.02|
|DASH_USDT|50.390000|-4.94|5.24|-3.66|13544666|1.98|
|LIT_USDT|3.037000|-4.14|3.63|-2.86|5811703|0.33|
|XMR_USDT|590.590000|-2.91|1.38|-1.63|6723524|3.89|
|PEPE_USDT|0.000004|-2.89|11.52|-1.61|68795699|0.23|
|WLD_USDT|0.439800|-2.74|-7.66|-1.46|72027942|2.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.034870|0.032120|0.034870|1.21|N|Y/Y|N/N|Y|N|
|DASH_USDT|50.390000|50.250000|50.390000|1.16|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005132|0.003891|0.005132|0.85|N|Y/Y|Y/N|Y|N|
|LIT_USDT|3.037000|3.065300|3.037000|4.81|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000004|0.000004|0.000004|2.05|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004964|0.004876|0.004964|1.66|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.439800|0.440400|0.439800|2.49|Y|Y/Y|Y/Y|Y|Y|
|XMR_USDT|590.590000|588.410000|590.590000|0.78|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T04:00:00+00:00, last15m_closed_end=2026-10-26T04:00+00:00, prior8high=0.036370, depth_time=2026-10-26T04:00:08+00:00, book20_bid_proxy_usdt=90148, book20_ask_proxy_usdt=47280, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.36%, turnover=12068793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T04:00:01+00:00, last15m_closed_end=2026-10-26T04:00+00:00, prior8high=51.070000, depth_time=2026-10-26T04:00:14+00:00, book20_bid_proxy_usdt=704842, book20_ask_proxy_usdt=530862, funding_indicative=0.000033, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.94%, turnover=13544666. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T04:00:00+00:00, last15m_closed_end=2026-10-26T04:00+00:00, prior8high=0.005751, depth_time=2026-10-26T04:00:08+00:00, book20_bid_proxy_usdt=24222, book20_ask_proxy_usdt=20495, funding_indicative=0.000206, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-25.67%, turnover=11471110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T04:00:00+00:00, last15m_closed_end=2026-10-26T04:00+00:00, prior8high=3.152900, depth_time=2026-10-26T04:00:17+00:00, book20_bid_proxy_usdt=21468, book20_ask_proxy_usdt=25965, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.14%, turnover=5811703. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T04:00:00+00:00, last15m_closed_end=2026-10-26T04:00+00:00, prior8high=0.000004, depth_time=2026-10-26T04:00:23+00:00, book20_bid_proxy_usdt=40918, book20_ask_proxy_usdt=57083, funding_indicative=-0.000024, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.89%, turnover=68795699. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T04:00:00+00:00, last15m_closed_end=2026-10-26T04:00+00:00, prior8high=0.004998, depth_time=2026-10-26T04:00:09+00:00, book20_bid_proxy_usdt=45134, book20_ask_proxy_usdt=55093, funding_indicative=-0.001654, next_funding_utc=2026-10-26T05:00:00+00:00, funding_cycle_h=1, 24h_change=-8.96%, turnover=6426313. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T04:00:00+00:00, last15m_closed_end=2026-10-26T04:00+00:00, prior8high=0.447900, depth_time=2026-10-26T04:00:25+00:00, book20_bid_proxy_usdt=2212555, book20_ask_proxy_usdt=2480245, funding_indicative=0.000086, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=72027942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T04:00:00+00:00, last15m_closed_end=2026-10-26T04:00+00:00, prior8high=598.030000, depth_time=2026-10-26T04:00:20+00:00, book20_bid_proxy_usdt=12653, book20_ask_proxy_usdt=42773, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=6723524. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
