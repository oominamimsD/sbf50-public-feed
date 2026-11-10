# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T10:15:43Z**
- feed_generated_utc: 2026-11-10T10:15:44+00:00
- source_sha256: `2ca49036200b73a1bcc68d3eca846a1afeead593987777f816f01297e16a7c31`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 23; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T10:15+00:00, close=74373.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T10:00+00:00, close=74485, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002448|-50.01|-55.50|-48.52|14376364|4.08|
|JCT_USDT|0.005980|-40.97|38.52|-39.48|24302153|3.34|
|ON_USDT|0.132200|-11.63|-22.00|-10.14|5696050|7.52|
|ARB_USDT|0.165860|-9.87|4.09|-8.38|36967945|0.60|
|XMR_USDT|545.380000|-9.68|-9.89|-8.19|5530928|0.18|
|ZEC_USDT|1137.040000|-7.23|-9.33|-5.74|2287696341|0.09|
|AVAX_USDT|8.351000|-7.10|-1.76|-5.61|50309884|1.20|
|AAVE_USDT|124.410000|-6.70|-4.71|-5.21|11990058|0.80|
|QNT_USDT|187.000000|-6.51|-7.63|-5.02|32871954|1.60|
|DOT_USDT|0.849200|-4.68|-9.08|-3.19|7944390|1.18|
|PUMPFUN_USDT|0.003521|-4.37|-14.20|-2.88|7284118|2.84|
|DASH_USDT|45.660000|-4.11|-3.26|-2.62|10137470|2.19|
|SUI_USDT|0.836600|-3.53|-5.44|-2.04|34536557|1.20|
|ENA_USDT|0.152270|-3.17|-13.00|-1.68|22870712|0.66|
|WLD_USDT|0.315900|-3.06|-17.13|-1.57|26949688|3.17|
|FILECOIN_USDT|0.765100|-3.01|-11.78|-1.52|5121164|1.31|
|HYPE_USDT|74.052000|-2.96|-13.60|-1.47|45991024|0.14|
|SOL_USDT|85.290000|-2.95|-8.79|-1.46|627001788|1.17|
|XRP_USDT|1.081400|-2.91|-13.37|-1.42|270860719|0.93|
|LINK_USDT|10.472000|-2.90|-6.78|-1.41|105543226|0.95|
|INJ_USDT|7.945000|-2.83|13.35|-1.34|15545205|1.26|
|HBAR_USDT|0.066550|-2.80|-5.56|-1.31|9594280|1.50|
|ADA_USDT|0.177600|-2.63|-6.42|-1.14|20633051|5.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|124.410000|124.500000|124.410000|1.29|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002448|0.002406|0.002448|0.55|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165860|0.166250|0.165770|0.87|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|8.351000|8.365000|8.351000|3.54|Y|Y/Y|N/N|Y|N|
|DASH_USDT|45.660000|45.390000|45.660000|0.57|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.849200|0.846200|0.849200|1.47|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.152270|0.151780|0.152270|1.18|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005980|0.005450|0.005960|1.22|N|Y/Y|Y/N|Y|N|
|ON_USDT|0.132200|0.125100|0.132200|1.95|N|Y/Y|N/Y|Y|N|
|PUMPFUN_USDT|0.003521|0.003516|0.003521|0.50|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|187.000000|187.970000|186.930000|2.56|Y|Y/Y|Y/Y|Y|Y|
|SUI_USDT|0.836600|0.836400|0.836600|1.40|N|Y/N|Y/Y|Y|N|
|WLD_USDT|0.315900|0.316300|0.315900|1.61|Y|Y/N|Y/Y|Y|N|
|XMR_USDT|545.380000|549.270000|545.380000|14.35|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1137.040000|1134.630000|1136.950000|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T10:14:59+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=127.220000, depth_time=2026-11-10T10:15:25+00:00, book20_bid_proxy_usdt=457798, book20_ask_proxy_usdt=372244, funding_indicative=0.000045, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.70%, turnover=11990058. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T10:15:02+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=0.002533, depth_time=2026-11-10T10:15:07+00:00, book20_bid_proxy_usdt=64129, book20_ask_proxy_usdt=46829, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-50.01%, turnover=14376364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T10:15:02+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=0.169380, depth_time=2026-11-10T10:15:14+00:00, book20_bid_proxy_usdt=62312, book20_ask_proxy_usdt=74944, funding_indicative=-0.000171, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.87%, turnover=36967945. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T10:15:02+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=8.494000, depth_time=2026-11-10T10:15:22+00:00, book20_bid_proxy_usdt=664056, book20_ask_proxy_usdt=794901, funding_indicative=0.000008, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.10%, turnover=50309884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T10:14:59+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=46.340000, depth_time=2026-11-10T10:15:34+00:00, book20_bid_proxy_usdt=830336, book20_ask_proxy_usdt=436903, funding_indicative=-0.000010, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.11%, turnover=10137470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T10:14:59+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=0.858200, depth_time=2026-11-10T10:15:29+00:00, book20_bid_proxy_usdt=729434, book20_ask_proxy_usdt=359238, funding_indicative=-0.000025, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.68%, turnover=7944390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-10T10:14:59+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=0.154080, depth_time=2026-11-10T10:15:37+00:00, book20_bid_proxy_usdt=339628, book20_ask_proxy_usdt=162250, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.17%, turnover=22870712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T10:15:02+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=0.006657, depth_time=2026-11-10T10:15:10+00:00, book20_bid_proxy_usdt=24988, book20_ask_proxy_usdt=36304, funding_indicative=0.000237, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-40.97%, turnover=24302153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ON_USDT: quote_utc=2026-11-10T10:15:02+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=0.194600, depth_time=2026-11-10T10:15:12+00:00, book20_bid_proxy_usdt=54114, book20_ask_proxy_usdt=58833, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.63%, turnover=5696050. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T10:14:59+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=0.003588, depth_time=2026-11-10T10:15:32+00:00, book20_bid_proxy_usdt=3041823, book20_ask_proxy_usdt=2745469, funding_indicative=0.000003, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.37%, turnover=7284118. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T10:14:59+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=191.700000, depth_time=2026-11-10T10:15:26+00:00, book20_bid_proxy_usdt=49358, book20_ask_proxy_usdt=59523, funding_indicative=-0.000163, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.51%, turnover=32871954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-10T10:15:02+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=0.850600, depth_time=2026-11-10T10:15:37+00:00, book20_bid_proxy_usdt=1127092, book20_ask_proxy_usdt=1076006, funding_indicative=0.000060, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.53%, turnover=34536557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T10:14:59+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=0.322000, depth_time=2026-11-10T10:15:40+00:00, book20_bid_proxy_usdt=5884243, book20_ask_proxy_usdt=4634282, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=26949688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T10:14:59+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=565.400000, depth_time=2026-11-10T10:15:17+00:00, book20_bid_proxy_usdt=3189, book20_ask_proxy_usdt=14759, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.68%, turnover=5530928. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T10:15:02+00:00, last15m_closed_end=2026-11-10T10:15+00:00, prior8high=1154.700000, depth_time=2026-11-10T10:15:19+00:00, book20_bid_proxy_usdt=96126, book20_ask_proxy_usdt=106140, funding_indicative=0.000068, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.23%, turnover=2287696341. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
