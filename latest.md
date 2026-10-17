# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T01:15:42Z**
- feed_generated_utc: 2026-10-17T01:15:44+00:00
- source_sha256: `e644789f660733d04447eb85f2e37a262355ca77303515bf852c8240f2899c58`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T01:15+00:00, close=81530, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T01:00+00:00, close=81532.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.968500|-6.31|-3.35|-6.56|16329154|0.51|
|ZEC_USDT|1146.880000|-3.46|-5.86|-3.71|1359884241|0.09|
|RIVER_USDT|1.088000|-3.37|-7.95|-3.62|5474204|9.20|
|INJ_USDT|8.695000|-3.15|25.48|-3.40|114903575|1.15|
|BAT_USDT|0.198700|-3.08|63.32|-3.33|15793170|1.51|
|ARB_USDT|0.189580|-2.74|4.85|-2.99|31405650|0.53|
|FILECOIN_USDT|1.141000|-2.21|6.63|-2.46|23079011|0.88|
|TAO_USDT|274.440000|-2.20|-0.08|-2.45|81334887|1.09|
|APT_USDT|0.839600|-1.92|4.88|-2.17|12474810|1.19|
|FET_USDT|0.195800|-1.90|-9.76|-2.15|11266741|5.11|
|AAVE_USDT|154.520000|-1.75|-9.02|-2.00|30999335|0.65|
|ONDO_USDT|0.449600|-1.64|-6.35|-1.89|28734401|2.22|
|AVAX_USDT|9.923000|-1.58|-2.63|-1.83|124922321|1.01|
|STRK_USDT|0.072780|-1.58|-3.35|-1.83|21109937|1.37|
|SUI_USDT|1.006600|-1.36|-4.82|-1.61|98408045|0.99|
|ENA_USDT|0.197220|-1.35|-8.51|-1.60|40616895|0.51|
|QNT_USDT|199.300000|-1.11|-20.09|-1.36|66821842|0.50|
|ICP_USDT|3.005000|-1.08|-0.46|-1.33|8793160|3.33|
|FARTCOIN_USDT|0.153250|-0.95|-6.19|-1.20|7158425|0.65|
|LTC_USDT|59.410000|-0.75|-6.58|-1.00|9125106|3.37|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.520000|153.940000|154.520000|0.74|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.839600|0.837300|0.839600|0.08|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189580|0.189100|0.189580|2.08|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.923000|9.893000|9.924000|1.00|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.198700|0.194970|0.198700|1.09|N|Y/Y|N/N|Y|N|
|FET_USDT|0.195800|0.195900|0.195800|1.79|Y|Y/Y|Y/Y|Y|Y|
|FILECOIN_USDT|1.141000|1.133500|1.140900|1.43|N|Y/N|N/N|Y|N|
|INJ_USDT|8.695000|8.619000|8.695000|0.19|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.449600|0.449000|0.449500|0.79|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.088000|1.078000|1.087000|0.10|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.072780|0.071710|0.072780|0.29|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.006600|1.003100|1.006500|1.75|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|274.440000|273.390000|274.410000|0.39|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1146.880000|1141.130000|1146.840000|1.05|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.968500|1.938500|1.968500|1.57|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T01:15:03+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=155.320000, depth_time=2026-10-17T01:15:30+00:00, book20_bid_proxy_usdt=275850, book20_ask_proxy_usdt=324754, funding_indicative=0.000054, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=30999335. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T01:15:03+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=0.848400, depth_time=2026-10-17T01:15:25+00:00, book20_bid_proxy_usdt=122951, book20_ask_proxy_usdt=139123, funding_indicative=0.000028, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=12474810. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T01:15:02+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=0.191850, depth_time=2026-10-17T01:15:19+00:00, book20_bid_proxy_usdt=88023, book20_ask_proxy_usdt=73186, funding_indicative=-0.000128, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=31405650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T01:15:02+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=9.997000, depth_time=2026-10-17T01:15:36+00:00, book20_bid_proxy_usdt=718464, book20_ask_proxy_usdt=616427, funding_indicative=0.000054, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=124922321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T01:15:02+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=0.198780, depth_time=2026-10-17T01:15:17+00:00, book20_bid_proxy_usdt=28165, book20_ask_proxy_usdt=25631, funding_indicative=-0.000054, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.08%, turnover=15793170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T01:15:03+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=0.199700, depth_time=2026-10-17T01:15:29+00:00, book20_bid_proxy_usdt=1525789, book20_ask_proxy_usdt=1154238, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=11266741. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T01:15:02+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=1.159600, depth_time=2026-10-17T01:15:21+00:00, book20_bid_proxy_usdt=562846, book20_ask_proxy_usdt=425616, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=23079011. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T01:15:02+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=8.742000, depth_time=2026-10-17T01:15:15+00:00, book20_bid_proxy_usdt=189450, book20_ask_proxy_usdt=231543, funding_indicative=-0.000128, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.15%, turnover=114903575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-17T01:15:02+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=0.456600, depth_time=2026-10-17T01:15:33+00:00, book20_bid_proxy_usdt=2189020, book20_ask_proxy_usdt=2165750, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.64%, turnover=28734401. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T01:15:03+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=1.099000, depth_time=2026-10-17T01:15:13+00:00, book20_bid_proxy_usdt=409288, book20_ask_proxy_usdt=370675, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.37%, turnover=5474204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T01:15:02+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=0.074200, depth_time=2026-10-17T01:15:36+00:00, book20_bid_proxy_usdt=344819, book20_ask_proxy_usdt=384732, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.58%, turnover=21109937. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T01:15:02+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=1.024100, depth_time=2026-10-17T01:15:41+00:00, book20_bid_proxy_usdt=672417, book20_ask_proxy_usdt=1288582, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=98408045. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T01:15:02+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=276.100000, depth_time=2026-10-17T01:15:22+00:00, book20_bid_proxy_usdt=105637, book20_ask_proxy_usdt=64857, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.20%, turnover=81334887. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T01:15:02+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=1153.700000, depth_time=2026-10-17T01:15:10+00:00, book20_bid_proxy_usdt=52351, book20_ask_proxy_usdt=558456, funding_indicative=0.000082, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.46%, turnover=1359884241. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T01:15:02+00:00, last15m_closed_end=2026-10-17T01:15+00:00, prior8high=2.066300, depth_time=2026-10-17T01:15:07+00:00, book20_bid_proxy_usdt=44920, book20_ask_proxy_usdt=40483, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.31%, turnover=16329154. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
