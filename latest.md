# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T01:45:24Z**
- feed_generated_utc: 2026-10-18T01:45:26+00:00
- source_sha256: `49f75053fdb4add168610e4b4e90c6e69d304eaace51fa9a1d1616243a7969f1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T01:45+00:00, close=81832, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T01:00+00:00, close=81513.3, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.158000|-14.68|59.43|-15.31|14855497|6.33|
|DNA_USDT|0.262200|-3.63|UNKNOWN|-4.26|5364410|3.81|
|TIA_USDT|0.638900|-2.90|24.54|-3.53|73202830|1.57|
|STRK_USDT|0.064450|-2.56|-31.01|-3.19|15831754|1.55|
|EIGEN_USDT|0.252400|-1.52|7.13|-2.15|10800766|3.96|
|FILECOIN_USDT|1.071200|-1.48|-5.01|-2.11|20253338|1.87|
|PUMPFUN_USDT|0.004386|-0.58|-23.38|-1.21|23782924|4.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DNA_USDT|0.262200|0.255400|0.262300|0.41|N|N/Y|?|Y|N|
|EIGEN_USDT|0.252400|0.248200|0.252400|0.45|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|1.071200|1.057500|1.069400|2.54|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.158000|0.155400|0.157900|0.48|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004386|0.004297|0.004384|0.94|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.064450|0.063700|0.064440|0.78|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.638900|0.630700|0.639000|0.72|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DNA_USDT: quote_utc=2026-10-18T01:45:02+00:00, last15m_closed_end=2026-10-18T01:45+00:00, prior8high=0.269200, depth_time=2026-10-18T01:45:10+00:00, book20_bid_proxy_usdt=73996, book20_ask_proxy_usdt=130696, funding_indicative=-0.002325, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.63%, turnover=5364410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T01:45:02+00:00, last15m_closed_end=2026-10-18T01:45+00:00, prior8high=0.253300, depth_time=2026-10-18T01:45:16+00:00, book20_bid_proxy_usdt=334101, book20_ask_proxy_usdt=306896, funding_indicative=-0.000008, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.52%, turnover=10800766. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T01:45:02+00:00, last15m_closed_end=2026-10-18T01:45+00:00, prior8high=1.070300, depth_time=2026-10-18T01:45:20+00:00, book20_bid_proxy_usdt=431976, book20_ask_proxy_usdt=446570, funding_indicative=-0.000037, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=20253338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T01:45:02+00:00, last15m_closed_end=2026-10-18T01:45+00:00, prior8high=0.173300, depth_time=2026-10-18T01:45:07+00:00, book20_bid_proxy_usdt=336946, book20_ask_proxy_usdt=178128, funding_indicative=-0.000016, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.68%, turnover=14855497. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T01:45:02+00:00, last15m_closed_end=2026-10-18T01:45+00:00, prior8high=0.004380, depth_time=2026-10-18T01:45:22+00:00, book20_bid_proxy_usdt=1912377, book20_ask_proxy_usdt=1474539, funding_indicative=0.000042, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.58%, turnover=23782924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T01:45:02+00:00, last15m_closed_end=2026-10-18T01:45+00:00, prior8high=0.064810, depth_time=2026-10-18T01:45:16+00:00, book20_bid_proxy_usdt=511445, book20_ask_proxy_usdt=356587, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=15831754. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T01:45:02+00:00, last15m_closed_end=2026-10-18T01:45+00:00, prior8high=0.651200, depth_time=2026-10-18T01:45:12+00:00, book20_bid_proxy_usdt=182034, book20_ask_proxy_usdt=226434, funding_indicative=0.000000, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.90%, turnover=73202830. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
