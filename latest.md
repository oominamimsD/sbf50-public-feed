# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T02:15:43Z**
- feed_generated_utc: 2026-10-17T02:15:45+00:00
- source_sha256: `fcde90e4d9dee22bd3a3bbaa0dcafb3acb6fc62733aef52661d54e7e723be51f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T02:15+00:00, close=81593.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T02:00+00:00, close=81511.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.964600|-6.50|-3.54|-6.83|15799821|0.51|
|RIVER_USDT|1.084000|-3.73|-8.29|-4.06|5402584|9.23|
|ZEC_USDT|1150.230000|-3.18|-5.59|-3.51|1376936835|0.17|
|ARB_USDT|0.189520|-2.78|4.82|-3.11|31483688|1.05|
|TAO_USDT|274.800000|-2.07|0.04|-2.40|79820585|1.09|
|FET_USDT|0.195900|-1.85|-9.72|-2.18|11345475|5.11|
|INJ_USDT|8.827000|-1.68|27.39|-2.01|112956981|1.13|
|AAVE_USDT|154.790000|-1.58|-8.86|-1.91|30501406|0.65|
|APT_USDT|0.843400|-1.48|5.35|-1.81|12605325|1.19|
|SUI_USDT|1.007200|-1.30|-4.76|-1.63|97176621|0.99|
|AVAX_USDT|9.960000|-1.21|-2.27|-1.54|123773270|1.00|
|ENA_USDT|0.197580|-1.17|-8.34|-1.50|40573156|0.51|
|ONDO_USDT|0.451900|-1.13|-5.87|-1.46|28631107|2.21|
|ICP_USDT|3.007000|-1.02|-0.39|-1.35|8971588|3.33|
|FARTCOIN_USDT|0.153450|-0.82|-6.07|-1.15|7132244|0.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.790000|153.940000|154.790000|0.83|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.843400|0.833600|0.843100|2.13|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189520|0.188590|0.189520|0.82|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.960000|9.881000|9.963000|1.45|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.197580|0.196360|0.197580|1.85|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.153450|0.152600|0.153550|0.31|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.195900|0.194100|0.195900|2.19|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|3.007000|2.986000|3.007000|7.43|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.827000|8.619000|8.825000|1.24|N|N/Y|N/N|Y|N|
|ONDO_USDT|0.451900|0.448400|0.451900|2.68|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.084000|1.075000|1.083000|1.61|N|Y/Y|N/N|Y|N|
|SUI_USDT|1.007200|1.001200|1.007000|1.70|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|274.800000|273.080000|274.800000|0.65|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1150.230000|1141.130000|1150.600000|1.96|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.964600|1.938500|1.964300|0.78|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=155.220000, depth_time=2026-10-17T02:15:26+00:00, book20_bid_proxy_usdt=410529, book20_ask_proxy_usdt=373549, funding_indicative=0.000057, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=30501406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=0.848400, depth_time=2026-10-17T02:15:27+00:00, book20_bid_proxy_usdt=137388, book20_ask_proxy_usdt=127936, funding_indicative=0.000047, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=12605325. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=0.191640, depth_time=2026-10-17T02:15:17+00:00, book20_bid_proxy_usdt=64125, book20_ask_proxy_usdt=43856, funding_indicative=-0.000099, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.78%, turnover=31483688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=9.954000, depth_time=2026-10-17T02:15:32+00:00, book20_bid_proxy_usdt=1149243, book20_ask_proxy_usdt=529623, funding_indicative=0.000080, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.21%, turnover=123773270. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=0.199050, depth_time=2026-10-17T02:15:35+00:00, book20_bid_proxy_usdt=230104, book20_ask_proxy_usdt=142616, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=40573156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=0.154720, depth_time=2026-10-17T02:15:42+00:00, book20_bid_proxy_usdt=61966, book20_ask_proxy_usdt=56590, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.82%, turnover=7132244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=0.199000, depth_time=2026-10-17T02:15:21+00:00, book20_bid_proxy_usdt=1992079, book20_ask_proxy_usdt=1109764, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=11345475. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=3.031000, depth_time=2026-10-17T02:15:39+00:00, book20_bid_proxy_usdt=1041089, book20_ask_proxy_usdt=1030078, funding_indicative=0.000078, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=8971588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=8.758000, depth_time=2026-10-17T02:15:24+00:00, book20_bid_proxy_usdt=210740, book20_ask_proxy_usdt=134466, funding_indicative=0.000116, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=112956981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=0.454000, depth_time=2026-10-17T02:15:38+00:00, book20_bid_proxy_usdt=2001374, book20_ask_proxy_usdt=1889920, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.13%, turnover=28631107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=1.093000, depth_time=2026-10-17T02:15:11+00:00, book20_bid_proxy_usdt=505326, book20_ask_proxy_usdt=455352, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.73%, turnover=5402584. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=1.020800, depth_time=2026-10-17T02:15:31+00:00, book20_bid_proxy_usdt=1103988, book20_ask_proxy_usdt=857266, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=97176621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=275.950000, depth_time=2026-10-17T02:15:19+00:00, book20_bid_proxy_usdt=109122, book20_ask_proxy_usdt=65983, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=79820585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=1153.700000, depth_time=2026-10-17T02:15:14+00:00, book20_bid_proxy_usdt=755637, book20_ask_proxy_usdt=725288, funding_indicative=0.000088, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.18%, turnover=1376936835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T02:15:00+00:00, last15m_closed_end=2026-10-17T02:15+00:00, prior8high=2.050600, depth_time=2026-10-17T02:15:08+00:00, book20_bid_proxy_usdt=62503, book20_ask_proxy_usdt=27997, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.50%, turnover=15799821. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
