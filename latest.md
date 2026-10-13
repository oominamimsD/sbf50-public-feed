# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T15:15:46Z**
- feed_generated_utc: 2026-10-13T15:15:49+00:00
- source_sha256: `8a6d0df829cde58f8b409caa7b31a6c05d54e79332793c6d43950663e7efa648`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T15:15+00:00, close=83630.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T15:00+00:00, close=83486.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T12:00+00:00, close=83325.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.216000|-25.38|1.40|-26.52|9468401|4.64|
|W_USDT|0.017992|-25.22|27.21|-26.36|12732725|9.45|
|ZRO_USDT|2.005000|-11.32|-1.98|-12.46|15424082|1.00|
|NEAR_USDT|5.021000|-9.51|-0.01|-10.65|276022717|1.99|
|QNT_USDT|206.770000|-9.46|-19.47|-10.60|92447454|0.48|
|LIT_USDT|3.325300|-8.27|-12.54|-9.41|7525849|0.30|
|PYTH_USDT|0.081790|-7.72|7.18|-8.86|8926480|3.67|
|RLC_USDT|0.919500|-6.98|67.79|-8.12|6117185|1.09|
|USELESS_USDT|0.169860|-6.46|-25.08|-7.60|5623899|0.59|
|ONDO_USDT|0.468100|-6.02|-4.23|-7.16|62982599|2.14|
|PUMPFUN_USDT|0.005000|-5.82|-21.07|-6.96|34764928|2.00|
|SEI_USDT|0.062580|-5.71|-12.97|-6.85|9581326|3.19|
|STRK_USDT|0.085990|-5.16|65.01|-6.30|51388013|1.16|
|JUP_USDT|0.325700|-5.01|-3.61|-6.15|8196685|3.07|
|ICP_USDT|3.132000|-4.94|-9.63|-6.08|15982644|3.19|
|HYPE_USDT|81.295000|-3.64|-12.25|-4.78|76532295|0.12|
|MAGIC_USDT|0.118240|-3.05|90.74|-4.19|7706790|1.69|
|SILVER_USDT|59.590000|-1.29|-2.66|-2.43|169586573|1.68|
|RENDER_USDT|2.017000|-0.29|2.33|-1.43|21144173|4.96|
|XAU_USDT|4172.060000|-0.01|0.76|-1.15|294105817|0.07|
|XAUT_USDT|4163.540000|0.00|0.64|-1.14|175300119|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.216000|0.216700|0.216000|1.22|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.132000|3.126000|3.134000|0.71|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.325700|0.324500|0.326000|1.03|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.325300|3.298800|3.325300|0.44|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.021000|4.968000|5.021000|0.66|N|Y/Y|Y/Y|N|N|
|ONDO_USDT|0.468100|0.463500|0.468100|0.51|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005000|0.004940|0.005001|5.32|N|Y/Y|Y/Y|N|N|
|PYTH_USDT|0.081790|0.081060|0.081790|2.67|N|Y/Y|N/N|N|N|
|QNT_USDT|206.770000|203.010000|206.730000|0.94|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.919500|0.896200|0.919500|1.10|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.062580|0.061960|0.062580|0.63|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085990|0.085110|0.085990|1.00|N|Y/Y|Y/Y|N|N|
|USELESS_USDT|0.169860|0.166270|0.169860|0.45|N|Y/Y|Y/Y|N|N|
|W_USDT|0.017992|0.017876|0.017998|0.90|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.005000|2.003400|2.004700|1.91|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T15:15:00+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=0.222500, depth_time=2026-10-13T15:15:08+00:00, book20_bid_proxy_usdt=137978, book20_ask_proxy_usdt=96351, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-25.38%, turnover=9468401. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T15:15:01+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=3.190000, depth_time=2026-10-13T15:15:45+00:00, book20_bid_proxy_usdt=866267, book20_ask_proxy_usdt=609343, funding_indicative=-0.000040, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.94%, turnover=15982644. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T15:15:01+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=0.330500, depth_time=2026-10-13T15:15:41+00:00, book20_bid_proxy_usdt=505837, book20_ask_proxy_usdt=416752, funding_indicative=-0.000064, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.01%, turnover=8196685. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T15:15:01+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=3.404100, depth_time=2026-10-13T15:15:20+00:00, book20_bid_proxy_usdt=18985, book20_ask_proxy_usdt=24889, funding_indicative=0.000040, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.27%, turnover=7525849. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T15:15:00+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=5.132000, depth_time=2026-10-13T15:15:16+00:00, book20_bid_proxy_usdt=2554156, book20_ask_proxy_usdt=1748357, funding_indicative=-0.000040, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.51%, turnover=276022717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-13T15:15:01+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=0.474700, depth_time=2026-10-13T15:15:31+00:00, book20_bid_proxy_usdt=1436437, book20_ask_proxy_usdt=1585503, funding_indicative=-0.000068, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.02%, turnover=62982599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T15:15:01+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=0.005077, depth_time=2026-10-13T15:15:33+00:00, book20_bid_proxy_usdt=1839755, book20_ask_proxy_usdt=754059, funding_indicative=-0.000022, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.82%, turnover=34764928. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-13T15:15:01+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=0.083530, depth_time=2026-10-13T15:15:22+00:00, book20_bid_proxy_usdt=143314, book20_ask_proxy_usdt=48484, funding_indicative=-0.000022, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.72%, turnover=8926480. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-13T15:15:00+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=210.460000, depth_time=2026-10-13T15:15:18+00:00, book20_bid_proxy_usdt=72569, book20_ask_proxy_usdt=58384, funding_indicative=-0.000257, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.46%, turnover=92447454. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T15:15:01+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=0.917300, depth_time=2026-10-13T15:15:24+00:00, book20_bid_proxy_usdt=58352, book20_ask_proxy_usdt=44772, funding_indicative=-0.000761, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.98%, turnover=6117185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T15:15:01+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=0.063460, depth_time=2026-10-13T15:15:35+00:00, book20_bid_proxy_usdt=237419, book20_ask_proxy_usdt=143355, funding_indicative=0.000020, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.71%, turnover=9581326. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T15:15:01+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=0.090370, depth_time=2026-10-13T15:15:40+00:00, book20_bid_proxy_usdt=144752, book20_ask_proxy_usdt=195207, funding_indicative=0.000018, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.16%, turnover=51388013. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T15:15:01+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=0.172750, depth_time=2026-10-13T15:15:28+00:00, book20_bid_proxy_usdt=21476, book20_ask_proxy_usdt=21234, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.46%, turnover=5623899. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T15:15:00+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=0.018630, depth_time=2026-10-13T15:15:09+00:00, book20_bid_proxy_usdt=18411, book20_ask_proxy_usdt=24794, funding_indicative=-0.000343, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-25.22%, turnover=12732725. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T15:15:01+00:00, last15m_closed_end=2026-10-13T15:15+00:00, prior8high=2.059100, depth_time=2026-10-13T15:15:13+00:00, book20_bid_proxy_usdt=30906, book20_ask_proxy_usdt=39770, funding_indicative=-0.000022, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.32%, turnover=15424082. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
