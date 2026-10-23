# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T14:45:28Z**
- feed_generated_utc: 2026-10-23T14:45:30+00:00
- source_sha256: `f2bc072e858edb416f647cffb7de6ddca43928cc8a2343611e3f2705c6cdbe93`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T14:45+00:00, close=81803.5, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T14:00+00:00, close=81969.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGMA_USDT|0.403800|-19.56|70.77|-19.74|5461963|1.24|
|LIT_USDT|3.376700|-6.57|9.22|-6.75|8809535|0.30|
|QNT_USDT|182.790000|-4.15|-12.08|-4.33|60070760|0.55|
|TIA_USDT|0.544900|-4.13|-9.56|-4.31|25204970|1.83|
|STRK_USDT|0.052570|-3.29|-45.44|-3.47|11927079|1.90|
|SILVER_USDT|54.040000|-2.20|-5.42|-2.38|351067500|1.85|
|PUMPFUN_USDT|0.004600|-1.68|1.63|-1.86|38719783|2.17|
|XAU_USDT|4009.700000|-1.23|-3.52|-1.41|652553299|0.03|
|XAUT_USDT|4005.000000|-1.21|-3.37|-1.39|242591438|1.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|LIT_USDT|3.376700|3.279300|3.376700|4.11|N|Y/Y|Y/Y|Y|N|
|MAGMA_USDT|0.403800|0.406660|0.403800|1.45|Y|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004600|0.004485|0.004602|2.34|N|N/Y|Y/Y|Y|N|
|QNT_USDT|182.790000|177.480000|182.870000|0.85|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.040000|53.130000|54.020000|2.44|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052570|0.051770|0.052570|0.34|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.544900|0.535200|0.544900|0.99|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4005.000000|3983.400000|4004.780000|8.26|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4009.700000|3986.160000|4009.450000|8.33|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- LIT_USDT: quote_utc=2026-10-23T14:45:02+00:00, last15m_closed_end=2026-10-23T14:45+00:00, prior8high=3.403600, depth_time=2026-10-23T14:45:11+00:00, book20_bid_proxy_usdt=23430, book20_ask_proxy_usdt=16063, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.57%, turnover=8809535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGMA_USDT: quote_utc=2026-10-23T14:45:01+00:00, last15m_closed_end=2026-10-23T14:45+00:00, prior8high=0.461700, depth_time=2026-10-23T14:45:08+00:00, book20_bid_proxy_usdt=6848, book20_ask_proxy_usdt=1730, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-19.56%, turnover=5461963. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T14:45:02+00:00, last15m_closed_end=2026-10-23T14:45+00:00, prior8high=0.004677, depth_time=2026-10-23T14:45:23+00:00, book20_bid_proxy_usdt=1494928, book20_ask_proxy_usdt=982118, funding_indicative=0.000022, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=38719783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T14:45:02+00:00, last15m_closed_end=2026-10-23T14:45+00:00, prior8high=183.630000, depth_time=2026-10-23T14:45:13+00:00, book20_bid_proxy_usdt=61287, book20_ask_proxy_usdt=82916, funding_indicative=-0.000177, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.15%, turnover=60070760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T14:45:02+00:00, last15m_closed_end=2026-10-23T14:45+00:00, prior8high=54.240000, depth_time=2026-10-23T14:45:20+00:00, book20_bid_proxy_usdt=32745742, book20_ask_proxy_usdt=31000823, funding_indicative=0.000066, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.20%, turnover=351067500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T14:45:02+00:00, last15m_closed_end=2026-10-23T14:45+00:00, prior8high=0.053770, depth_time=2026-10-23T14:45:18+00:00, book20_bid_proxy_usdt=719946, book20_ask_proxy_usdt=618275, funding_indicative=-0.000016, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.29%, turnover=11927079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T14:45:02+00:00, last15m_closed_end=2026-10-23T14:45+00:00, prior8high=0.552300, depth_time=2026-10-23T14:45:15+00:00, book20_bid_proxy_usdt=248206, book20_ask_proxy_usdt=349975, funding_indicative=-0.000005, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.13%, turnover=25204970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T14:45:02+00:00, last15m_closed_end=2026-10-23T14:45+00:00, prior8high=4035.760000, depth_time=2026-10-23T14:45:27+00:00, book20_bid_proxy_usdt=103273, book20_ask_proxy_usdt=149223, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.21%, turnover=242591438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T14:45:01+00:00, last15m_closed_end=2026-10-23T14:45+00:00, prior8high=4042.750000, depth_time=2026-10-23T14:45:25+00:00, book20_bid_proxy_usdt=979381, book20_ask_proxy_usdt=1872516, funding_indicative=0.000179, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.23%, turnover=652553299. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
