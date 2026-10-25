# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T10:00:47Z**
- feed_generated_utc: 2026-10-25T10:00:51+00:00
- source_sha256: `878353aa747e21e2c8e2e76f539cd13bf65d7d536ac6f2ed1382b2d554371726`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T10:00+00:00, close=80293, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T10:00+00:00, close=80293, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.034880|-24.25|173.35|-24.91|31504973|2.87|
|ORDER_USDT|0.052100|-22.70|68.33|-23.36|11703867|1.92|
|BTW_USDT|1.645400|-5.36|-27.49|-6.02|11159664|0.61|
|STRK_USDT|0.045440|-3.95|-31.30|-4.61|9009604|2.20|
|WLD_USDT|0.447000|-3.60|-9.80|-4.26|92004317|2.24|
|DOT_USDT|1.023600|-2.43|-8.39|-3.09|11699022|1.95|
|PENGU_USDT|0.007373|-2.34|-1.07|-3.00|5616500|1.36|
|AKE_USDT|0.028569|-1.78|-1.35|-2.44|5119430|0.70|
|SEI_USDT|0.052370|-1.74|-15.54|-2.40|7744690|1.91|
|APT_USDT|0.694900|-1.65|-12.86|-2.31|5842573|1.44|
|ARB_USDT|0.164620|-1.53|-10.49|-2.19|15366853|0.61|
|SUI_USDT|0.911600|-1.44|-7.15|-2.10|65921384|1.10|
|ONDO_USDT|0.399500|-1.26|-9.12|-1.92|14668187|2.50|
|LINK_USDT|11.319000|-1.23|-4.93|-1.89|46909741|0.88|
|OP_USDT|0.110270|-0.60|-14.51|-1.26|5955364|1.81|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028569|0.028536|0.028569|0.85|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.694900|0.687600|0.694900|0.11|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164620|0.163130|0.164620|1.01|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.645400|1.636300|1.645400|0.38|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.023600|1.011600|1.023600|0.72|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.034880|0.034520|0.034860|0.62|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.319000|11.255000|11.319000|0.46|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.399500|0.396800|0.399500|0.43|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.110270|0.109150|0.110270|0.96|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.052100|0.048370|0.052240|0.63|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007373|0.007294|0.007373|0.17|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052370|0.051870|0.052370|0.25|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045440|0.045060|0.045440|0.69|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.911600|0.903500|0.911700|0.43|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.447000|0.431900|0.447000|0.91|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-25T10:00:00+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=0.029186, depth_time=2026-10-25T10:00:28+00:00, book20_bid_proxy_usdt=10541, book20_ask_proxy_usdt=12672, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.78%, turnover=5119430. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-25T10:00:00+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=0.703200, depth_time=2026-10-25T10:00:33+00:00, book20_bid_proxy_usdt=137672, book20_ask_proxy_usdt=145049, funding_indicative=-0.000075, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=5842573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T10:00:00+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=0.166810, depth_time=2026-10-25T10:00:36+00:00, book20_bid_proxy_usdt=104062, book20_ask_proxy_usdt=104717, funding_indicative=0.000056, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=15366853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T10:00:00+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=1.695600, depth_time=2026-10-25T10:00:14+00:00, book20_bid_proxy_usdt=14806, book20_ask_proxy_usdt=11036, funding_indicative=-0.016342, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.36%, turnover=11159664. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T10:00:00+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=1.032000, depth_time=2026-10-25T10:00:23+00:00, book20_bid_proxy_usdt=304328, book20_ask_proxy_usdt=311504, funding_indicative=-0.000030, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=11699022. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T10:00:00+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=0.038050, depth_time=2026-10-25T10:00:09+00:00, book20_bid_proxy_usdt=39203, book20_ask_proxy_usdt=142644, funding_indicative=-0.001300, next_funding_utc=2026-10-25T11:00:00+00:00, funding_cycle_h=1, 24h_change=-24.25%, turnover=31504973. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T10:00:00+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=11.417000, depth_time=2026-10-25T10:00:43+00:00, book20_bid_proxy_usdt=464041, book20_ask_proxy_usdt=443959, funding_indicative=0.000039, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=46909741. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-25T10:00:00+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=0.405500, depth_time=2026-10-25T10:00:40+00:00, book20_bid_proxy_usdt=3346044, book20_ask_proxy_usdt=3020534, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.26%, turnover=14668187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-25T10:00:01+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=0.112040, depth_time=2026-10-25T10:00:46+00:00, book20_bid_proxy_usdt=109374, book20_ask_proxy_usdt=107283, funding_indicative=0.000030, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.60%, turnover=5955364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T10:00:00+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=0.052340, depth_time=2026-10-25T10:00:11+00:00, book20_bid_proxy_usdt=36506, book20_ask_proxy_usdt=51095, funding_indicative=-0.001461, next_funding_utc=2026-10-25T11:00:00+00:00, funding_cycle_h=1, 24h_change=-22.70%, turnover=11703867. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T10:00:01+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=0.007475, depth_time=2026-10-25T10:00:24+00:00, book20_bid_proxy_usdt=206508, book20_ask_proxy_usdt=227442, funding_indicative=-0.000062, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=5616500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T10:00:01+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=0.052970, depth_time=2026-10-25T10:00:30+00:00, book20_bid_proxy_usdt=238702, book20_ask_proxy_usdt=327591, funding_indicative=-0.000106, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=7744690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T10:00:01+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=0.046630, depth_time=2026-10-25T10:00:17+00:00, book20_bid_proxy_usdt=686691, book20_ask_proxy_usdt=744516, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.95%, turnover=9009604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T10:00:00+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=0.920800, depth_time=2026-10-25T10:00:38+00:00, book20_bid_proxy_usdt=1443224, book20_ask_proxy_usdt=872893, funding_indicative=0.000071, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=65921384. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-25T10:00:00+00:00, last15m_closed_end=2026-10-25T10:00+00:00, prior8high=0.466600, depth_time=2026-10-25T10:00:20+00:00, book20_bid_proxy_usdt=1871134, book20_ask_proxy_usdt=2341422, funding_indicative=0.000010, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.60%, turnover=92004317. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
