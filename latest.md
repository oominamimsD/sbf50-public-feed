# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T01:00:24Z**
- feed_generated_utc: 2026-10-26T01:00:27+00:00
- source_sha256: `9dfc513b5100a0cdf8f062bd01846fff5cbcafa76c74de885c3a024d37bb8fcf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T01:00+00:00, close=80135.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T01:00+00:00, close=80135.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005592|-19.79|203.41|-19.22|10438012|3.58|
|IRYS_USDT|0.036500|-5.04|199.18|-4.47|20198334|2.74|
|BTW_USDT|1.617700|-2.48|-29.82|-1.91|12687370|1.85|
|PEPE_USDT|0.000004|-2.14|11.59|-1.57|75900611|1.87|
|WLD_USDT|0.448300|-1.81|-5.87|-1.24|74919555|2.23|
|XMR_USDT|596.210000|-1.81|2.35|-1.24|6696051|0.17|
|DASH_USDT|51.570000|-1.60|7.70|-1.03|13977331|1.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.617700|1.606400|1.617700|1.24|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|51.570000|50.870000|51.570000|0.23|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.036500|0.034710|0.036500|1.85|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005592|0.005640|0.005582|4.69|Y|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.24|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.448300|0.443500|0.448300|0.73|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|596.210000|589.580000|596.210000|0.67|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T00:59:59+00:00, last15m_closed_end=2026-10-26T01:00+00:00, prior8high=1.653300, depth_time=2026-10-26T01:00:13+00:00, book20_bid_proxy_usdt=18274, book20_ask_proxy_usdt=17814, funding_indicative=-0.007377, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.48%, turnover=12687370. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T00:59:59+00:00, last15m_closed_end=2026-10-26T01:00+00:00, prior8high=51.950000, depth_time=2026-10-26T01:00:23+00:00, book20_bid_proxy_usdt=815141, book20_ask_proxy_usdt=545083, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=13977331. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T00:59:59+00:00, last15m_closed_end=2026-10-26T01:00+00:00, prior8high=0.039720, depth_time=2026-10-26T01:00:10+00:00, book20_bid_proxy_usdt=38887, book20_ask_proxy_usdt=44369, funding_indicative=-0.000256, next_funding_utc=2026-10-26T02:00:00+00:00, funding_cycle_h=1, 24h_change=-5.04%, turnover=20198334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T00:59:59+00:00, last15m_closed_end=2026-10-26T01:00+00:00, prior8high=0.006470, depth_time=2026-10-26T01:00:08+00:00, book20_bid_proxy_usdt=17359, book20_ask_proxy_usdt=28179, funding_indicative=0.000050, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-19.79%, turnover=10438012. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T00:59:59+00:00, last15m_closed_end=2026-10-26T01:00+00:00, prior8high=0.000004, depth_time=2026-10-26T01:00:16+00:00, book20_bid_proxy_usdt=39224, book20_ask_proxy_usdt=63303, funding_indicative=0.000075, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=75900611. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T00:59:59+00:00, last15m_closed_end=2026-10-26T01:00+00:00, prior8high=0.454000, depth_time=2026-10-26T01:00:18+00:00, book20_bid_proxy_usdt=1405271, book20_ask_proxy_usdt=1973804, funding_indicative=0.000043, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=74919555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T00:59:59+00:00, last15m_closed_end=2026-10-26T01:00+00:00, prior8high=596.050000, depth_time=2026-10-26T01:00:20+00:00, book20_bid_proxy_usdt=48164, book20_ask_proxy_usdt=24044, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=6696051. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
