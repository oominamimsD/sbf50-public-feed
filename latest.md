# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T05:15:48Z**
- feed_generated_utc: 2026-11-05T05:15:50+00:00
- source_sha256: `8136c8a5baeeb028459c2e556f652613eddf9dccfb6087fb419853829817fe84`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T05:15+00:00, close=80458.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T05:00+00:00, close=80490.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T04:00+00:00, close=80514.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.020688|-11.84|138.97|-12.06|5476038|1.93|
|TRUMPOFFICIAL_USDT|1.256000|-11.79|-26.50|-12.01|26707368|7.96|
|CLANKER_USDT|16.800000|-9.72|25.74|-9.94|20090685|5.97|
|AKE_USDT|0.002586|-7.97|-87.13|-8.19|16176043|3.87|
|BTW_USDT|1.023100|-6.90|-41.13|-7.12|5714735|1.95|
|VVV_USDT|21.611000|-6.66|-9.26|-6.88|5243606|0.46|
|WLD_USDT|0.374000|-4.61|-13.58|-4.83|67469643|2.68|
|OP_USDT|0.109720|-3.92|-1.22|-4.14|10010372|0.91|
|PEPE_USDT|0.000005|-3.80|2.59|-4.02|133457920|0.20|
|SEI_USDT|0.048330|-3.74|-8.55|-3.96|6752931|2.07|
|ENA_USDT|0.179740|-3.24|-8.38|-3.46|100688577|0.56|
|PENGU_USDT|0.007213|-3.07|-7.00|-3.29|7523313|1.39|
|ZRO_USDT|1.808200|-3.02|5.61|-3.24|9248394|0.55|
|HYPE_USDT|83.696000|-2.57|4.80|-2.79|82665577|0.12|
|AVAX_USDT|8.753000|-2.16|-1.50|-2.38|25529137|1.14|
|DOT_USDT|0.949200|-2.04|-5.42|-2.26|11953206|1.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002586|0.002428|0.002587|0.66|N|Y/Y|Y/Y|N|N|
|AVAX_USDT|8.753000|8.743000|8.753000|2.93|N|N/N|N/N|N|N|
|BTW_USDT|1.023100|1.015400|1.023100|0.97|N|Y/Y|Y/Y|N|N|
|CLANKER_USDT|16.800000|16.230000|16.800000|0.80|N|Y/Y|N/N|N|N|
|ENA_USDT|0.179740|0.180160|0.179740|2.46|Y|N/N|N/N|N|N|
|HYPE_USDT|83.696000|83.085000|83.699000|0.78|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.020688|0.020300|0.020688|0.66|N|Y/Y|N/N|N|N|
|OP_USDT|0.109720|0.109650|0.109720|0.88|N|Y/Y|Y/Y|N|N|
|PENGU_USDT|0.007213|0.007232|0.007213|8.38|Y|Y/N|N/N|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.96|N|Y/N|N/N|N|N|
|SEI_USDT|0.048330|0.048570|0.048330|3.72|Y|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.256000|1.247000|1.256000|1.86|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.611000|21.380000|21.611000|0.73|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.374000|0.372200|0.374000|1.87|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.808200|1.810200|1.808200|1.50|Y|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=0.002618, depth_time=2026-11-05T05:15:16+00:00, book20_bid_proxy_usdt=34437, book20_ask_proxy_usdt=49623, funding_indicative=-0.000536, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.97%, turnover=16176043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=8.854000, depth_time=2026-11-05T05:15:48+00:00, book20_bid_proxy_usdt=1530847, book20_ask_proxy_usdt=833826, funding_indicative=0.000070, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=25529137. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=1.061500, depth_time=2026-11-05T05:15:18+00:00, book20_bid_proxy_usdt=16378, book20_ask_proxy_usdt=17128, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.90%, turnover=5714735. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=17.050000, depth_time=2026-11-05T05:15:12+00:00, book20_bid_proxy_usdt=118698, book20_ask_proxy_usdt=135104, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.72%, turnover=20090685. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=0.183980, depth_time=2026-11-05T05:15:34+00:00, book20_bid_proxy_usdt=193693, book20_ask_proxy_usdt=118366, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.24%, turnover=100688577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=84.509000, depth_time=2026-11-05T05:15:44+00:00, book20_bid_proxy_usdt=45572, book20_ask_proxy_usdt=88595, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=82665577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=0.021553, depth_time=2026-11-05T05:15:07+00:00, book20_bid_proxy_usdt=10077, book20_ask_proxy_usdt=10252, funding_indicative=0.000067, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.84%, turnover=5476038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=0.111820, depth_time=2026-11-05T05:15:26+00:00, book20_bid_proxy_usdt=90105, book20_ask_proxy_usdt=102261, funding_indicative=0.000042, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.92%, turnover=10010372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=0.007385, depth_time=2026-11-05T05:15:39+00:00, book20_bid_proxy_usdt=485681, book20_ask_proxy_usdt=258206, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=7523313. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=0.000005, depth_time=2026-11-05T05:15:29+00:00, book20_bid_proxy_usdt=59941, book20_ask_proxy_usdt=55620, funding_indicative=0.000069, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.80%, turnover=133457920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=0.049420, depth_time=2026-11-05T05:15:31+00:00, book20_bid_proxy_usdt=362285, book20_ask_proxy_usdt=284673, funding_indicative=0.000100, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.74%, turnover=6752931. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=1.290000, depth_time=2026-11-05T05:15:06+00:00, book20_bid_proxy_usdt=1119882, book20_ask_proxy_usdt=1261665, funding_indicative=-0.000346, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.79%, turnover=26707368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=22.117000, depth_time=2026-11-05T05:15:20+00:00, book20_bid_proxy_usdt=24089, book20_ask_proxy_usdt=19316, funding_indicative=-0.000203, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.66%, turnover=5243606. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=0.380500, depth_time=2026-11-05T05:15:24+00:00, book20_bid_proxy_usdt=2965048, book20_ask_proxy_usdt=2583374, funding_indicative=-0.000359, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.61%, turnover=67469643. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T05:15:01+00:00, last15m_closed_end=2026-11-05T05:15+00:00, prior8high=1.861000, depth_time=2026-11-05T05:15:38+00:00, book20_bid_proxy_usdt=28509, book20_ask_proxy_usdt=45942, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=9248394. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
