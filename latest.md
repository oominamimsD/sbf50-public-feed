# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T00:15:44Z**
- feed_generated_utc: 2026-11-03T00:15:47+00:00
- source_sha256: `445b64e36d640fe290c1d08dea0f1b083be9a6582b0cec9cb01a376229acc492`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T00:15+00:00, close=76799.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-03T00:00+00:00, close=76791.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-03T00:00+00:00, close=76791.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|0.971400|-11.43|-18.75|-10.56|9920768|1.03|
|ZEC_USDT|1143.020000|-8.85|-8.39|-7.98|1876821068|0.09|
|AKE_USDT|0.005018|-8.79|-83.69|-7.92|13961759|3.98|
|UAI_USDT|0.121900|-8.13|-51.00|-7.26|6548171|8.20|
|XPL_USDT|0.066640|-4.22|-10.29|-3.35|10982500|1.50|
|QNT_USDT|194.360000|-3.99|-7.57|-3.12|45987131|0.52|
|XLM_USDT|0.162290|-3.16|-4.30|-2.29|34380583|1.23|
|PUMPFUN_USDT|0.003974|-3.16|-8.17|-2.29|9181248|2.52|
|AAVE_USDT|126.650000|-2.99|-7.37|-2.12|23086653|0.79|
|NEAR_USDT|3.891000|-2.96|-14.91|-2.09|79355795|2.57|
|TIA_USDT|0.444800|-2.64|-16.96|-1.77|12456265|2.25|
|TRUMPOFFICIAL_USDT|1.594000|-2.56|-5.62|-1.69|11600581|6.28|
|ZRO_USDT|1.725100|-2.43|1.05|-1.56|6165807|0.58|
|OP_USDT|0.109910|-2.24|-1.60|-1.37|11818296|1.82|
|DASH_USDT|46.170000|-2.18|-11.58|-1.31|9979821|2.17|
|ENA_USDT|0.171260|-2.15|-18.59|-1.28|73381917|0.58|
|ARB_USDT|0.155910|-2.14|-8.28|-1.27|13311481|1.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.650000|126.520000|126.650000|1.42|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005018|0.004935|0.005018|1.74|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.971400|0.957600|0.971400|2.49|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.170000|46.000000|46.170000|1.13|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.891000|3.853000|3.891000|0.52|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.109910|0.109570|0.109910|0.57|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003974|0.003942|0.003974|1.21|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.360000|193.860000|194.360000|0.96|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.444800|0.443000|0.444800|0.61|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.594000|1.594000|1.594000|0.12|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.121900|0.113200|0.121900|1.88|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.162290|0.162540|0.162290|3.11|Y|Y/Y|Y/Y|Y|Y|
|XPL_USDT|0.066640|0.066060|0.066640|0.19|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1143.020000|1131.050000|1143.020000|0.69|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.725100|1.700600|1.725200|1.04|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=128.070000, depth_time=2026-11-03T00:15:28+00:00, book20_bid_proxy_usdt=311072, book20_ask_proxy_usdt=438396, funding_indicative=0.000100, next_funding_utc=2026-11-03T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.99%, turnover=23086653. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=0.005937, depth_time=2026-11-03T00:15:14+00:00, book20_bid_proxy_usdt=30004, book20_ask_proxy_usdt=58290, funding_indicative=-0.004484, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.79%, turnover=13961759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=1.061200, depth_time=2026-11-03T00:15:08+00:00, book20_bid_proxy_usdt=13935, book20_ask_proxy_usdt=22489, funding_indicative=0.000050, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.43%, turnover=9920768. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=46.490000, depth_time=2026-11-03T00:15:42+00:00, book20_bid_proxy_usdt=471124, book20_ask_proxy_usdt=573493, funding_indicative=0.000100, next_funding_utc=2026-11-03T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=9979821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=3.921000, depth_time=2026-11-03T00:15:31+00:00, book20_bid_proxy_usdt=3411610, book20_ask_proxy_usdt=4450633, funding_indicative=0.000100, next_funding_utc=2026-11-03T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=79355795. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=0.111120, depth_time=2026-11-03T00:15:40+00:00, book20_bid_proxy_usdt=70872, book20_ask_proxy_usdt=132588, funding_indicative=0.000100, next_funding_utc=2026-11-03T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=11818296. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=0.003996, depth_time=2026-11-03T00:15:25+00:00, book20_bid_proxy_usdt=1452029, book20_ask_proxy_usdt=2249188, funding_indicative=0.000050, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.16%, turnover=9181248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=197.000000, depth_time=2026-11-03T00:15:21+00:00, book20_bid_proxy_usdt=79660, book20_ask_proxy_usdt=68466, funding_indicative=0.000100, next_funding_utc=2026-11-03T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.99%, turnover=45987131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=0.451700, depth_time=2026-11-03T00:15:32+00:00, book20_bid_proxy_usdt=234020, book20_ask_proxy_usdt=284005, funding_indicative=0.000050, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.64%, turnover=12456265. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=1.612000, depth_time=2026-11-03T00:15:36+00:00, book20_bid_proxy_usdt=1699953, book20_ask_proxy_usdt=1638470, funding_indicative=0.000050, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=11600581. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=0.119300, depth_time=2026-11-03T00:15:16+00:00, book20_bid_proxy_usdt=144693, book20_ask_proxy_usdt=102164, funding_indicative=0.000037, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.13%, turnover=6548171. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=0.164090, depth_time=2026-11-03T00:15:23+00:00, book20_bid_proxy_usdt=134757, book20_ask_proxy_usdt=251609, funding_indicative=0.000100, next_funding_utc=2026-11-03T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=34380583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=0.067060, depth_time=2026-11-03T00:15:18+00:00, book20_bid_proxy_usdt=309057, book20_ask_proxy_usdt=476225, funding_indicative=0.000050, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.22%, turnover=10982500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=1162.310000, depth_time=2026-11-03T00:15:11+00:00, book20_bid_proxy_usdt=1299679, book20_ask_proxy_usdt=229181, funding_indicative=0.000100, next_funding_utc=2026-11-03T08:00:00+00:00, funding_cycle_h=8, 24h_change=-8.85%, turnover=1876821068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-03T00:15:00+00:00, last15m_closed_end=2026-11-03T00:15+00:00, prior8high=1.727200, depth_time=2026-11-03T00:15:38+00:00, book20_bid_proxy_usdt=27360, book20_ask_proxy_usdt=48835, funding_indicative=0.000050, next_funding_utc=2026-11-03T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.43%, turnover=6165807. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
