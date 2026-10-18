# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T03:15:20Z**
- feed_generated_utc: 2026-10-18T03:15:22+00:00
- source_sha256: `cf88b21d81ec1c81f1c50d620a2d68d90d091d92dac709d63895cd4661b84b37`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T03:15+00:00, close=81894.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T03:00+00:00, close=81790, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.165700|-10.52|67.20|-11.22|14413188|6.04|
|TIA_USDT|0.634800|-3.52|23.74|-4.22|72119603|1.58|
|STRK_USDT|0.064070|-3.14|-31.42|-3.84|14609139|3.12|
|EIGEN_USDT|0.252500|-1.48|7.17|-2.18|10517771|3.96|
|FILECOIN_USDT|1.072500|-1.37|-4.90|-2.07|20921094|0.93|
|PUMPFUN_USDT|0.004363|-1.11|-23.79|-1.81|23206099|2.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|EIGEN_USDT|0.252500|0.247900|0.252500|1.49|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|1.072500|1.054300|1.072500|1.55|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.165700|0.152200|0.165700|1.96|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004363|0.004299|0.004363|1.88|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.064070|0.063420|0.064070|3.77|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.634800|0.628300|0.634800|1.19|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- EIGEN_USDT: quote_utc=2026-10-18T03:15:01+00:00, last15m_closed_end=2026-10-18T03:15+00:00, prior8high=0.253300, depth_time=2026-10-18T03:15:14+00:00, book20_bid_proxy_usdt=298856, book20_ask_proxy_usdt=307910, funding_indicative=0.000006, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.48%, turnover=10517771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T03:15:01+00:00, last15m_closed_end=2026-10-18T03:15+00:00, prior8high=1.071500, depth_time=2026-10-18T03:15:17+00:00, book20_bid_proxy_usdt=322032, book20_ask_proxy_usdt=351177, funding_indicative=-0.000065, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.37%, turnover=20921094. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T03:15:00+00:00, last15m_closed_end=2026-10-18T03:15+00:00, prior8high=0.169300, depth_time=2026-10-18T03:15:07+00:00, book20_bid_proxy_usdt=324468, book20_ask_proxy_usdt=195897, funding_indicative=-0.000007, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.52%, turnover=14413188. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T03:15:01+00:00, last15m_closed_end=2026-10-18T03:15+00:00, prior8high=0.004390, depth_time=2026-10-18T03:15:19+00:00, book20_bid_proxy_usdt=1204404, book20_ask_proxy_usdt=1276209, funding_indicative=0.000023, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.11%, turnover=23206099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T03:15:01+00:00, last15m_closed_end=2026-10-18T03:15+00:00, prior8high=0.064470, depth_time=2026-10-18T03:15:12+00:00, book20_bid_proxy_usdt=544068, book20_ask_proxy_usdt=352505, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.14%, turnover=14609139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T03:15:00+00:00, last15m_closed_end=2026-10-18T03:15+00:00, prior8high=0.649100, depth_time=2026-10-18T03:15:09+00:00, book20_bid_proxy_usdt=153481, book20_ask_proxy_usdt=202340, funding_indicative=-0.000020, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.52%, turnover=72119603. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
