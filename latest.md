# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T21:30:37Z**
- feed_generated_utc: 2026-10-17T21:30:39+00:00
- source_sha256: `05837469630bbf5a4b08fd236533729f7bec8ceb5ef4d6e938fe274e278c6366`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T21:30+00:00, close=81089.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T21:00+00:00, close=81610.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DNA_USDT|0.257300|-5.43|UNKNOWN|-5.14|6478554|3.89|
|QNT_USDT|193.010000|-3.69|-21.26|-3.40|62331715|1.04|
|STRK_USDT|0.063710|-3.68|-31.80|-3.39|15722331|1.57|
|EIGEN_USDT|0.248000|-3.23|5.26|-2.94|10106444|4.04|
|PUMPFUN_USDT|0.004314|-2.22|-24.64|-1.93|39269060|2.32|
|FILECOIN_USDT|1.064600|-2.09|-5.60|-1.80|22573784|0.94|
|ARB_USDT|0.180250|-1.99|-3.43|-1.70|29116154|0.55|
|ZRO_USDT|1.853500|-1.68|-8.26|-1.39|8681013|2.16|
|TIA_USDT|0.647200|-1.64|26.15|-1.35|74960282|1.55|
|ZEC_USDT|1123.170000|-1.59|-8.81|-1.30|1113831819|0.18|
|PEPE_USDT|0.000004|-1.41|-4.96|-1.12|50796322|0.52|
|AVAX_USDT|9.690000|-1.31|-7.93|-1.02|75812639|1.03|
|SUI_USDT|0.968900|-1.31|-13.79|-1.02|69783322|1.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180250|0.182530|0.180350|10.19|Y|Y/Y|Y/Y|Y|Y|
|AVAX_USDT|9.690000|9.852000|9.712000|2.15|Y|Y/Y|Y/Y|Y|Y|
|DNA_USDT|0.257300|0.253100|0.257600|2.55|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.248000|0.252500|0.248700|2.38|Y|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.064600|1.081300|1.067800|3.15|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000004|0.000004|0.000004|3.47|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.004314|0.004430|0.004313|5.38|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|193.010000|198.420000|193.330000|3.33|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.063710|0.064670|0.063650|1.72|Y|Y/Y|Y/Y|Y|Y|
|SUI_USDT|0.968900|0.987100|0.970000|2.81|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.647200|0.663200|0.646900|3.29|Y|Y/Y|N/N|Y|N|
|ZEC_USDT|1123.170000|1146.680000|1123.190000|1.95|Y|N/Y|Y/Y|Y|N|
|ZRO_USDT|1.853500|1.885600|1.853500|5.04|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T21:30:02+00:00, last15m_closed_end=2026-10-17T21:30+00:00, prior8high=0.184600, depth_time=2026-10-17T21:30:22+00:00, book20_bid_proxy_usdt=37747, book20_ask_proxy_usdt=79130, funding_indicative=0.000042, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=29116154. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T21:30:02+00:00, last15m_closed_end=2026-10-17T21:30+00:00, prior8high=9.906000, depth_time=2026-10-17T21:30:34+00:00, book20_bid_proxy_usdt=352505, book20_ask_proxy_usdt=675314, funding_indicative=0.000011, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=75812639. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T21:30:02+00:00, last15m_closed_end=2026-10-17T21:30+00:00, prior8high=0.261400, depth_time=2026-10-17T21:30:06+00:00, book20_bid_proxy_usdt=84100, book20_ask_proxy_usdt=64898, funding_indicative=-0.001174, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.43%, turnover=6478554. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T21:30:02+00:00, last15m_closed_end=2026-10-17T21:30+00:00, prior8high=0.256500, depth_time=2026-10-17T21:30:14+00:00, book20_bid_proxy_usdt=305234, book20_ask_proxy_usdt=310315, funding_indicative=0.000013, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=10106444. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T21:30:02+00:00, last15m_closed_end=2026-10-17T21:30+00:00, prior8high=1.098300, depth_time=2026-10-17T21:30:19+00:00, book20_bid_proxy_usdt=215557, book20_ask_proxy_usdt=551401, funding_indicative=-0.000112, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=22573784. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-17T21:30:02+00:00, last15m_closed_end=2026-10-17T21:30+00:00, prior8high=0.000004, depth_time=2026-10-17T21:30:32+00:00, book20_bid_proxy_usdt=39208, book20_ask_proxy_usdt=34407, funding_indicative=-0.000310, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=50796322. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-17T21:30:02+00:00, last15m_closed_end=2026-10-17T21:30+00:00, prior8high=0.004487, depth_time=2026-10-17T21:30:17+00:00, book20_bid_proxy_usdt=956391, book20_ask_proxy_usdt=1269888, funding_indicative=0.000017, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=39269060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T21:30:02+00:00, last15m_closed_end=2026-10-17T21:30+00:00, prior8high=200.420000, depth_time=2026-10-17T21:30:10+00:00, book20_bid_proxy_usdt=37409, book20_ask_proxy_usdt=71728, funding_indicative=-0.000024, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=62331715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T21:30:02+00:00, last15m_closed_end=2026-10-17T21:30+00:00, prior8high=0.066320, depth_time=2026-10-17T21:30:12+00:00, book20_bid_proxy_usdt=199699, book20_ask_proxy_usdt=296436, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.68%, turnover=15722331. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T21:30:02+00:00, last15m_closed_end=2026-10-17T21:30+00:00, prior8high=0.996100, depth_time=2026-10-17T21:30:36+00:00, book20_bid_proxy_usdt=259733, book20_ask_proxy_usdt=789843, funding_indicative=0.000012, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=69783322. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-17T21:30:02+00:00, last15m_closed_end=2026-10-17T21:30+00:00, prior8high=0.677200, depth_time=2026-10-17T21:30:27+00:00, book20_bid_proxy_usdt=150448, book20_ask_proxy_usdt=153488, funding_indicative=-0.000055, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.64%, turnover=74960282. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T21:30:02+00:00, last15m_closed_end=2026-10-17T21:30+00:00, prior8high=1163.390000, depth_time=2026-10-17T21:30:29+00:00, book20_bid_proxy_usdt=282700, book20_ask_proxy_usdt=1131504, funding_indicative=0.000037, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=1113831819. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T21:30:02+00:00, last15m_closed_end=2026-10-17T21:30+00:00, prior8high=1.919600, depth_time=2026-10-17T21:30:24+00:00, book20_bid_proxy_usdt=18726, book20_ask_proxy_usdt=63524, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=8681013. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
