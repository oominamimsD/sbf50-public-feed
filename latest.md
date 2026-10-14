# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T10:00:32Z**
- feed_generated_utc: 2026-10-14T10:00:34+00:00
- source_sha256: `d3a3e4d4656eba1e2b8a6e2cac0145bb3c810833cda052aaeee37bb7a686a145`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T10:00+00:00, close=83219.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T10:00+00:00, close=83219.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.056380|-20.14|29.01|-19.94|24669525|1.77|
|W_USDT|0.015990|-11.02|10.18|-10.82|6734145|2.50|
|STRK_USDT|0.079590|-8.44|52.50|-8.24|29053383|1.25|
|TIA_USDT|0.546900|-6.51|14.82|-6.31|36436069|1.83|
|DOT_USDT|1.134000|-4.26|-5.61|-4.06|19871472|0.88|
|RENDER_USDT|1.970000|-2.42|-7.51|-2.22|9469622|5.08|
|UNI_USDT|7.347000|-2.37|-15.21|-2.17|18945788|1.36|
|ICP_USDT|3.072000|-2.19|-9.70|-1.99|9550966|3.25|
|XLM_USDT|0.188500|-1.82|-11.78|-1.62|9802447|0.53|
|SILVER_USDT|58.700000|-1.52|-4.35|-1.32|252552992|1.70|
|FILECOIN_USDT|1.133600|-1.35|-1.46|-1.15|25561175|0.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.134000|1.130800|1.134000|2.00|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.133600|1.129200|1.133600|1.20|N|Y/Y|N/N|Y|N|
|ICP_USDT|3.072000|3.061000|3.072000|1.55|N|Y/Y|Y/Y|Y|N|
|RENDER_USDT|1.970000|1.946000|1.970000|2.57|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|58.700000|58.570000|58.700000|0.24|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.079590|0.078200|0.079690|0.82|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.056380|0.055870|0.056380|1.02|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.546900|0.544200|0.546900|0.47|N|Y/Y|Y/N|Y|N|
|UNI_USDT|7.347000|7.330000|7.347000|1.32|N|Y/Y|Y/Y|Y|N|
|W_USDT|0.015990|0.015659|0.015990|0.91|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.188500|0.188210|0.188500|1.04|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-14T10:00:02+00:00, last15m_closed_end=2026-10-14T10:00+00:00, prior8high=1.164200, depth_time=2026-10-14T10:00:17+00:00, book20_bid_proxy_usdt=244032, book20_ask_proxy_usdt=299170, funding_indicative=0.000015, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.26%, turnover=19871472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-14T10:00:01+00:00, last15m_closed_end=2026-10-14T10:00+00:00, prior8high=1.179300, depth_time=2026-10-14T10:00:31+00:00, book20_bid_proxy_usdt=762785, book20_ask_proxy_usdt=580544, funding_indicative=-0.000012, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=25561175. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-14T10:00:02+00:00, last15m_closed_end=2026-10-14T10:00+00:00, prior8high=3.139000, depth_time=2026-10-14T10:00:24+00:00, book20_bid_proxy_usdt=646556, book20_ask_proxy_usdt=601366, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=9550966. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RENDER_USDT: quote_utc=2026-10-14T10:00:02+00:00, last15m_closed_end=2026-10-14T10:00+00:00, prior8high=2.037000, depth_time=2026-10-14T10:00:17+00:00, book20_bid_proxy_usdt=1451283, book20_ask_proxy_usdt=1659118, funding_indicative=0.000034, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.42%, turnover=9469622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T10:00:01+00:00, last15m_closed_end=2026-10-14T10:00+00:00, prior8high=59.010000, depth_time=2026-10-14T10:00:29+00:00, book20_bid_proxy_usdt=56371980, book20_ask_proxy_usdt=43942175, funding_indicative=0.000091, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.52%, turnover=252552992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T10:00:01+00:00, last15m_closed_end=2026-10-14T10:00+00:00, prior8high=0.082970, depth_time=2026-10-14T10:00:11+00:00, book20_bid_proxy_usdt=307825, book20_ask_proxy_usdt=226480, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.44%, turnover=29053383. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T10:00:01+00:00, last15m_closed_end=2026-10-14T10:00+00:00, prior8high=0.057430, depth_time=2026-10-14T10:00:07+00:00, book20_bid_proxy_usdt=49564, book20_ask_proxy_usdt=103380, funding_indicative=-0.000069, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-20.14%, turnover=24669525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T10:00:01+00:00, last15m_closed_end=2026-10-14T10:00+00:00, prior8high=0.564000, depth_time=2026-10-14T10:00:15+00:00, book20_bid_proxy_usdt=120940, book20_ask_proxy_usdt=233790, funding_indicative=0.000007, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.51%, turnover=36436069. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T10:00:01+00:00, last15m_closed_end=2026-10-14T10:00+00:00, prior8high=7.502000, depth_time=2026-10-14T10:00:22+00:00, book20_bid_proxy_usdt=1176847, book20_ask_proxy_usdt=1617302, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.37%, turnover=18945788. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T10:00:01+00:00, last15m_closed_end=2026-10-14T10:00+00:00, prior8high=0.016686, depth_time=2026-10-14T10:00:09+00:00, book20_bid_proxy_usdt=32859, book20_ask_proxy_usdt=24650, funding_indicative=-0.000354, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.02%, turnover=6734145. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T10:00:02+00:00, last15m_closed_end=2026-10-14T10:00+00:00, prior8high=0.192050, depth_time=2026-10-14T10:00:26+00:00, book20_bid_proxy_usdt=168130, book20_ask_proxy_usdt=229569, funding_indicative=-0.000097, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=9802447. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
