# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T15:00:46Z**
- feed_generated_utc: 2026-10-28T15:00:51+00:00
- source_sha256: `02084a5377c2af0a46cca85b18a905cbeb0ddacac7f8a0f86f4b5eacbeff0e41`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T15:00+00:00, close=80572.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T15:00+00:00, close=80572.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.019455|-34.19|-37.42|-34.26|6715528|1.03|
|Q_USDT|0.057740|-9.19|-52.96|-9.26|16873464|1.73|
|ENA_USDT|0.194110|-8.77|2.22|-8.84|83485593|0.52|
|BEAT_USDT|0.079900|-7.31|6.94|-7.38|11572825|1.25|
|INJ_USDT|7.792000|-4.88|-9.39|-4.95|24367692|1.28|
|QNT_USDT|193.170000|-2.38|-1.01|-2.45|66481799|0.52|
|DASH_USDT|53.020000|-2.12|6.16|-2.19|14143832|1.89|
|PUMPFUN_USDT|0.004194|-2.12|-7.02|-2.19|13184164|2.39|
|ARB_USDT|0.165370|-1.85|-12.47|-1.92|18243037|0.60|
|SILVER_USDT|53.730000|-1.66|-7.28|-1.73|248194625|1.86|
|ASTER_USDT|0.702000|-1.54|-1.68|-1.61|5564914|1.42|
|WLD_USDT|0.429700|-1.44|-23.64|-1.51|59356046|2.33|
|ADA_USDT|0.202300|-1.17|-8.62|-1.24|37588070|4.94|
|UNI_USDT|7.034000|-1.16|-3.25|-1.23|13798707|1.42|
|ZEC_USDT|1277.740000|-1.15|7.27|-1.22|1543763372|0.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.202300|0.201100|0.202300|1.72|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.019455|0.019128|0.019455|0.70|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165370|0.163310|0.165270|1.05|N|Y/Y|Y/Y|Y|N|
|ASTER_USDT|0.702000|0.701400|0.702100|1.66|N|Y/Y|N/N|Y|N|
|BEAT_USDT|0.079900|0.078520|0.079850|0.19|N|Y/Y|Y/N|Y|N|
|DASH_USDT|53.020000|52.690000|53.000000|0.11|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.194110|0.193030|0.194080|0.66|N|Y/Y|Y/N|Y|N|
|INJ_USDT|7.792000|7.748000|7.793000|0.67|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004194|0.004162|0.004191|2.79|N|Y/Y|N/N|Y|N|
|QNT_USDT|193.170000|192.380000|193.110000|0.71|N|Y/Y|N/N|Y|N|
|Q_USDT|0.057740|0.052780|0.057790|1.78|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.730000|53.600000|53.730000|1.91|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.034000|6.969000|7.034000|1.16|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.429700|0.425400|0.429500|0.38|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1277.740000|1268.350000|1277.180000|0.83|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=0.203700, depth_time=2026-10-28T15:00:40+00:00, book20_bid_proxy_usdt=7464753, book20_ask_proxy_usdt=6944820, funding_indicative=-0.000075, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=37588070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=0.019953, depth_time=2026-10-28T15:00:10+00:00, book20_bid_proxy_usdt=2958, book20_ask_proxy_usdt=4502, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-34.19%, turnover=6715528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=0.165900, depth_time=2026-10-28T15:00:28+00:00, book20_bid_proxy_usdt=77514, book20_ask_proxy_usdt=96624, funding_indicative=-0.000088, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=18243037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=0.707400, depth_time=2026-10-28T15:00:35+00:00, book20_bid_proxy_usdt=790906, book20_ask_proxy_usdt=706689, funding_indicative=0.000017, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.54%, turnover=5564914. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=0.080810, depth_time=2026-10-28T15:00:17+00:00, book20_bid_proxy_usdt=9662, book20_ask_proxy_usdt=8235, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.31%, turnover=11572825. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=53.460000, depth_time=2026-10-28T15:00:21+00:00, book20_bid_proxy_usdt=825213, book20_ask_proxy_usdt=757472, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=14143832. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=0.200120, depth_time=2026-10-28T15:00:14+00:00, book20_bid_proxy_usdt=211811, book20_ask_proxy_usdt=160348, funding_indicative=-0.000038, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.77%, turnover=83485593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=7.877000, depth_time=2026-10-28T15:00:19+00:00, book20_bid_proxy_usdt=319076, book20_ask_proxy_usdt=244266, funding_indicative=0.000091, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.88%, turnover=24367692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=0.004262, depth_time=2026-10-28T15:00:26+00:00, book20_bid_proxy_usdt=2036127, book20_ask_proxy_usdt=2386296, funding_indicative=0.000000, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=13184164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=198.160000, depth_time=2026-10-28T15:00:22+00:00, book20_bid_proxy_usdt=57053, book20_ask_proxy_usdt=95521, funding_indicative=-0.000238, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=66481799. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=0.056490, depth_time=2026-10-28T15:00:12+00:00, book20_bid_proxy_usdt=29168, book20_ask_proxy_usdt=24013, funding_indicative=-0.000679, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.19%, turnover=16873464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=54.480000, depth_time=2026-10-28T15:00:31+00:00, book20_bid_proxy_usdt=46100692, book20_ask_proxy_usdt=54421363, funding_indicative=0.000031, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.66%, turnover=248194625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=7.068000, depth_time=2026-10-28T15:00:42+00:00, book20_bid_proxy_usdt=1661476, book20_ask_proxy_usdt=2083353, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=13798707. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=0.432900, depth_time=2026-10-28T15:00:36+00:00, book20_bid_proxy_usdt=3104810, book20_ask_proxy_usdt=4150074, funding_indicative=-0.000051, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=59356046. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-28T15:00:03+00:00, last15m_closed_end=2026-10-28T15:00+00:00, prior8high=1292.460000, depth_time=2026-10-28T15:00:45+00:00, book20_bid_proxy_usdt=263439, book20_ask_proxy_usdt=676794, funding_indicative=0.000091, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.15%, turnover=1543763372. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
