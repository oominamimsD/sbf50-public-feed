# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T07:00:19Z**
- feed_generated_utc: 2026-10-14T07:00:21+00:00
- source_sha256: `5a324dd66f8f2b5173168f4054f663ac321795c9a8e1109af66830e7f1930c15`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T07:00+00:00, close=83400, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T07:00+00:00, close=83400, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.081390|-6.37|55.94|-6.37|31347865|1.23|
|MAGIC_USDT|0.111320|-6.17|63.41|-6.17|5506261|0.90|
|TIA_USDT|0.556700|-3.56|16.88|-3.56|45098636|1.80|
|W_USDT|0.016308|-2.94|12.37|-2.94|7146121|1.23|
|UNI_USDT|7.358000|-2.82|-15.08|-2.82|19908116|1.36|
|SILVER_USDT|58.760000|-1.06|-4.25|-1.06|247794188|1.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.111320|0.111620|0.111320|0.61|N|Y/Y|Y/N|N|N|
|SILVER_USDT|58.760000|58.510000|58.750000|0.55|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.081390|0.080270|0.081390|1.05|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.556700|0.547400|0.556700|0.81|N|Y/Y|N/N|N|N|
|UNI_USDT|7.358000|7.259000|7.358000|0.20|N|Y/Y|Y/N|N|N|
|W_USDT|0.016308|0.015869|0.016308|0.81|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T06:59:59+00:00, last15m_closed_end=2026-10-14T07:00+00:00, prior8high=0.115440, depth_time=2026-10-14T07:00:09+00:00, book20_bid_proxy_usdt=179761, book20_ask_proxy_usdt=329209, funding_indicative=-0.000021, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.17%, turnover=5506261. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T06:59:59+00:00, last15m_closed_end=2026-10-14T07:00+00:00, prior8high=59.470000, depth_time=2026-10-14T07:00:19+00:00, book20_bid_proxy_usdt=41902254, book20_ask_proxy_usdt=54994319, funding_indicative=0.000064, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.06%, turnover=247794188. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T06:59:59+00:00, last15m_closed_end=2026-10-14T07:00+00:00, prior8high=0.085530, depth_time=2026-10-14T07:00:07+00:00, book20_bid_proxy_usdt=215246, book20_ask_proxy_usdt=151728, funding_indicative=0.000050, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.37%, turnover=31347865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T06:59:59+00:00, last15m_closed_end=2026-10-14T07:00+00:00, prior8high=0.581500, depth_time=2026-10-14T07:00:11+00:00, book20_bid_proxy_usdt=125657, book20_ask_proxy_usdt=226521, funding_indicative=-0.000004, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.56%, turnover=45098636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T06:59:59+00:00, last15m_closed_end=2026-10-14T07:00+00:00, prior8high=7.510000, depth_time=2026-10-14T07:00:15+00:00, book20_bid_proxy_usdt=1614020, book20_ask_proxy_usdt=1176285, funding_indicative=0.000100, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=19908116. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T06:59:59+00:00, last15m_closed_end=2026-10-14T07:00+00:00, prior8high=0.016644, depth_time=2026-10-14T07:00:13+00:00, book20_bid_proxy_usdt=35434, book20_ask_proxy_usdt=33749, funding_indicative=-0.000185, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.94%, turnover=7146121. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
