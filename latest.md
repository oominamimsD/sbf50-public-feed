# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T21:45:31Z**
- feed_generated_utc: 2026-11-04T21:45:34+00:00
- source_sha256: `10ebabc50c41c581145606d9985bc83e1c97620e6fdd20d55e715e4d80e3b165`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T21:45+00:00, close=80168.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T21:00+00:00, close=80098.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.265000|-11.16|-25.98|-11.03|26019093|7.90|
|IDOL_USDT|0.021193|-9.69|144.80|-9.56|6401802|2.83|
|AKE_USDT|0.002543|-9.50|-87.34|-9.37|16996963|3.93|
|BTW_USDT|1.028900|-6.37|-40.79|-6.24|6430995|0.97|
|PUMPFUN_USDT|0.004230|-4.94|0.54|-4.81|19322242|2.37|
|PEPE_USDT|0.000005|-4.45|1.90|-4.32|146335845|0.20|
|WLD_USDT|0.375000|-4.36|-13.35|-4.23|77635456|2.67|
|OP_USDT|0.109780|-3.87|-1.17|-3.74|11774801|0.91|
|HYPE_USDT|83.316000|-3.01|4.33|-2.88|92465497|0.12|
|ZRO_USDT|1.814300|-2.70|5.97|-2.57|11213006|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002543|0.002455|0.002543|0.38|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.028900|1.030900|1.028900|0.96|N|Y/Y|Y/N|N|N|
|HYPE_USDT|83.316000|83.008000|83.316000|1.17|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.021193|0.021000|0.021193|0.72|N|Y/N|N/N|N|N|
|OP_USDT|0.109780|0.108620|0.109780|0.38|N|Y/Y|Y/N|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.12|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004230|0.004163|0.004229|0.10|N|Y/Y|Y/N|N|N|
|TRUMPOFFICIAL_USDT|1.265000|1.266000|1.265000|1.38|Y|Y/Y|Y/Y|N|Y|
|WLD_USDT|0.375000|0.370800|0.375000|0.46|N|Y/Y|Y/N|N|N|
|ZRO_USDT|1.814300|1.757900|1.814200|0.52|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T21:45:02+00:00, last15m_closed_end=2026-11-04T21:45+00:00, prior8high=0.002701, depth_time=2026-11-04T21:45:13+00:00, book20_bid_proxy_usdt=74343, book20_ask_proxy_usdt=65865, funding_indicative=-0.000766, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.50%, turnover=16996963. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-04T21:45:02+00:00, last15m_closed_end=2026-11-04T21:45+00:00, prior8high=1.077000, depth_time=2026-11-04T21:45:16+00:00, book20_bid_proxy_usdt=33263, book20_ask_proxy_usdt=31585, funding_indicative=0.000014, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.37%, turnover=6430995. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T21:45:02+00:00, last15m_closed_end=2026-11-04T21:45+00:00, prior8high=84.628000, depth_time=2026-11-04T21:45:25+00:00, book20_bid_proxy_usdt=110469, book20_ask_proxy_usdt=236599, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=92465497. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-04T21:45:02+00:00, last15m_closed_end=2026-11-04T21:45+00:00, prior8high=0.022552, depth_time=2026-11-04T21:45:08+00:00, book20_bid_proxy_usdt=4717, book20_ask_proxy_usdt=9716, funding_indicative=0.000095, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.69%, turnover=6401802. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-04T21:45:02+00:00, last15m_closed_end=2026-11-04T21:45+00:00, prior8high=0.110610, depth_time=2026-11-04T21:45:25+00:00, book20_bid_proxy_usdt=144434, book20_ask_proxy_usdt=130617, funding_indicative=0.000019, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.87%, turnover=11774801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-04T21:45:02+00:00, last15m_closed_end=2026-11-04T21:45+00:00, prior8high=0.000005, depth_time=2026-11-04T21:45:20+00:00, book20_bid_proxy_usdt=61118, book20_ask_proxy_usdt=54137, funding_indicative=0.000100, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.45%, turnover=146335845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T21:45:02+00:00, last15m_closed_end=2026-11-04T21:45+00:00, prior8high=0.004240, depth_time=2026-11-04T21:45:18+00:00, book20_bid_proxy_usdt=2062818, book20_ask_proxy_usdt=2488884, funding_indicative=0.000046, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.94%, turnover=19322242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T21:45:02+00:00, last15m_closed_end=2026-11-04T21:45+00:00, prior8high=1.308000, depth_time=2026-11-04T21:45:07+00:00, book20_bid_proxy_usdt=1014704, book20_ask_proxy_usdt=996298, funding_indicative=-0.000158, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.16%, turnover=26019093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-04T21:45:02+00:00, last15m_closed_end=2026-11-04T21:45+00:00, prior8high=0.378500, depth_time=2026-11-04T21:45:23+00:00, book20_bid_proxy_usdt=3282799, book20_ask_proxy_usdt=2349632, funding_indicative=-0.000549, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.36%, turnover=77635456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T21:45:02+00:00, last15m_closed_end=2026-11-04T21:45+00:00, prior8high=1.813900, depth_time=2026-11-04T21:45:31+00:00, book20_bid_proxy_usdt=42715, book20_ask_proxy_usdt=35650, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.70%, turnover=11213006. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
