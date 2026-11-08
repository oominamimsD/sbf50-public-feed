# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T23:45:42Z**
- feed_generated_utc: 2026-11-08T23:45:44+00:00
- source_sha256: `994ab83d8c21a6a6c0428ef650e555d5ca6b4ada07248102bb294c47b41f5cef`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T23:45+00:00, close=75017.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T23:00+00:00, close=74432.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CLAUDIA_USDT|0.007070|-15.22|287.18|-13.89|11524110|2.83|
|ONE_USDT|0.001712|-12.58|46.98|-11.25|12615825|0.58|
|DASH_USDT|45.290000|-5.27|-6.81|-3.94|15150988|2.21|
|PUMPFUN_USDT|0.003560|-4.73|-15.59|-3.40|8430667|2.81|
|TRUMPOFFICIAL_USDT|1.136000|-4.45|-33.79|-3.12|6509233|8.80|
|ZEC_USDT|1214.230000|-4.44|-1.91|-3.11|1686412951|0.08|
|WLD_USDT|0.311800|-4.32|-21.20|-2.99|30401324|3.21|
|LIT_USDT|3.067300|-3.94|-5.04|-2.61|11171965|0.33|
|XRP_USDT|1.115300|-3.50|-10.76|-2.17|228670055|1.79|
|HYPE_USDT|74.763000|-3.44|-14.73|-2.11|35978122|0.13|
|ENA_USDT|0.149070|-3.18|-19.49|-1.85|34854878|0.67|
|SOL_USDT|86.830000|-3.17|-8.36|-1.84|433081837|1.15|
|DOT_USDT|0.863000|-3.13|-8.87|-1.80|7215822|1.16|
|UNI_USDT|6.803000|-2.85|-6.24|-1.52|31171433|2.94|
|AAVE_USDT|126.270000|-2.65|-8.14|-1.32|10172835|0.79|
|AKE_USDT|0.005228|-2.40|-42.92|-1.07|15258867|3.82|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.270000|123.980000|126.270000|2.31|N|Y/Y|Y/Y|Y|N|
|CLAUDIA_USDT|0.007070|0.006266|0.007070|0.42|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.290000|44.290000|45.310000|1.84|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.863000|0.840600|0.863000|1.24|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.149070|0.144230|0.149080|0.80|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|74.763000|73.578000|74.763000|0.86|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.067300|3.007700|3.067300|2.44|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001712|0.001607|0.001712|0.93|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003560|0.003488|0.003560|1.24|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.830000|84.820000|86.860000|3.54|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.136000|1.104000|1.136000|0.99|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.803000|6.616000|6.802000|1.07|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.311800|0.301700|0.311800|3.00|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.115300|1.088800|1.116000|0.84|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1214.230000|1178.000000|1215.210000|1.57|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T23:45:02+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=129.190000, depth_time=2026-11-08T23:45:37+00:00, book20_bid_proxy_usdt=1008385, book20_ask_proxy_usdt=377479, funding_indicative=0.000044, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.65%, turnover=10172835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLAUDIA_USDT: quote_utc=2026-11-08T23:45:01+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=0.007650, depth_time=2026-11-08T23:45:06+00:00, book20_bid_proxy_usdt=58, book20_ask_proxy_usdt=622, funding_indicative=0.000128, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-15.22%, turnover=11524110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-08T23:45:02+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=46.840000, depth_time=2026-11-08T23:45:12+00:00, book20_bid_proxy_usdt=721413, book20_ask_proxy_usdt=478976, funding_indicative=0.000047, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.27%, turnover=15150988. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-08T23:45:02+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=0.887900, depth_time=2026-11-08T23:45:36+00:00, book20_bid_proxy_usdt=432147, book20_ask_proxy_usdt=575123, funding_indicative=0.000024, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.13%, turnover=7215822. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T23:45:02+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=0.153150, depth_time=2026-11-08T23:45:30+00:00, book20_bid_proxy_usdt=143966, book20_ask_proxy_usdt=134055, funding_indicative=-0.000025, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.18%, turnover=34854878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-08T23:45:02+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=76.043000, depth_time=2026-11-08T23:45:27+00:00, book20_bid_proxy_usdt=91434, book20_ask_proxy_usdt=63353, funding_indicative=0.000023, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.44%, turnover=35978122. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-08T23:45:01+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=3.143100, depth_time=2026-11-08T23:45:22+00:00, book20_bid_proxy_usdt=25911, book20_ask_proxy_usdt=28402, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.94%, turnover=11171965. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T23:45:01+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=0.001757, depth_time=2026-11-08T23:45:09+00:00, book20_bid_proxy_usdt=16881, book20_ask_proxy_usdt=15947, funding_indicative=-0.000686, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.58%, turnover=12615825. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-08T23:45:02+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=0.003715, depth_time=2026-11-08T23:45:14+00:00, book20_bid_proxy_usdt=2163785, book20_ask_proxy_usdt=2881026, funding_indicative=-0.000025, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.73%, turnover=8430667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-08T23:45:02+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=89.140000, depth_time=2026-11-08T23:45:33+00:00, book20_bid_proxy_usdt=15094051, book20_ask_proxy_usdt=11640696, funding_indicative=-0.000031, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=433081837. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-08T23:45:02+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=1.169000, depth_time=2026-11-08T23:45:11+00:00, book20_bid_proxy_usdt=2095452, book20_ask_proxy_usdt=2677831, funding_indicative=-0.000055, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.45%, turnover=6509233. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-08T23:45:02+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=6.951000, depth_time=2026-11-08T23:45:38+00:00, book20_bid_proxy_usdt=2193484, book20_ask_proxy_usdt=2619320, funding_indicative=0.000019, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=31171433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T23:45:02+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=0.321300, depth_time=2026-11-08T23:45:20+00:00, book20_bid_proxy_usdt=5391174, book20_ask_proxy_usdt=4311594, funding_indicative=-0.000135, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.32%, turnover=30401324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-08T23:45:02+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=1.147700, depth_time=2026-11-08T23:45:25+00:00, book20_bid_proxy_usdt=2986703, book20_ask_proxy_usdt=1997491, funding_indicative=0.000087, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.50%, turnover=228670055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T23:45:02+00:00, last15m_closed_end=2026-11-08T23:45+00:00, prior8high=1239.650000, depth_time=2026-11-08T23:45:19+00:00, book20_bid_proxy_usdt=930706, book20_ask_proxy_usdt=194523, funding_indicative=0.000007, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.44%, turnover=1686412951. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
