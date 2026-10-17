# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T22:30:42Z**
- feed_generated_utc: 2026-10-17T22:30:44+00:00
- source_sha256: `ef6fe7acfcd561ffde9ea8a62bfcf7e5e2b09f702053e743484723c4b3028feb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T22:30+00:00, close=81275.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T22:00+00:00, close=81099.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.171400|-7.45|72.95|-7.41|14559616|5.84|
|FILECOIN_USDT|1.054400|-3.03|-6.50|-2.99|21782397|0.95|
|STRK_USDT|0.064210|-2.93|-31.27|-2.89|16031817|3.12|
|EIGEN_USDT|0.249200|-2.77|5.77|-2.73|10533600|4.01|
|QNT_USDT|195.540000|-2.43|-20.23|-2.39|65508820|0.51|
|TIA_USDT|0.643800|-2.15|25.49|-2.11|75707665|1.55|
|ARB_USDT|0.180080|-2.08|-3.53|-2.04|30826979|0.56|
|ZRO_USDT|1.847200|-2.02|-8.58|-1.98|8326075|1.08|
|WLD_USDT|0.486200|-1.89|-13.02|-1.85|68097848|2.06|
|ZEC_USDT|1120.000000|-1.86|-9.07|-1.82|1158158054|0.09|
|PUMPFUN_USDT|0.004340|-1.63|-24.19|-1.59|29681177|2.31|
|PEPE_USDT|0.000004|-1.42|-4.97|-1.38|58573038|0.26|
|SUI_USDT|0.970800|-1.12|-13.62|-1.08|77012748|1.03|
|AVAX_USDT|9.711000|-1.09|-7.73|-1.05|78721855|1.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180080|0.176600|0.180080|1.27|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|9.711000|9.551000|9.711000|1.31|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.249200|0.241300|0.249200|0.97|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.054400|1.038400|1.054400|0.21|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.171400|0.166700|0.171400|0.70|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|5.96|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004340|0.004262|0.004340|3.80|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.540000|190.470000|195.630000|1.50|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.064210|0.063090|0.064220|0.75|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.970800|0.952000|0.971000|0.69|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.643800|0.634700|0.643800|0.58|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.486200|0.477800|0.486200|1.11|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1120.000000|1098.000000|1120.190000|0.58|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.847200|1.845300|1.847200|1.49|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T22:30:00+00:00, last15m_closed_end=2026-10-17T22:30+00:00, prior8high=0.184600, depth_time=2026-10-17T22:30:23+00:00, book20_bid_proxy_usdt=51377, book20_ask_proxy_usdt=49825, funding_indicative=0.000043, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=30826979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T22:30:00+00:00, last15m_closed_end=2026-10-17T22:30+00:00, prior8high=9.906000, depth_time=2026-10-17T22:30:40+00:00, book20_bid_proxy_usdt=841059, book20_ask_proxy_usdt=598947, funding_indicative=-0.000005, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=78721855. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T22:30:00+00:00, last15m_closed_end=2026-10-17T22:30+00:00, prior8high=0.256300, depth_time=2026-10-17T22:30:15+00:00, book20_bid_proxy_usdt=394545, book20_ask_proxy_usdt=454329, funding_indicative=0.000019, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=10533600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T22:30:00+00:00, last15m_closed_end=2026-10-17T22:30+00:00, prior8high=1.098300, depth_time=2026-10-17T22:30:09+00:00, book20_bid_proxy_usdt=347450, book20_ask_proxy_usdt=673551, funding_indicative=-0.000085, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.03%, turnover=21782397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-17T22:30:00+00:00, last15m_closed_end=2026-10-17T22:30+00:00, prior8high=0.196500, depth_time=2026-10-17T22:30:07+00:00, book20_bid_proxy_usdt=116305, book20_ask_proxy_usdt=98046, funding_indicative=-0.000344, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.45%, turnover=14559616. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-17T22:30:00+00:00, last15m_closed_end=2026-10-17T22:30+00:00, prior8high=0.000004, depth_time=2026-10-17T22:30:35+00:00, book20_bid_proxy_usdt=26763, book20_ask_proxy_usdt=85998, funding_indicative=-0.000312, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=58573038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-17T22:30:00+00:00, last15m_closed_end=2026-10-17T22:30+00:00, prior8high=0.004487, depth_time=2026-10-17T22:30:33+00:00, book20_bid_proxy_usdt=1694431, book20_ask_proxy_usdt=1380003, funding_indicative=0.000007, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=29681177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T22:30:00+00:00, last15m_closed_end=2026-10-17T22:30+00:00, prior8high=200.290000, depth_time=2026-10-17T22:30:15+00:00, book20_bid_proxy_usdt=59734, book20_ask_proxy_usdt=56935, funding_indicative=-0.000071, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=65508820. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T22:30:00+00:00, last15m_closed_end=2026-10-17T22:30+00:00, prior8high=0.065560, depth_time=2026-10-17T22:30:13+00:00, book20_bid_proxy_usdt=382262, book20_ask_proxy_usdt=295928, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=16031817. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T22:30:00+00:00, last15m_closed_end=2026-10-17T22:30+00:00, prior8high=0.996100, depth_time=2026-10-17T22:30:38+00:00, book20_bid_proxy_usdt=1048256, book20_ask_proxy_usdt=647185, funding_indicative=-0.000018, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=77012748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-17T22:30:00+00:00, last15m_closed_end=2026-10-17T22:30+00:00, prior8high=0.673300, depth_time=2026-10-17T22:30:20+00:00, book20_bid_proxy_usdt=198194, book20_ask_proxy_usdt=171061, funding_indicative=-0.000059, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.15%, turnover=75707665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-17T22:30:00+00:00, last15m_closed_end=2026-10-17T22:30+00:00, prior8high=0.506800, depth_time=2026-10-17T22:30:27+00:00, book20_bid_proxy_usdt=1433526, book20_ask_proxy_usdt=1462996, funding_indicative=-0.000119, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=68097848. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T22:30:00+00:00, last15m_closed_end=2026-10-17T22:30+00:00, prior8high=1163.390000, depth_time=2026-10-17T22:30:30+00:00, book20_bid_proxy_usdt=56827, book20_ask_proxy_usdt=405419, funding_indicative=0.000029, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.86%, turnover=1158158054. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T22:30:00+00:00, last15m_closed_end=2026-10-17T22:30+00:00, prior8high=1.919600, depth_time=2026-10-17T22:30:24+00:00, book20_bid_proxy_usdt=34908, book20_ask_proxy_usdt=39784, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.02%, turnover=8326075. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
