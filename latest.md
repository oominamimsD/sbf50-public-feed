# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T15:15:23Z**
- feed_generated_utc: 2026-10-21T15:15:26+00:00
- source_sha256: `2ff971835d4a97f3cbbafdd071449a789f223e9ae88b4cf2c8bf3654a40a35e2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1206; contracts: 1198; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T15:15+00:00, close=84661.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T15:00+00:00, close=84530, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.046883|-27.45|189.81|-29.96|6183569|3.20|
|BAT_USDT|0.178550|-17.24|0.65|-19.75|9240519|0.56|
|BTW_USDT|1.536700|-16.91|-21.29|-19.42|26516482|1.30|
|BR_USDT|0.559780|-13.96|29.27|-16.47|19149892|3.75|
|AKE_USDT|0.027572|-11.31|9.99|-13.82|9642666|3.99|
|JCT_USDT|0.004207|-8.28|113.77|-10.79|18897400|4.75|
|SILVER_USDT|57.540000|-0.70|-3.11|-3.21|163904041|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.046883|0.044473|0.046883|1.18|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.027572|0.026510|0.027572|0.47|N|Y/Y|Y/N|N|N|
|BAT_USDT|0.178550|0.177360|0.178550|0.93|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.559780|0.575600|0.560310|1.94|Y|Y/Y|N/N|N|N|
|BTW_USDT|1.536700|1.471900|1.532100|0.74|N|Y/Y|Y/Y|N|N|
|JCT_USDT|0.004207|0.004171|0.004210|0.89|N|Y/N|N/N|N|N|
|SILVER_USDT|57.540000|57.440000|57.540000|0.16|N|N/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T15:15:00+00:00, last15m_closed_end=2026-10-21T15:15+00:00, prior8high=0.046265, depth_time=2026-10-21T15:15:08+00:00, book20_bid_proxy_usdt=14566, book20_ask_proxy_usdt=10097, funding_indicative=0.000164, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-27.45%, turnover=6183569. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-21T15:15:00+00:00, last15m_closed_end=2026-10-21T15:15+00:00, prior8high=0.028653, depth_time=2026-10-21T15:15:17+00:00, book20_bid_proxy_usdt=10294, book20_ask_proxy_usdt=12119, funding_indicative=0.000050, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.31%, turnover=9642666. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T15:15:00+00:00, last15m_closed_end=2026-10-21T15:15+00:00, prior8high=0.181140, depth_time=2026-10-21T15:15:11+00:00, book20_bid_proxy_usdt=27669, book20_ask_proxy_usdt=19311, funding_indicative=-0.000244, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-17.24%, turnover=9240519. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T15:15:00+00:00, last15m_closed_end=2026-10-21T15:15+00:00, prior8high=0.634300, depth_time=2026-10-21T15:15:15+00:00, book20_bid_proxy_usdt=2541, book20_ask_proxy_usdt=3704, funding_indicative=0.000016, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.96%, turnover=19149892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T15:15:00+00:00, last15m_closed_end=2026-10-21T15:15+00:00, prior8high=1.641600, depth_time=2026-10-21T15:15:13+00:00, book20_bid_proxy_usdt=7384, book20_ask_proxy_usdt=7702, funding_indicative=-0.004861, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-16.91%, turnover=26516482. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-21T15:15:00+00:00, last15m_closed_end=2026-10-21T15:15+00:00, prior8high=0.004860, depth_time=2026-10-21T15:15:20+00:00, book20_bid_proxy_usdt=66139, book20_ask_proxy_usdt=53609, funding_indicative=0.000155, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.28%, turnover=18897400. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T15:15:00+00:00, last15m_closed_end=2026-10-21T15:15+00:00, prior8high=57.950000, depth_time=2026-10-21T15:15:23+00:00, book20_bid_proxy_usdt=37283527, book20_ask_proxy_usdt=32705156, funding_indicative=0.000043, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.70%, turnover=163904041. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
