# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T05:00:43Z**
- feed_generated_utc: 2026-10-27T05:00:47+00:00
- source_sha256: `47c5e8e90d832c6c2ff9a8064c31045fb2343ecdd60869333f4410264b0781ce`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T05:00+00:00, close=79721.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T05:00+00:00, close=79721.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|200.410000|-4.69|2.40|-3.85|124204766|0.50|
|PUMPFUN_USDT|0.004154|-4.65|-6.77|-3.81|20776460|2.41|
|DOT_USDT|0.990500|-3.94|-13.62|-3.10|10879742|1.01|
|AAVE_USDT|132.460000|-3.93|-10.02|-3.09|23611342|0.76|
|FILECOIN_USDT|0.895100|-3.38|-11.55|-2.54|6394790|1.12|
|NEAR_USDT|4.421000|-3.32|-9.84|-2.48|98963021|2.26|
|ARB_USDT|0.166690|-3.03|-14.79|-2.19|20352683|0.60|
|AVAX_USDT|8.739000|-2.91|-8.60|-2.07|52016977|1.15|
|ONDO_USDT|0.407200|-2.76|-5.87|-1.92|22594460|2.46|
|FET_USDT|0.171900|-2.66|-9.04|-1.82|6632199|5.82|
|TAO_USDT|248.600000|-2.45|-7.34|-1.61|44971112|0.81|
|ZEC_USDT|1221.250000|-2.12|8.53|-1.28|1443692678|0.08|
|PENGU_USDT|0.007423|-1.99|-0.90|-1.15|5419473|1.35|
|WLD_USDT|0.436200|-1.97|-13.84|-1.13|69203485|2.29|
|LINK_USDT|11.345000|-1.90|-5.00|-1.06|110783525|0.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.460000|131.800000|132.460000|0.47|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166690|0.165910|0.166670|0.71|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.739000|8.726000|8.739000|0.97|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.990500|0.987800|0.990500|0.74|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.171900|0.170600|0.171900|0.16|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.895100|0.892600|0.895100|1.19|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.345000|11.264000|11.344000|0.95|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.421000|4.389000|4.422000|0.64|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.407200|0.404300|0.407400|1.90|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007423|0.007387|0.007424|0.12|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004154|0.004118|0.004154|0.72|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|200.410000|199.100000|200.530000|0.74|N|Y/Y|N/N|Y|N|
|TAO_USDT|248.600000|247.350000|248.600000|0.82|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.436200|0.433900|0.436300|0.20|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1221.250000|1216.410000|1220.750000|0.91|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T05:00:03+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=133.660000, depth_time=2026-10-27T05:00:16+00:00, book20_bid_proxy_usdt=806015, book20_ask_proxy_usdt=493861, funding_indicative=0.000090, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.93%, turnover=23611342. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T05:00:03+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=0.167860, depth_time=2026-10-27T05:00:23+00:00, book20_bid_proxy_usdt=95007, book20_ask_proxy_usdt=91692, funding_indicative=0.000009, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.03%, turnover=20352683. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T05:00:02+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=8.847000, depth_time=2026-10-27T05:00:25+00:00, book20_bid_proxy_usdt=2028797, book20_ask_proxy_usdt=1045782, funding_indicative=-0.000067, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=52016977. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T05:00:03+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=0.997900, depth_time=2026-10-27T05:00:13+00:00, book20_bid_proxy_usdt=254391, book20_ask_proxy_usdt=466390, funding_indicative=-0.000132, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.94%, turnover=10879742. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T05:00:03+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=0.172900, depth_time=2026-10-27T05:00:28+00:00, book20_bid_proxy_usdt=1825425, book20_ask_proxy_usdt=1247186, funding_indicative=0.000021, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=6632199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T05:00:03+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=0.902100, depth_time=2026-10-27T05:00:14+00:00, book20_bid_proxy_usdt=1093634, book20_ask_proxy_usdt=1227851, funding_indicative=-0.000035, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.38%, turnover=6394790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T05:00:02+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=11.365000, depth_time=2026-10-27T05:00:42+00:00, book20_bid_proxy_usdt=420213, book20_ask_proxy_usdt=541471, funding_indicative=-0.000030, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=110783525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T05:00:02+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=4.467000, depth_time=2026-10-27T05:00:20+00:00, book20_bid_proxy_usdt=4050271, book20_ask_proxy_usdt=3376072, funding_indicative=0.000042, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.32%, turnover=98963021. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T05:00:02+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=0.408600, depth_time=2026-10-27T05:00:25+00:00, book20_bid_proxy_usdt=2213229, book20_ask_proxy_usdt=3577335, funding_indicative=0.000020, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=22594460. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-27T05:00:03+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=0.007458, depth_time=2026-10-27T05:00:37+00:00, book20_bid_proxy_usdt=221060, book20_ask_proxy_usdt=198903, funding_indicative=0.000008, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=5419473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T05:00:03+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=0.004206, depth_time=2026-10-27T05:00:11+00:00, book20_bid_proxy_usdt=1646786, book20_ask_proxy_usdt=2366521, funding_indicative=0.000016, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.65%, turnover=20776460. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T05:00:02+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=205.230000, depth_time=2026-10-27T05:00:08+00:00, book20_bid_proxy_usdt=40301, book20_ask_proxy_usdt=40897, funding_indicative=-0.000116, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.69%, turnover=124204766. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T05:00:02+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=249.520000, depth_time=2026-10-27T05:00:33+00:00, book20_bid_proxy_usdt=98046, book20_ask_proxy_usdt=142306, funding_indicative=0.000036, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.45%, turnover=44971112. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T05:00:02+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=0.440800, depth_time=2026-10-27T05:00:39+00:00, book20_bid_proxy_usdt=3482256, book20_ask_proxy_usdt=3199046, funding_indicative=-0.000199, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=69203485. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-27T05:00:02+00:00, last15m_closed_end=2026-10-27T05:00+00:00, prior8high=1226.710000, depth_time=2026-10-27T05:00:35+00:00, book20_bid_proxy_usdt=760798, book20_ask_proxy_usdt=168110, funding_indicative=0.000085, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=1443692678. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
