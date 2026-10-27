# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T04:45:41Z**
- feed_generated_utc: 2026-10-27T04:45:45+00:00
- source_sha256: `0084f0b5f5573ccfd38293d315e3c8accbc3b13cfb3116460e278bd57697fa60`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T04:45+00:00, close=79623.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|199.960000|-4.90|2.17|-3.94|125172550|0.50|
|PUMPFUN_USDT|0.004135|-4.45|-7.20|-3.49|21174992|2.42|
|AAVE_USDT|131.920000|-3.51|-10.39|-2.55|25173199|0.76|
|NEAR_USDT|4.420000|-3.34|-9.86|-2.38|101705057|2.26|
|DOT_USDT|0.988400|-3.34|-13.81|-2.38|11031181|1.01|
|ONDO_USDT|0.405700|-3.12|-6.21|-2.16|22650881|2.46|
|AVAX_USDT|8.732000|-2.94|-8.68|-1.98|58133572|1.15|
|FET_USDT|0.171400|-2.94|-9.31|-1.98|6699195|5.84|
|FILECOIN_USDT|0.894500|-2.84|-11.61|-1.88|6450470|3.35|
|ZEC_USDT|1216.790000|-2.47|8.13|-1.51|1487396317|0.08|
|ICP_USDT|2.573000|-2.16|-9.81|-1.20|5047086|3.89|
|TAO_USDT|248.120000|-2.12|-7.52|-1.16|46239802|0.81|
|WLD_USDT|0.435900|-2.04|-13.90|-1.08|70732556|2.29|
|PENGU_USDT|0.007421|-2.02|-0.93|-1.06|5540126|1.35|
|ARB_USDT|0.166630|-1.97|-14.82|-1.01|20484390|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.920000|132.240000|131.930000|0.87|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166630|0.165910|0.166630|0.22|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.732000|8.752000|8.732000|5.08|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|0.988400|0.988500|0.988400|2.41|Y|Y/Y|Y/Y|Y|Y|
|FET_USDT|0.171400|0.170600|0.171300|4.34|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.894500|0.892600|0.894700|0.07|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.573000|2.562000|2.574000|0.70|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.420000|4.389000|4.419000|0.36|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.405700|0.404300|0.405800|0.59|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007421|0.007387|0.007421|0.51|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004135|0.004118|0.004136|0.26|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|199.960000|199.100000|199.880000|0.84|N|Y/Y|N/N|Y|N|
|TAO_USDT|248.120000|247.350000|248.120000|0.50|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.435900|0.433900|0.435900|0.53|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1216.790000|1216.410000|1216.790000|0.61|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=133.660000, depth_time=2026-10-27T04:45:12+00:00, book20_bid_proxy_usdt=482068, book20_ask_proxy_usdt=379617, funding_indicative=0.000090, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.51%, turnover=25173199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=0.168130, depth_time=2026-10-27T04:45:41+00:00, book20_bid_proxy_usdt=75357, book20_ask_proxy_usdt=103991, funding_indicative=0.000002, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=20484390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=8.860000, depth_time=2026-10-27T04:45:21+00:00, book20_bid_proxy_usdt=1758411, book20_ask_proxy_usdt=1192242, funding_indicative=-0.000060, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=58133572. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=0.999000, depth_time=2026-10-27T04:45:16+00:00, book20_bid_proxy_usdt=194900, book20_ask_proxy_usdt=374673, funding_indicative=-0.000136, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.34%, turnover=11031181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=0.173100, depth_time=2026-10-27T04:45:22+00:00, book20_bid_proxy_usdt=1882661, book20_ask_proxy_usdt=1352906, funding_indicative=0.000033, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=6699195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=0.902700, depth_time=2026-10-27T04:45:22+00:00, book20_bid_proxy_usdt=1197008, book20_ask_proxy_usdt=1366938, funding_indicative=-0.000034, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.84%, turnover=6450470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=2.588000, depth_time=2026-10-27T04:45:30+00:00, book20_bid_proxy_usdt=1011456, book20_ask_proxy_usdt=1009512, funding_indicative=0.000048, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=5047086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=4.467000, depth_time=2026-10-27T04:45:13+00:00, book20_bid_proxy_usdt=4987054, book20_ask_proxy_usdt=3016413, funding_indicative=0.000042, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.34%, turnover=101705057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=0.408700, depth_time=2026-10-27T04:45:18+00:00, book20_bid_proxy_usdt=2293066, book20_ask_proxy_usdt=2553435, funding_indicative=0.000022, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.12%, turnover=22650881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=0.007468, depth_time=2026-10-27T04:45:38+00:00, book20_bid_proxy_usdt=170142, book20_ask_proxy_usdt=250228, funding_indicative=0.000005, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.02%, turnover=5540126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=0.004208, depth_time=2026-10-27T04:45:07+00:00, book20_bid_proxy_usdt=2241074, book20_ask_proxy_usdt=1951432, funding_indicative=0.000019, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.45%, turnover=21174992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=205.230000, depth_time=2026-10-27T04:45:07+00:00, book20_bid_proxy_usdt=50975, book20_ask_proxy_usdt=62302, funding_indicative=-0.000118, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.90%, turnover=125172550. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=249.520000, depth_time=2026-10-27T04:45:32+00:00, book20_bid_proxy_usdt=355101, book20_ask_proxy_usdt=116590, funding_indicative=0.000035, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=46239802. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=0.440800, depth_time=2026-10-27T04:45:35+00:00, book20_bid_proxy_usdt=3338901, book20_ask_proxy_usdt=3249973, funding_indicative=-0.000203, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=70732556. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-27T04:45:02+00:00, last15m_closed_end=2026-10-27T04:45+00:00, prior8high=1228.480000, depth_time=2026-10-27T04:45:28+00:00, book20_bid_proxy_usdt=2030301, book20_ask_proxy_usdt=406271, funding_indicative=0.000086, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=1487396317. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
