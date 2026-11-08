# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T01:45:19Z**
- feed_generated_utc: 2026-11-08T01:45:20+00:00
- source_sha256: `c3e3229bb3b1f85c0d44f80b25e30c0e6e76dfe804d56bdca6c007343ff90bc9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T01:45+00:00, close=75747.2, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T01:00+00:00, close=75774, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|194.250000|-2.31|-3.38|-2.33|43346841|0.52|
|WLD_USDT|0.330400|-1.54|-18.29|-1.56|26306058|3.03|
|AAVE_USDT|130.250000|-1.49|-3.88|-1.51|9578213|0.77|
|ENA_USDT|0.156010|-1.37|-19.58|-1.39|27885450|0.64|
|TIA_USDT|0.436700|-1.10|-10.89|-1.12|7064135|2.29|
|PEPE_USDT|0.000005|-1.01|-2.70|-1.03|39431333|0.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.250000|130.580000|130.250000|0.68|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.156010|0.156170|0.156010|2.12|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000005|0.000005|0.000005|0.75|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.250000|194.240000|194.250000|1.05|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.436700|0.436000|0.436700|0.49|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.330400|0.330300|0.330400|1.77|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T01:45:00+00:00, last15m_closed_end=2026-11-08T01:45+00:00, prior8high=131.790000, depth_time=2026-11-08T01:45:06+00:00, book20_bid_proxy_usdt=386363, book20_ask_proxy_usdt=348706, funding_indicative=0.000006, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=9578213. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T01:45:00+00:00, last15m_closed_end=2026-11-08T01:45+00:00, prior8high=0.159120, depth_time=2026-11-08T01:45:14+00:00, book20_bid_proxy_usdt=242739, book20_ask_proxy_usdt=229134, funding_indicative=-0.000072, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.37%, turnover=27885450. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-08T01:45:00+00:00, last15m_closed_end=2026-11-08T01:45+00:00, prior8high=0.000005, depth_time=2026-11-08T01:45:18+00:00, book20_bid_proxy_usdt=56609, book20_ask_proxy_usdt=37061, funding_indicative=0.000099, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.01%, turnover=39431333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T01:45:00+00:00, last15m_closed_end=2026-11-08T01:45+00:00, prior8high=196.770000, depth_time=2026-11-08T01:45:06+00:00, book20_bid_proxy_usdt=44673, book20_ask_proxy_usdt=66137, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.31%, turnover=43346841. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T01:45:00+00:00, last15m_closed_end=2026-11-08T01:45+00:00, prior8high=0.442300, depth_time=2026-11-08T01:45:09+00:00, book20_bid_proxy_usdt=295745, book20_ask_proxy_usdt=327285, funding_indicative=0.000000, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=7064135. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T01:45:00+00:00, last15m_closed_end=2026-11-08T01:45+00:00, prior8high=0.335400, depth_time=2026-11-08T01:45:08+00:00, book20_bid_proxy_usdt=3972931, book20_ask_proxy_usdt=3488293, funding_indicative=-0.000106, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=26306058. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
