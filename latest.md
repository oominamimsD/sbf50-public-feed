# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T23:30:38Z**
- feed_generated_utc: 2026-10-17T23:30:40+00:00
- source_sha256: `42b868582cd909b7aa4f8d72b38ea855737e5b0666b0d5006f145e1fd7b66753`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T23:30+00:00, close=81251.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T23:00+00:00, close=81327, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.169800|-8.31|71.34|-8.24|14713415|5.89|
|DNA_USDT|0.257000|-5.54|UNKNOWN|-5.47|6080873|3.89|
|QNT_USDT|194.250000|-3.07|-20.75|-3.00|65957957|2.06|
|EIGEN_USDT|0.249000|-2.84|5.68|-2.77|10663620|4.02|
|TIA_USDT|0.641100|-2.56|24.97|-2.49|75689032|1.56|
|FILECOIN_USDT|1.060000|-2.51|-6.01|-2.44|21516460|1.89|
|STRK_USDT|0.064610|-2.32|-30.84|-2.25|16223556|1.55|
|PUMPFUN_USDT|0.004315|-2.19|-24.62|-2.12|26745211|2.32|
|ARB_USDT|0.180580|-1.81|-3.26|-1.74|30991053|0.55|
|ZEC_USDT|1123.250000|-1.58|-8.81|-1.51|1164388120|0.09|
|ZRO_USDT|1.857500|-1.47|-8.07|-1.40|8504018|0.54|
|WLD_USDT|0.489100|-1.31|-12.50|-1.24|66655699|2.04|
|NEAR_USDT|4.830000|-1.12|-9.97|-1.05|124393173|2.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180580|0.176600|0.180580|0.29|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.257000|0.245300|0.257000|0.48|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.249000|0.241300|0.249000|0.74|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.060000|1.038400|1.060000|0.82|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.169800|0.163200|0.169700|0.24|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.830000|4.770000|4.834000|1.02|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004315|0.004262|0.004315|0.58|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.250000|190.470000|194.280000|0.68|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.064610|0.063090|0.064680|0.66|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.641100|0.634700|0.640700|0.48|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.489100|0.477800|0.489100|0.98|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1123.250000|1098.000000|1123.600000|0.74|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.857500|1.841200|1.857500|0.58|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T23:30:01+00:00, last15m_closed_end=2026-10-17T23:30+00:00, prior8high=0.183920, depth_time=2026-10-17T23:30:27+00:00, book20_bid_proxy_usdt=67070, book20_ask_proxy_usdt=51050, funding_indicative=0.000046, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=30991053. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T23:30:01+00:00, last15m_closed_end=2026-10-17T23:30+00:00, prior8high=0.263400, depth_time=2026-10-17T23:30:09+00:00, book20_bid_proxy_usdt=63558, book20_ask_proxy_usdt=58932, funding_indicative=-0.001526, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.54%, turnover=6080873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T23:30:01+00:00, last15m_closed_end=2026-10-17T23:30+00:00, prior8high=0.253300, depth_time=2026-10-17T23:30:14+00:00, book20_bid_proxy_usdt=570884, book20_ask_proxy_usdt=269391, funding_indicative=0.000002, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=10663620. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T23:30:01+00:00, last15m_closed_end=2026-10-17T23:30+00:00, prior8high=1.094900, depth_time=2026-10-17T23:30:19+00:00, book20_bid_proxy_usdt=581286, book20_ask_proxy_usdt=658970, funding_indicative=-0.000053, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=21516460. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-17T23:30:01+00:00, last15m_closed_end=2026-10-17T23:30+00:00, prior8high=0.190000, depth_time=2026-10-17T23:30:07+00:00, book20_bid_proxy_usdt=404816, book20_ask_proxy_usdt=159145, funding_indicative=-0.000207, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.31%, turnover=14713415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-17T23:30:01+00:00, last15m_closed_end=2026-10-17T23:30+00:00, prior8high=4.999000, depth_time=2026-10-17T23:30:37+00:00, book20_bid_proxy_usdt=2513638, book20_ask_proxy_usdt=921791, funding_indicative=-0.000017, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=124393173. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-17T23:30:01+00:00, last15m_closed_end=2026-10-17T23:30+00:00, prior8high=0.004436, depth_time=2026-10-17T23:30:24+00:00, book20_bid_proxy_usdt=1961850, book20_ask_proxy_usdt=1607883, funding_indicative=0.000019, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.19%, turnover=26745211. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T23:30:01+00:00, last15m_closed_end=2026-10-17T23:30+00:00, prior8high=198.740000, depth_time=2026-10-17T23:30:12+00:00, book20_bid_proxy_usdt=83323, book20_ask_proxy_usdt=95730, funding_indicative=-0.000058, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.07%, turnover=65957957. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T23:30:01+00:00, last15m_closed_end=2026-10-17T23:30+00:00, prior8high=0.065060, depth_time=2026-10-17T23:30:22+00:00, book20_bid_proxy_usdt=463334, book20_ask_proxy_usdt=313841, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.32%, turnover=16223556. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-17T23:30:01+00:00, last15m_closed_end=2026-10-17T23:30+00:00, prior8high=0.665400, depth_time=2026-10-17T23:30:17+00:00, book20_bid_proxy_usdt=122599, book20_ask_proxy_usdt=180036, funding_indicative=-0.000026, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=75689032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-17T23:30:01+00:00, last15m_closed_end=2026-10-17T23:30+00:00, prior8high=0.504600, depth_time=2026-10-17T23:30:35+00:00, book20_bid_proxy_usdt=1956144, book20_ask_proxy_usdt=1518243, funding_indicative=-0.000100, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=66655699. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T23:30:01+00:00, last15m_closed_end=2026-10-17T23:30+00:00, prior8high=1156.890000, depth_time=2026-10-17T23:30:30+00:00, book20_bid_proxy_usdt=598759, book20_ask_proxy_usdt=146959, funding_indicative=0.000040, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=1164388120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T23:30:01+00:00, last15m_closed_end=2026-10-17T23:30+00:00, prior8high=1.889300, depth_time=2026-10-17T23:30:32+00:00, book20_bid_proxy_usdt=28502, book20_ask_proxy_usdt=61617, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.47%, turnover=8504018. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
