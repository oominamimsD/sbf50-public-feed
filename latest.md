# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T05:15:19Z**
- feed_generated_utc: 2026-11-08T05:15:20+00:00
- source_sha256: `a804ec43dea9305a0a378fbb996cfee5958da2da3cda4ce3c77d46aa6c626166`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T05:15+00:00, close=75877.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T05:00+00:00, close=75830.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001910|-6.20|62.69|-6.39|26180502|0.52|
|ENA_USDT|0.154220|-2.50|-20.50|-2.69|28195798|0.65|
|TIA_USDT|0.434100|-1.69|-11.42|-1.88|7336736|2.30|
|QNT_USDT|195.620000|-1.62|-2.70|-1.81|45667165|1.02|
|ONDO_USDT|0.358500|-1.26|-13.06|-1.45|8654341|2.79|
|WLD_USDT|0.331600|-1.19|-18.00|-1.38|23653176|3.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.154220|0.153230|0.154220|0.70|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.358500|0.357400|0.358500|0.89|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001910|0.001804|0.001910|0.94|N|Y/Y|N/N|Y|N|
|QNT_USDT|195.620000|193.760000|195.620000|0.88|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.434100|0.432800|0.434100|0.68|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.331600|0.329900|0.331600|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-08T05:14:59+00:00, last15m_closed_end=2026-11-08T05:15+00:00, prior8high=0.155430, depth_time=2026-11-08T05:15:08+00:00, book20_bid_proxy_usdt=169609, book20_ask_proxy_usdt=173681, funding_indicative=0.000030, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=28195798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T05:14:59+00:00, last15m_closed_end=2026-11-08T05:15+00:00, prior8high=0.362000, depth_time=2026-11-08T05:15:16+00:00, book20_bid_proxy_usdt=1622170, book20_ask_proxy_usdt=2048354, funding_indicative=-0.000009, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.26%, turnover=8654341. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T05:14:59+00:00, last15m_closed_end=2026-11-08T05:15+00:00, prior8high=0.001974, depth_time=2026-11-08T05:15:05+00:00, book20_bid_proxy_usdt=21822, book20_ask_proxy_usdt=14775, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.20%, turnover=26180502. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T05:14:59+00:00, last15m_closed_end=2026-11-08T05:15+00:00, prior8high=195.100000, depth_time=2026-11-08T05:15:13+00:00, book20_bid_proxy_usdt=127341, book20_ask_proxy_usdt=113753, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=45667165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T05:14:59+00:00, last15m_closed_end=2026-11-08T05:15+00:00, prior8high=0.438300, depth_time=2026-11-08T05:15:09+00:00, book20_bid_proxy_usdt=302542, book20_ask_proxy_usdt=286769, funding_indicative=0.000000, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.69%, turnover=7336736. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T05:14:59+00:00, last15m_closed_end=2026-11-08T05:15+00:00, prior8high=0.332300, depth_time=2026-11-08T05:15:18+00:00, book20_bid_proxy_usdt=3207218, book20_ask_proxy_usdt=3652595, funding_indicative=-0.000145, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=23653176. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
