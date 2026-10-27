# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T12:30:42Z**
- feed_generated_utc: 2026-10-27T12:30:46+00:00
- source_sha256: `8d368fd59db859c1cc9802b6b45dc19b5505579ea860dfedc3a881c770b93565`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T12:30+00:00, close=80221.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.024980|-9.42|103.42|-9.20|7279777|4.00|
|QNT_USDT|202.680000|-3.61|3.56|-3.39|113057808|0.49|
|AAVE_USDT|132.200000|-3.31|-10.20|-3.09|27823646|0.76|
|DOT_USDT|0.991300|-3.06|-13.55|-2.84|11067778|1.01|
|PUMPFUN_USDT|0.004207|-2.79|-5.58|-2.57|19517623|2.38|
|FILECOIN_USDT|0.896600|-2.61|-11.40|-2.39|6491163|1.11|
|AVAX_USDT|8.797000|-2.22|-8.00|-2.00|21002652|1.14|
|WLD_USDT|0.435700|-2.08|-13.94|-1.86|67326040|2.30|
|HBAR_USDT|0.076140|-1.57|-6.99|-1.35|10885339|1.31|
|TIA_USDT|0.527600|-1.51|-13.29|-1.29|17338757|1.90|
|PEPE_USDT|0.000004|-1.39|4.68|-1.17|60147000|0.23|
|ICP_USDT|2.594000|-1.36|-9.07|-1.14|5137258|3.85|
|SOL_USDT|100.490000|-1.32|-3.45|-1.10|684000830|1.99|
|LINK_USDT|11.377000|-1.30|-4.73|-1.08|132507391|0.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.200000|129.420000|132.200000|0.87|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.797000|8.703000|8.797000|2.31|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.991300|0.979600|0.991300|0.73|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.896600|0.884300|0.896600|1.63|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.076140|0.075460|0.076140|3.26|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.594000|2.560000|2.594000|4.39|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.024980|0.024650|0.024980|0.74|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.377000|11.225000|11.375000|1.23|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.55|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004207|0.004102|0.004207|1.32|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|202.680000|200.570000|202.680000|0.69|N|Y/N|N/N|Y|N|
|SOL_USDT|100.490000|99.130000|100.510000|2.35|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.527600|0.519800|0.527600|1.22|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.435700|0.428400|0.435700|1.08|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T12:30:00+00:00, last15m_closed_end=2026-10-27T12:30+00:00, prior8high=131.800000, depth_time=2026-10-27T12:30:14+00:00, book20_bid_proxy_usdt=390428, book20_ask_proxy_usdt=483055, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.31%, turnover=27823646. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T12:30:00+00:00, last15m_closed_end=2026-10-27T12:30+00:00, prior8high=8.826000, depth_time=2026-10-27T12:30:23+00:00, book20_bid_proxy_usdt=784125, book20_ask_proxy_usdt=1438231, funding_indicative=0.000058, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.22%, turnover=21002652. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T12:30:00+00:00, last15m_closed_end=2026-10-27T12:30+00:00, prior8high=0.992500, depth_time=2026-10-27T12:30:16+00:00, book20_bid_proxy_usdt=389764, book20_ask_proxy_usdt=342821, funding_indicative=-0.000132, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=11067778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T12:30:01+00:00, last15m_closed_end=2026-10-27T12:30+00:00, prior8high=0.900900, depth_time=2026-10-27T12:30:21+00:00, book20_bid_proxy_usdt=844156, book20_ask_proxy_usdt=1193374, funding_indicative=0.000057, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=6491163. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T12:30:00+00:00, last15m_closed_end=2026-10-27T12:30+00:00, prior8high=0.076310, depth_time=2026-10-27T12:30:29+00:00, book20_bid_proxy_usdt=879944, book20_ask_proxy_usdt=974489, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=10885339. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T12:30:01+00:00, last15m_closed_end=2026-10-27T12:30+00:00, prior8high=2.597000, depth_time=2026-10-27T12:30:37+00:00, book20_bid_proxy_usdt=935472, book20_ask_proxy_usdt=756885, funding_indicative=0.000088, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=5137258. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T12:30:00+00:00, last15m_closed_end=2026-10-27T12:30+00:00, prior8high=0.025490, depth_time=2026-10-27T12:30:03+00:00, book20_bid_proxy_usdt=101125, book20_ask_proxy_usdt=98655, funding_indicative=-0.000317, next_funding_utc=2026-10-27T13:00:00+00:00, funding_cycle_h=1, 24h_change=-9.42%, turnover=7279777. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T12:30:00+00:00, last15m_closed_end=2026-10-27T12:30+00:00, prior8high=11.404000, depth_time=2026-10-27T12:30:42+00:00, book20_bid_proxy_usdt=490251, book20_ask_proxy_usdt=427004, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=132507391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-27T12:30:00+00:00, last15m_closed_end=2026-10-27T12:30+00:00, prior8high=0.000004, depth_time=2026-10-27T12:30:34+00:00, book20_bid_proxy_usdt=57116, book20_ask_proxy_usdt=36794, funding_indicative=0.000079, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=60147000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T12:30:00+00:00, last15m_closed_end=2026-10-27T12:30+00:00, prior8high=0.004221, depth_time=2026-10-27T12:30:19+00:00, book20_bid_proxy_usdt=1369848, book20_ask_proxy_usdt=2002650, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.79%, turnover=19517623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T12:30:00+00:00, last15m_closed_end=2026-10-27T12:30+00:00, prior8high=206.180000, depth_time=2026-10-27T12:30:11+00:00, book20_bid_proxy_usdt=40462, book20_ask_proxy_usdt=40046, funding_indicative=-0.000192, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.61%, turnover=113057808. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T12:30:00+00:00, last15m_closed_end=2026-10-27T12:30+00:00, prior8high=100.560000, depth_time=2026-10-27T12:30:39+00:00, book20_bid_proxy_usdt=13818653, book20_ask_proxy_usdt=15034721, funding_indicative=0.000086, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=684000830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T12:30:00+00:00, last15m_closed_end=2026-10-27T12:30+00:00, prior8high=0.529500, depth_time=2026-10-27T12:30:32+00:00, book20_bid_proxy_usdt=348708, book20_ask_proxy_usdt=278006, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=17338757. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T12:30:00+00:00, last15m_closed_end=2026-10-27T12:30+00:00, prior8high=0.435500, depth_time=2026-10-27T12:30:26+00:00, book20_bid_proxy_usdt=2099456, book20_ask_proxy_usdt=2927626, funding_indicative=-0.000066, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=67326040. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
