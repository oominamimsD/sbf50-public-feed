# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T05:30:34Z**
- feed_generated_utc: 2026-10-31T05:30:36+00:00
- source_sha256: `1aef3af00fc8d3df51b6dbaaa92d90143deb6eaa9e9b68e522ebba06e2017d85`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T05:30+00:00, close=77233.7, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T05:00+00:00, close=77154.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011067|-41.50|-68.37|-41.06|6691499|0.90|
|BEAT_USDT|0.098250|-6.56|35.34|-6.12|8678007|4.07|
|BTW_USDT|1.133300|-5.51|-33.42|-5.07|9518648|1.76|
|EVAA_USDT|1.214400|-5.28|131.35|-4.84|6307665|0.82|
|PEPE_USDT|0.000005|-4.58|-0.66|-4.14|135217154|0.21|
|HYPE_USDT|88.640000|-4.01|13.05|-3.57|110045977|0.11|
|WLD_USDT|0.395700|-3.93|-25.67|-3.49|49956499|2.53|
|TRX_USDT|0.324630|-3.23|-1.43|-2.79|6827716|1.54|
|LIT_USDT|2.738600|-3.03|-17.61|-2.59|5096620|0.36|
|FET_USDT|0.162700|-2.34|-13.13|-1.90|6576323|6.15|
|DASH_USDT|48.070000|-1.97|-10.73|-1.53|15772753|2.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011067|0.010838|0.011067|0.86|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.098250|0.096950|0.098240|0.27|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.133300|1.116500|1.133300|1.58|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.070000|47.930000|48.070000|0.45|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.214400|1.141300|1.214000|1.26|N|Y/N|N/N|Y|N|
|FET_USDT|0.162700|0.162600|0.162700|0.69|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.640000|88.396000|88.684000|1.09|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.738600|2.717700|2.739900|0.72|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.94|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.324630|0.322650|0.324630|0.68|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.395700|0.392600|0.395700|0.57|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T05:30:01+00:00, last15m_closed_end=2026-10-31T05:30+00:00, prior8high=0.012057, depth_time=2026-10-31T05:30:07+00:00, book20_bid_proxy_usdt=6902, book20_ask_proxy_usdt=8058, funding_indicative=-0.000046, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-41.50%, turnover=6691499. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T05:30:01+00:00, last15m_closed_end=2026-10-31T05:30+00:00, prior8high=0.101470, depth_time=2026-10-31T05:30:10+00:00, book20_bid_proxy_usdt=14137, book20_ask_proxy_usdt=7970, funding_indicative=0.000139, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.56%, turnover=8678007. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T05:30:01+00:00, last15m_closed_end=2026-10-31T05:30+00:00, prior8high=1.210000, depth_time=2026-10-31T05:30:13+00:00, book20_bid_proxy_usdt=13188, book20_ask_proxy_usdt=7857, funding_indicative=-0.000452, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.51%, turnover=9518648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T05:30:01+00:00, last15m_closed_end=2026-10-31T05:30+00:00, prior8high=48.640000, depth_time=2026-10-31T05:30:31+00:00, book20_bid_proxy_usdt=886298, book20_ask_proxy_usdt=584154, funding_indicative=0.000043, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=15772753. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T05:30:00+00:00, last15m_closed_end=2026-10-31T05:30+00:00, prior8high=1.275000, depth_time=2026-10-31T05:30:15+00:00, book20_bid_proxy_usdt=9120, book20_ask_proxy_usdt=5194, funding_indicative=0.000218, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.28%, turnover=6307665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T05:30:01+00:00, last15m_closed_end=2026-10-31T05:30+00:00, prior8high=0.165300, depth_time=2026-10-31T05:30:26+00:00, book20_bid_proxy_usdt=1239626, book20_ask_proxy_usdt=899600, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=6576323. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T05:30:00+00:00, last15m_closed_end=2026-10-31T05:30+00:00, prior8high=89.960000, depth_time=2026-10-31T05:30:20+00:00, book20_bid_proxy_usdt=54523, book20_ask_proxy_usdt=141664, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.01%, turnover=110045977. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T05:30:01+00:00, last15m_closed_end=2026-10-31T05:30+00:00, prior8high=2.768800, depth_time=2026-10-31T05:30:27+00:00, book20_bid_proxy_usdt=22510, book20_ask_proxy_usdt=35010, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.03%, turnover=5096620. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T05:30:00+00:00, last15m_closed_end=2026-10-31T05:30+00:00, prior8high=0.000005, depth_time=2026-10-31T05:30:18+00:00, book20_bid_proxy_usdt=21826, book20_ask_proxy_usdt=28279, funding_indicative=-0.000133, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.58%, turnover=135217154. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T05:30:01+00:00, last15m_closed_end=2026-10-31T05:30+00:00, prior8high=0.327950, depth_time=2026-10-31T05:30:23+00:00, book20_bid_proxy_usdt=46983, book20_ask_proxy_usdt=41718, funding_indicative=-0.001161, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=6827716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T05:30:01+00:00, last15m_closed_end=2026-10-31T05:30+00:00, prior8high=0.402700, depth_time=2026-10-31T05:30:21+00:00, book20_bid_proxy_usdt=3270385, book20_ask_proxy_usdt=3545339, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.93%, turnover=49956499. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
