# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T04:45:33Z**
- feed_generated_utc: 2026-10-23T04:45:34+00:00
- source_sha256: `08d26f59a165fdcf434b2dcc9effc07efd567d9dbe3b5c42776d72f21b610041`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T04:45+00:00, close=81651.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004260|-7.55|114.60|-7.55|9101146|7.04|
|LIT_USDT|3.445700|-4.66|11.46|-4.66|10831456|0.29|
|SILVER_USDT|53.730000|-2.76|-5.96|-2.76|358029988|1.86|
|STRK_USDT|0.052950|-2.59|-45.04|-2.59|11918890|1.89|
|PUMPFUN_USDT|0.004603|-1.62|1.70|-1.62|38572747|2.17|
|TIA_USDT|0.559500|-1.56|-7.13|-1.56|23264125|3.58|
|ZEC_USDT|1215.460000|-1.52|3.02|-1.52|1903908142|0.08|
|XAU_USDT|4012.630000|-1.15|-3.45|-1.15|739947821|0.03|
|XAUT_USDT|4009.620000|-1.09|-3.26|-1.09|284188048|0.07|
|XPT_USDT|1569.410000|-1.09|-3.16|-1.09|5103232|2.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004260|0.004168|0.004260|1.42|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.445700|3.452400|3.441500|2.06|Y|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004603|0.004615|0.004602|0.40|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.730000|53.760000|53.730000|1.24|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052950|0.052700|0.052950|1.30|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.559500|0.558400|0.559500|0.96|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4009.620000|4012.190000|4009.590000|1.09|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4012.630000|4014.690000|4012.630000|0.40|N|Y/Y|Y/Y|Y|N|
|XPT_USDT|1569.410000|1570.540000|1569.100000|14.80|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1215.460000|1216.150000|1215.470000|0.71|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T04:45:01+00:00, last15m_closed_end=2026-10-23T04:45+00:00, prior8high=0.004422, depth_time=2026-10-23T04:45:07+00:00, book20_bid_proxy_usdt=54315, book20_ask_proxy_usdt=33413, funding_indicative=0.000052, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.55%, turnover=9101146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T04:45:01+00:00, last15m_closed_end=2026-10-23T04:45+00:00, prior8high=3.544400, depth_time=2026-10-23T04:45:10+00:00, book20_bid_proxy_usdt=27101, book20_ask_proxy_usdt=29281, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.66%, turnover=10831456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T04:45:01+00:00, last15m_closed_end=2026-10-23T04:45+00:00, prior8high=0.004691, depth_time=2026-10-23T04:45:15+00:00, book20_bid_proxy_usdt=2455595, book20_ask_proxy_usdt=2626336, funding_indicative=0.000023, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=38572747. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T04:45:01+00:00, last15m_closed_end=2026-10-23T04:45+00:00, prior8high=54.410000, depth_time=2026-10-23T04:45:13+00:00, book20_bid_proxy_usdt=38253112, book20_ask_proxy_usdt=32673082, funding_indicative=0.000131, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=358029988. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T04:45:01+00:00, last15m_closed_end=2026-10-23T04:45+00:00, prior8high=0.053500, depth_time=2026-10-23T04:45:16+00:00, book20_bid_proxy_usdt=698930, book20_ask_proxy_usdt=654808, funding_indicative=0.000008, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.59%, turnover=11918890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T04:45:01+00:00, last15m_closed_end=2026-10-23T04:45+00:00, prior8high=0.566300, depth_time=2026-10-23T04:45:21+00:00, book20_bid_proxy_usdt=379177, book20_ask_proxy_usdt=275953, funding_indicative=0.000012, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.56%, turnover=23264125. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T04:45:01+00:00, last15m_closed_end=2026-10-23T04:45+00:00, prior8high=4030.690000, depth_time=2026-10-23T04:45:29+00:00, book20_bid_proxy_usdt=164757, book20_ask_proxy_usdt=100883, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.09%, turnover=284188048. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T04:45:01+00:00, last15m_closed_end=2026-10-23T04:45+00:00, prior8high=4032.600000, depth_time=2026-10-23T04:45:26+00:00, book20_bid_proxy_usdt=1899839, book20_ask_proxy_usdt=379727, funding_indicative=0.000086, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.15%, turnover=739947821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPT_USDT: quote_utc=2026-10-23T04:45:02+00:00, last15m_closed_end=2026-10-23T04:45+00:00, prior8high=1580.400000, depth_time=2026-10-23T04:45:32+00:00, book20_bid_proxy_usdt=385381, book20_ask_proxy_usdt=166693, funding_indicative=0.000000, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.09%, turnover=5103232. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-23T04:45:01+00:00, last15m_closed_end=2026-10-23T04:45+00:00, prior8high=1238.200000, depth_time=2026-10-23T04:45:23+00:00, book20_bid_proxy_usdt=183089, book20_ask_proxy_usdt=974669, funding_indicative=-0.000004, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=1903908142. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
