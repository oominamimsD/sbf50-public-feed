# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T21:45:41Z**
- feed_generated_utc: 2026-11-02T21:45:43+00:00
- source_sha256: `89e5724807f3fd272ef86e07b0ae3e1a116e85b0b1a294a31e2388209f29fa17`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T21:45+00:00, close=76953.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T21:00+00:00, close=76766.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T20:00+00:00, close=77068.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.120300|-9.34|-51.64|-8.67|6499040|8.30|
|ZEC_USDT|1158.800000|-7.59|-7.12|-6.92|1891057870|0.09|
|XPL_USDT|0.066950|-3.77|-9.88|-3.10|10051804|1.49|
|PUMPFUN_USDT|0.003978|-3.07|-8.08|-2.40|11250944|2.51|
|QNT_USDT|196.390000|-2.99|-6.60|-2.32|51206723|0.51|
|ZRO_USDT|1.716400|-2.92|0.54|-2.25|6240202|1.17|
|NEAR_USDT|3.908000|-2.54|-14.54|-1.87|82588055|2.56|
|AAVE_USDT|127.630000|-2.24|-6.65|-1.57|23554108|0.78|
|XLM_USDT|0.163940|-2.18|-3.33|-1.51|33197167|0.61|
|ENA_USDT|0.171610|-1.95|-18.42|-1.28|75632207|1.17|
|DASH_USDT|46.300000|-1.90|-11.33|-1.23|10331799|2.16|
|TRUMPOFFICIAL_USDT|1.606000|-1.83|-4.91|-1.16|12696220|6.23|
|TIA_USDT|0.449000|-1.72|-16.18|-1.05|12406911|2.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.630000|126.360000|127.630000|0.84|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.300000|45.500000|46.300000|0.80|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.171610|0.169020|0.171600|0.55|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.908000|3.843000|3.908000|0.58|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003978|0.003877|0.003977|0.64|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|196.390000|192.300000|196.390000|0.88|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.449000|0.440400|0.449000|0.52|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.606000|1.563000|1.606000|0.62|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.120300|0.112100|0.120500|1.09|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.163940|0.163080|0.163940|1.02|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.066950|0.066130|0.066950|0.41|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1158.800000|1127.170000|1159.430000|1.00|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.716400|1.692200|1.716400|0.25|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-02T21:45:02+00:00, last15m_closed_end=2026-11-02T21:45+00:00, prior8high=127.880000, depth_time=2026-11-02T21:45:27+00:00, book20_bid_proxy_usdt=481734, book20_ask_proxy_usdt=400945, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=23554108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-02T21:45:02+00:00, last15m_closed_end=2026-11-02T21:45+00:00, prior8high=46.180000, depth_time=2026-11-02T21:45:32+00:00, book20_bid_proxy_usdt=654698, book20_ask_proxy_usdt=647510, funding_indicative=0.000057, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=10331799. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-02T21:45:02+00:00, last15m_closed_end=2026-11-02T21:45+00:00, prior8high=0.172110, depth_time=2026-11-02T21:45:31+00:00, book20_bid_proxy_usdt=251748, book20_ask_proxy_usdt=194201, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=75632207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-02T21:45:02+00:00, last15m_closed_end=2026-11-02T21:45+00:00, prior8high=3.936000, depth_time=2026-11-02T21:45:25+00:00, book20_bid_proxy_usdt=4625361, book20_ask_proxy_usdt=3289015, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=82588055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T21:45:02+00:00, last15m_closed_end=2026-11-02T21:45+00:00, prior8high=0.003989, depth_time=2026-11-02T21:45:15+00:00, book20_bid_proxy_usdt=2453000, book20_ask_proxy_usdt=3030995, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=11250944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-02T21:45:02+00:00, last15m_closed_end=2026-11-02T21:45+00:00, prior8high=195.610000, depth_time=2026-11-02T21:45:19+00:00, book20_bid_proxy_usdt=81662, book20_ask_proxy_usdt=47772, funding_indicative=0.000088, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.99%, turnover=51206723. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-02T21:45:02+00:00, last15m_closed_end=2026-11-02T21:45+00:00, prior8high=0.447000, depth_time=2026-11-02T21:45:40+00:00, book20_bid_proxy_usdt=264858, book20_ask_proxy_usdt=296147, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=12406911. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-02T21:45:02+00:00, last15m_closed_end=2026-11-02T21:45+00:00, prior8high=1.602000, depth_time=2026-11-02T21:45:36+00:00, book20_bid_proxy_usdt=2093782, book20_ask_proxy_usdt=2046686, funding_indicative=0.000004, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.83%, turnover=12696220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T21:45:02+00:00, last15m_closed_end=2026-11-02T21:45+00:00, prior8high=0.120200, depth_time=2026-11-02T21:45:09+00:00, book20_bid_proxy_usdt=175397, book20_ask_proxy_usdt=157937, funding_indicative=-0.000126, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.34%, turnover=6499040. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-02T21:45:02+00:00, last15m_closed_end=2026-11-02T21:45+00:00, prior8high=0.165410, depth_time=2026-11-02T21:45:29+00:00, book20_bid_proxy_usdt=167520, book20_ask_proxy_usdt=236374, funding_indicative=0.000097, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=33197167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T21:45:02+00:00, last15m_closed_end=2026-11-02T21:45+00:00, prior8high=0.067700, depth_time=2026-11-02T21:45:14+00:00, book20_bid_proxy_usdt=372417, book20_ask_proxy_usdt=486238, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.77%, turnover=10051804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T21:45:02+00:00, last15m_closed_end=2026-11-02T21:45+00:00, prior8high=1164.850000, depth_time=2026-11-02T21:45:11+00:00, book20_bid_proxy_usdt=781774, book20_ask_proxy_usdt=463204, funding_indicative=0.000064, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.59%, turnover=1891057870. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-02T21:45:02+00:00, last15m_closed_end=2026-11-02T21:45+00:00, prior8high=1.734000, depth_time=2026-11-02T21:45:22+00:00, book20_bid_proxy_usdt=60991, book20_ask_proxy_usdt=48109, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.92%, turnover=6240202. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
