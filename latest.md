# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T09:00:24Z**
- feed_generated_utc: 2026-10-26T09:00:27+00:00
- source_sha256: `52ffdf0245d572266a03e9bd30f67820d9fcac303841761c7c9c9ea3a2b386ac`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T09:00+00:00, close=80203.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T09:00+00:00, close=80203.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CAP_USDT|0.075580|-29.67|13.65|-29.18|6957949|1.32|
|IRYS_USDT|0.029470|-23.33|141.55|-22.84|12747509|3.39|
|BTW_USDT|1.505400|-9.25|-34.70|-8.76|10787914|3.32|
|APR_USDT|0.037970|-8.08|39.39|-7.59|8824454|7.90|
|WLD_USDT|0.440500|-3.52|-7.51|-3.03|63825493|4.54|
|DASH_USDT|51.470000|-2.90|7.49|-2.41|11649808|1.94|
|XMR_USDT|591.590000|-2.75|1.56|-2.26|5874929|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.037970|0.032200|0.038010|0.54|N|N/Y|N/N|Y|N|
|BTW_USDT|1.505400|1.440500|1.506700|1.38|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.075580|0.075630|0.075770|4.14|N|Y/Y|N/N|Y|N|
|DASH_USDT|51.470000|50.720000|51.470000|1.96|N|N/Y|Y/Y|Y|N|
|IRYS_USDT|0.029470|0.028610|0.029470|1.02|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.440500|0.434300|0.440500|1.79|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|591.590000|583.530000|591.590000|1.20|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T09:00:02+00:00, last15m_closed_end=2026-10-26T09:00+00:00, prior8high=0.039060, depth_time=2026-10-26T09:00:16+00:00, book20_bid_proxy_usdt=66700, book20_ask_proxy_usdt=47382, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.08%, turnover=8824454. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T09:00:03+00:00, last15m_closed_end=2026-10-26T09:00+00:00, prior8high=1.621200, depth_time=2026-10-26T09:00:13+00:00, book20_bid_proxy_usdt=19217, book20_ask_proxy_usdt=12329, funding_indicative=-0.008121, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.25%, turnover=10787914. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T09:00:02+00:00, last15m_closed_end=2026-10-26T09:00+00:00, prior8high=0.106860, depth_time=2026-10-26T09:00:08+00:00, book20_bid_proxy_usdt=51524, book20_ask_proxy_usdt=63742, funding_indicative=0.000151, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-29.67%, turnover=6957949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T09:00:03+00:00, last15m_closed_end=2026-10-26T09:00+00:00, prior8high=51.910000, depth_time=2026-10-26T09:00:19+00:00, book20_bid_proxy_usdt=917206, book20_ask_proxy_usdt=540589, funding_indicative=0.000053, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.90%, turnover=11649808. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T09:00:02+00:00, last15m_closed_end=2026-10-26T09:00+00:00, prior8high=0.031910, depth_time=2026-10-26T09:00:10+00:00, book20_bid_proxy_usdt=59562, book20_ask_proxy_usdt=45882, funding_indicative=-0.000133, next_funding_utc=2026-10-26T10:00:00+00:00, funding_cycle_h=1, 24h_change=-23.33%, turnover=12747509. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T09:00:02+00:00, last15m_closed_end=2026-10-26T09:00+00:00, prior8high=0.443900, depth_time=2026-10-26T09:00:18+00:00, book20_bid_proxy_usdt=2480050, book20_ask_proxy_usdt=2304324, funding_indicative=-0.000087, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.52%, turnover=63825493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T09:00:03+00:00, last15m_closed_end=2026-10-26T09:00+00:00, prior8high=591.620000, depth_time=2026-10-26T09:00:23+00:00, book20_bid_proxy_usdt=27329, book20_ask_proxy_usdt=8753, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=5874929. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
