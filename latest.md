# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T19:00:37Z**
- feed_generated_utc: 2026-10-17T19:00:39+00:00
- source_sha256: `ace10f2d7bb248dd27392ae6dd5d613bd29b4839d1610539cfc65aa7a44f644f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T19:00+00:00, close=81466.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T19:00+00:00, close=81466.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T16:00+00:00, close=81315.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DNA_USDT|0.251000|-8.99|UNKNOWN|-9.17|7116706|3.98|
|STRK_USDT|0.065350|-4.06|-30.05|-4.24|14701771|1.53|
|FILECOIN_USDT|1.076300|-3.02|-4.56|-3.20|23532222|0.93|
|EIGEN_USDT|0.252900|-2.61|7.34|-2.79|9426806|3.95|
|ARB_USDT|0.182580|-1.82|-2.19|-2.00|25683441|0.55|
|PUMPFUN_USDT|0.004449|-1.54|-22.28|-1.72|40642843|2.25|
|DOT_USDT|1.119000|-1.49|-10.97|-1.67|13715305|2.68|
|AAVE_USDT|152.480000|-1.38|-11.03|-1.56|17646149|1.31|
|NEAR_USDT|4.947000|-1.37|-7.79|-1.55|110532462|2.02|
|ENA_USDT|0.190800|-1.20|-14.06|-1.38|29502229|0.52|
|PEPE_USDT|0.000004|-1.10|-3.45|-1.28|47111459|0.26|
|SUI_USDT|0.985800|-0.90|-12.28|-1.08|67500807|1.01|
|SEI_USDT|0.062580|-0.85|-9.90|-1.03|10493675|1.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|152.480000|150.100000|152.480000|0.72|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.182580|0.180230|0.182580|0.32|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.251000|0.255600|0.251000|0.97|N|Y/Y|?|Y|N|
|DOT_USDT|1.119000|1.102200|1.119000|1.16|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.252900|0.247500|0.252900|0.45|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.190800|0.185970|0.190800|0.60|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.076300|1.059300|1.076300|0.49|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.947000|4.826000|4.947000|0.43|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.71|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004449|0.004320|0.004449|0.24|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.062580|0.061120|0.062580|0.17|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.065350|0.065660|0.065350|3.29|Y|Y/Y|Y/Y|Y|Y|
|SUI_USDT|0.985800|0.969000|0.985800|0.63|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T19:00:01+00:00, last15m_closed_end=2026-10-17T19:00+00:00, prior8high=152.720000, depth_time=2026-10-17T19:00:23+00:00, book20_bid_proxy_usdt=435149, book20_ask_proxy_usdt=424435, funding_indicative=0.000100, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=17646149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T19:00:00+00:00, last15m_closed_end=2026-10-17T19:00+00:00, prior8high=0.182840, depth_time=2026-10-17T19:00:14+00:00, book20_bid_proxy_usdt=115363, book20_ask_proxy_usdt=91387, funding_indicative=-0.000009, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=25683441. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T19:00:00+00:00, last15m_closed_end=2026-10-17T19:00+00:00, prior8high=0.272400, depth_time=2026-10-17T19:00:07+00:00, book20_bid_proxy_usdt=156617, book20_ask_proxy_usdt=111629, funding_indicative=-0.001383, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.99%, turnover=7116706. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-17T19:00:01+00:00, last15m_closed_end=2026-10-17T19:00+00:00, prior8high=1.121000, depth_time=2026-10-17T19:00:22+00:00, book20_bid_proxy_usdt=401424, book20_ask_proxy_usdt=303092, funding_indicative=-0.000046, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=13715305. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T19:00:01+00:00, last15m_closed_end=2026-10-17T19:00+00:00, prior8high=0.254600, depth_time=2026-10-17T19:00:14+00:00, book20_bid_proxy_usdt=377326, book20_ask_proxy_usdt=576240, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=9426806. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-17T19:00:00+00:00, last15m_closed_end=2026-10-17T19:00+00:00, prior8high=0.191110, depth_time=2026-10-17T19:00:28+00:00, book20_bid_proxy_usdt=290410, book20_ask_proxy_usdt=212333, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.20%, turnover=29502229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T19:00:00+00:00, last15m_closed_end=2026-10-17T19:00+00:00, prior8high=1.083000, depth_time=2026-10-17T19:00:11+00:00, book20_bid_proxy_usdt=570051, book20_ask_proxy_usdt=548750, funding_indicative=-0.000111, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.02%, turnover=23532222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-17T19:00:00+00:00, last15m_closed_end=2026-10-17T19:00+00:00, prior8high=4.957000, depth_time=2026-10-17T19:00:24+00:00, book20_bid_proxy_usdt=1743592, book20_ask_proxy_usdt=3414349, funding_indicative=-0.000077, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.37%, turnover=110532462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-17T19:00:00+00:00, last15m_closed_end=2026-10-17T19:00+00:00, prior8high=0.000004, depth_time=2026-10-17T19:00:31+00:00, book20_bid_proxy_usdt=111596, book20_ask_proxy_usdt=203614, funding_indicative=-0.000395, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=47111459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-17T19:00:00+00:00, last15m_closed_end=2026-10-17T19:00+00:00, prior8high=0.004469, depth_time=2026-10-17T19:00:19+00:00, book20_bid_proxy_usdt=1714658, book20_ask_proxy_usdt=1300288, funding_indicative=-0.000022, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.54%, turnover=40642843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-17T19:00:01+00:00, last15m_closed_end=2026-10-17T19:00+00:00, prior8high=0.062650, depth_time=2026-10-17T19:00:36+00:00, book20_bid_proxy_usdt=220399, book20_ask_proxy_usdt=342921, funding_indicative=0.000083, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.85%, turnover=10493675. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T19:00:00+00:00, last15m_closed_end=2026-10-17T19:00+00:00, prior8high=0.068220, depth_time=2026-10-17T19:00:10+00:00, book20_bid_proxy_usdt=174762, book20_ask_proxy_usdt=246965, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.06%, turnover=14701771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T19:00:00+00:00, last15m_closed_end=2026-10-17T19:00+00:00, prior8high=0.987400, depth_time=2026-10-17T19:00:33+00:00, book20_bid_proxy_usdt=1285138, book20_ask_proxy_usdt=1174636, funding_indicative=0.000059, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.90%, turnover=67500807. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
