# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T07:00:43Z**
- feed_generated_utc: 2026-10-18T07:00:45+00:00
- source_sha256: `2e55947f18a6656040eabe5c1f46a15525ae2642f5765d112c9ef1185296b202`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T07:00+00:00, close=81687.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T07:00+00:00, close=81687.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.063010|-7.50|-32.55|-7.95|14086624|1.59|
|PUMPFUN_USDT|0.004282|-5.24|-25.20|-5.69|23388174|2.34|
|FILECOIN_USDT|1.051800|-5.23|-6.73|-5.68|19424777|0.95|
|TIA_USDT|0.626400|-5.20|22.10|-5.65|59244924|1.60|
|QNT_USDT|193.740000|-4.37|-20.96|-4.82|68826745|1.03|
|EIGEN_USDT|0.247700|-3.35|5.13|-3.80|7679086|4.04|
|ZRO_USDT|1.843300|-2.95|-8.77|-3.40|7175990|0.54|
|DOT_USDT|1.103400|-2.86|-12.21|-3.31|16522025|0.91|
|XPL_USDT|0.078660|-2.61|-9.33|-3.06|5269731|1.27|
|OP_USDT|0.126730|-2.54|-8.53|-2.99|9454018|0.79|
|FARTCOIN_USDT|0.147570|-1.72|-9.96|-2.17|5941331|0.68|
|ONDO_USDT|0.438400|-1.46|-11.36|-1.91|22041555|2.28|
|WLD_USDT|0.491900|-1.36|-12.00|-1.81|58550903|2.03|
|ICNT_USDT|0.194400|-1.31|96.16|-1.76|13456343|5.15|
|ICP_USDT|2.918000|-1.31|-7.33|-1.76|6239264|3.42|
|AVAX_USDT|9.762000|-1.28|-7.24|-1.73|79290132|1.02|
|APT_USDT|0.790000|-0.94|-4.45|-1.39|10186209|1.27|
|ENA_USDT|0.187620|-0.81|-15.50|-1.26|28397578|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.103400|1.089000|1.103400|1.58|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.247700|0.244000|0.247600|1.98|N|Y/Y|N/Y|N|N|
|FARTCOIN_USDT|0.147570|0.146450|0.147570|0.56|N|Y/Y|Y/Y|N|N|
|FILECOIN_USDT|1.051800|1.040400|1.051800|0.09|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.194400|0.182900|0.194400|0.56|N|N/N|N/N|N|N|
|ICP_USDT|2.918000|2.885000|2.918000|0.81|N|Y/Y|Y/Y|N|N|
|ONDO_USDT|0.438400|0.435700|0.438400|1.03|N|Y/Y|Y/Y|N|N|
|OP_USDT|0.126730|0.124920|0.126730|1.64|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004282|0.004262|0.004282|1.20|N|Y/Y|Y/Y|N|N|
|QNT_USDT|193.740000|191.970000|193.740000|0.52|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.063010|0.062400|0.063010|0.47|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.626400|0.622800|0.626400|0.46|N|Y/Y|Y/N|N|N|
|WLD_USDT|0.491900|0.483600|0.491900|0.83|N|Y/Y|Y/Y|N|N|
|XPL_USDT|0.078660|0.077620|0.078660|1.59|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.843300|1.827700|1.843300|0.73|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T07:00:01+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=1.107500, depth_time=2026-10-18T07:00:25+00:00, book20_bid_proxy_usdt=365478, book20_ask_proxy_usdt=295576, funding_indicative=-0.000085, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=16522025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T07:00:01+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=0.249000, depth_time=2026-10-18T07:00:19+00:00, book20_bid_proxy_usdt=562964, book20_ask_proxy_usdt=324014, funding_indicative=-0.000040, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.35%, turnover=7679086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-18T07:00:01+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=0.149010, depth_time=2026-10-18T07:00:31+00:00, book20_bid_proxy_usdt=38364, book20_ask_proxy_usdt=38653, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=5941331. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T07:00:01+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=1.059500, depth_time=2026-10-18T07:00:11+00:00, book20_bid_proxy_usdt=682291, book20_ask_proxy_usdt=656977, funding_indicative=-0.000094, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.23%, turnover=19424777. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T07:00:00+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=0.200200, depth_time=2026-10-18T07:00:40+00:00, book20_bid_proxy_usdt=182468, book20_ask_proxy_usdt=127769, funding_indicative=-0.000037, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=13456343. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T07:00:01+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=2.929000, depth_time=2026-10-18T07:00:42+00:00, book20_bid_proxy_usdt=933510, book20_ask_proxy_usdt=1257286, funding_indicative=-0.000001, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=6239264. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-18T07:00:00+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=0.440800, depth_time=2026-10-18T07:00:34+00:00, book20_bid_proxy_usdt=1640681, book20_ask_proxy_usdt=1827776, funding_indicative=0.000025, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.46%, turnover=22041555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T07:00:01+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=0.127610, depth_time=2026-10-18T07:00:30+00:00, book20_bid_proxy_usdt=75472, book20_ask_proxy_usdt=112750, funding_indicative=-0.000163, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=9454018. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T07:00:01+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=0.004340, depth_time=2026-10-18T07:00:09+00:00, book20_bid_proxy_usdt=1476276, book20_ask_proxy_usdt=1730287, funding_indicative=0.000048, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.24%, turnover=23388174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T07:00:00+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=196.100000, depth_time=2026-10-18T07:00:18+00:00, book20_bid_proxy_usdt=87961, book20_ask_proxy_usdt=139869, funding_indicative=-0.000065, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.37%, turnover=68826745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T07:00:01+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=0.063440, depth_time=2026-10-18T07:00:07+00:00, book20_bid_proxy_usdt=480097, book20_ask_proxy_usdt=210043, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.50%, turnover=14086624. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T07:00:00+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=0.633300, depth_time=2026-10-18T07:00:15+00:00, book20_bid_proxy_usdt=172884, book20_ask_proxy_usdt=303167, funding_indicative=-0.000041, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.20%, turnover=59244924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T07:00:00+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=0.494400, depth_time=2026-10-18T07:00:36+00:00, book20_bid_proxy_usdt=2127102, book20_ask_proxy_usdt=1817999, funding_indicative=-0.000130, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=58550903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T07:00:01+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=0.078780, depth_time=2026-10-18T07:00:26+00:00, book20_bid_proxy_usdt=539581, book20_ask_proxy_usdt=636629, funding_indicative=0.000028, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=5269731. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T07:00:01+00:00, last15m_closed_end=2026-10-18T07:00+00:00, prior8high=1.875700, depth_time=2026-10-18T07:00:21+00:00, book20_bid_proxy_usdt=112813, book20_ask_proxy_usdt=44069, funding_indicative=0.000032, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.95%, turnover=7175990. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
