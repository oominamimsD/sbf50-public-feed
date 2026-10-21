# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T14:45:33Z**
- feed_generated_utc: 2026-10-21T14:45:36+00:00
- source_sha256: `95733574683cac12a89776088e6fa22b0b2f930e6ee5ae6a1a9bc43c9f972fe3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1206; contracts: 1198; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T14:45+00:00, close=84174.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T14:00+00:00, close=83782.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.045521|-29.56|181.39|-31.46|6391317|0.22|
|BAT_USDT|0.179310|-16.89|1.08|-18.79|10758273|0.56|
|BTW_USDT|1.565300|-15.37|-19.83|-17.27|26918045|3.83|
|AKE_USDT|0.027141|-12.70|8.27|-14.60|9808789|0.74|
|BR_USDT|0.578200|-11.13|33.53|-13.03|19871161|4.15|
|OP_USDT|0.129430|-1.41|-8.94|-3.31|7534744|0.77|
|SILVER_USDT|57.620000|-0.56|-2.98|-2.46|213528076|1.74|
|SEI_USDT|0.061650|0.03|-1.15|-1.87|10187472|3.24|
|TIA_USDT|0.624800|0.33|8.22|-1.57|45795098|1.60|
|QNT_USDT|196.230000|0.54|-4.02|-1.36|75507653|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.045521|0.044473|0.045521|0.58|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.027141|0.026106|0.027137|0.41|N|Y/Y|Y/N|N|N|
|BAT_USDT|0.179310|0.177360|0.179310|0.86|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.578200|0.575600|0.578600|0.86|N|Y/Y|N/N|N|N|
|BTW_USDT|1.565300|1.471900|1.565300|1.15|N|Y/Y|Y/Y|N|N|
|OP_USDT|0.129430|0.127930|0.129510|0.96|N|Y/Y|N/N|N|N|
|QNT_USDT|196.230000|192.220000|196.220000|1.53|N|Y/Y|N/N|N|N|
|SEI_USDT|0.061650|0.060870|0.061650|1.32|N|Y/N|N/N|N|N|
|SILVER_USDT|57.620000|57.440000|57.620000|0.91|N|N/N|N/N|N|N|
|TIA_USDT|0.624800|0.611200|0.625000|0.63|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T14:45:02+00:00, last15m_closed_end=2026-10-21T14:45+00:00, prior8high=0.046369, depth_time=2026-10-21T14:45:07+00:00, book20_bid_proxy_usdt=9625, book20_ask_proxy_usdt=5340, funding_indicative=0.000162, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-29.56%, turnover=6391317. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-21T14:45:02+00:00, last15m_closed_end=2026-10-21T14:45+00:00, prior8high=0.030311, depth_time=2026-10-21T14:45:17+00:00, book20_bid_proxy_usdt=11165, book20_ask_proxy_usdt=9660, funding_indicative=0.000050, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.70%, turnover=9808789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T14:45:02+00:00, last15m_closed_end=2026-10-21T14:45+00:00, prior8high=0.182410, depth_time=2026-10-21T14:45:12+00:00, book20_bid_proxy_usdt=14510, book20_ask_proxy_usdt=21630, funding_indicative=-0.000232, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-16.89%, turnover=10758273. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T14:45:02+00:00, last15m_closed_end=2026-10-21T14:45+00:00, prior8high=0.634300, depth_time=2026-10-21T14:45:19+00:00, book20_bid_proxy_usdt=2989, book20_ask_proxy_usdt=2674, funding_indicative=0.000047, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.13%, turnover=19871161. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T14:45:02+00:00, last15m_closed_end=2026-10-21T14:45+00:00, prior8high=1.641600, depth_time=2026-10-21T14:45:14+00:00, book20_bid_proxy_usdt=8772, book20_ask_proxy_usdt=13489, funding_indicative=-0.005285, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-15.37%, turnover=26918045. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-21T14:45:02+00:00, last15m_closed_end=2026-10-21T14:45+00:00, prior8high=0.131020, depth_time=2026-10-21T14:45:22+00:00, book20_bid_proxy_usdt=74810, book20_ask_proxy_usdt=85373, funding_indicative=0.000043, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=7534744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-21T14:45:02+00:00, last15m_closed_end=2026-10-21T14:45+00:00, prior8high=200.010000, depth_time=2026-10-21T14:45:31+00:00, book20_bid_proxy_usdt=61160, book20_ask_proxy_usdt=92263, funding_indicative=-0.000039, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.54%, turnover=75507653. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-21T14:45:02+00:00, last15m_closed_end=2026-10-21T14:45+00:00, prior8high=0.062450, depth_time=2026-10-21T14:45:27+00:00, book20_bid_proxy_usdt=244045, book20_ask_proxy_usdt=222616, funding_indicative=-0.000062, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.03%, turnover=10187472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T14:45:02+00:00, last15m_closed_end=2026-10-21T14:45+00:00, prior8high=57.950000, depth_time=2026-10-21T14:45:24+00:00, book20_bid_proxy_usdt=39199545, book20_ask_proxy_usdt=40105265, funding_indicative=0.000039, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.56%, turnover=213528076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T14:45:02+00:00, last15m_closed_end=2026-10-21T14:45+00:00, prior8high=0.626700, depth_time=2026-10-21T14:45:29+00:00, book20_bid_proxy_usdt=254902, book20_ask_proxy_usdt=263334, funding_indicative=-0.000061, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=0.33%, turnover=45795098. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
